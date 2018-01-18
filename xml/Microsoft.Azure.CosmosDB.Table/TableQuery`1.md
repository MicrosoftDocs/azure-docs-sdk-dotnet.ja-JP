<Type Name="TableQuery&lt;TElement&gt;" FullName="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;">
  <TypeSignature Language="C#" Value="public class TableQuery&lt;TElement&gt; : System.Collections.Generic.IEnumerable&lt;TElement&gt;, System.Linq.IQueryable&lt;TElement&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TableQuery`1&lt;TElement&gt; extends System.Object implements class System.Collections.Generic.IEnumerable`1&lt;!TElement&gt;, class System.Collections.IEnumerable, class System.Linq.IQueryable, class System.Linq.IQueryable`1&lt;!TElement&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.TableQuery`1" />
  <TypeSignature Language="VB.NET" Value="Public Class TableQuery(Of TElement)&#xA;Implements IEnumerable(Of TElement), IQueryable(Of TElement)" />
  <TypeSignature Language="F#" Value="type TableQuery&lt;'Element&gt; = class&#xA;    interface IQueryable&lt;'Element&gt;&#xA;    interface seq&lt;'Element&gt;&#xA;    interface IEnumerable&#xA;    interface IQueryable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
  <Docs>
    <typeparam name="TElement"><span data-ttu-id="00636-101">実装するクラス<see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" />です。</span><span class="sxs-lookup"><span data-stu-id="00636-101">A class which implements <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" />.</span></span></typeparam>
    <summary>
            <span data-ttu-id="00636-102">Microsoft Azure のテーブルに対してクエリを表します。</span><span class="sxs-lookup"><span data-stu-id="00636-102">Represents a query against a Microsoft Azure table.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableQuery ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="00636-103"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery`1" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="00636-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery`1" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteSegmented (Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteSegmented(class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery`1.BeginExecuteSegmented(Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecuteSegmented (currentToken As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteSegmented : Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteSegmented : Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="tableQuery.BeginExecuteSegmented (currentToken, callback, state)" />
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
        <param name="currentToken"><span data-ttu-id="00636-104">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />前の一覧作成操作によって返されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="00636-104">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object returned by a previous listing operation.</span></span> <span data-ttu-id="00636-105">あります<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="00636-105">May be <c>null</c>.</span></span></param>
        <param name="callback"><span data-ttu-id="00636-106"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="00636-106">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="00636-107">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="00636-107">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="00636-108">クエリを実行して結果セグメントとして結果を返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="00636-108">Begins an asynchronous operation to execute a query and return the results as a result segment.</span></span>
            </summary>
        <returns><span data-ttu-id="00636-109"><see cref="T:System.IAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="00636-109">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteSegmented (Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteSegmented(class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery`1.BeginExecuteSegmented(Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteSegmented : Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteSegmented : Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="tableQuery.BeginExecuteSegmented (currentToken, requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="00636-110">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />前の一覧作成操作によって返されるオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="00636-110">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object returned by a previous listing operation.</span></span> <span data-ttu-id="00636-111">あります<c>null</c>です。</span><span class="sxs-lookup"><span data-stu-id="00636-111">May be <c>null</c>.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="00636-112">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="00636-112">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="00636-113"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="00636-113">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="callback"><span data-ttu-id="00636-114"><see cref="T:System.AsyncCallback" />非同期操作が完了したら、通知を受信するデリゲート。</span><span class="sxs-lookup"><span data-stu-id="00636-114">An <see cref="T:System.AsyncCallback" /> delegate that will receive notification when the asynchronous operation completes.</span></span></param>
        <param name="state"><span data-ttu-id="00636-115">コールバック デリゲートに渡されるユーザー定義のオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="00636-115">A user-defined object that will be passed to the callback delegate.</span></span></param>
        <summary>
            <span data-ttu-id="00636-116">クエリを実行して結果セグメントとして結果を返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="00636-116">Begins an asynchronous operation to execute a query and return the results as a result segment.</span></span>
            </summary>
        <returns><span data-ttu-id="00636-117"><see cref="T:System.IAsyncResult" />非同期操作を参照します。</span><span class="sxs-lookup"><span data-stu-id="00636-117">An <see cref="T:System.IAsyncResult" /> that references the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Copy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; Copy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!TElement&gt; Copy() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery`1.Copy" />
      <MemberSignature Language="VB.NET" Value="Public Function Copy () As TableQuery(Of TElement)" />
      <MemberSignature Language="F#" Value="member this.Copy : unit -&gt; Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element&gt;" Usage="tableQuery.Copy " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="00636-118">TableQuery の簡易コピー</span><span class="sxs-lookup"><span data-stu-id="00636-118">Shallow copy of TableQuery</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElementType">
      <MemberSignature Language="C#" Value="public Type ElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type ElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableQuery`1.ElementType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ElementType As Type" />
      <MemberSignature Language="F#" Value="member this.ElementType : Type" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element&gt;.ElementType" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Linq.IQueryable.ElementType</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00636-119">式ツリーは実行時に返される要素の型を取得します。</span><span class="sxs-lookup"><span data-stu-id="00636-119">Gets the type of the element(s) that are returned when the expression tree is executed.</span></span>
            </summary>
        <value><span data-ttu-id="00636-120">A<see cref="T:System.Type" />このオブジェクトに関連付けられている式ツリーは実行時に返される要素の型を表すです。</span><span class="sxs-lookup"><span data-stu-id="00636-120">A <see cref="T:System.Type" /> that represents the type of the element(s) that are returned when the expression tree associated with this object is executed.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecuteSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt; EndExecuteSegmented (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!TElement&gt; EndExecuteSegmented(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery`1.EndExecuteSegmented(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExecuteSegmented (asyncResult As IAsyncResult) As TableQuerySegment(Of TElement)" />
      <MemberSignature Language="F#" Value="abstract member EndExecuteSegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&#xA;override this.EndExecuteSegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;" Usage="tableQuery.EndExecuteSegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult"><span data-ttu-id="00636-121">終了させる保留状態の非同期リクエストへの参照。</span><span class="sxs-lookup"><span data-stu-id="00636-121">The reference to the pending asynchronous request to finish.</span></span></param>
        <summary>
            <span data-ttu-id="00636-122">クエリを実行して結果セグメントとして結果を返す非同期操作を終了します。</span><span class="sxs-lookup"><span data-stu-id="00636-122">Ends an asynchronous operation to execute a query and return the results as a result segment.</span></span>
            </summary>
        <returns><span data-ttu-id="00636-123"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> 型の <typeparamref name="TElement" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="00636-123">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> object of type <typeparamref name="TElement" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Execute">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;TElement&gt; Execute (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!TElement&gt; Execute(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery`1.Execute(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Execute : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;'Element&gt;&#xA;override this.Execute : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;'Element&gt;" Usage="tableQuery.Execute (requestOptions, operationContext)" />
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
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions"><span data-ttu-id="00636-124">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="00636-124">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="00636-125"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="00636-125">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="00636-126">テーブルに対するクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="00636-126">Executes a query on a table.</span></span>
            </summary>
        <returns><span data-ttu-id="00636-127">型の列挙可能なコレクションに特殊化<c>TElement</c>クエリの実行の結果。</span><span class="sxs-lookup"><span data-stu-id="00636-127">An enumerable collection, specialized for type <c>TElement</c>, of the results of executing the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt; ExecuteSegmented (Microsoft.Azure.CosmosDB.Table.TableContinuationToken continuationToken, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!TElement&gt; ExecuteSegmented(class Microsoft.Azure.CosmosDB.Table.TableContinuationToken continuationToken, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery`1.ExecuteSegmented(Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteSegmented : Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&#xA;override this.ExecuteSegmented : Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;" Usage="tableQuery.ExecuteSegmented (continuationToken, requestOptions, operationContext)" />
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
      <Parameters>
        <Parameter Name="continuationToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="continuationToken"><span data-ttu-id="00636-128">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />操作には、部分的な結果が返されるときに、サーバーから継続トークンを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="00636-128">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> object representing a continuation token from the server when the operation returns a partial result.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="00636-129">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="00636-129">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="00636-130"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="00636-130">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="00636-131">テーブルに対してセグメント化されたクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="00636-131">Executes a segmented query against a table.</span></span>
            </summary>
        <returns><span data-ttu-id="00636-132">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />型に対して特殊化されて、 <c>TElement</c>クエリの実行の結果を格納します。</span><span class="sxs-lookup"><span data-stu-id="00636-132">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />, specialized for type <c>TElement</c>, containing the results of executing the query.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteSegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!TElement&gt;&gt; ExecuteSegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery`1.ExecuteSegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteSegmentedAsync (currentToken As TableContinuationToken) As Task(Of TableQuerySegment(Of TElement))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt;&#xA;override this.ExecuteSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt;" Usage="tableQuery.ExecuteSegmentedAsync currentToken" />
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
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="00636-133">前の一覧作成操作によって返される継続トークンを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="00636-133">A continuation token returned by a previous listing operation, can be null.</span></span></param>
        <summary>
            <span data-ttu-id="00636-134">クエリを実行して結果セグメントとして結果を返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="00636-134">Initiates an asynchronous operation to execute a query and return the results as a result segment.</span></span>
            </summary>
        <returns><span data-ttu-id="00636-135">A<see cref="T:System.Threading.Tasks.Task`1" />型の<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="00636-135">A <see cref="T:System.Threading.Tasks.Task`1" /> of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteSegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!TElement&gt;&gt; ExecuteSegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery`1.ExecuteSegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt;&#xA;override this.ExecuteSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt;" Usage="tableQuery.ExecuteSegmentedAsync (currentToken, cancellationToken)" />
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
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="00636-136">前の一覧作成操作によって返される継続トークンを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="00636-136">A continuation token returned by a previous listing operation, can be null.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="00636-137">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="00636-137">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="00636-138">クエリを実行して結果セグメントとして結果を返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="00636-138">Initiates an asynchronous operation to execute a query and return the results as a result segment.</span></span>
            </summary>
        <returns><span data-ttu-id="00636-139">A<see cref="T:System.Threading.Tasks.Task`1" />型の<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="00636-139">A <see cref="T:System.Threading.Tasks.Task`1" /> of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteSegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!TElement&gt;&gt; ExecuteSegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery`1.ExecuteSegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt;&#xA;override this.ExecuteSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt;" Usage="tableQuery.ExecuteSegmentedAsync (currentToken, requestOptions, operationContext)" />
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
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="00636-140">前の一覧作成操作によって返される継続トークンを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="00636-140">A continuation token returned by a previous listing operation, can be null.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="00636-141">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="00636-141">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="00636-142"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="00636-142">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="00636-143">クエリを実行して結果セグメントとして結果を返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="00636-143">Initiates an asynchronous operation to execute a query and return the results as a result segment.</span></span>
            </summary>
        <returns><span data-ttu-id="00636-144">A<see cref="T:System.Threading.Tasks.Task`1" />型の<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="00636-144">A <see cref="T:System.Threading.Tasks.Task`1" /> of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteSegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!TElement&gt;&gt; ExecuteSegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery`1.ExecuteSegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt;&#xA;override this.ExecuteSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt;" Usage="tableQuery.ExecuteSegmentedAsync (currentToken, requestOptions, operationContext, cancellationToken)" />
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
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken"><span data-ttu-id="00636-145">前の一覧作成操作によって返される継続トークンを null にすることができます。</span><span class="sxs-lookup"><span data-stu-id="00636-145">A continuation token returned by a previous listing operation, can be null.</span></span></param>
        <param name="requestOptions"><span data-ttu-id="00636-146">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />要求の追加のオプションを指定するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="00636-146">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> object that specifies additional options for the request.</span></span></param>
        <param name="operationContext"><span data-ttu-id="00636-147"><see cref="T:Microsoft.Azure.Storage.OperationContext" />を現在の操作コンテキストを表すオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="00636-147">An <see cref="T:Microsoft.Azure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="00636-148">タスクの完了を待機しているときに監視する <see cref="T:System.Threading.CancellationToken" />。</span><span class="sxs-lookup"><span data-stu-id="00636-148">A <see cref="T:System.Threading.CancellationToken" /> to observe while waiting for a task to complete.</span></span></param>
        <summary>
            <span data-ttu-id="00636-149">クエリを実行して結果セグメントとして結果を返す非同期操作を開始します。</span><span class="sxs-lookup"><span data-stu-id="00636-149">Initiates an asynchronous operation to execute a query and return the results as a result segment.</span></span>
            </summary>
        <returns><span data-ttu-id="00636-150">A<see cref="T:System.Threading.Tasks.Task`1" />型の<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />非同期操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="00636-150">A <see cref="T:System.Threading.Tasks.Task`1" /> of type <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expression">
      <MemberSignature Language="C#" Value="public System.Linq.Expressions.Expression Expression { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Linq.Expressions.Expression Expression" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableQuery`1.Expression" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Expression As Expression" />
      <MemberSignature Language="F#" Value="member this.Expression : System.Linq.Expressions.Expression" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element&gt;.Expression" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Linq.IQueryable.Expression</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.Expressions.Expression</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00636-151">式ツリーを取得します。</span><span class="sxs-lookup"><span data-stu-id="00636-151">Gets the expression tree.</span></span>
            </summary>
        <value><span data-ttu-id="00636-152"><see cref="T:System.Linq.Expressions.Expression" />のこのインスタンスに関連付けられている<see cref="T:System.Linq.IQueryable" />です。</span><span class="sxs-lookup"><span data-stu-id="00636-152">The <see cref="T:System.Linq.Expressions.Expression" /> that is associated with this instance of <see cref="T:System.Linq.IQueryable" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilterString">
      <MemberSignature Language="C#" Value="public string FilterString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilterString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableQuery`1.FilterString" />
      <MemberSignature Language="VB.NET" Value="Public Property FilterString As String" />
      <MemberSignature Language="F#" Value="member this.FilterString : string with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element&gt;.FilterString" />
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
            <span data-ttu-id="00636-153">取得またはテーブルのクエリで使用するフィルター式を設定します。</span><span class="sxs-lookup"><span data-stu-id="00636-153">Gets or sets the filter expression to use in the table query.</span></span>
            </summary>
        <value><span data-ttu-id="00636-154">クエリで使用するフィルター式を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="00636-154">A string containing the filter expression to use in the query.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerator&lt;TElement&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;!TElement&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery`1.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetEnumerator () As IEnumerator(Of TElement)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;'Element&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;'Element&gt;" Usage="tableQuery.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="00636-155"><see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery`1" /> を反復処理する列挙子を返します。</span><span class="sxs-lookup"><span data-stu-id="00636-155">Returns an enumerator that iterates through the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery`1" />.</span></span>
            </summary>
        <returns><span data-ttu-id="00636-156"><see cref="T:System.Collections.Generic.IEnumerator`1" /> の <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery`1" />。</span><span class="sxs-lookup"><span data-stu-id="00636-156">An <see cref="T:System.Collections.Generic.IEnumerator`1" /> for the <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery`1" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Provider">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryProvider Provider { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Linq.IQueryProvider Provider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableQuery`1.Provider" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Provider As IQueryProvider" />
      <MemberSignature Language="F#" Value="member this.Provider : System.Linq.IQueryProvider" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element&gt;.Provider" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Linq.IQueryable.Provider</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryProvider</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00636-157">このデータ ソースに関連付けられているクエリ プロバイダーを取得します。</span><span class="sxs-lookup"><span data-stu-id="00636-157">Gets the query provider that is associated with this data source.</span></span>
            </summary>
        <value><span data-ttu-id="00636-158"><see cref="T:System.Linq.IQueryProvider" />このデータ ソースに関連付けられています。</span><span class="sxs-lookup"><span data-stu-id="00636-158">The <see cref="T:System.Linq.IQueryProvider" /> that is associated with this data source.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Select">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; Select (System.Collections.Generic.IList&lt;string&gt; columns);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!TElement&gt; Select(class System.Collections.Generic.IList`1&lt;string&gt; columns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery`1.Select(System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function Select (columns As IList(Of String)) As TableQuery(Of TElement)" />
      <MemberSignature Language="F#" Value="member this.Select : System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element&gt;" Usage="tableQuery.Select columns" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="columns" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="columns"><span data-ttu-id="00636-159">クエリの実行時に返されるテーブル エンティティのプロパティのプロパティ名を含む文字列オブジェクトの一覧です。</span><span class="sxs-lookup"><span data-stu-id="00636-159">A list of string objects containing the property names of the table entity properties to return when the query is executed.</span></span></param>
        <summary>
            <span data-ttu-id="00636-160">テーブル クエリの実行時に返されるテーブル エンティティのプロパティのプロパティ名を定義します。</span><span class="sxs-lookup"><span data-stu-id="00636-160">Defines the property names of the table entity properties to return when the table query is executed.</span></span> 
            </summary>
        <returns><span data-ttu-id="00636-161">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />インスタンス テーブル エンティティのプロパティを返すように設定します。</span><span class="sxs-lookup"><span data-stu-id="00636-161">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance set with the table entity properties to return.</span></span></returns>
        <remarks><span data-ttu-id="00636-162">Select 句は、テーブルのクエリでは省略可能、サーバーから返されるテーブルのプロパティを制限するために使用します。</span><span class="sxs-lookup"><span data-stu-id="00636-162">The select clause is optional on a table query, and is used to limit the table properties returned from the server.</span></span> <span data-ttu-id="00636-163">既定では、クエリは、テーブル エンティティから、すべてのプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="00636-163">By default, a query will return all properties from the table entity.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="SelectColumns">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SelectColumns { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SelectColumns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableQuery`1.SelectColumns" />
      <MemberSignature Language="VB.NET" Value="Public Property SelectColumns As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SelectColumns : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element&gt;.SelectColumns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00636-164">取得またはテーブルのクエリの実行時に返されるテーブル エンティティのプロパティのプロパティ名を設定します。</span><span class="sxs-lookup"><span data-stu-id="00636-164">Gets or sets the property names of the table entity properties to return when the table query is executed.</span></span>
            </summary>
        <value><span data-ttu-id="00636-165">クエリの実行時に返されるテーブル エンティティのプロパティのプロパティ名を含む文字列のリスト。</span><span class="sxs-lookup"><span data-stu-id="00636-165">A list of strings containing the property names of the table entity properties to return when the query is executed.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery`1.System#Collections#IEnumerable#GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Function GetEnumerator () As IEnumerator Implements IEnumerable.GetEnumerator" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IEnumerable.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
    <Member MemberName="Take">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; Take (Nullable&lt;int&gt; take);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!TElement&gt; Take(valuetype System.Nullable`1&lt;int32&gt; take) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery`1.Take(System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Function Take (take As Nullable(Of Integer)) As TableQuery(Of TElement)" />
      <MemberSignature Language="F#" Value="member this.Take : Nullable&lt;int&gt; -&gt; Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element&gt;" Usage="tableQuery.Take take" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="take" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="take"><span data-ttu-id="00636-166">テーブル クエリで返されるエンティティの最大数。</span><span class="sxs-lookup"><span data-stu-id="00636-166">The maximum number of entities for the table query to return.</span></span></param>
        <summary>
            <span data-ttu-id="00636-167">クエリから返されるエンティティの数の上限の境界を定義します。</span><span class="sxs-lookup"><span data-stu-id="00636-167">Defines the upper bound for the number of entities the query returns.</span></span>
            </summary>
        <returns><span data-ttu-id="00636-168">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />インスタンスのエンティティの数を返すように設定します。</span><span class="sxs-lookup"><span data-stu-id="00636-168">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance set with the number of entities to return.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TakeCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TakeCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TakeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableQuery`1.TakeCount" />
      <MemberSignature Language="VB.NET" Value="Public Property TakeCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TakeCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element&gt;.TakeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00636-169">取得またはクエリからテーブルのクエリで返されるエンティティの数を設定します。</span><span class="sxs-lookup"><span data-stu-id="00636-169">Gets or sets the number of entities the query returns specified in the table query.</span></span> 
            </summary>
        <value><span data-ttu-id="00636-170">テーブル クエリで返されるエンティティの最大数。</span><span class="sxs-lookup"><span data-stu-id="00636-170">The maximum number of entities for the table query to return.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Where">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; Where (string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!TElement&gt; Where(string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableQuery`1.Where(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Where (filter As String) As TableQuery(Of TElement)" />
      <MemberSignature Language="F#" Value="member this.Where : string -&gt; Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element&gt;" Usage="tableQuery.Where filter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="filter"><span data-ttu-id="00636-171">テーブル クエリに適用するフィルター式を含む文字列。</span><span class="sxs-lookup"><span data-stu-id="00636-171">A string containing the filter expression to apply to the table query.</span></span></param>
        <summary>
            <span data-ttu-id="00636-172">テーブル クエリのフィルター式を定義します。</span><span class="sxs-lookup"><span data-stu-id="00636-172">Defines a filter expression for the table query.</span></span> <span data-ttu-id="00636-173">指定したフィルター式を満たすエンティティのみが、クエリによって返されます。</span><span class="sxs-lookup"><span data-stu-id="00636-173">Only entities that satisfy the specified filter expression will be returned by the query.</span></span> 
            </summary>
        <returns><span data-ttu-id="00636-174">A<see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" />インスタンスのフィルターでエンティティを返すように設定します。</span><span class="sxs-lookup"><span data-stu-id="00636-174">A <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> instance set with the filter on entities to return.</span></span></returns>
        <remarks><span data-ttu-id="00636-175">フィルター式の設定は省略可能です。既定では、テーブルのクエリでフィルター式が指定されていない場合、テーブル内のすべてのエンティティが返されます。</span><span class="sxs-lookup"><span data-stu-id="00636-175">Setting a filter expression is optional; by default, all entities in the table are returned if no filter expression is specified in the table query.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>