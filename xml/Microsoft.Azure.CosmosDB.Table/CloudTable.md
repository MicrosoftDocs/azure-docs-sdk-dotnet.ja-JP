<Type Name="CloudTable" FullName="Microsoft.Azure.CosmosDB.Table.CloudTable">
  <TypeSignature Language="C#" Value="public class CloudTable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudTable extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.CloudTable" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudTable" />
  <TypeSignature Language="F#" Value="type CloudTable = class" />
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
            <span data-ttu-id="15e42-101">Microsoft Azure テーブルを表します。</span><span class="sxs-lookup"><span data-stu-id="15e42-101">Represents a Microsoft Azure table.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudTable (Uri tableAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri tableAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tableAddress As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.CloudTable : Uri -&gt; Microsoft.Azure.CosmosDB.Table.CloudTable" Usage="new Microsoft.Azure.CosmosDB.Table.CloudTable tableAddress" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tableAddress" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="tableAddress"><span data-ttu-id="15e42-102">A<see cref="T:System.Uri" />テーブルへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="15e42-102">A <see cref="T:System.Uri" /> specifying the absolute URI to the table.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-103"><see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="15e42-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudTable (Microsoft.Azure.Storage.StorageUri tableAddress, Microsoft.Azure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Storage.StorageUri tableAddress, class Microsoft.Azure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.#ctor(Microsoft.Azure.Storage.StorageUri,Microsoft.Azure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tableAddress As StorageUri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.CloudTable : Microsoft.Azure.Storage.StorageUri * Microsoft.Azure.Storage.Auth.StorageCredentials -&gt; Microsoft.Azure.CosmosDB.Table.CloudTable" Usage="new Microsoft.Azure.CosmosDB.Table.CloudTable (tableAddress, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tableAddress" Type="Microsoft.Azure.Storage.StorageUri" />
        <Parameter Name="credentials" Type="Microsoft.Azure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="tableAddress"><span data-ttu-id="15e42-104">A<see cref="P:Microsoft.Azure.CosmosDB.Table.CloudTable.StorageUri" />プライマリとセカンダリの両方の場所にあるテーブルに対して絶対 URI を格納します。</span><span class="sxs-lookup"><span data-stu-id="15e42-104">A <see cref="P:Microsoft.Azure.CosmosDB.Table.CloudTable.StorageUri" /> containing the absolute URI to the table at both the primary and secondary locations.</span></span></param>
        <param name="credentials"><span data-ttu-id="15e42-105"><see cref="T:Microsoft.Azure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-105">A <see cref="T:Microsoft.Azure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-106"><see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="15e42-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudTable (Uri tableAbsoluteUri, Microsoft.Azure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri tableAbsoluteUri, class Microsoft.Azure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.#ctor(System.Uri,Microsoft.Azure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tableAbsoluteUri As Uri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.CloudTable : Uri * Microsoft.Azure.Storage.Auth.StorageCredentials -&gt; Microsoft.Azure.CosmosDB.Table.CloudTable" Usage="new Microsoft.Azure.CosmosDB.Table.CloudTable (tableAbsoluteUri, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tableAbsoluteUri" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.Azure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="tableAbsoluteUri"><span data-ttu-id="15e42-107">A<see cref="T:System.Uri" />テーブルへの絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="15e42-107">A <see cref="T:System.Uri" /> specifying the absolute URI to the table.</span></span></param>
        <param name="credentials"><span data-ttu-id="15e42-108"><see cref="T:Microsoft.Azure.Storage.Auth.StorageCredentials" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-108">A <see cref="T:Microsoft.Azure.Storage.Auth.StorageCredentials" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-109"><see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="15e42-109">Initializes a new instance of the <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreate (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreate(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginCreate(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginCreate (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreate (callback, state)" />
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
        <param name="callback"><span data-ttu-id="15e42-110"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-110">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-111">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-111">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-112">テーブルを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-112">Begins an asynchronous operation to create a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-113"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-113">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreate (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreate(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginCreate(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreate (requestOptions, operationContext, callback, state)" />
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
        <param name="requestOptions"><span data-ttu-id="15e42-114">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-114">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-115"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-115">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15e42-116"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-116">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-117">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-117">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-118">テーブルを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-118">Begins an asynchronous operation to create a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-119"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-119">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreate (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, Nullable&lt;Microsoft.Azure.CosmosDB.IndexingMode&gt; indexingMode, Nullable&lt;int&gt; throughput, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreate(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.CosmosDB.IndexingMode&gt; indexingMode, valuetype System.Nullable`1&lt;int32&gt; throughput, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginCreate(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Nullable{Microsoft.Azure.CosmosDB.IndexingMode},System.Nullable{System.Int32},System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * Nullable&lt;Microsoft.Azure.CosmosDB.IndexingMode&gt; * Nullable&lt;int&gt; * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * Nullable&lt;Microsoft.Azure.CosmosDB.IndexingMode&gt; * Nullable&lt;int&gt; * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreate (requestOptions, operationContext, indexingMode, throughput, callback, state)" />
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
        <Parameter Name="indexingMode" Type="System.Nullable&lt;Microsoft.Azure.CosmosDB.IndexingMode&gt;" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="15e42-120">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-120">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-121"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-121">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="indexingMode"><span data-ttu-id="15e42-122">CosmosDB テーブルのインデックス作成モードを指定します。</span><span class="sxs-lookup"><span data-stu-id="15e42-122">Specify indexing mode for CosmosDB table</span></span></param>
        <param name="throughput"><span data-ttu-id="15e42-123">CosmosDB テーブル スループット</span><span class="sxs-lookup"><span data-stu-id="15e42-123">CosmosDB table throughput</span></span></param>
        <param name="callback"><span data-ttu-id="15e42-124"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-124">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-125">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-125">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-126">テーブルを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-126">Begins an asynchronous operation to create a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-127"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-127">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreate (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, Nullable&lt;int&gt; throughput, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreate(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, valuetype System.Nullable`1&lt;int32&gt; throughput, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginCreate(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.String,System.Nullable{System.Int32},System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreate (requestOptions, operationContext, serializedIndexingPolicy, throughput, callback, state)" />
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
        <Parameter Name="serializedIndexingPolicy" Type="System.String" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="15e42-128">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-128">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-129"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-129">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="serializedIndexingPolicy"><span data-ttu-id="15e42-130">CosmosDB テーブルのインデックス作成ポリシー</span><span class="sxs-lookup"><span data-stu-id="15e42-130">CosmosDB table indexing policy</span></span></param>
        <param name="throughput"><span data-ttu-id="15e42-131">CosmosDB テーブル スループット</span><span class="sxs-lookup"><span data-stu-id="15e42-131">CosmosDB table throughput</span></span></param>
        <param name="callback"><span data-ttu-id="15e42-132"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-132">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-133">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-133">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-134">テーブルを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-134">Begins an asynchronous operation to create a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-135"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-135">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreateIfNotExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreateIfNotExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginCreateIfNotExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginCreateIfNotExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateIfNotExists : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateIfNotExists : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreateIfNotExists (callback, state)" />
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
        <param name="callback"><span data-ttu-id="15e42-136"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-136">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-137">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-137">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-138">既に存在しない場合は、テーブルを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-138">Begins an asynchronous operation to create a table if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-139"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-139">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="15e42-140">この API は、存在の確認を実行し、したがってリスト権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="15e42-140">This API performs an existence check and therefore requires list permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreateIfNotExists (Microsoft.Azure.CosmosDB.IndexingMode indexingMode, Nullable&lt;int&gt; throughput, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreateIfNotExists(valuetype Microsoft.Azure.CosmosDB.IndexingMode indexingMode, valuetype System.Nullable`1&lt;int32&gt; throughput, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginCreateIfNotExists(Microsoft.Azure.CosmosDB.IndexingMode,System.Nullable{System.Int32},System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateIfNotExists : Microsoft.Azure.CosmosDB.IndexingMode * Nullable&lt;int&gt; * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateIfNotExists : Microsoft.Azure.CosmosDB.IndexingMode * Nullable&lt;int&gt; * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreateIfNotExists (indexingMode, throughput, callback, state)" />
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
        <Parameter Name="indexingMode" Type="Microsoft.Azure.CosmosDB.IndexingMode" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="indexingMode"><span data-ttu-id="15e42-141">CosmosDB テーブルのインデックス作成モード</span><span class="sxs-lookup"><span data-stu-id="15e42-141">CosmosDB table indexing mode</span></span></param>
        <param name="throughput"><span data-ttu-id="15e42-142">CosmosDB テーブル スループット</span><span class="sxs-lookup"><span data-stu-id="15e42-142">CosmosDB table throughput</span></span></param>
        <param name="callback"><span data-ttu-id="15e42-143"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-143">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-144">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-144">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-145">既に存在しない場合は、テーブルを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-145">Begins an asynchronous operation to create a table if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-146"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-146">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="15e42-147">この API は、存在の確認を実行し、したがってリスト権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="15e42-147">This API performs an existence check and therefore requires list permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreateIfNotExists (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreateIfNotExists(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginCreateIfNotExists(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateIfNotExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateIfNotExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreateIfNotExists (requestOptions, operationContext, callback, state)" />
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
        <param name="requestOptions"><span data-ttu-id="15e42-148">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-148">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-149"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-149">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15e42-150"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-150">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-151">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-151">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-152">既に存在しない場合は、テーブルを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-152">Begins an asynchronous operation to create a table if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-153"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-153">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="15e42-154">この API は、存在の確認を実行し、したがってリスト権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="15e42-154">This API performs an existence check and therefore requires list permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreateIfNotExists (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, Nullable&lt;int&gt; throughput, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreateIfNotExists(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, valuetype System.Nullable`1&lt;int32&gt; throughput, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginCreateIfNotExists(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.String,System.Nullable{System.Int32},System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateIfNotExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateIfNotExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreateIfNotExists (requestOptions, operationContext, serializedIndexingPolicy, throughput, callback, state)" />
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
        <Parameter Name="serializedIndexingPolicy" Type="System.String" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="15e42-155">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-155">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-156"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-156">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="serializedIndexingPolicy"><span data-ttu-id="15e42-157">CosmosDB テーブルのインデックス作成ポリシー</span><span class="sxs-lookup"><span data-stu-id="15e42-157">CosmosDB table indexing policy</span></span></param>
        <param name="throughput"><span data-ttu-id="15e42-158">CosmosDB テーブル スループット</span><span class="sxs-lookup"><span data-stu-id="15e42-158">CosmosDB table throughput</span></span></param>
        <param name="callback"><span data-ttu-id="15e42-159"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-159">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-160">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-160">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-161">既に存在しない場合は、テーブルを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-161">Begins an asynchronous operation to create a table if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-162"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-162">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="15e42-163">この API は、存在の確認を実行し、したがってリスト権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="15e42-163">This API performs an existence check and therefore requires list permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginDelete (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginDelete(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginDelete(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDelete (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDelete : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginDelete : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginDelete (callback, state)" />
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
        <param name="callback"><span data-ttu-id="15e42-164"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-164">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-165">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-165">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-166">テーブルを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-166">Begins an asynchronous operation to delete a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-167"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-167">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginDelete (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginDelete(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginDelete(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDelete : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginDelete : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginDelete (requestOptions, operationContext, callback, state)" />
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
        <param name="requestOptions"><span data-ttu-id="15e42-168">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-168">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-169"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-169">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15e42-170"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-170">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-171">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-171">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-172">テーブルを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-172">Begins an asynchronous operation to delete a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-173"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-173">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginDeleteIfExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginDeleteIfExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginDeleteIfExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDeleteIfExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteIfExists : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteIfExists : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginDeleteIfExists (callback, state)" />
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
        <param name="callback"><span data-ttu-id="15e42-174"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-174">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-175">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-175">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-176">存在する場合は、テーブルを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-176">Begins an asynchronous operation to delete the table if it exists.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-177"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-177">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginDeleteIfExists (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginDeleteIfExists(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginDeleteIfExists(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteIfExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteIfExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginDeleteIfExists (requestOptions, operationContext, callback, state)" />
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
        <param name="requestOptions"><span data-ttu-id="15e42-178">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-178">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-179"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-179">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15e42-180"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-180">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-181">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-181">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-182">存在する場合は、テーブルを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-182">Begins an asynchronous operation to delete the table if it exists.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-183"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-183">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecute">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecute (Microsoft.Azure.CosmosDB.Table.TableOperation operation, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecute(class Microsoft.Azure.CosmosDB.Table.TableOperation operation, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecute(Microsoft.Azure.CosmosDB.Table.TableOperation,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecute (operation As TableOperation, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecute : Microsoft.Azure.CosmosDB.Table.TableOperation * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecute : Microsoft.Azure.CosmosDB.Table.TableOperation * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecute (operation, callback, state)" />
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
        <Parameter Name="operation" Type="Microsoft.Azure.CosmosDB.Table.TableOperation" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="operation"><span data-ttu-id="15e42-184">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />を実行する操作を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-184">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> object that represents the operation to perform.</span></span></param>
        <param name="callback"><span data-ttu-id="15e42-185"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-185">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-186">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-186">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-187">非同期のテーブル操作の実行を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-187">Begins execution of an asynchronous table operation.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-188"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-188">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecute">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecute (Microsoft.Azure.CosmosDB.Table.TableOperation operation, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecute(class Microsoft.Azure.CosmosDB.Table.TableOperation operation, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecute(Microsoft.Azure.CosmosDB.Table.TableOperation,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecute : Microsoft.Azure.CosmosDB.Table.TableOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecute : Microsoft.Azure.CosmosDB.Table.TableOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecute (operation, requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="operation" Type="Microsoft.Azure.CosmosDB.Table.TableOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="operation"><span data-ttu-id="15e42-189">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />を実行する操作を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-189">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> object that represents the operation to perform.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-190">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-190">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-191"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-191">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15e42-192"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-192">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-193">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-193">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-194">非同期のテーブル操作の実行を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-194">Begins execution of an asynchronous table operation.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-195"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-195">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteBatch">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteBatch (Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteBatch(class Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteBatch(Microsoft.Azure.CosmosDB.Table.TableBatchOperation,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecuteBatch (batch As TableBatchOperation, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteBatch : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteBatch : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteBatch (batch, callback, state)" />
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
        <Parameter Name="batch" Type="Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="batch"><span data-ttu-id="15e42-196"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />テーブルに対して実行する操作を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-196">The <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> object representing the operations to execute on the table.</span></span></param>
        <param name="callback"><span data-ttu-id="15e42-197"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-197">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-198">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-198">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-199">テーブルに対する操作のバッチを実行する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-199">Begins an asynchronous operation to execute a batch of operations on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-200"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-200">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteBatch">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteBatch (Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteBatch(class Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteBatch(Microsoft.Azure.CosmosDB.Table.TableBatchOperation,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteBatch : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteBatch : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteBatch (batch, requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="batch" Type="Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="batch"><span data-ttu-id="15e42-201"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />テーブルに対して実行する操作を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-201">The <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> object representing the operations to execute on the table.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-202">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-202">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-203"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-203">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15e42-204"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-204">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-205">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-205">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-206">テーブルに対する操作のバッチを実行する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-206">Begins an asynchronous operation to execute a batch of operations on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-207"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-207">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQueryForKeyRotationSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQueryForKeyRotationSegmented (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQueryForKeyRotationSegmented(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQueryForKeyRotationSegmented(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecuteQueryForKeyRotationSegmented (query As TableQuery, token As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQueryForKeyRotationSegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteQueryForKeyRotationSegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteQueryForKeyRotationSegmented (query, token, callback, state)" />
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
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="15e42-208">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />を表すクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="15e42-208">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-209">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-209">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="callback"><span data-ttu-id="15e42-210"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-210">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-211">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-211">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-212">テーブルで、非同期のセグメント化されたクエリを開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-212">Begins an asynchronous segmented query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-213"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-213">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQueryForKeyRotationSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQueryForKeyRotationSegmented (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQueryForKeyRotationSegmented(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQueryForKeyRotationSegmented(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQueryForKeyRotationSegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteQueryForKeyRotationSegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteQueryForKeyRotationSegmented (query, token, requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="15e42-214">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />を表すクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="15e42-214">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-215">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-215">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-216">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-216">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-217"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-217">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15e42-218"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-218">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-219">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-219">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-220">テーブルで、非同期のセグメント化されたクエリを開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-220">Begins an asynchronous segmented query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-221"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-221">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQuerySegmented(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecuteQuerySegmented (query As TableQuery, token As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteQuerySegmented (query, token, callback, state)" />
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
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="15e42-222">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />を表すクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="15e42-222">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-223">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-223">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="callback"><span data-ttu-id="15e42-224"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-224">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-225">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-225">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-226">テーブルで、非同期のセグメント化されたクエリを開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-226">Begins an asynchronous segmented query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-227"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-227">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQuerySegmented(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteQuerySegmented (query, token, requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="15e42-228">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />を表すクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="15e42-228">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-229">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-229">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-230">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-230">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-231"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-231">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15e42-232"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-232">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-233">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-233">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-234">テーブルで、非同期のセグメント化されたクエリを開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-234">Begins an asynchronous segmented query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-235"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-235">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TElement&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, AsyncCallback callback, object state) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQuerySegmented``1(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecuteQuerySegmented(Of TElement As {ITableEntityNew}) (query As TableQuery(Of TElement), token As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.BeginExecuteQuerySegmented (query, token, callback, state)" />
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
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="15e42-236">クエリのエンティティ型。</span><span class="sxs-lookup"><span data-stu-id="15e42-236">The entity type of the query.</span></span></typeparam>
        <param name="query"><span data-ttu-id="15e42-237">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-237">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-238">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-238">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="callback"><span data-ttu-id="15e42-239"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-239">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-240">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-240">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-241">セグメント化モードでテーブルをクエリする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-241">Begins an asynchronous operation to query a table in segmented mode.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-242"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-242">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TElement&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQuerySegmented``1(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.BeginExecuteQuerySegmented (query, token, requestOptions, operationContext, callback, state)" />
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
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="15e42-243">クエリのエンティティ型。</span><span class="sxs-lookup"><span data-stu-id="15e42-243">The entity type of the query.</span></span></typeparam>
        <param name="query"><span data-ttu-id="15e42-244">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-244">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-245">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-245">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-246">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-246">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-247"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-247">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15e42-248"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-248">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-249">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-249">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-250">セグメント化モードでテーブルをクエリする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-250">Begins an asynchronous operation to query a table in segmented mode.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-251"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-251">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQuerySegmented``1(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecuteQuerySegmented(Of TResult) (query As TableQuery, resolver As EntityResolver(Of TResult), token As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteQuerySegmented (query, resolver, token, callback, state)" />
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
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">To be added.</typeparam>
        <param name="query"><span data-ttu-id="15e42-252">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />を表すクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="15e42-252">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="resolver"><span data-ttu-id="15e42-253"><see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-253">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-254">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-254">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="callback"><span data-ttu-id="15e42-255"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-255">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-256">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-256">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-257">セグメント化されたクエリを実行して、指定された適用する非同期操作を開始<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />結果にします。</span><span class="sxs-lookup"><span data-stu-id="15e42-257">Begins an asynchronous operation to execute a segmented query and apply the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the result.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-258"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-258">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQuerySegmented``1(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteQuerySegmented (query, resolver, token, requestOptions, operationContext, callback, state)" />
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
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TResult"><span data-ttu-id="15e42-259">先の種類、<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />クエリ結果の射影されます。</span><span class="sxs-lookup"><span data-stu-id="15e42-259">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="query"><span data-ttu-id="15e42-260">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />クエリおよびクエリ パラメーターを使用するテーブルを指定します。</span><span class="sxs-lookup"><span data-stu-id="15e42-260">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use.</span></span></param>
        <param name="resolver"><span data-ttu-id="15e42-261"><see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-261">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-262">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-262">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-263">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-263">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-264"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-264">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15e42-265"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-265">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-266">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-266">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-267">セグメント化されたクエリを実行して、指定された適用する非同期操作を開始<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />結果にします。</span><span class="sxs-lookup"><span data-stu-id="15e42-267">Begins an asynchronous operation to execute a segmented query and apply the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the result.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-268"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-268">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TElement,TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, AsyncCallback callback, object state) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQuerySegmented``2(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.EntityResolver{``1},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecuteQuerySegmented(Of TElement As {ITableEntityNew}, TResult As {ITableEntityNew}) (query As TableQuery(Of TElement), resolver As EntityResolver(Of TResult), token As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.BeginExecuteQuerySegmented (query, resolver, token, callback, state)" />
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
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="15e42-269">クエリのエンティティ型。</span><span class="sxs-lookup"><span data-stu-id="15e42-269">The entity type of the query.</span></span></typeparam>
        <typeparam name="TResult"><span data-ttu-id="15e42-270">先の種類、<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />クエリ結果の射影されます。</span><span class="sxs-lookup"><span data-stu-id="15e42-270">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="query"><span data-ttu-id="15e42-271">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-271">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="resolver"><span data-ttu-id="15e42-272"><see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-272">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-273">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-273">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="callback"><span data-ttu-id="15e42-274"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-274">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-275">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-275">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-276">セグメント化モードでテーブルをクエリして、指定された適用する非同期操作を開始<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />結果にします。</span><span class="sxs-lookup"><span data-stu-id="15e42-276">Begins an asynchronous operation to query a table in segmented mode and apply the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the results.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-277"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-277">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TElement,TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQuerySegmented``2(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.EntityResolver{``1},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.BeginExecuteQuerySegmented (query, resolver, token, requestOptions, operationContext, callback, state)" />
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
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="15e42-278">クエリのエンティティ型。</span><span class="sxs-lookup"><span data-stu-id="15e42-278">The entity type of the query.</span></span></typeparam>
        <typeparam name="TResult"><span data-ttu-id="15e42-279">先の種類、<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />クエリ結果の射影されます。</span><span class="sxs-lookup"><span data-stu-id="15e42-279">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="query"><span data-ttu-id="15e42-280">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-280">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="resolver"><span data-ttu-id="15e42-281"><see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-281">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-282">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-282">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-283">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-283">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-284"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-284">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15e42-285"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-285">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-286">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-286">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-287">セグメント化モードでクエリを実行して、指定された適用する非同期操作を開始<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />結果にします。</span><span class="sxs-lookup"><span data-stu-id="15e42-287">Begins an asynchronous operation to execute a query in segmented mode and apply the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the results.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-288"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-288">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExists : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExists : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExists (callback, state)" />
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
        <param name="callback"><span data-ttu-id="15e42-289"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-289">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-290">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-290">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-291">テーブルが存在するかどうかを判断する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-291">Begins an asynchronous operation to determine whether a table exists.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-292"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-292">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExists (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExists(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExists(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExists (requestOptions, operationContext, callback, state)" />
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
        <param name="requestOptions"><span data-ttu-id="15e42-293">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-293">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-294"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-294">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15e42-295"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-295">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-296">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-296">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-297">テーブルが存在するかどうかを判断する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-297">Begins an asynchronous operation to determine whether a table exists.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-298"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-298">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetPermissions (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetPermissions(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginGetPermissions(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetPermissions (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetPermissions : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetPermissions : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginGetPermissions (callback, state)" />
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
        <param name="callback"><span data-ttu-id="15e42-299"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-299">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-300">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-300">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-301">テーブルのアクセス許可の設定を取得する非同期の要求を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-301">Begins an asynchronous request to get the permissions settings for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-302"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-302">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetPermissions (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetPermissions(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginGetPermissions(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetPermissions : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetPermissions : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginGetPermissions (requestOptions, operationContext, callback, state)" />
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
        <param name="requestOptions"><span data-ttu-id="15e42-303">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-303">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-304"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-304">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15e42-305"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-305">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-306">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-306">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-307">テーブルのアクセス許可の設定を取得する非同期の要求を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-307">Begins an asynchronous request to get the permissions settings for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-308"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-308">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginSetPermissions (Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginSetPermissions(class Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginSetPermissions(Microsoft.Azure.CosmosDB.Table.TablePermissions,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSetPermissions (permissions As TablePermissions, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSetPermissions : Microsoft.Azure.CosmosDB.Table.TablePermissions * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetPermissions : Microsoft.Azure.CosmosDB.Table.TablePermissions * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginSetPermissions (permissions, callback, state)" />
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
        <Parameter Name="permissions" Type="Microsoft.Azure.CosmosDB.Table.TablePermissions" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="15e42-309">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" />へのアクセス許可を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-309">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> object that represents the permissions to set.</span></span></param>
        <param name="callback"><span data-ttu-id="15e42-310"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-310">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-311">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-311">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-312">テーブルのアクセス許可を設定する非同期要求を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-312">Begins an asynchronous request to set permissions for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-313"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-313">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginSetPermissions (Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginSetPermissions(class Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginSetPermissions(Microsoft.Azure.CosmosDB.Table.TablePermissions,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetPermissions : Microsoft.Azure.CosmosDB.Table.TablePermissions * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetPermissions : Microsoft.Azure.CosmosDB.Table.TablePermissions * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginSetPermissions (permissions, requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="permissions" Type="Microsoft.Azure.CosmosDB.Table.TablePermissions" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="15e42-314">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" />へのアクセス許可を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-314">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> object that represents the permissions to set.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-315">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-315">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-316"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-316">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="15e42-317"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="15e42-317">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="15e42-318">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-318">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-319">テーブルのアクセス許可を設定する非同期要求を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-319">Begins an asynchronous request to set permissions for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-320"><see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-320">An <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public virtual void Create (Nullable&lt;Microsoft.Azure.CosmosDB.IndexingMode&gt; indexingMode, Nullable&lt;int&gt; throughput = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Create(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.CosmosDB.IndexingMode&gt; indexingMode, valuetype System.Nullable`1&lt;int32&gt; throughput) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.Create(System.Nullable{Microsoft.Azure.CosmosDB.IndexingMode},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Create (indexingMode As Nullable(Of IndexingMode), Optional throughput As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="abstract member Create : Nullable&lt;Microsoft.Azure.CosmosDB.IndexingMode&gt; * Nullable&lt;int&gt; -&gt; unit&#xA;override this.Create : Nullable&lt;Microsoft.Azure.CosmosDB.IndexingMode&gt; * Nullable&lt;int&gt; -&gt; unit" Usage="cloudTable.Create (indexingMode, throughput)" />
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
        <Parameter Name="indexingMode" Type="System.Nullable&lt;Microsoft.Azure.CosmosDB.IndexingMode&gt;" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="indexingMode"><span data-ttu-id="15e42-321">CosmosDB テーブルのインデックス作成モードを指定します。</span><span class="sxs-lookup"><span data-stu-id="15e42-321">Specify indexing mode for CosmosDB table</span></span></param>
        <param name="throughput"><span data-ttu-id="15e42-322">CosmosDB テーブル スループット</span><span class="sxs-lookup"><span data-stu-id="15e42-322">CosmosDB table throughput</span></span></param>
        <summary>
            <span data-ttu-id="15e42-323">テーブルを作成します。</span><span class="sxs-lookup"><span data-stu-id="15e42-323">Creates a table.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public virtual void Create (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null, string serializedIndexingPolicy = null, Nullable&lt;int&gt; throughput = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Create(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, valuetype System.Nullable`1&lt;int32&gt; throughput) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.Create(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="F#" Value="abstract member Create : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; -&gt; unit&#xA;override this.Create : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; -&gt; unit" Usage="cloudTable.Create (requestOptions, operationContext, serializedIndexingPolicy, throughput)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="serializedIndexingPolicy" Type="System.String" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="15e42-324">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-324">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-325"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-325">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="serializedIndexingPolicy"><span data-ttu-id="15e42-326">CosmosDB テーブルのインデックス作成ポリシー</span><span class="sxs-lookup"><span data-stu-id="15e42-326">CosmosDB table indexing policy</span></span></param>
        <param name="throughput"><span data-ttu-id="15e42-327">CosmosDB テーブル スループット</span><span class="sxs-lookup"><span data-stu-id="15e42-327">CosmosDB table throughput</span></span></param>
        <summary>
            <span data-ttu-id="15e42-328">テーブルを作成します。</span><span class="sxs-lookup"><span data-stu-id="15e42-328">Creates a table.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudTable.CreateAsync " />
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
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="15e42-329">テーブルを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-329">Initiates an asynchronous operation to create a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-330">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-330">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.CreateAsync cancellationToken" />
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
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="15e42-331">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-331">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-332">テーブルを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-332">Initiates an asynchronous operation to create a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-333">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-333">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudTable.CreateAsync (requestOptions, operationContext)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="15e42-334">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-334">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-335"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-335">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-336">テーブルを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-336">Initiates an asynchronous operation to create a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-337">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-337">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.CreateAsync (requestOptions, operationContext, cancellationToken)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="15e42-338">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-338">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-339"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-339">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-340">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-340">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-341">テーブルを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-341">Initiates an asynchronous operation to create a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-342">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-342">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Nullable&lt;int&gt; throughput, Microsoft.Azure.CosmosDB.IndexingMode indexingMode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(valuetype System.Nullable`1&lt;int32&gt; throughput, valuetype Microsoft.Azure.CosmosDB.IndexingMode indexingMode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateAsync(System.Nullable{System.Int32},Microsoft.Azure.CosmosDB.IndexingMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Nullable&lt;int&gt; * Microsoft.Azure.CosmosDB.IndexingMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Nullable&lt;int&gt; * Microsoft.Azure.CosmosDB.IndexingMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.CreateAsync (throughput, indexingMode, cancellationToken)" />
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
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="indexingMode" Type="Microsoft.Azure.CosmosDB.IndexingMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="throughput"><span data-ttu-id="15e42-343">CosmosDB テーブル スループット</span><span class="sxs-lookup"><span data-stu-id="15e42-343">CosmosDB table throughput</span></span></param>
        <param name="indexingMode"><span data-ttu-id="15e42-344">CosmosDB テーブルのインデックス作成モードを指定します。</span><span class="sxs-lookup"><span data-stu-id="15e42-344">Specify indexing mode for CosmosDB table</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-345">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-345">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-346">テーブルを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-346">Initiates an asynchronous operation to create a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-347">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-347">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Nullable&lt;int&gt; throughput, string serializedindexingPolicy, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(valuetype System.Nullable`1&lt;int32&gt; throughput, string serializedindexingPolicy, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateAsync(System.Nullable{System.Int32},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Nullable&lt;int&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Nullable&lt;int&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.CreateAsync (throughput, serializedindexingPolicy, cancellationToken)" />
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
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="serializedindexingPolicy" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="throughput"><span data-ttu-id="15e42-348">CosmosDB テーブル スループット</span><span class="sxs-lookup"><span data-stu-id="15e42-348">CosmosDB table throughput</span></span></param>
        <param name="serializedindexingPolicy"><span data-ttu-id="15e42-349">CosmosDB テーブルのインデックス作成ポリシー</span><span class="sxs-lookup"><span data-stu-id="15e42-349">CosmosDB table indexing policy</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-350">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-350">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-351">テーブルを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-351">Initiates an asynchronous operation to create a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-352">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-352">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, Nullable&lt;int&gt; throughput, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, valuetype System.Nullable`1&lt;int32&gt; throughput, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.CreateAsync (requestOptions, operationContext, serializedIndexingPolicy, throughput, cancellationToken)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="serializedIndexingPolicy" Type="System.String" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="15e42-353">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-353">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-354"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-354">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="serializedIndexingPolicy"><span data-ttu-id="15e42-355">CosmosDB テーブルのインデックス作成ポリシー</span><span class="sxs-lookup"><span data-stu-id="15e42-355">CosmosDB table indexing policy</span></span></param>
        <param name="throughput"><span data-ttu-id="15e42-356">CosmosDB テーブル スループット</span><span class="sxs-lookup"><span data-stu-id="15e42-356">CosmosDB table throughput</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-357">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-357">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-358">テーブルを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-358">Initiates an asynchronous operation to create a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-359">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-359">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual bool CreateIfNotExists (Microsoft.Azure.CosmosDB.IndexingMode indexingMode, Nullable&lt;int&gt; throughput = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool CreateIfNotExists(valuetype Microsoft.Azure.CosmosDB.IndexingMode indexingMode, valuetype System.Nullable`1&lt;int32&gt; throughput) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateIfNotExists(Microsoft.Azure.CosmosDB.IndexingMode,System.Nullable{System.Int32})" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExists : Microsoft.Azure.CosmosDB.IndexingMode * Nullable&lt;int&gt; -&gt; bool&#xA;override this.CreateIfNotExists : Microsoft.Azure.CosmosDB.IndexingMode * Nullable&lt;int&gt; -&gt; bool" Usage="cloudTable.CreateIfNotExists (indexingMode, throughput)" />
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="indexingMode" Type="Microsoft.Azure.CosmosDB.IndexingMode" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="indexingMode"><span data-ttu-id="15e42-360">CosmosDB テーブルのインデックス作成モード</span><span class="sxs-lookup"><span data-stu-id="15e42-360">CosmosDB table indexing mode</span></span></param>
        <param name="throughput"><span data-ttu-id="15e42-361">CosmosDB テーブル スループット</span><span class="sxs-lookup"><span data-stu-id="15e42-361">CosmosDB table throughput</span></span></param>
        <summary>
            <span data-ttu-id="15e42-362">既に存在しない場合は、テーブルを作成します。</span><span class="sxs-lookup"><span data-stu-id="15e42-362">Creates the table if it does not already exist.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="15e42-363"><c>true</c>テーブルが作成された、それ以外の場合は<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-363"><c>true</c> if table was created; otherwise, <c>false</c>.</span></span></returns>
        <remarks><span data-ttu-id="15e42-364">この API は、存在の確認を実行し、したがってリスト権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="15e42-364">This API performs an existence check and therefore requires list permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual bool CreateIfNotExists (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null, string serializedIndexingPolicy = null, Nullable&lt;int&gt; throughput = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool CreateIfNotExists(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, valuetype System.Nullable`1&lt;int32&gt; throughput) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateIfNotExists(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; -&gt; bool&#xA;override this.CreateIfNotExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; -&gt; bool" Usage="cloudTable.CreateIfNotExists (requestOptions, operationContext, serializedIndexingPolicy, throughput)" />
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="serializedIndexingPolicy" Type="System.String" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="15e42-365">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-365">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-366"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-366">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="serializedIndexingPolicy"><span data-ttu-id="15e42-367">CosmosDB テーブルのインデックス作成ポリシー</span><span class="sxs-lookup"><span data-stu-id="15e42-367">CosmosDB table indexing policy</span></span></param>
        <param name="throughput"><span data-ttu-id="15e42-368">CosmosDB テーブル スループット</span><span class="sxs-lookup"><span data-stu-id="15e42-368">CosmosDB table throughput</span></span></param>
        <summary>
            <span data-ttu-id="15e42-369">既に存在しない場合は、テーブルを作成します。</span><span class="sxs-lookup"><span data-stu-id="15e42-369">Creates the table if it does not already exist.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="15e42-370"><c>true</c>テーブルが作成された、それ以外の場合は<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-370"><c>true</c> if table was created; otherwise, <c>false</c>.</span></span></returns>
        <remarks><span data-ttu-id="15e42-371">この API は、存在の確認を実行し、したがってリスト権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="15e42-371">This API performs an existence check and therefore requires list permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateIfNotExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateIfNotExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.CreateIfNotExistsAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="15e42-372">既に存在しない場合は、テーブルを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-372">Initiates an asynchronous operation to create a table if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-373">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-373">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="15e42-374">この API は、存在の確認を実行し、したがってリスト権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="15e42-374">This API performs an existence check and therefore requires list permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateIfNotExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.CreateIfNotExistsAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="15e42-375">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-375">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-376">既に存在しない場合は、テーブルを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-376">Initiates an asynchronous operation to create a table if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-377">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-377">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="15e42-378">この API は、存在の確認を実行し、したがってリスト権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="15e42-378">This API performs an existence check and therefore requires list permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateIfNotExistsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.CreateIfNotExistsAsync (requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="15e42-379">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-379">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-380"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-380">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-381">既に存在しない場合は、テーブルを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-381">Initiates an asynchronous operation to create a table if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-382">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-382">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="15e42-383">この API は、存在の確認を実行し、したがってリスト権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="15e42-383">This API performs an existence check and therefore requires list permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (Microsoft.Azure.CosmosDB.IndexingMode indexingMode, Nullable&lt;int&gt; throughput, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(valuetype Microsoft.Azure.CosmosDB.IndexingMode indexingMode, valuetype System.Nullable`1&lt;int32&gt; throughput, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateIfNotExistsAsync(Microsoft.Azure.CosmosDB.IndexingMode,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : Microsoft.Azure.CosmosDB.IndexingMode * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : Microsoft.Azure.CosmosDB.IndexingMode * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.CreateIfNotExistsAsync (indexingMode, throughput, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="indexingMode" Type="Microsoft.Azure.CosmosDB.IndexingMode" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="indexingMode"><span data-ttu-id="15e42-384">CosmosDB テーブルのインデックス作成モード</span><span class="sxs-lookup"><span data-stu-id="15e42-384">CosmosDB table indexing mode</span></span></param>
        <param name="throughput"><span data-ttu-id="15e42-385">CosmosDB テーブル スループット</span><span class="sxs-lookup"><span data-stu-id="15e42-385">CosmosDB table throughput</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-386">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-386">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-387">既に存在しない場合は、テーブルを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-387">Initiates an asynchronous operation to create a table if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-388">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-388">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="15e42-389">この API は、存在の確認を実行し、したがってリスト権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="15e42-389">This API performs an existence check and therefore requires list permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateIfNotExistsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.CreateIfNotExistsAsync (requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="15e42-390">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-390">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-391"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-391">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-392">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-392">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-393">既に存在しない場合は、テーブルを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-393">Initiates an asynchronous operation to create a table if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-394">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-394">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="15e42-395">この API は、存在の確認を実行し、したがってリスト権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="15e42-395">This API performs an existence check and therefore requires list permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, Nullable&lt;int&gt; throughput, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, valuetype System.Nullable`1&lt;int32&gt; throughput, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateIfNotExistsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.CreateIfNotExistsAsync (requestOptions, operationContext, serializedIndexingPolicy, throughput, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="serializedIndexingPolicy" Type="System.String" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="15e42-396">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-396">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-397"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-397">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="serializedIndexingPolicy"><span data-ttu-id="15e42-398">CosmosDB テーブルのインデックス作成ポリシー</span><span class="sxs-lookup"><span data-stu-id="15e42-398">CosmosDB table indexing policy</span></span></param>
        <param name="throughput"><span data-ttu-id="15e42-399">CosmosDB テーブル スループット</span><span class="sxs-lookup"><span data-stu-id="15e42-399">CosmosDB table throughput</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-400">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-400">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-401">既に存在しない場合は、テーブルを作成する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-401">Initiates an asynchronous operation to create a table if it does not already exist.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-402">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-402">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="15e42-403">この API は、存在の確認を実行し、したがってリスト権限が必要です。</span><span class="sxs-lookup"><span data-stu-id="15e42-403">This API performs an existence check and therefore requires list permissions.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQuery&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; CreateQuery&lt;TElement&gt; () where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; CreateQuery&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateQuery``1" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateQuery(Of TElement As {ITableEntityNew}) () As TableQuery(Of TElement)" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : unit -&gt; Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.CreateQuery : unit -&gt; Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.CreateQuery " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="15e42-404">クエリのエンティティ型。</span><span class="sxs-lookup"><span data-stu-id="15e42-404">The entity type of the query.</span></span></typeparam>
        <summary>
            <span data-ttu-id="15e42-405">LINQ を使用して、クエリを作成するファクトリ メソッドを変更できます。</span><span class="sxs-lookup"><span data-stu-id="15e42-405">A factory method that creates a query that can be modified using LINQ.</span></span> <span data-ttu-id="15e42-406">クエリ、後で実行できますの使用可能な実行方法のいずれかを使用して<see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" />など<see cref="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuery(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />、 <see cref="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmented(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />、または<see cref="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />です。</span><span class="sxs-lookup"><span data-stu-id="15e42-406">The query may be subsequently executed using one of the execution methods available for <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" />, such as <see cref="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuery(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />, <see cref="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmented(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />, or <see cref="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-407">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />オブジェクト、型に特化した<c>TElement</c>を後で実行できます。</span><span class="sxs-lookup"><span data-stu-id="15e42-407">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> object, specialized for type <c>TElement</c>, that may subsequently be executed.</span></span></returns>
        <remarks>
            <span data-ttu-id="15e42-408"><see cref="N:Microsoft.Azure.CosmosDB.Table.Queryable" />名前空間には拡張メソッドが含まれています、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />オブジェクトを含む<see cref="M:WithOptions" />、 <see cref="M:WithContext" />、および<see cref="M:AsTableQuery" />です。</span><span class="sxs-lookup"><span data-stu-id="15e42-408">The <see cref="N:Microsoft.Azure.CosmosDB.Table.Queryable" /> namespace includes extension methods for the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> object, including <see cref="M:WithOptions" />, <see cref="M:WithContext" />, and <see cref="M:AsTableQuery" />.</span></span> <span data-ttu-id="15e42-409">これらのメソッドを使用するのには、<c>を使用して</c>を参照するステートメント、<see cref="N:Microsoft.Azure.CosmosDB.Table.Queryable" />名前空間。</span><span class="sxs-lookup"><span data-stu-id="15e42-409">To use these methods, include a <c>using</c> statement that references the <see cref="N:Microsoft.Azure.CosmosDB.Table.Queryable" /> namespace.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public virtual void Delete (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Delete(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.Delete(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Delete : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; unit&#xA;override this.Delete : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; unit" Usage="cloudTable.Delete (requestOptions, operationContext)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="15e42-410">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-410">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-411"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-411">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-412">テーブルを削除します。</span><span class="sxs-lookup"><span data-stu-id="15e42-412">Deletes a table.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudTable.DeleteAsync " />
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
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="15e42-413">テーブルを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-413">Initiates an asynchronous operation to delete a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-414">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-414">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.DeleteAsync cancellationToken" />
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
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="15e42-415">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-415">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-416">テーブルを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-416">Initiates an asynchronous operation to delete a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-417">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-417">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudTable.DeleteAsync (requestOptions, operationContext)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="15e42-418">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-418">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-419"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-419">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-420">テーブルを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-420">Initiates an asynchronous operation to delete a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-421">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-421">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.DeleteAsync (requestOptions, operationContext, cancellationToken)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="15e42-422">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-422">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-423"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-423">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-424">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-424">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-425">テーブルを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-425">Initiates an asynchronous operation to delete a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-426">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-426">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual bool DeleteIfExists (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool DeleteIfExists(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteIfExists(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; bool&#xA;override this.DeleteIfExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; bool" Usage="cloudTable.DeleteIfExists (requestOptions, operationContext)" />
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="15e42-427">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-427">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-428"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-428">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-429">存在する場合は、テーブルを削除します。</span><span class="sxs-lookup"><span data-stu-id="15e42-429">Deletes the table if it exists.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="15e42-430"><c>true</c>テーブルが削除された、それ以外の場合<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-430"><c>true</c> if the table was deleted; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteIfExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteIfExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.DeleteIfExistsAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="15e42-431">存在する場合は、テーブルを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-431">Initiates an asynchronous operation to delete the table if it exists.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-432">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-432">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteIfExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.DeleteIfExistsAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="15e42-433">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-433">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-434">存在する場合は、テーブルを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-434">Initiates an asynchronous operation to delete the table if it exists.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-435">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-435">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteIfExistsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.DeleteIfExistsAsync (requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="15e42-436">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-436">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-437"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-437">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-438">存在する場合は、テーブルを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-438">Initiates an asynchronous operation to delete the table if it exists.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-439">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-439">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteIfExistsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.DeleteIfExistsAsync (requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="15e42-440">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-440">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-441"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-441">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-442">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-442">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-443">存在する場合は、テーブルを削除する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-443">Initiates an asynchronous operation to delete the table if it exists.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-444">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-444">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCreate">
      <MemberSignature Language="C#" Value="public virtual void EndCreate (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndCreate(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndCreate(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndCreate (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndCreate : IAsyncResult -&gt; unit&#xA;override this.EndCreate : IAsyncResult -&gt; unit" Usage="cloudTable.EndCreate asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="15e42-445"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-445">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-446">テーブルを作成する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="15e42-446">Ends an asynchronous operation to create a table.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual bool EndCreateIfNotExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndCreateIfNotExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndCreateIfNotExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndCreateIfNotExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndCreateIfNotExists : IAsyncResult -&gt; bool&#xA;override this.EndCreateIfNotExists : IAsyncResult -&gt; bool" Usage="cloudTable.EndCreateIfNotExists asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="15e42-447"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-447">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-448">既に存在しない場合は、テーブルを作成する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="15e42-448">Ends an asynchronous operation to create a table if it does not already exist.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="15e42-449"><c>true</c>テーブルが作成された、それ以外の場合は<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-449"><c>true</c> if table was created; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDelete">
      <MemberSignature Language="C#" Value="public virtual void EndDelete (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndDelete(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndDelete(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndDelete (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndDelete : IAsyncResult -&gt; unit&#xA;override this.EndDelete : IAsyncResult -&gt; unit" Usage="cloudTable.EndDelete asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="15e42-450"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-450">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-451">テーブルを削除する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="15e42-451">Ends an asynchronous operation to delete a table.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual bool EndDeleteIfExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndDeleteIfExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndDeleteIfExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndDeleteIfExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndDeleteIfExists : IAsyncResult -&gt; bool&#xA;override this.EndDeleteIfExists : IAsyncResult -&gt; bool" Usage="cloudTable.EndDeleteIfExists asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="15e42-452"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-452">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-453">存在する場合は、テーブルを削除する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="15e42-453">Ends an asynchronous operation to delete the table if it exists.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="15e42-454"><c>true</c>テーブルが削除された、それ以外の場合<c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-454"><c>true</c> if the table was deleted; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecute">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableResult EndExecute (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableResult EndExecute(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndExecute(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExecute (asyncResult As IAsyncResult) As TableResult" />
      <MemberSignature Language="F#" Value="abstract member EndExecute : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableResult&#xA;override this.EndExecute : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableResult" Usage="cloudTable.EndExecute asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="15e42-455"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-455">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-456">非同期のテーブル操作の実行を終了します。</span><span class="sxs-lookup"><span data-stu-id="15e42-456">Ends execution of an asynchronous table operation.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-457">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" />テーブルに対する操作の実行結果を含むです。</span><span class="sxs-lookup"><span data-stu-id="15e42-457">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> containing the result executing the operation on the table.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecuteBatch">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt; EndExecuteBatch (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt; EndExecuteBatch(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndExecuteBatch(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExecuteBatch (asyncResult As IAsyncResult) As IList(Of TableResult)" />
      <MemberSignature Language="F#" Value="abstract member EndExecuteBatch : IAsyncResult -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&#xA;override this.EndExecuteBatch : IAsyncResult -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;" Usage="cloudTable.EndExecuteBatch asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="15e42-458"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-458">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-459">テーブルに対する操作のバッチを実行する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="15e42-459">Ends an asynchronous operation to execute a batch of operations on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-460">型の列挙可能なコレクション<see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" />内の各操作の順序で、結果を含む、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />テーブルにします。</span><span class="sxs-lookup"><span data-stu-id="15e42-460">A enumerable collection of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> that contains the results, in order, of each operation in the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> on the table.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecuteQueryForKeyRotationSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt; EndExecuteQueryForKeyRotationSegmented (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt; EndExecuteQueryForKeyRotationSegmented(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndExecuteQueryForKeyRotationSegmented(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExecuteQueryForKeyRotationSegmented (asyncResult As IAsyncResult) As TableQuerySegment(Of KeyRotationEntity)" />
      <MemberSignature Language="F#" Value="abstract member EndExecuteQueryForKeyRotationSegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&#xA;override this.EndExecuteQueryForKeyRotationSegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;" Usage="cloudTable.EndExecuteQueryForKeyRotationSegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="15e42-461"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-461">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-462">テーブルで、非同期のセグメント化されたクエリを終了します。</span><span class="sxs-lookup"><span data-stu-id="15e42-462">Ends an asynchronous segmented query on a table.</span></span> 
            </summary>
        <returns><span data-ttu-id="15e42-463">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" />クエリの実行結果を格納します。</span><span class="sxs-lookup"><span data-stu-id="15e42-463">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" /> containing the results of executing the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecuteQuerySegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt; EndExecuteQuerySegmented (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt; EndExecuteQuerySegmented(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndExecuteQuerySegmented(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExecuteQuerySegmented (asyncResult As IAsyncResult) As TableQuerySegment(Of DynamicTableEntity)" />
      <MemberSignature Language="F#" Value="abstract member EndExecuteQuerySegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&#xA;override this.EndExecuteQuerySegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;" Usage="cloudTable.EndExecuteQuerySegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="15e42-464"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-464">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-465">テーブルで、非同期のセグメント化されたクエリを終了します。</span><span class="sxs-lookup"><span data-stu-id="15e42-465">Ends an asynchronous segmented query on a table.</span></span> 
            </summary>
        <returns><span data-ttu-id="15e42-466">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" />クエリの実行結果を格納します。</span><span class="sxs-lookup"><span data-stu-id="15e42-466">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> containing the results of executing the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecuteQuerySegmented&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt; EndExecuteQuerySegmented&lt;TResult&gt; (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt; EndExecuteQuerySegmented&lt;TResult&gt;(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndExecuteQuerySegmented``1(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExecuteQuerySegmented(Of TResult) (asyncResult As IAsyncResult) As TableQuerySegment(Of TResult)" />
      <MemberSignature Language="F#" Value="abstract member EndExecuteQuerySegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&#xA;override this.EndExecuteQuerySegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;" Usage="cloudTable.EndExecuteQuerySegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <typeparam name="TResult"><span data-ttu-id="15e42-467">返される結果の型。</span><span class="sxs-lookup"><span data-stu-id="15e42-467">The type of the results to be returned.</span></span> <span data-ttu-id="15e42-468">Begin で指定されたエンティティ型または競合回避モジュールの結果の型を指定できます。</span><span class="sxs-lookup"><span data-stu-id="15e42-468">Can be the entity type specified in the Begin or the result type of the resolver</span></span></typeparam>
        <param name="asyncResult"><span data-ttu-id="15e42-469"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-469">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-470">セグメント化モードでテーブルをクエリする非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="15e42-470">Ends an asynchronous operation to query a table in segmented mode.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-471">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />クエリの実行結果を格納します。</span><span class="sxs-lookup"><span data-stu-id="15e42-471">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> containing the results of executing the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecuteQuerySegmented&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt; EndExecuteQuerySegmented&lt;TElement,TResult&gt; (IAsyncResult asyncResult) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt; EndExecuteQuerySegmented&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndExecuteQuerySegmented``2(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExecuteQuerySegmented(Of TElement As {ITableEntityNew}, TResult As {ITableEntityNew}) (asyncResult As IAsyncResult) As TableQuerySegment(Of TResult)" />
      <MemberSignature Language="F#" Value="abstract member EndExecuteQuerySegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.EndExecuteQuerySegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.EndExecuteQuerySegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="15e42-472">クエリのエンティティ型。</span><span class="sxs-lookup"><span data-stu-id="15e42-472">The entity type of the query.</span></span></typeparam>
        <typeparam name="TResult"><span data-ttu-id="15e42-473">先の種類、<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />クエリ結果の射影されます。</span><span class="sxs-lookup"><span data-stu-id="15e42-473">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="asyncResult"><span data-ttu-id="15e42-474"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-474">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-475">セグメント化モードでクエリを実行する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="15e42-475">Ends an asynchronous operation to execute a query in segmented mode.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-476">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />を含む型に射影<c>TResult</c>クエリの実行の結果。</span><span class="sxs-lookup"><span data-stu-id="15e42-476">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> containing the projection into type <c>TResult</c> of the results of executing the query.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExists">
      <MemberSignature Language="C#" Value="public virtual bool EndExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndExists : IAsyncResult -&gt; bool&#xA;override this.EndExists : IAsyncResult -&gt; bool" Usage="cloudTable.EndExists asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="15e42-477"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-477">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-478">テーブルが存在するかどうかを判断する非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="15e42-478">Ends an asynchronous operation to determine whether a table exists.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="15e42-479"><c>true</c>テーブルが存在する場合は、それ以外の場合、 <c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-479"><c>true</c> if table exists; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TablePermissions EndGetPermissions (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TablePermissions EndGetPermissions(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndGetPermissions(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetPermissions (asyncResult As IAsyncResult) As TablePermissions" />
      <MemberSignature Language="F#" Value="abstract member EndGetPermissions : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TablePermissions&#xA;override this.EndGetPermissions : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TablePermissions" Usage="cloudTable.EndGetPermissions asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TablePermissions</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="15e42-480"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-480">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-481">テーブルのアクセス許可の設定を取得する要求の非同期の結果を返します。</span><span class="sxs-lookup"><span data-stu-id="15e42-481">Returns the asynchronous result of the request to get the permissions settings for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-482"><see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-482">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetPermissions">
      <MemberSignature Language="C#" Value="public virtual void EndSetPermissions (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetPermissions(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndSetPermissions(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetPermissions (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetPermissions : IAsyncResult -&gt; unit&#xA;override this.EndSetPermissions : IAsyncResult -&gt; unit" Usage="cloudTable.EndSetPermissions asyncResult" />
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
        <param name="asyncResult"><span data-ttu-id="15e42-483"><see cref="T:System.IAsyncResult" />保留中の非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="15e42-483">An <see cref="T:System.IAsyncResult" /> that references the pending asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-484">テーブルのアクセス許可の設定を取得する要求の非同期の結果を返します。</span><span class="sxs-lookup"><span data-stu-id="15e42-484">Returns the asynchronous result of the request to get the permissions settings for the table.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Execute">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableResult Execute (Microsoft.Azure.CosmosDB.Table.TableOperation operation, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableResult Execute(class Microsoft.Azure.CosmosDB.Table.TableOperation operation, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.Execute(Microsoft.Azure.CosmosDB.Table.TableOperation,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Execute : Microsoft.Azure.CosmosDB.Table.TableOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableResult&#xA;override this.Execute : Microsoft.Azure.CosmosDB.Table.TableOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableResult" Usage="cloudTable.Execute (operation, requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="Microsoft.Azure.CosmosDB.Table.TableOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="operation"><span data-ttu-id="15e42-485">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />を実行する操作を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-485">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> object that represents the operation to perform.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-486">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-486">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-487"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-487">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-488">テーブルに対する操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="15e42-488">Executes an operation on a table.</span></span>  
            </summary>
        <returns><span data-ttu-id="15e42-489"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-489">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteAsync (Microsoft.Azure.CosmosDB.Table.TableOperation operation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteAsync(class Microsoft.Azure.CosmosDB.Table.TableOperation operation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteAsync(Microsoft.Azure.CosmosDB.Table.TableOperation)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteAsync (operation As TableOperation) As Task(Of TableResult)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteAsync : Microsoft.Azure.CosmosDB.Table.TableOperation -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&#xA;override this.ExecuteAsync : Microsoft.Azure.CosmosDB.Table.TableOperation -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;" Usage="cloudTable.ExecuteAsync operation" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="Microsoft.Azure.CosmosDB.Table.TableOperation" />
      </Parameters>
      <Docs>
        <param name="operation"><span data-ttu-id="15e42-490">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />を実行する操作を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-490">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> object that represents the operation to perform.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-491">非同期のテーブル操作を実行する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-491">Initiates an asynchronous operation that executes an asynchronous table operation.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-492">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-492">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteAsync (Microsoft.Azure.CosmosDB.Table.TableOperation operation, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteAsync(class Microsoft.Azure.CosmosDB.Table.TableOperation operation, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteAsync(Microsoft.Azure.CosmosDB.Table.TableOperation,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteAsync : Microsoft.Azure.CosmosDB.Table.TableOperation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&#xA;override this.ExecuteAsync : Microsoft.Azure.CosmosDB.Table.TableOperation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;" Usage="cloudTable.ExecuteAsync (operation, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="Microsoft.Azure.CosmosDB.Table.TableOperation" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operation"><span data-ttu-id="15e42-493">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />を実行する操作を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-493">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> object that represents the operation to perform.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-494">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-494">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-495">非同期のテーブル操作を実行する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-495">Initiates an asynchronous operation that executes an asynchronous table operation.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-496">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-496">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteAsync (Microsoft.Azure.CosmosDB.Table.TableOperation operation, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteAsync(class Microsoft.Azure.CosmosDB.Table.TableOperation operation, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteAsync(Microsoft.Azure.CosmosDB.Table.TableOperation,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteAsync : Microsoft.Azure.CosmosDB.Table.TableOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&#xA;override this.ExecuteAsync : Microsoft.Azure.CosmosDB.Table.TableOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;" Usage="cloudTable.ExecuteAsync (operation, requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="Microsoft.Azure.CosmosDB.Table.TableOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="operation"><span data-ttu-id="15e42-497">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />を実行する操作を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-497">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> object that represents the operation to perform.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-498">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-498">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-499"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-499">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-500">非同期のテーブル操作を実行する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-500">Initiates an asynchronous operation that executes an asynchronous table operation.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-501">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-501">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteAsync (Microsoft.Azure.CosmosDB.Table.TableOperation operation, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteAsync(class Microsoft.Azure.CosmosDB.Table.TableOperation operation, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteAsync(Microsoft.Azure.CosmosDB.Table.TableOperation,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteAsync : Microsoft.Azure.CosmosDB.Table.TableOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&#xA;override this.ExecuteAsync : Microsoft.Azure.CosmosDB.Table.TableOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;" Usage="cloudTable.ExecuteAsync (operation, requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="Microsoft.Azure.CosmosDB.Table.TableOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operation"><span data-ttu-id="15e42-502">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />を実行する操作を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-502">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> object that represents the operation to perform.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-503">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-503">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-504"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-504">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-505">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-505">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-506">非同期のテーブル操作を実行する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-506">Initiates an asynchronous operation that executes an asynchronous table operation.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-507">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-507">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteBatch">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteBatch (Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteBatch(class Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteBatch(Microsoft.Azure.CosmosDB.Table.TableBatchOperation,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteBatch : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&#xA;override this.ExecuteBatch : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;" Usage="cloudTable.ExecuteBatch (batch, requestOptions, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="batch"><span data-ttu-id="15e42-508"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />テーブルに対して実行する操作を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-508">The <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> object representing the operations to execute on the table.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-509">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-509">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-510"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-510">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-511">分割不可能な操作として、テーブルに対するバッチ操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="15e42-511">Executes a batch operation on a table as an atomic operation.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-512">列挙可能なコレクション<see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" />オブジェクト内の各操作の順序で、結果を含む、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />テーブルにします。</span><span class="sxs-lookup"><span data-stu-id="15e42-512">An enumerable collection of <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> objects that contains the results, in order, of each operation in the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> on the table.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteBatchAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt; ExecuteBatchAsync (Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt; ExecuteBatchAsync(class Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteBatchAsync(Microsoft.Azure.CosmosDB.Table.TableBatchOperation)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteBatchAsync (batch As TableBatchOperation) As Task(Of IList(Of TableResult))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteBatchAsync : Microsoft.Azure.CosmosDB.Table.TableBatchOperation -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;&#xA;override this.ExecuteBatchAsync : Microsoft.Azure.CosmosDB.Table.TableBatchOperation -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;" Usage="cloudTable.ExecuteBatchAsync batch" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />
      </Parameters>
      <Docs>
        <param name="batch"><span data-ttu-id="15e42-513"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />テーブルに対して実行する操作を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-513">The <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> object representing the operations to execute on the table.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-514">テーブルに対する操作のバッチを実行する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-514">Initiates an asynchronous operation to execute a batch of operations on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-515">A<see cref="T:System.Threading.Tasks.Task`1" />型のリストであるオブジェクトを<see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-515">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is list of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteBatchAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt; ExecuteBatchAsync (Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt; ExecuteBatchAsync(class Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteBatchAsync(Microsoft.Azure.CosmosDB.Table.TableBatchOperation,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteBatchAsync : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;&#xA;override this.ExecuteBatchAsync : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;" Usage="cloudTable.ExecuteBatchAsync (batch, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="batch"><span data-ttu-id="15e42-516"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />テーブルに対して実行する操作を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-516">The <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> object representing the operations to execute on the table.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-517">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-517">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-518">テーブルに対する操作のバッチを実行する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-518">Initiates an asynchronous operation to execute a batch of operations on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-519">A<see cref="T:System.Threading.Tasks.Task`1" />型のリストであるオブジェクトを<see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-519">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is list of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteBatchAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt; ExecuteBatchAsync (Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt; ExecuteBatchAsync(class Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteBatchAsync(Microsoft.Azure.CosmosDB.Table.TableBatchOperation,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteBatchAsync : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;&#xA;override this.ExecuteBatchAsync : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;" Usage="cloudTable.ExecuteBatchAsync (batch, requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="batch"><span data-ttu-id="15e42-520"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />テーブルに対して実行する操作を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-520">The <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> object representing the operations to execute on the table.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-521">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-521">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-522"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-522">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-523">テーブルに対する操作のバッチを実行する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-523">Initiates an asynchronous operation to execute a batch of operations on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-524">A<see cref="T:System.Threading.Tasks.Task`1" />型のリストであるオブジェクトを<see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-524">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is list of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteBatchAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt; ExecuteBatchAsync (Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt; ExecuteBatchAsync(class Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteBatchAsync(Microsoft.Azure.CosmosDB.Table.TableBatchOperation,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteBatchAsync : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;&#xA;override this.ExecuteBatchAsync : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;" Usage="cloudTable.ExecuteBatchAsync (batch, requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="batch"><span data-ttu-id="15e42-525"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />テーブルに対して実行する操作を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-525">The <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> object representing the operations to execute on the table.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-526">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-526">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-527"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-527">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-528">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-528">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-529">テーブルに対する操作のバッチを実行する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-529">Initiates an asynchronous operation to execute a batch of operations on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-530">A<see cref="T:System.Threading.Tasks.Task`1" />型のリストであるオブジェクトを<see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-530">A <see cref="T:System.Threading.Tasks.Task`1" /> object that is list of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuery">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt; ExecuteQuery (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt; ExecuteQuery(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuery(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuery : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&#xA;override this.ExecuteQuery : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;" Usage="cloudTable.ExecuteQuery (query, requestOptions, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="15e42-531">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />を表すクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="15e42-531">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-532">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-532">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-533"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-533">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-534">テーブルに対するクエリを実行しの列挙可能なコレクションを返します<see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-534">Executes a query on a table and returns an enumerable collection of <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> objects.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-535">列挙可能なコレクション<see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" />をクエリによって返されるテーブル エンティティを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-535">An enumerable collection of <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> objects, representing table entities returned by the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuery&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;TElement&gt; ExecuteQuery&lt;TElement&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!!TElement&gt; ExecuteQuery&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuery``1(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuery : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuery : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuery (query, requestOptions, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="15e42-536">クエリのエンティティ型。</span><span class="sxs-lookup"><span data-stu-id="15e42-536">The entity type of the query.</span></span></typeparam>
        <param name="query"><span data-ttu-id="15e42-537">型のテーブルをクエリし、使用するクエリ パラメーターを指定して TableQuery インスタンスに特殊化<c>TElement</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-537">A TableQuery instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-538">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-538">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-539"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-539">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-540">テーブルに対するクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="15e42-540">Executes a query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-541">型の列挙可能なコレクションに特殊化<c>TElement</c>クエリの実行の結果。</span><span class="sxs-lookup"><span data-stu-id="15e42-541">An enumerable collection, specialized for type <c>TElement</c>, of the results of executing the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuery&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;TResult&gt; ExecuteQuery&lt;TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!!TResult&gt; ExecuteQuery&lt;TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuery``1(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuery : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;'Result&gt;&#xA;override this.ExecuteQuery : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;'Result&gt;" Usage="cloudTable.ExecuteQuery (query, resolver, requestOptions, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">To be added.</typeparam>
        <param name="query"><span data-ttu-id="15e42-542">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />を表すクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="15e42-542">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="resolver"><span data-ttu-id="15e42-543"><see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-543">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-544">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-544">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-545"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-545">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-546">テーブルに対するクエリを実行し、指定された適用<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />結果にします。</span><span class="sxs-lookup"><span data-stu-id="15e42-546">Executes a query on a table and applies the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the result.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-547">型に射影を含む列挙可能なコレクション<c>TResult</c>クエリの実行の結果。</span><span class="sxs-lookup"><span data-stu-id="15e42-547">An enumerable collection, containing the projection into type <c>TResult</c>, of the results of executing the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuery&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;TResult&gt; ExecuteQuery&lt;TElement,TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!!TResult&gt; ExecuteQuery&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuery``2(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.EntityResolver{``1},Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuery : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;'Result&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuery : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;'Result&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuery (query, resolver, requestOptions, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="15e42-548">クエリのエンティティ型。</span><span class="sxs-lookup"><span data-stu-id="15e42-548">The entity type of the query.</span></span></typeparam>
        <typeparam name="TResult"><span data-ttu-id="15e42-549">先の種類、<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />クエリ結果の射影されます。</span><span class="sxs-lookup"><span data-stu-id="15e42-549">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="query"><span data-ttu-id="15e42-550">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-550">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="resolver"><span data-ttu-id="15e42-551"><see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-551">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-552">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-552">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-553"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-553">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-554">クエリを実行し、指定された適用<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />結果にします。</span><span class="sxs-lookup"><span data-stu-id="15e42-554">Executes a query and applies the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the result.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-555">型に射影を含む列挙可能なコレクション<c>TResult</c>クエリの実行の結果。</span><span class="sxs-lookup"><span data-stu-id="15e42-555">An enumerable collection, containing the projection into type <c>TResult</c>, of the results of executing the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQueryForKeyRotation">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt; ExecuteQueryForKeyRotation (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt; ExecuteQueryForKeyRotation(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQueryForKeyRotation(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQueryForKeyRotation : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&#xA;override this.ExecuteQueryForKeyRotation : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;" Usage="cloudTable.ExecuteQueryForKeyRotation (query, requestOptions, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="15e42-556">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />を表すクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="15e42-556">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-557">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-557">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-558"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-558">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-559">テーブルに対するクエリを実行しの列挙可能なコレクションを返します<see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-559">Executes a query on a table and returns an enumerable collection of <see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" /> objects.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-560">列挙可能なコレクション<see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" />をクエリによって返されるテーブル エンティティを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-560">An enumerable collection of <see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" /> objects, representing table entities returned by the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQueryForKeyRotationSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt; ExecuteQueryForKeyRotationSegmented (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt; ExecuteQueryForKeyRotationSegmented(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQueryForKeyRotationSegmented(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQueryForKeyRotationSegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&#xA;override this.ExecuteQueryForKeyRotationSegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;" Usage="cloudTable.ExecuteQueryForKeyRotationSegmented (query, token, requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="15e42-561">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />を表すクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="15e42-561">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-562">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-562">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-563">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-563">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-564"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-564">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-565">テーブルのセグメント化されたクエリを実行し、返します、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />を含む<see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-565">Executes a segmented query on a table and returns a <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> containing <see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" /> objects.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-566">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" />クエリの実行結果を格納します。</span><span class="sxs-lookup"><span data-stu-id="15e42-566">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" /> containing the results of executing the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQueryForKeyRotationSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQueryForKeyRotationSegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteQueryForKeyRotationSegmentedAsync (query As TableQuery, token As TableContinuationToken) As Task(Of TableQuerySegment(Of KeyRotationEntity))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;&#xA;override this.ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;" Usage="cloudTable.ExecuteQueryForKeyRotationSegmentedAsync (query, token)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="15e42-567">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />を表すクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="15e42-567">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-568">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-568">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-569">テーブルにセグメント化されたクエリを実行する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-569">Initiates an asynchronous operation to perform a segmented query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-570">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-570">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQueryForKeyRotationSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQueryForKeyRotationSegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;&#xA;override this.ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;" Usage="cloudTable.ExecuteQueryForKeyRotationSegmentedAsync (query, token, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="15e42-571">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />を表すクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="15e42-571">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-572">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-572">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-573">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-573">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-574">テーブルにセグメント化されたクエリを実行する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-574">Initiates an asynchronous operation to perform a segmented query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-575">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-575">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQueryForKeyRotationSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQueryForKeyRotationSegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;&#xA;override this.ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;" Usage="cloudTable.ExecuteQueryForKeyRotationSegmentedAsync (query, token, requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="15e42-576">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />を表すクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="15e42-576">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-577">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-577">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-578">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-578">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-579"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-579">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-580">テーブルにセグメント化されたクエリを実行する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-580">Initiates an asynchronous operation to perform a segmented query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-581">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-581">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQueryForKeyRotationSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQueryForKeyRotationSegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;&#xA;override this.ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;" Usage="cloudTable.ExecuteQueryForKeyRotationSegmentedAsync (query, token, requestOptions, operationContext, cancellationToken)" />
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
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.CosmosDB.Table.CloudTable/&lt;ExecuteQueryForKeyRotationSegmentedAsync&gt;d__85))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="15e42-582">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />を表すクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="15e42-582">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-583">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-583">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-584">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-584">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-585"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-585">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-586">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-586">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-587">テーブルにセグメント化されたクエリを実行する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-587">Initiates an asynchronous operation to perform a segmented query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-588">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-588">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt; ExecuteQuerySegmented (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt; ExecuteQuerySegmented(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmented(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&#xA;override this.ExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;" Usage="cloudTable.ExecuteQuerySegmented (query, token, requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="15e42-589">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />を表すクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="15e42-589">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-590">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-590">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-591">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-591">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-592"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-592">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-593">テーブルのセグメント化されたクエリを実行し、返します、<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />を含む<see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-593">Executes a segmented query on a table and returns a <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> containing <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> objects.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-594">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" />クエリの実行結果を格納します。</span><span class="sxs-lookup"><span data-stu-id="15e42-594">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> containing the results of executing the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmented&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt; ExecuteQuerySegmented&lt;TElement&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TElement&gt; ExecuteQuerySegmented&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmented``1(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmented (query, token, requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="15e42-595">クエリのエンティティ型。</span><span class="sxs-lookup"><span data-stu-id="15e42-595">The entity type of the query.</span></span></typeparam>
        <param name="query"><span data-ttu-id="15e42-596">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-596">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-597">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-597">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-598">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-598">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-599"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-599">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-600">セグメント化モードでテーブルに対するクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="15e42-600">Executes a query on a table in segmented mode.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-601">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />型に対して特殊化されて、 <c>TElement</c>クエリの実行の結果を格納します。</span><span class="sxs-lookup"><span data-stu-id="15e42-601">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />, specialized for type <c>TElement</c>, containing the results of executing the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmented&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt; ExecuteQuerySegmented&lt;TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt; ExecuteQuerySegmented&lt;TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmented``1(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&#xA;override this.ExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;" Usage="cloudTable.ExecuteQuerySegmented (query, resolver, token, requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">To be added.</typeparam>
        <param name="query"><span data-ttu-id="15e42-602">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />を表すクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="15e42-602">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="resolver"><span data-ttu-id="15e42-603"><see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-603">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-604">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-604">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-605">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-605">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-606"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-606">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-607">テーブルでセグメント化されたクエリを実行し、指定された適用<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />結果にします。</span><span class="sxs-lookup"><span data-stu-id="15e42-607">Executes a segmented query on a table and applies the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the result.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-608">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />クエリの実行結果を含むオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-608">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> object containing the results of executing the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmented&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt; ExecuteQuerySegmented&lt;TElement,TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt; ExecuteQuerySegmented&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmented``2(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.EntityResolver{``1},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmented (query, resolver, token, requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="15e42-609">クエリのエンティティ型。</span><span class="sxs-lookup"><span data-stu-id="15e42-609">The entity type of the query.</span></span></typeparam>
        <typeparam name="TResult"><span data-ttu-id="15e42-610">先の種類、<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />クエリ結果の射影されます。</span><span class="sxs-lookup"><span data-stu-id="15e42-610">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="query"><span data-ttu-id="15e42-611">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-611">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="resolver"><span data-ttu-id="15e42-612"><see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-612">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-613">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-613">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-614">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-614">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-615"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-615">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-616">セグメント化モードでクエリを実行し、指定された適用<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />結果にします。</span><span class="sxs-lookup"><span data-stu-id="15e42-616">Executes a query in segmented mode and applies the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the results.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-617">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />を含む型に射影<c>TResult</c>クエリの実行の結果。</span><span class="sxs-lookup"><span data-stu-id="15e42-617">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> containing the projection into type <c>TResult</c> of the results of executing the query.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteQuerySegmentedAsync (query As TableQuery, token As TableContinuationToken) As Task(Of TableQuerySegment(Of DynamicTableEntity))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="15e42-618">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />を表すクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="15e42-618">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-619">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-619">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-620">テーブルにセグメント化されたクエリを実行する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-620">Initiates an asynchronous operation to perform a segmented query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-621">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-621">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="15e42-622">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />を表すクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="15e42-622">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-623">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-623">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-624">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-624">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-625">テーブルにセグメント化されたクエリを実行する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-625">Initiates an asynchronous operation to perform a segmented query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-626">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-626">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token, requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="15e42-627">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />を表すクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="15e42-627">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-628">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-628">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-629">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-629">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-630"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-630">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-631">テーブルにセグメント化されたクエリを実行する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-631">Initiates an asynchronous operation to perform a segmented query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-632">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-632">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token, requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="15e42-633">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />を表すクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="15e42-633">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> representing the query to execute.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-634">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-634">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-635">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-635">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-636"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-636">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-637">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-637">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-638">テーブルにセグメント化されたクエリを実行する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-638">Initiates an asynchronous operation to perform a segmented query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-639">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-639">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteQuerySegmentedAsync(Of TElement As {ITableEntityNew}) (query As TableQuery(Of TElement), token As TableContinuationToken) As Task(Of TableQuerySegment(Of TElement))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="15e42-640">クエリのエンティティ型。</span><span class="sxs-lookup"><span data-stu-id="15e42-640">The entity type of the query.</span></span></typeparam>
        <param name="query"><span data-ttu-id="15e42-641">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-641">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-642">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-642">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-643">セグメント化モードでテーブルをクエリする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-643">Initiates an asynchronous operation to query a table in segmented mode.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-644">非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-644">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, System.Threading.CancellationToken cancellationToken) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="15e42-645">クエリのエンティティ型。</span><span class="sxs-lookup"><span data-stu-id="15e42-645">The entity type of the query.</span></span></typeparam>
        <param name="query"><span data-ttu-id="15e42-646">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-646">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-647">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-647">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-648">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-648">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-649">セグメント化モードでテーブルをクエリする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-649">Initiates an asynchronous operation to query a table in segmented mode.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-650">非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-650">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token, requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="15e42-651">クエリのエンティティ型。</span><span class="sxs-lookup"><span data-stu-id="15e42-651">The entity type of the query.</span></span></typeparam>
        <param name="query"><span data-ttu-id="15e42-652">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-652">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-653">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-653">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-654">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-654">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-655"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-655">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-656">セグメント化モードでテーブルをクエリする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-656">Initiates an asynchronous operation to query a table in segmented mode.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-657">非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-657">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token, requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="15e42-658">クエリのエンティティ型。</span><span class="sxs-lookup"><span data-stu-id="15e42-658">The entity type of the query.</span></span></typeparam>
        <param name="query"><span data-ttu-id="15e42-659">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-659">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-660">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-660">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-661">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-661">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-662"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-662">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-663">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-663">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-664">セグメント化モードでテーブルをクエリする非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-664">Initiates an asynchronous operation to query a table in segmented mode.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-665">非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-665">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteQuerySegmentedAsync(Of TResult) (query As TableQuery, resolver As EntityResolver(Of TResult), token As TableContinuationToken) As Task(Of TableQuerySegment(Of TResult))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TResult"><span data-ttu-id="15e42-666">先の種類、<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />クエリ結果の射影されます。</span><span class="sxs-lookup"><span data-stu-id="15e42-666">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="query"><span data-ttu-id="15e42-667">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />クエリおよびクエリ パラメーターを使用するテーブルを指定します。</span><span class="sxs-lookup"><span data-stu-id="15e42-667">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use.</span></span></param>
        <param name="resolver"><span data-ttu-id="15e42-668"><see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-668">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-669">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-669">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-670">セグメント化されたクエリを実行し、指定されたを適用する非同期操作を開始<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />結果にします。</span><span class="sxs-lookup"><span data-stu-id="15e42-670">Initiates an asynchronous operation to execute a segmented query and apply the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the result.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-671">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-671">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TResult"><span data-ttu-id="15e42-672">先の種類、<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />クエリ結果の射影されます。</span><span class="sxs-lookup"><span data-stu-id="15e42-672">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="query"><span data-ttu-id="15e42-673">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />クエリおよびクエリ パラメーターを使用するテーブルを指定します。</span><span class="sxs-lookup"><span data-stu-id="15e42-673">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use.</span></span></param>
        <param name="resolver"><span data-ttu-id="15e42-674"><see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-674">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-675">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-675">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-676">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-676">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-677">セグメント化されたクエリを実行し、指定されたを適用する非同期操作を開始<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />結果にします。</span><span class="sxs-lookup"><span data-stu-id="15e42-677">Initiates an asynchronous operation to execute a segmented query and apply the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the result.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-678">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-678">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token, requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TResult"><span data-ttu-id="15e42-679">先の種類、<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />クエリ結果の射影されます。</span><span class="sxs-lookup"><span data-stu-id="15e42-679">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="query"><span data-ttu-id="15e42-680">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />クエリおよびクエリ パラメーターを使用するテーブルを指定します。</span><span class="sxs-lookup"><span data-stu-id="15e42-680">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use.</span></span></param>
        <param name="resolver"><span data-ttu-id="15e42-681"><see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-681">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-682">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-682">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-683">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-683">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-684"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-684">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-685">セグメント化されたクエリを実行し、指定されたを適用する非同期操作を開始<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />結果にします。</span><span class="sxs-lookup"><span data-stu-id="15e42-685">Initiates an asynchronous operation to execute a segmented query and apply the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the result.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-686">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-686">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token, requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TResult"><span data-ttu-id="15e42-687">先の種類、<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />クエリ結果の射影されます。</span><span class="sxs-lookup"><span data-stu-id="15e42-687">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="query"><span data-ttu-id="15e42-688">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />クエリおよびクエリ パラメーターを使用するテーブルを指定します。</span><span class="sxs-lookup"><span data-stu-id="15e42-688">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use.</span></span></param>
        <param name="resolver"><span data-ttu-id="15e42-689"><see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-689">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-690">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-690">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-691">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-691">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-692"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-692">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-693">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-693">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-694">セグメント化されたクエリを実行し、指定されたを適用する非同期操作を開始<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />結果にします。</span><span class="sxs-lookup"><span data-stu-id="15e42-694">Initiates an asynchronous operation to execute a segmented query and apply the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the result.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-695">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-695">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``2(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.EntityResolver{``1},Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteQuerySegmentedAsync(Of TElement As {ITableEntityNew}, TResult As {ITableEntityNew}) (query As TableQuery(Of TElement), resolver As EntityResolver(Of TResult), token As TableContinuationToken) As Task(Of TableQuerySegment(Of TResult))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="15e42-696">クエリのエンティティ型。</span><span class="sxs-lookup"><span data-stu-id="15e42-696">The entity type of the query.</span></span></typeparam>
        <typeparam name="TResult"><span data-ttu-id="15e42-697">先の種類、<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />クエリ結果の射影されます。</span><span class="sxs-lookup"><span data-stu-id="15e42-697">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="query"><span data-ttu-id="15e42-698">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-698">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="resolver"><span data-ttu-id="15e42-699"><see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-699">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-700">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-700">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-701">セグメント化モードでクエリを実行し、指定されたを適用する非同期操作を開始<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />結果にします。</span><span class="sxs-lookup"><span data-stu-id="15e42-701">Initiates an asynchronous operation to execute a query in segmented mode and apply the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the results.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-702">非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-702">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, System.Threading.CancellationToken cancellationToken) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``2(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.EntityResolver{``1},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="15e42-703">クエリのエンティティ型。</span><span class="sxs-lookup"><span data-stu-id="15e42-703">The entity type of the query.</span></span></typeparam>
        <typeparam name="TResult"><span data-ttu-id="15e42-704">先の種類、<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />クエリ結果の射影されます。</span><span class="sxs-lookup"><span data-stu-id="15e42-704">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="query"><span data-ttu-id="15e42-705">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-705">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="resolver"><span data-ttu-id="15e42-706"><see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-706">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-707">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-707">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-708">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-708">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-709">セグメント化モードでクエリを実行し、指定されたを適用する非同期操作を開始<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />結果にします。</span><span class="sxs-lookup"><span data-stu-id="15e42-709">Initiates an asynchronous operation to execute a query in segmented mode and apply the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the results.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-710">非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-710">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``2(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.EntityResolver{``1},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token, requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="15e42-711">クエリのエンティティ型。</span><span class="sxs-lookup"><span data-stu-id="15e42-711">The entity type of the query.</span></span></typeparam>
        <typeparam name="TResult"><span data-ttu-id="15e42-712">先の種類、<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />クエリ結果の射影されます。</span><span class="sxs-lookup"><span data-stu-id="15e42-712">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="query"><span data-ttu-id="15e42-713">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-713">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="resolver"><span data-ttu-id="15e42-714"><see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-714">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-715">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-715">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-716">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-716">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-717"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-717">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-718">セグメント化モードでクエリを実行し、指定されたを適用する非同期操作を開始<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />結果にします。</span><span class="sxs-lookup"><span data-stu-id="15e42-718">Initiates an asynchronous operation to execute a query in segmented mode and apply the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the results.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-719">非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-719">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``2(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.EntityResolver{``1},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token, requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TElement"><span data-ttu-id="15e42-720">クエリのエンティティ型。</span><span class="sxs-lookup"><span data-stu-id="15e42-720">The entity type of the query.</span></span></typeparam>
        <typeparam name="TResult"><span data-ttu-id="15e42-721">先の種類、<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />クエリ結果の射影されます。</span><span class="sxs-lookup"><span data-stu-id="15e42-721">The type into which the <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> will project the query results.</span></span></typeparam>
        <param name="query"><span data-ttu-id="15e42-722">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />インスタンスの型に特化したテーブルをクエリし、使用するクエリ パラメーターを指定する<c>TElement</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-722">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance specifying the table to query and the query parameters to use, specialized for a type <c>TElement</c>.</span></span></param>
        <param name="resolver"><span data-ttu-id="15e42-723"><see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />射影する、テーブルのクエリ結果エンティティを指定した型にインスタンス<c>TResult</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-723">An <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> instance which creates a projection of the table query result entities into the specified type <c>TResult</c>.</span></span></param>
        <param name="token"><span data-ttu-id="15e42-724">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-724">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-725">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-725">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-726"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-726">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-727">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-727">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-728">セグメント化モードでクエリを実行し、指定されたを適用する非同期操作を開始<see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" />結果にします。</span><span class="sxs-lookup"><span data-stu-id="15e42-728">Initiates an asynchronous operation to execute a query in segmented mode and apply the specified <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> to the results.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-729">非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-729">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public virtual bool Exists (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Exists(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.Exists(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Exists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; bool&#xA;override this.Exists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; bool" Usage="cloudTable.Exists (requestOptions, operationContext)" />
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="15e42-730">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-730">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-731"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-731">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-732">テーブルが存在するかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="15e42-732">Checks whether the table exists.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="15e42-733"><c>true</c>テーブルが存在する場合は、それ以外の場合、 <c>false</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-733"><c>true</c> if table exists; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.ExistsAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="15e42-734">テーブルが存在するかどうかを判断する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-734">Initiates an asynchronous operation to determine whether a table exists.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-735">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-735">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.ExistsAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="15e42-736">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-736">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-737">テーブルが存在するかどうかを判断する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-737">Initiates an asynchronous operation to determine whether a table exists.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-738">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-738">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExistsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.ExistsAsync (requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="15e42-739">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-739">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-740"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-740">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-741">テーブルが存在するかどうかを判断する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-741">Initiates an asynchronous operation to determine whether a table exists.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-742">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-742">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExistsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.ExistsAsync (requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="15e42-743">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-743">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-744"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-744">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-745">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-745">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-746">テーブルが存在するかどうかを判断する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-746">Initiates an asynchronous operation to determine whether a table exists.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-747">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<c>bool</c>非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-747">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <c>bool</c> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TablePermissions GetPermissions (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TablePermissions GetPermissions(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetPermissions(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissions : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TablePermissions&#xA;override this.GetPermissions : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TablePermissions" Usage="cloudTable.GetPermissions (requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TablePermissions</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="15e42-748">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-748">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-749"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-749">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-750">テーブルのアクセス許可の設定を取得します。</span><span class="sxs-lookup"><span data-stu-id="15e42-750">Gets the permissions settings for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-751"><see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-751">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt; GetPermissionsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TablePermissions&gt; GetPermissionsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetPermissionsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetPermissionsAsync () As Task(Of TablePermissions)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;&#xA;override this.GetPermissionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;" Usage="cloudTable.GetPermissionsAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="15e42-752">テーブルのアクセス許可の設定を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-752">Initiates an asynchronous operation to get the permissions settings for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-753">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-753">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt; GetPermissionsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TablePermissions&gt; GetPermissionsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetPermissionsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;&#xA;override this.GetPermissionsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;" Usage="cloudTable.GetPermissionsAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="15e42-754">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-754">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-755">テーブルのアクセス許可の設定を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-755">Initiates an asynchronous operation to get the permissions settings for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-756">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-756">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt; GetPermissionsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TablePermissions&gt; GetPermissionsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetPermissionsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;&#xA;override this.GetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;" Usage="cloudTable.GetPermissionsAsync (requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="15e42-757">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-757">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-758"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-758">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-759">テーブルのアクセス許可の設定を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-759">Initiates an asynchronous operation to get the permissions settings for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-760">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-760">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt; GetPermissionsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TablePermissions&gt; GetPermissionsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetPermissionsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;&#xA;override this.GetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;" Usage="cloudTable.GetPermissionsAsync (requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="15e42-761">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-761">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-762"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-762">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-763">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-763">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-764">テーブルのアクセス許可の設定を取得する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-764">Initiates an asynchronous operation to get the permissions settings for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-765">A<see cref="T:System.Threading.Tasks.Task`1" />型のオブジェクト<see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="15e42-765">A <see cref="T:System.Threading.Tasks.Task`1" /> object of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy policy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy policy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetSharedAccessSignature(Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSharedAccessSignature (policy As SharedAccessTablePolicy) As String" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy -&gt; string" Usage="cloudTable.GetSharedAccessSignature policy" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policy" Type="Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" />
      </Parameters>
      <Docs>
        <param name="policy"><span data-ttu-id="15e42-766">A<see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" />共有アクセス署名のアクセス ポリシーを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-766">A <see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" /> object specifying the access policy for the shared access signature.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-767">テーブルの共有アクセス署名を返します。</span><span class="sxs-lookup"><span data-stu-id="15e42-767">Returns a shared access signature for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-768">URI クエリ文字列としての共有アクセス署名します。</span><span class="sxs-lookup"><span data-stu-id="15e42-768">A shared access signature, as a URI query string.</span></span></returns>
        <remarks><span data-ttu-id="15e42-769">返されるクエリ文字列には、先頭に疑問符が含まれています。</span><span class="sxs-lookup"><span data-stu-id="15e42-769">The query string returned includes the leading question mark.</span></span></remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="15e42-770">現在の資格情報が共有アクセス署名の作成をサポートしていない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="15e42-770">Thrown if the current credentials don't support creating a shared access signature.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy policy, string accessPolicyIdentifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy policy, string accessPolicyIdentifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetSharedAccessSignature(Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSharedAccessSignature (policy As SharedAccessTablePolicy, accessPolicyIdentifier As String) As String" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy * string -&gt; string" Usage="cloudTable.GetSharedAccessSignature (policy, accessPolicyIdentifier)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policy" Type="Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" />
        <Parameter Name="accessPolicyIdentifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="policy"><span data-ttu-id="15e42-771">A<see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" />共有アクセス署名のアクセス ポリシーを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-771">A <see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" /> object specifying the access policy for the shared access signature.</span></span></param>
        <param name="accessPolicyIdentifier"><span data-ttu-id="15e42-772">保存されているアクセス ポリシーを識別する文字列。</span><span class="sxs-lookup"><span data-stu-id="15e42-772">A string identifying a stored access policy.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-773">テーブルの共有アクセス署名を返します。</span><span class="sxs-lookup"><span data-stu-id="15e42-773">Returns a shared access signature for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-774">URI クエリ文字列としての共有アクセス署名します。</span><span class="sxs-lookup"><span data-stu-id="15e42-774">A shared access signature, as a URI query string.</span></span></returns>
        <remarks><span data-ttu-id="15e42-775">返されるクエリ文字列には、先頭に疑問符が含まれています。</span><span class="sxs-lookup"><span data-stu-id="15e42-775">The query string returned includes the leading question mark.</span></span></remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="15e42-776">現在の資格情報が共有アクセス署名の作成をサポートしていない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="15e42-776">Thrown if the current credentials don't support creating a shared access signature.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy policy, string accessPolicyIdentifier, string startPartitionKey, string startRowKey, string endPartitionKey, string endRowKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy policy, string accessPolicyIdentifier, string startPartitionKey, string startRowKey, string endPartitionKey, string endRowKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetSharedAccessSignature(Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSharedAccessSignature (policy As SharedAccessTablePolicy, accessPolicyIdentifier As String, startPartitionKey As String, startRowKey As String, endPartitionKey As String, endRowKey As String) As String" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy * string * string * string * string * string -&gt; string" Usage="cloudTable.GetSharedAccessSignature (policy, accessPolicyIdentifier, startPartitionKey, startRowKey, endPartitionKey, endRowKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policy" Type="Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" />
        <Parameter Name="accessPolicyIdentifier" Type="System.String" />
        <Parameter Name="startPartitionKey" Type="System.String" />
        <Parameter Name="startRowKey" Type="System.String" />
        <Parameter Name="endPartitionKey" Type="System.String" />
        <Parameter Name="endRowKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="policy"><span data-ttu-id="15e42-777">A<see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" />共有アクセス署名のアクセス ポリシーを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-777">A <see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" /> object specifying the access policy for the shared access signature.</span></span></param>
        <param name="accessPolicyIdentifier"><span data-ttu-id="15e42-778">保存されているアクセス ポリシーを識別する文字列。</span><span class="sxs-lookup"><span data-stu-id="15e42-778">A string identifying a stored access policy.</span></span></param>
        <param name="startPartitionKey"><span data-ttu-id="15e42-779">開始パーティション キーを指定する文字列または<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-779">A string specifying the start partition key, or <c>null</c>.</span></span></param>
        <param name="startRowKey"><span data-ttu-id="15e42-780">開始行キーを指定する文字列または<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-780">A string specifying the start row key, or <c>null</c>.</span></span></param>
        <param name="endPartitionKey"><span data-ttu-id="15e42-781">終了パーティション キーを指定する文字列または<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-781">A string specifying the end partition key, or <c>null</c>.</span></span></param>
        <param name="endRowKey"><span data-ttu-id="15e42-782">終了行キーを指定する文字列または<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-782">A string specifying the end row key, or <c>null</c>.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-783">テーブルの共有アクセス署名を返します。</span><span class="sxs-lookup"><span data-stu-id="15e42-783">Returns a shared access signature for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-784">URI クエリ文字列としての共有アクセス署名します。</span><span class="sxs-lookup"><span data-stu-id="15e42-784">A shared access signature, as a URI query string.</span></span></returns>
        <remarks><span data-ttu-id="15e42-785">返されるクエリ文字列には、先頭に疑問符が含まれています。</span><span class="sxs-lookup"><span data-stu-id="15e42-785">The query string returned includes the leading question mark.</span></span></remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="15e42-786">現在の資格情報が共有アクセス署名の作成をサポートしていない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="15e42-786">Thrown if the current credentials don't support creating a shared access signature.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy policy, string accessPolicyIdentifier, string startPartitionKey, string startRowKey, string endPartitionKey, string endRowKey, Nullable&lt;Microsoft.Azure.Storage.SharedAccessProtocol&gt; protocols, Microsoft.Azure.Storage.IPAddressOrRange ipAddressOrRange);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy policy, string accessPolicyIdentifier, string startPartitionKey, string startRowKey, string endPartitionKey, string endRowKey, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Storage.SharedAccessProtocol&gt; protocols, class Microsoft.Azure.Storage.IPAddressOrRange ipAddressOrRange) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetSharedAccessSignature(Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy,System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Storage.SharedAccessProtocol},Microsoft.Azure.Storage.IPAddressOrRange)" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy * string * string * string * string * string * Nullable&lt;Microsoft.Azure.Storage.SharedAccessProtocol&gt; * Microsoft.Azure.Storage.IPAddressOrRange -&gt; string" Usage="cloudTable.GetSharedAccessSignature (policy, accessPolicyIdentifier, startPartitionKey, startRowKey, endPartitionKey, endRowKey, protocols, ipAddressOrRange)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policy" Type="Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" />
        <Parameter Name="accessPolicyIdentifier" Type="System.String" />
        <Parameter Name="startPartitionKey" Type="System.String" />
        <Parameter Name="startRowKey" Type="System.String" />
        <Parameter Name="endPartitionKey" Type="System.String" />
        <Parameter Name="endRowKey" Type="System.String" />
        <Parameter Name="protocols" Type="System.Nullable&lt;Microsoft.Azure.Storage.SharedAccessProtocol&gt;" />
        <Parameter Name="ipAddressOrRange" Type="Microsoft.Azure.Storage.IPAddressOrRange" />
      </Parameters>
      <Docs>
        <param name="policy"><span data-ttu-id="15e42-787">A<see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" />共有アクセス署名のアクセス ポリシーを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-787">A <see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" /> object specifying the access policy for the shared access signature.</span></span></param>
        <param name="accessPolicyIdentifier"><span data-ttu-id="15e42-788">保存されているアクセス ポリシーを識別する文字列。</span><span class="sxs-lookup"><span data-stu-id="15e42-788">A string identifying a stored access policy.</span></span></param>
        <param name="startPartitionKey"><span data-ttu-id="15e42-789">開始パーティション キーを指定する文字列または<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-789">A string specifying the start partition key, or <c>null</c>.</span></span></param>
        <param name="startRowKey"><span data-ttu-id="15e42-790">開始行キーを指定する文字列または<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-790">A string specifying the start row key, or <c>null</c>.</span></span></param>
        <param name="endPartitionKey"><span data-ttu-id="15e42-791">終了パーティション キーを指定する文字列または<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-791">A string specifying the end partition key, or <c>null</c>.</span></span></param>
        <param name="endRowKey"><span data-ttu-id="15e42-792">終了行キーを指定する文字列または<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="15e42-792">A string specifying the end row key, or <c>null</c>.</span></span></param>
        <param name="protocols"><span data-ttu-id="15e42-793">許可されているプロトコル (https のみ、または http と https)。</span><span class="sxs-lookup"><span data-stu-id="15e42-793">The allowed protocols (https only, or http and https).</span></span> <span data-ttu-id="15e42-794">プロトコルを制限したくない場合は null です。</span><span class="sxs-lookup"><span data-stu-id="15e42-794">Null if you don't want to restrict protocol.</span></span></param>
        <param name="ipAddressOrRange"><span data-ttu-id="15e42-795">許可されている IP アドレスまたは IP アドレスの範囲を実行します。</span><span class="sxs-lookup"><span data-stu-id="15e42-795">The allowed IP address or IP address range.</span></span> <span data-ttu-id="15e42-796">Null を制限したくない場合は、IP アドレスに基づいています。</span><span class="sxs-lookup"><span data-stu-id="15e42-796">Null if you don't want to restrict based on IP address.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-797">テーブルの共有アクセス署名を返します。</span><span class="sxs-lookup"><span data-stu-id="15e42-797">Returns a shared access signature for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-798">URI クエリ文字列としての共有アクセス署名します。</span><span class="sxs-lookup"><span data-stu-id="15e42-798">A shared access signature, as a URI query string.</span></span></returns>
        <remarks><span data-ttu-id="15e42-799">返されるクエリ文字列には、先頭に疑問符が含まれています。</span><span class="sxs-lookup"><span data-stu-id="15e42-799">The query string returned includes the leading question mark.</span></span></remarks>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="15e42-800">現在の資格情報が共有アクセス署名の作成をサポートしていない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="15e42-800">Thrown if the current credentials don't support creating a shared access signature.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTable.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.CosmosDB.Table.CloudTable.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="15e42-801">テーブルの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="15e42-801">Gets the name of the table.</span></span>
            </summary>
        <value><span data-ttu-id="15e42-802">テーブルの名前を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="15e42-802">A string containing the name of the table.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceClient">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.CloudTableClient ServiceClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.CosmosDB.Table.CloudTableClient ServiceClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTable.ServiceClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceClient As CloudTableClient" />
      <MemberSignature Language="F#" Value="member this.ServiceClient : Microsoft.Azure.CosmosDB.Table.CloudTableClient" Usage="Microsoft.Azure.CosmosDB.Table.CloudTable.ServiceClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.CloudTableClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="15e42-803">取得、<see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTableClient" />テーブル サービスを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-803">Gets the <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTableClient" /> object that represents the Table service.</span></span>
            </summary>
        <value><span data-ttu-id="15e42-804">A<see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTableClient" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-804">A <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTableClient" /> object .</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissions">
      <MemberSignature Language="C#" Value="public virtual void SetPermissions (Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetPermissions(class Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.SetPermissions(Microsoft.Azure.CosmosDB.Table.TablePermissions,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissions : Microsoft.Azure.CosmosDB.Table.TablePermissions * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; unit&#xA;override this.SetPermissions : Microsoft.Azure.CosmosDB.Table.TablePermissions * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; unit" Usage="cloudTable.SetPermissions (permissions, requestOptions, operationContext)" />
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
        <Parameter Name="permissions" Type="Microsoft.Azure.CosmosDB.Table.TablePermissions" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="15e42-805">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" />へのアクセス許可を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-805">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> object that represents the permissions to set.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-806">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-806">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-807"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-807">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-808">テーブルのアクセス許可の設定を設定します。</span><span class="sxs-lookup"><span data-stu-id="15e42-808">Sets the permissions settings for the table.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.Azure.CosmosDB.Table.TablePermissions permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.Azure.CosmosDB.Table.TablePermissions permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.SetPermissionsAsync(Microsoft.Azure.CosmosDB.Table.TablePermissions)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetPermissionsAsync (permissions As TablePermissions) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TablePermissions -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TablePermissions -&gt; System.Threading.Tasks.Task" Usage="cloudTable.SetPermissionsAsync permissions" />
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
        <Parameter Name="permissions" Type="Microsoft.Azure.CosmosDB.Table.TablePermissions" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="15e42-809">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" />へのアクセス許可を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-809">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> object that represents the permissions to set.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-810">テーブルのアクセス許可を設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-810">Initiates an asynchronous operation to set permissions for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-811">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-811">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.SetPermissionsAsync(Microsoft.Azure.CosmosDB.Table.TablePermissions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TablePermissions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TablePermissions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.SetPermissionsAsync (permissions, cancellationToken)" />
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
        <Parameter Name="permissions" Type="Microsoft.Azure.CosmosDB.Table.TablePermissions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="15e42-812">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" />へのアクセス許可を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-812">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> object that represents the permissions to set.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-813">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-813">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-814">テーブルのアクセス許可を設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-814">Initiates an asynchronous operation to set permissions for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-815">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-815">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.SetPermissionsAsync(Microsoft.Azure.CosmosDB.Table.TablePermissions,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TablePermissions * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TablePermissions * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudTable.SetPermissionsAsync (permissions, requestOptions, operationContext)" />
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
        <Parameter Name="permissions" Type="Microsoft.Azure.CosmosDB.Table.TablePermissions" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="15e42-816">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" />へのアクセス許可を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-816">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> object that represents the permissions to set.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-817">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-817">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-818"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-818">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-819">テーブルのアクセス許可を設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-819">Initiates an asynchronous operation to set permissions for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-820">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-820">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.SetPermissionsAsync(Microsoft.Azure.CosmosDB.Table.TablePermissions,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TablePermissions * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TablePermissions * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.SetPermissionsAsync (permissions, requestOptions, operationContext, cancellationToken)" />
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
        <Parameter Name="permissions" Type="Microsoft.Azure.CosmosDB.Table.TablePermissions" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="permissions"><span data-ttu-id="15e42-821">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" />へのアクセス許可を表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-821">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> object that represents the permissions to set.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="15e42-822">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-822">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="15e42-823"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-823">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="15e42-824">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="15e42-824">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="15e42-825">テーブルのアクセス許可を設定する非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="15e42-825">Initiates an asynchronous operation to set permissions for the table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-826">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="15e42-826">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Storage.StorageUri StorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Storage.StorageUri StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTable.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.StorageUri : Microsoft.Azure.Storage.StorageUri" Usage="Microsoft.Azure.CosmosDB.Table.CloudTable.StorageUri" />
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
            <span data-ttu-id="15e42-827">プライマリとセカンダリの両方の場所のテーブルの Uri を取得します。</span><span class="sxs-lookup"><span data-stu-id="15e42-827">Gets the table's URIs for both the primary and secondary locations.</span></span>
            </summary>
        <value><span data-ttu-id="15e42-828">型のオブジェクト<see cref="P:Microsoft.Azure.CosmosDB.Table.CloudTable.StorageUri" />テーブルの Uri は、プライマリとセカンダリの両方の場所を格納します。</span><span class="sxs-lookup"><span data-stu-id="15e42-828">An object of type <see cref="P:Microsoft.Azure.CosmosDB.Table.CloudTable.StorageUri" /> containing the table's URIs for both the primary and secondary locations.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="cloudTable.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="15e42-829">テーブルの名前を返します。</span><span class="sxs-lookup"><span data-stu-id="15e42-829">Returns the name of the table.</span></span>
            </summary>
        <returns><span data-ttu-id="15e42-830">テーブルの名前を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="15e42-830">A string containing the name of the table.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Uri">
      <MemberSignature Language="C#" Value="public Uri Uri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Uri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTable.Uri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Uri As Uri" />
      <MemberSignature Language="F#" Value="member this.Uri : Uri" Usage="Microsoft.Azure.CosmosDB.Table.CloudTable.Uri" />
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
            <span data-ttu-id="15e42-831">プライマリの場所のテーブルの URI を取得します。</span><span class="sxs-lookup"><span data-stu-id="15e42-831">Gets the table URI for the primary location.</span></span>
            </summary>
        <value><span data-ttu-id="15e42-832">A<see cref="T:System.Uri" />プライマリの場所にあるテーブルに対して絶対 URI を指定します。</span><span class="sxs-lookup"><span data-stu-id="15e42-832">A <see cref="T:System.Uri" /> specifying the absolute URI to the table at the primary location.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>