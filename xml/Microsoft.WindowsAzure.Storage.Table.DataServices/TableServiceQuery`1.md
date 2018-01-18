<Type Name="TableServiceQuery&lt;TElement&gt;" FullName="Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery&lt;TElement&gt;">
  <TypeSignature Language="C#" Value="public class TableServiceQuery&lt;TElement&gt; : System.Collections.Generic.IEnumerable&lt;TElement&gt;, System.Linq.IQueryable&lt;TElement&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TableServiceQuery`1&lt;TElement&gt; extends System.Object implements class System.Collections.Generic.IEnumerable`1&lt;!TElement&gt;, class System.Collections.IEnumerable, class System.Linq.IQueryable, class System.Linq.IQueryable`1&lt;!TElement&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery`1" />
  <TypeSignature Language="VB.NET" Value="Public Class TableServiceQuery(Of TElement)&#xA;Implements IEnumerable(Of TElement), IQueryable(Of TElement)" />
  <TypeSignature Language="F#" Value="type TableServiceQuery&lt;'Element&gt; = class&#xA;    interface IQueryable&lt;'Element&gt;&#xA;    interface seq&lt;'Element&gt;&#xA;    interface IQueryable&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TElement" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;TElement&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Linq.IQueryable&lt;TElement&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <typeparam name="TElement"><span data-ttu-id="441dc-101">要素の型。</span><span class="sxs-lookup"><span data-stu-id="441dc-101">The type of the element.</span></span></typeparam>
    <summary>
            <span data-ttu-id="441dc-102">テーブル サービスに対するクエリを構築するためのクラスです。</span><span class="sxs-lookup"><span data-stu-id="441dc-102">A class for constructing a query against the Table service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableServiceQuery (System.Linq.IQueryable&lt;TElement&gt; query, Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Linq.IQueryable`1&lt;!TElement&gt; query, class Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery`1.#ctor(System.Linq.IQueryable{`0},Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (query As IQueryable(Of TElement), context As TableServiceContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery&lt;'Element&gt; : System.Linq.IQueryable&lt;'Element&gt; * Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext -&gt; Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery&lt;'Element&gt;" Usage="new Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery&lt;'Element&gt; (query, context)" />
      <MemberType>Constructor</MemberType>
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
      <Parameters>
        <Parameter Name="query" Type="System.Linq.IQueryable&lt;TElement&gt;" />
        <Parameter Name="context" Type="Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" />
      </Parameters>
      <Docs>
        <param name="query"><span data-ttu-id="441dc-103"><see cref="T:System.Linq.IQueryable" /> を実装するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="441dc-103">An object that implements <see cref="T:System.Linq.IQueryable" />.</span></span></param>
        <param name="context"><span data-ttu-id="441dc-104"><see cref="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="441dc-104">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" /> object.</span></span></param>
        <summary>
            <span data-ttu-id="441dc-105"><see cref="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery`1" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="441dc-105">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery`1" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteSegmented">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteSegmented (Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteSegmented(class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery`1.BeginExecuteSegmented(Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function BeginExecuteSegmented (currentToken As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="member this.BeginExecuteSegmented : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="tableServiceQuery.BeginExecuteSegmented (currentToken, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
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
        <param name="currentToken"><span data-ttu-id="441dc-106">前の一覧作成操作によって返される継続トークンを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="441dc-106">A continuation token returned by a previous listing operation, can be null.</span></span></param>
        <param name="callback"><span data-ttu-id="441dc-107"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="441dc-107">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="441dc-108">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="441dc-108">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="441dc-109">クエリを実行して結果セグメントとして結果を返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="441dc-109">Begins an asynchronous operation to execute a query and return the results as a result segment.</span></span>
            </summary>
        <returns><span data-ttu-id="441dc-110"><see cref="T:System.IAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="441dc-110">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteSegmented">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteSegmented (Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteSegmented(class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery`1.BeginExecuteSegmented(Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="member this.BeginExecuteSegmented : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="tableServiceQuery.BeginExecuteSegmented (currentToken, requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="441dc-111">前の一覧作成操作によって返される継続トークンを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="441dc-111">A continuation token returned by a previous listing operation, can be null.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="441dc-112">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="441dc-112">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="441dc-113"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="441dc-113">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="441dc-114"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="441dc-114">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="441dc-115">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="441dc-115">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="441dc-116">クエリを実行して結果セグメントとして結果を返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="441dc-116">Begins an asynchronous operation to execute a query and return the results as a result segment.</span></span>
            </summary>
        <returns><span data-ttu-id="441dc-117"><see cref="T:System.IAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="441dc-117">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery`1.Context" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Context As TableServiceContext" />
      <MemberSignature Language="F#" Value="member this.Context : Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" Usage="Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery&lt;'Element&gt;.Context" />
      <MemberType>Property</MemberType>
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
      <Docs>
        <summary>
            <span data-ttu-id="441dc-118">テーブル サービスのコンテキストを取得します。</span><span class="sxs-lookup"><span data-stu-id="441dc-118">Gets the Table service context.</span></span>
            </summary>
        <value>
            <span data-ttu-id="441dc-119"><see cref="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" /> 型のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="441dc-119">An object of type <see cref="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" />.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElementType">
      <MemberSignature Language="C#" Value="public Type ElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type ElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery`1.ElementType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ElementType As Type" />
      <MemberSignature Language="F#" Value="member this.ElementType : Type" Usage="Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery&lt;'Element&gt;.ElementType" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Linq.IQueryable.ElementType</InterfaceMember>
      </Implements>
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
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="441dc-120">式ツリーは、のこのインスタンスに関連付けられているときに返される要素の型を取得<see cref="T:System.Linq.IQueryable" />を実行します。</span><span class="sxs-lookup"><span data-stu-id="441dc-120">Gets the type of the element(s) that are returned when the expression tree associated with this instance of <see cref="T:System.Linq.IQueryable" /> is executed.</span></span>
            </summary>
        <value>
            <span data-ttu-id="441dc-121">A<see cref="T:System.Type" />このオブジェクトに関連付けられている式ツリーは実行時に返される要素の型を表すです。</span><span class="sxs-lookup"><span data-stu-id="441dc-121">A <see cref="T:System.Type" /> that represents the type of the element(s) that are returned when the expression tree associated with this object is executed.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecuteSegmented">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt; EndExecuteSegmented (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!TElement&gt; EndExecuteSegmented(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery`1.EndExecuteSegmented(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Function EndExecuteSegmented (asyncResult As IAsyncResult) As TableQuerySegment(Of TElement)" />
      <MemberSignature Language="F#" Value="member this.EndExecuteSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element&gt;" Usage="tableServiceQuery.EndExecuteSegmented asyncResult" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="441dc-122">終了させる保留状態の非同期リクエストへの参照。</span><span class="sxs-lookup"><span data-stu-id="441dc-122">The reference to the pending asynchronous request to finish.</span></span></param>
        <summary>
            <span data-ttu-id="441dc-123">クエリを実行して結果セグメントとして結果を返す非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="441dc-123">Ends an asynchronous operation to execute a query and return the results as a result segment.</span></span>
            </summary>
        <returns><span data-ttu-id="441dc-124">型のオブジェクトを含む結果セグメント<typeparamref name="TElement" />です。</span><span class="sxs-lookup"><span data-stu-id="441dc-124">A result segment containing objects of type <typeparamref name="TElement" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Execute">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;TElement&gt; Execute (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;!TElement&gt; Execute(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery`1.Execute(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.Execute : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;'Element&gt;" Usage="tableServiceQuery.Execute (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="441dc-125">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="441dc-125">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="441dc-126"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="441dc-126">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="441dc-127">指定されたオプションで要求を実行します。</span><span class="sxs-lookup"><span data-stu-id="441dc-127">Executes the request with any specified options.</span></span>
            </summary>
        <returns><span data-ttu-id="441dc-128">型の列挙可能なコレクションに特殊化<c>TElement</c>クエリの実行の結果。</span><span class="sxs-lookup"><span data-stu-id="441dc-128">An enumerable collection, specialized for type <c>TElement</c>, of the results of executing the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteSegmented">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt; ExecuteSegmented (Microsoft.WindowsAzure.Storage.Table.TableContinuationToken continuationToken, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!TElement&gt; ExecuteSegmented(class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken continuationToken, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery`1.ExecuteSegmented(Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.ExecuteSegmented : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element&gt;" Usage="tableServiceQuery.ExecuteSegmented (continuationToken, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="continuationToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="continuationToken"><span data-ttu-id="441dc-129">継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="441dc-129">The continuation token.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="441dc-130">要求オプション。</span><span class="sxs-lookup"><span data-stu-id="441dc-130">The request options.</span></span></param>
        <param name="operationContext"><span data-ttu-id="441dc-131"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="441dc-131">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="441dc-132">テーブル サービスに対して、セグメント化されたクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="441dc-132">Executes a segmented query against the Table service.</span></span>
            </summary>
        <returns><span data-ttu-id="441dc-133">型のオブジェクトを含む結果セグメント<typeparamref name="TElement" />です。</span><span class="sxs-lookup"><span data-stu-id="441dc-133">A result segment containing objects of type <typeparamref name="TElement" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteSegmentedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteSegmentedAsync (Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!TElement&gt;&gt; ExecuteSegmentedAsync(class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery`1.ExecuteSegmentedAsync(Microsoft.WindowsAzure.Storage.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteSegmentedAsync (currentToken As TableContinuationToken) As Task(Of TableQuerySegment(Of TElement))" />
      <MemberSignature Language="F#" Value="member this.ExecuteSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element&gt;&gt;" Usage="tableServiceQuery.ExecuteSegmentedAsync currentToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="441dc-134">前の一覧作成操作によって返される継続トークンを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="441dc-134">A continuation token returned by a previous listing operation, can be null.</span></span></param>
        <summary>
            <span data-ttu-id="441dc-135">クエリを実行して結果セグメントとして結果を返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="441dc-135">Initiates an asynchronous operation to execute a query and return the results as a result segment.</span></span>
            </summary>
        <returns><span data-ttu-id="441dc-136">非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="441dc-136">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteSegmentedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteSegmentedAsync (Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!TElement&gt;&gt; ExecuteSegmentedAsync(class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery`1.ExecuteSegmentedAsync(Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ExecuteSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element&gt;&gt;" Usage="tableServiceQuery.ExecuteSegmentedAsync (currentToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="441dc-137">前の一覧作成操作によって返される継続トークンを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="441dc-137">A continuation token returned by a previous listing operation, can be null.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="441dc-138">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="441dc-138">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="441dc-139">クエリを実行して結果セグメントとして結果を返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="441dc-139">Initiates an asynchronous operation to execute a query and return the results as a result segment.</span></span>
            </summary>
        <returns><span data-ttu-id="441dc-140">非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="441dc-140">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteSegmentedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteSegmentedAsync (Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!TElement&gt;&gt; ExecuteSegmentedAsync(class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery`1.ExecuteSegmentedAsync(Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.ExecuteSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element&gt;&gt;" Usage="tableServiceQuery.ExecuteSegmentedAsync (currentToken, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="441dc-141">前の一覧作成操作によって返される継続トークンを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="441dc-141">A continuation token returned by a previous listing operation, can be null.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="441dc-142">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="441dc-142">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="441dc-143"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="441dc-143">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="441dc-144">クエリを実行して結果セグメントとして結果を返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="441dc-144">Initiates an asynchronous operation to execute a query and return the results as a result segment.</span></span>
            </summary>
        <returns><span data-ttu-id="441dc-145">非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="441dc-145">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteSegmentedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteSegmentedAsync (Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!TElement&gt;&gt; ExecuteSegmentedAsync(class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery`1.ExecuteSegmentedAsync(Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ExecuteSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element&gt;&gt;" Usage="tableServiceQuery.ExecuteSegmentedAsync (currentToken, requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="441dc-146">前の一覧作成操作によって返される継続トークンを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="441dc-146">A continuation token returned by a previous listing operation, can be null.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="441dc-147">A<see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="441dc-147">A <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="441dc-148"><see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="441dc-148">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="441dc-149">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="441dc-149">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="441dc-150">クエリを実行して結果セグメントとして結果を返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="441dc-150">Initiates an asynchronous operation to execute a query and return the results as a result segment.</span></span>
            </summary>
        <returns><span data-ttu-id="441dc-151">非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="441dc-151">A <see cref="T:System.Threading.Tasks.Task`1" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expand">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery&lt;TElement&gt; Expand (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery`1&lt;!TElement&gt; Expand(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery`1.Expand(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Expand (path As String) As TableServiceQuery(Of TElement)" />
      <MemberSignature Language="F#" Value="member this.Expand : string -&gt; Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery&lt;'Element&gt;" Usage="tableServiceQuery.Expand path" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="441dc-152">展開へのパス。</span><span class="sxs-lookup"><span data-stu-id="441dc-152">The path to expand.</span></span></param>
        <summary>
            <span data-ttu-id="441dc-153">指定されたパスを展開します。</span><span class="sxs-lookup"><span data-stu-id="441dc-153">Expands the specified path.</span></span>
            </summary>
        <returns><span data-ttu-id="441dc-154">展開されたパスに新しいクエリ。</span><span class="sxs-lookup"><span data-stu-id="441dc-154">A new query with the expanded path.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expression">
      <MemberSignature Language="C#" Value="public System.Linq.Expressions.Expression Expression { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Linq.Expressions.Expression Expression" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery`1.Expression" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Expression As Expression" />
      <MemberSignature Language="F#" Value="member this.Expression : System.Linq.Expressions.Expression" Usage="Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery&lt;'Element&gt;.Expression" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Linq.IQueryable.Expression</InterfaceMember>
      </Implements>
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
        <ReturnType>System.Linq.Expressions.Expression</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="441dc-155">インスタンスに関連付けられている式ツリーを取得<see cref="T:System.Linq.IQueryable" />です。</span><span class="sxs-lookup"><span data-stu-id="441dc-155">Gets the expression tree that is associated with the instance of <see cref="T:System.Linq.IQueryable" />.</span></span>
            </summary>
        <value>
            <span data-ttu-id="441dc-156"><see cref="T:System.Linq.Expressions.Expression" />のこのインスタンスに関連付けられている<see cref="T:System.Linq.IQueryable" />です。</span><span class="sxs-lookup"><span data-stu-id="441dc-156">The <see cref="T:System.Linq.Expressions.Expression" /> that is associated with this instance of <see cref="T:System.Linq.IQueryable" />.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;TElement&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;!TElement&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery`1.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of TElement)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;'Element&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;'Element&gt;" Usage="tableServiceQuery.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
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
        <ReturnType>System.Collections.Generic.IEnumerator&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="441dc-157">コレクションを反復処理する列挙子を返します。</span><span class="sxs-lookup"><span data-stu-id="441dc-157">Returns an enumerator that iterates through the collection.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="441dc-158">コレクションを反復処理するために使用できる <see cref="T:System.Collections.Generic.IEnumerator`1" />。</span><span class="sxs-lookup"><span data-stu-id="441dc-158">A <see cref="T:System.Collections.Generic.IEnumerator`1" /> that can be used to iterate through the collection.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Provider">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryProvider Provider { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Linq.IQueryProvider Provider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery`1.Provider" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Provider As IQueryProvider" />
      <MemberSignature Language="F#" Value="member this.Provider : System.Linq.IQueryProvider" Usage="Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery&lt;'Element&gt;.Provider" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Linq.IQueryable.Provider</InterfaceMember>
      </Implements>
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
        <ReturnType>System.Linq.IQueryProvider</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="441dc-159">このデータ ソースに関連付けられているクエリ プロバイダーを取得します。</span><span class="sxs-lookup"><span data-stu-id="441dc-159">Gets the query provider that is associated with this data source.</span></span>
            </summary>
        <value>
            <span data-ttu-id="441dc-160"><see cref="T:System.Linq.IQueryProvider" />このデータ ソースに関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="441dc-160">The <see cref="T:System.Linq.IQueryProvider" /> that is associated with this data source.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceQuery`1.System#Collections#IEnumerable#GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Function GetEnumerator () As IEnumerator Implements IEnumerable.GetEnumerator" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IEnumerable.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.IEnumerator</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>