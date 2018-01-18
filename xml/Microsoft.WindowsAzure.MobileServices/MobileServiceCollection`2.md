<Type Name="MobileServiceCollection&lt;TTable,TCollection&gt;" FullName="Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;TTable,TCollection&gt;">
  <TypeSignature Language="C#" Value="public class MobileServiceCollection&lt;TTable,TCollection&gt; : System.Collections.ObjectModel.ObservableCollection&lt;TCollection&gt;, Microsoft.WindowsAzure.MobileServices.IQueryResultEnumerable&lt;TCollection&gt;, Microsoft.WindowsAzure.MobileServices.ITotalCountProvider, System.Collections.Generic.IEnumerable&lt;TCollection&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileServiceCollection`2&lt;TTable, TCollection&gt; extends System.Collections.ObjectModel.ObservableCollection`1&lt;!TCollection&gt; implements class Microsoft.WindowsAzure.MobileServices.IQueryResultEnumerable`1&lt;!TCollection&gt;, class Microsoft.WindowsAzure.MobileServices.ITotalCountProvider, class System.Collections.Generic.IEnumerable`1&lt;!TCollection&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServiceCollection(Of TTable, TCollection)&#xA;Inherits ObservableCollection(Of TCollection)&#xA;Implements IEnumerable(Of TCollection), IQueryResultEnumerable(Of TCollection), ITotalCountProvider" />
  <TypeSignature Language="F#" Value="type MobileServiceCollection&lt;'able, 'Collection&gt; = class&#xA;    inherit ObservableCollection&lt;'Collection&gt;&#xA;    interface ITotalCountProvider&#xA;    interface IQueryResultEnumerable&lt;'Collection&gt;&#xA;    interface seq&lt;'Collection&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TTable" />
    <TypeParameter Name="TCollection" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Collections.ObjectModel.ObservableCollection&lt;TCollection&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">TCollection</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.MobileServices.IQueryResultEnumerable&lt;TCollection&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.MobileServices.ITotalCountProvider</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;TCollection&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TTable"><span data-ttu-id="8ada4-101">データ ソースの要素の型。</span><span class="sxs-lookup"><span data-stu-id="8ada4-101">Data source element type.</span></span></typeparam>
    <typeparam name="TCollection"><span data-ttu-id="8ada4-102">最終的に、コレクション内の要素の型。</span><span class="sxs-lookup"><span data-stu-id="8ada4-102">Type of elements ending up in the collection.</span></span></typeparam>
    <summary>
            <span data-ttu-id="8ada4-103">ListView、GridView、ListBox などの Xaml コレクション制御によって簡単に使用されるようにモバイル サービスのクエリの結果をラップできる非同期データ ソース。</span><span class="sxs-lookup"><span data-stu-id="8ada4-103">An asynchronous data source that can wrap the results of a Mobile Services query in a way that's easily consumed by Xaml collection controls like ListView, GridView or ListBox.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="8ada4-104">現在、データの読み込み、コントロールへの通知、およびページングを非同期的にも処理します。</span><span class="sxs-lookup"><span data-stu-id="8ada4-104">Currently handles asynchronously loading the data, notifying the controls and paging.</span></span> <span data-ttu-id="8ada4-105">使用して、<see cref="T:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`1" />クラスの場合は、テーブルとコレクション アイテムが同じ型です。</span><span class="sxs-lookup"><span data-stu-id="8ada4-105">Use the <see cref="T:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`1" /> class if the table and collection items are of the same type.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceCollection (Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;TTable&gt; query, int pageSize = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!TTable&gt; query, int32 pageSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.#ctor(Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{`0},System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (query As IMobileServiceTableQuery(Of TTable), Optional pageSize As Integer = 0)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt; : Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'able&gt; * int -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt;" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt; (query, pageSize)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;TTable&gt;" />
        <Parameter Name="pageSize" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="query">
            <span data-ttu-id="8ada4-106">データを提供するデータ ソースのクエリです。</span><span class="sxs-lookup"><span data-stu-id="8ada4-106">The data source's query which provides the data.</span></span>
            </param>
        <param name="pageSize">
            <span data-ttu-id="8ada4-107">要求ごとに要求された項目の数。</span><span class="sxs-lookup"><span data-stu-id="8ada4-107">The number of items requested per request.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ada4-108"><see cref="T:IncrementalLoadingMobileServiceCollection{TTable, TCollection}" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8ada4-108">Initializes a new instance of the <see cref="T:IncrementalLoadingMobileServiceCollection{TTable, TCollection}" /> class.</span></span> <span data-ttu-id="8ada4-109">このコンス トラクターは、TTable と TCollection が同じ型で使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="8ada4-109">This constructior should be used in cases where TTable and TCollection are the same type.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceCollection (Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;TTable&gt; query, Func&lt;System.Collections.Generic.IEnumerable&lt;TTable&gt;,System.Collections.Generic.IEnumerable&lt;TCollection&gt;&gt; selector, int pageSize = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!TTable&gt; query, class System.Func`2&lt;class System.Collections.Generic.IEnumerable`1&lt;!TTable&gt;, class System.Collections.Generic.IEnumerable`1&lt;!TCollection&gt;&gt; selector, int32 pageSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.#ctor(Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{`0},System.Func{System.Collections.Generic.IEnumerable{`0},System.Collections.Generic.IEnumerable{`1}},System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (query As IMobileServiceTableQuery(Of TTable), selector As Func(Of IEnumerable(Of TTable), IEnumerable(Of TCollection)), Optional pageSize As Integer = 0)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt; : Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'able&gt; * Func&lt;seq&lt;'able&gt;, seq&lt;'Collection&gt;&gt; * int -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt;" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt; (query, selector, pageSize)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;TTable&gt;" />
        <Parameter Name="selector" Type="System.Func&lt;System.Collections.Generic.IEnumerable&lt;TTable&gt;,System.Collections.Generic.IEnumerable&lt;TCollection&gt;&gt;" />
        <Parameter Name="pageSize" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="query">
            <span data-ttu-id="8ada4-110">データを提供するデータ ソースのクエリです。</span><span class="sxs-lookup"><span data-stu-id="8ada4-110">The data source's query which provides the data.</span></span>
            </param>
        <param name="selector">
            <span data-ttu-id="8ada4-111">クライアント側の射影を提供するセレクター関数。</span><span class="sxs-lookup"><span data-stu-id="8ada4-111">A selector function to provide client side projections.</span></span>
            </param>
        <param name="pageSize">
            <span data-ttu-id="8ada4-112">要求ごとに要求された項目の数。</span><span class="sxs-lookup"><span data-stu-id="8ada4-112">The number of items requested per request.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ada4-113"><see cref="T:IncrementalLoadingMobileServiceCollection{TTable, TCollection}" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8ada4-113">Initializes a new instance of the <see cref="T:IncrementalLoadingMobileServiceCollection{TTable, TCollection}" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceCollection (Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;TTable&gt; query, Func&lt;TTable,TCollection&gt; selector, int pageSize = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!TTable&gt; query, class System.Func`2&lt;!TTable, !TCollection&gt; selector, int32 pageSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.#ctor(Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{`0},System.Func{`0,`1},System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (query As IMobileServiceTableQuery(Of TTable), selector As Func(Of TTable, TCollection), Optional pageSize As Integer = 0)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt; : Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'able&gt; * Func&lt;'able, 'Collection&gt; * int -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt;" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt; (query, selector, pageSize)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;TTable&gt;" />
        <Parameter Name="selector" Type="System.Func&lt;TTable,TCollection&gt;" />
        <Parameter Name="pageSize" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="query">
            <span data-ttu-id="8ada4-114">データを提供するデータ ソースのクエリです。</span><span class="sxs-lookup"><span data-stu-id="8ada4-114">The data source's query which provides the data.</span></span>
            </param>
        <param name="selector">
            <span data-ttu-id="8ada4-115">クライアント側の射影を提供するセレクター関数。</span><span class="sxs-lookup"><span data-stu-id="8ada4-115">A selector function to provide client side projections.</span></span>
            </param>
        <param name="pageSize">
            <span data-ttu-id="8ada4-116">要求ごとに要求された項目の数。</span><span class="sxs-lookup"><span data-stu-id="8ada4-116">The number of items requested per request.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ada4-117"><see cref="T:IncrementalLoadingMobileServiceCollection{TTable, TCollection}" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="8ada4-117">Initializes a new instance of the <see cref="T:IncrementalLoadingMobileServiceCollection{TTable, TCollection}" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasMoreItems">
      <MemberSignature Language="C#" Value="public bool HasMoreItems { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasMoreItems" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.HasMoreItems" />
      <MemberSignature Language="VB.NET" Value="Public Property HasMoreItems As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasMoreItems : bool with get, set" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt;.HasMoreItems" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ada4-118">増分読み込みできる項目があるかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="8ada4-118">Gets a value indicating whether there are more items that can be loaded incrementally.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadingComplete">
      <MemberSignature Language="C#" Value="public event EventHandler&lt;Microsoft.WindowsAzure.MobileServices.LoadingCompleteEventArgs&gt; LoadingComplete;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler`1&lt;class Microsoft.WindowsAzure.MobileServices.LoadingCompleteEventArgs&gt; LoadingComplete" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.LoadingComplete" />
      <MemberSignature Language="VB.NET" Value="Public Event LoadingComplete As EventHandler(Of LoadingCompleteEventArgs) " />
      <MemberSignature Language="F#" Value="member this.LoadingComplete : EventHandler&lt;Microsoft.WindowsAzure.MobileServices.LoadingCompleteEventArgs&gt; " Usage="member this.LoadingComplete : System.EventHandler&lt;Microsoft.WindowsAzure.MobileServices.LoadingCompleteEventArgs&gt; " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler&lt;Microsoft.WindowsAzure.MobileServices.LoadingCompleteEventArgs&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ada4-119">アイテムの読み込みを完了すると発生します。</span><span class="sxs-lookup"><span data-stu-id="8ada4-119">Occurs when finished loading items.</span></span> <span data-ttu-id="8ada4-120">提供<see cref="T:Microsoft.WindowsAzure.MobileServices.LoadingCompleteEventArgs" />項目の数が読み込まれたとします。</span><span class="sxs-lookup"><span data-stu-id="8ada4-120">Provides <see cref="T:Microsoft.WindowsAzure.MobileServices.LoadingCompleteEventArgs" /> with how many items were loaded.</span></span>  
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadingItems">
      <MemberSignature Language="C#" Value="public event EventHandler LoadingItems;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler LoadingItems" />
      <MemberSignature Language="DocId" Value="E:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.LoadingItems" />
      <MemberSignature Language="VB.NET" Value="Public Event LoadingItems As EventHandler " />
      <MemberSignature Language="F#" Value="member this.LoadingItems : EventHandler " Usage="member this.LoadingItems : System.EventHandler " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ada4-121">発生したときに<see cref="M:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.LoadMoreItemsAsync(System.Int32)" />項目の読み込みを開始します。</span><span class="sxs-lookup"><span data-stu-id="8ada4-121">Occurs when <see cref="M:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.LoadMoreItemsAsync(System.Int32)" /> starting to load items.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadMoreItemsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;int&gt; LoadMoreItemsAsync (int count = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int32&gt; LoadMoreItemsAsync(int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.LoadMoreItemsAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function LoadMoreItemsAsync (Optional count As Integer = 0) As Task(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LoadMoreItemsAsync : int -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="mobileServiceCollection.LoadMoreItemsAsync count" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="count">
            <span data-ttu-id="8ada4-122">読み込む項目の数。</span><span class="sxs-lookup"><span data-stu-id="8ada4-122">The number of items to load.</span></span>
            <span data-ttu-id="8ada4-123">このパラメーターは、コンス トラクターで指定された pageSize をオーバーライドします。</span><span class="sxs-lookup"><span data-stu-id="8ada4-123">This parameter overrides the pageSize specified in the constructor.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ada4-124">他のアイテムを非同期的にロードします。</span><span class="sxs-lookup"><span data-stu-id="8ada4-124">Load more items asynchronously.</span></span>
            <span data-ttu-id="8ada4-125">Windows 8 の GridView などの増分読み込みをサポートするコントロールは、自動的にこのメソッドを呼び出します。</span><span class="sxs-lookup"><span data-stu-id="8ada4-125">Controls which support incremental loading on such as GridView on Windows 8 call this method automatically.</span></span>
            <span data-ttu-id="8ada4-126">それ以外の場合はこのメソッドを呼び出す自分でします。</span><span class="sxs-lookup"><span data-stu-id="8ada4-126">In other cases you should call this method yourself.</span></span>
            </summary>
        <returns><span data-ttu-id="8ada4-127">項目の読み込みの結果。</span><span class="sxs-lookup"><span data-stu-id="8ada4-127">The result of loading the items.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadMoreItemsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;int&gt; LoadMoreItemsAsync (System.Threading.CancellationToken token, int count = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int32&gt; LoadMoreItemsAsync(valuetype System.Threading.CancellationToken token, int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.LoadMoreItemsAsync(System.Threading.CancellationToken,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function LoadMoreItemsAsync (token As CancellationToken, Optional count As Integer = 0) As Task(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LoadMoreItemsAsync : System.Threading.CancellationToken * int -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="mobileServiceCollection.LoadMoreItemsAsync (token, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2/&lt;LoadMoreItemsAsync&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="token">
            <span data-ttu-id="8ada4-128">タスクの取り消しに使用されるキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8ada4-128">The cancellation token to be used to cancel the task.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="8ada4-129">読み込む項目の数。</span><span class="sxs-lookup"><span data-stu-id="8ada4-129">The number of items to load.</span></span>
            <span data-ttu-id="8ada4-130">このパラメーターは、コンス トラクターで指定された pageSize をオーバーライドします。</span><span class="sxs-lookup"><span data-stu-id="8ada4-130">This parameter overrides the pageSize specified in the constructor.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ada4-131">他のアイテムを非同期的にロードします。</span><span class="sxs-lookup"><span data-stu-id="8ada4-131">Load more items asynchronously.</span></span>
            <span data-ttu-id="8ada4-132">Windows 8 の GridView などの増分読み込みをサポートするコントロールは、自動的にこのメソッドを呼び出します。</span><span class="sxs-lookup"><span data-stu-id="8ada4-132">Controls which support incremental loading on such as GridView on Windows 8 call this method automatically.</span></span>
            <span data-ttu-id="8ada4-133">それ以外の場合はこのメソッドを呼び出す自分でします。</span><span class="sxs-lookup"><span data-stu-id="8ada4-133">In other cases you should call this method yourself.</span></span>
            </summary>
        <returns><span data-ttu-id="8ada4-134">項目の読み込みの結果。</span><span class="sxs-lookup"><span data-stu-id="8ada4-134">The result of loading the items.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextLink">
      <MemberSignature Language="C#" Value="public string NextLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.NextLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextLink As String" />
      <MemberSignature Language="F#" Value="member this.NextLink : string" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt;.NextLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ada4-135">応答ヘッダーで返される結果の次のページへのリンクを取得します。</span><span class="sxs-lookup"><span data-stu-id="8ada4-135">Gets the link to next page of result that is returned in response headers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnPropertyChanged">
      <MemberSignature Language="C#" Value="protected virtual void OnPropertyChanged (string propertyName = null);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnPropertyChanged(string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.OnPropertyChanged(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnPropertyChanged (Optional propertyName As String = null)" />
      <MemberSignature Language="F#" Value="override this.OnPropertyChanged : string -&gt; unit" Usage="mobileServiceCollection.OnPropertyChanged propertyName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String">
          <Attributes>
            <Attribute>
              <AttributeName>System.Runtime.CompilerServices.CallerMemberName</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="propertyName">
            <span data-ttu-id="8ada4-136">変更されたプロパティの名前。</span><span class="sxs-lookup"><span data-stu-id="8ada4-136">The name of the property that has changed.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ada4-137">PropertyChanged イベントを呼び出す、<paramref name="propertyName" />プロパティです。</span><span class="sxs-lookup"><span data-stu-id="8ada4-137">Invokes the PropertyChanged event for the <paramref name="propertyName" /> property.</span></span>
            <span data-ttu-id="8ada4-138">サブクラスをイベントの呼び出しの動作をオーバーライドするための手段を提供します。</span><span class="sxs-lookup"><span data-stu-id="8ada4-138">Provides a way for subclasses to override the event invocation behavior.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="8ada4-139">CallerMemberName 属性は明示的な値が指定されていない場合に、値を提供します。</span><span class="sxs-lookup"><span data-stu-id="8ada4-139">The CallerMemberName attribute will supply the value if no explicit value is provided.</span></span>
            <span data-ttu-id="8ada4-140">詳細については、http://msdn.microsoft.com/en-us/library/hh534540.aspx を参照してください。 必要があります、null チェックでは、明示的なパラメーターとして null を渡すもできるためです。</span><span class="sxs-lookup"><span data-stu-id="8ada4-140">For more info see http://msdn.microsoft.com/en-us/library/hh534540.aspx We still need the null check, because you can still pass null as an explicit parameter.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PageSize">
      <MemberSignature Language="C#" Value="public int PageSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.PageSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PageSize As Integer" />
      <MemberSignature Language="F#" Value="member this.PageSize : int" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt;.PageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ada4-141">コンス トラクターで指定されたページ サイズ。</span><span class="sxs-lookup"><span data-stu-id="8ada4-141">The page size specified in the constructor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrepareDataForCollection">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;TCollection&gt; PrepareDataForCollection (System.Collections.Generic.IEnumerable&lt;TTable&gt; items);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!TCollection&gt; PrepareDataForCollection(class System.Collections.Generic.IEnumerable`1&lt;!TTable&gt; items) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.PrepareDataForCollection(System.Collections.Generic.IEnumerable{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function PrepareDataForCollection (items As IEnumerable(Of TTable)) As IEnumerable(Of TCollection)" />
      <MemberSignature Language="F#" Value="abstract member PrepareDataForCollection : seq&lt;'able&gt; -&gt; seq&lt;'Collection&gt;&#xA;override this.PrepareDataForCollection : seq&lt;'able&gt; -&gt; seq&lt;'Collection&gt;" Usage="mobileServiceCollection.PrepareDataForCollection items" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;TCollection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="items" Type="System.Collections.Generic.IEnumerable&lt;TTable&gt;" />
      </Parameters>
      <Docs>
        <param name="items"><span data-ttu-id="8ada4-142">項目。</span><span class="sxs-lookup"><span data-stu-id="8ada4-142">The items.</span></span></param>
        <summary>
            <span data-ttu-id="8ada4-143">指定されたセレクター関数を使用して、コレクションのデータにクエリからデータを変換します。</span><span class="sxs-lookup"><span data-stu-id="8ada4-143">Transforms the data from the query into data for the collection using the provided selector function.</span></span>
            </summary>
        <returns><span data-ttu-id="8ada4-144">変換されたデータ。</span><span class="sxs-lookup"><span data-stu-id="8ada4-144">The transformed data.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrepareDataForCollection">
      <MemberSignature Language="C#" Value="public TCollection PrepareDataForCollection (TTable item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !TCollection PrepareDataForCollection(!TTable item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.PrepareDataForCollection(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function PrepareDataForCollection (item As TTable) As TCollection" />
      <MemberSignature Language="F#" Value="member this.PrepareDataForCollection : 'able -&gt; 'Collection" Usage="mobileServiceCollection.PrepareDataForCollection item" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TCollection</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="TTable" />
      </Parameters>
      <Docs>
        <param name="item"><span data-ttu-id="8ada4-145">項目。</span><span class="sxs-lookup"><span data-stu-id="8ada4-145">The item.</span></span></param>
        <summary>
            <span data-ttu-id="8ada4-146">指定されたセレクター関数を使用して、コレクションの項目に 1 つの項目を変換します。</span><span class="sxs-lookup"><span data-stu-id="8ada4-146">Transforms one item into an item for the collection using the provided selector function.</span></span>
            </summary>
        <returns><span data-ttu-id="8ada4-147">変換された項目。</span><span class="sxs-lookup"><span data-stu-id="8ada4-147">The transformed item.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessQueryAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;int&gt; ProcessQueryAsync (System.Threading.CancellationToken token, Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;TTable&gt; query);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;int32&gt; ProcessQueryAsync(valuetype System.Threading.CancellationToken token, class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!TTable&gt; query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.ProcessQueryAsync(System.Threading.CancellationToken,Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{`0})" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function ProcessQueryAsync (token As CancellationToken, query As IMobileServiceTableQuery(Of TTable)) As Task(Of Integer)" />
      <MemberSignature Language="F#" Value="abstract member ProcessQueryAsync : System.Threading.CancellationToken * Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'able&gt; -&gt; System.Threading.Tasks.Task&lt;int&gt;&#xA;override this.ProcessQueryAsync : System.Threading.CancellationToken * Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'able&gt; -&gt; System.Threading.Tasks.Task&lt;int&gt;" Usage="mobileServiceCollection.ProcessQueryAsync (token, query)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2/&lt;ProcessQueryAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;TTable&gt;" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="8ada4-148">操作をキャンセルするトークンです。</span><span class="sxs-lookup"><span data-stu-id="8ada4-148">A token to cancel the operation.</span></span></param>
        <param name="query"><span data-ttu-id="8ada4-149">評価するクエリ。</span><span class="sxs-lookup"><span data-stu-id="8ada4-149">The query to evaluate.</span></span></param>
        <summary>
            <span data-ttu-id="8ada4-150">クエリを評価し、結果をコレクションに追加します。</span><span class="sxs-lookup"><span data-stu-id="8ada4-150">Evaluates the query and adds the result to the collection.</span></span>
            </summary>
        <returns><span data-ttu-id="8ada4-151">進行中の操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="8ada4-151">A task representing the ongoing operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="selectorFunction">
      <MemberSignature Language="C#" Value="protected Func&lt;System.Collections.Generic.IEnumerable&lt;TTable&gt;,System.Collections.Generic.IEnumerable&lt;TCollection&gt;&gt; selectorFunction;" />
      <MemberSignature Language="ILAsm" Value=".field family class System.Func`2&lt;class System.Collections.Generic.IEnumerable`1&lt;!TTable&gt;, class System.Collections.Generic.IEnumerable`1&lt;!TCollection&gt;&gt; selectorFunction" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.selectorFunction" />
      <MemberSignature Language="VB.NET" Value="Protected selectorFunction As Func(Of IEnumerable(Of TTable), IEnumerable(Of TCollection)) " />
      <MemberSignature Language="F#" Value="val mutable selectorFunction : Func&lt;seq&lt;'able&gt;, seq&lt;'Collection&gt;&gt;" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt;.selectorFunction" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Collections.Generic.IEnumerable&lt;TTable&gt;,System.Collections.Generic.IEnumerable&lt;TCollection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ada4-152">なるデータに appied サーバーから戻ったときにセレクター関数。</span><span class="sxs-lookup"><span data-stu-id="8ada4-152">A selector function which will be appied to the data when it comes back from the server.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalCount">
      <MemberSignature Language="C#" Value="public long TotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TotalCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceCollection`2.TotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalCount As Long" />
      <MemberSignature Language="F#" Value="member this.TotalCount : int64" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceCollection&lt;'able, 'Collection&gt;.TotalCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ada4-153">クライアントまたはサーバーで指定された任意の take paging/limit 句を無視して返されたすべてのレコードの合計数を取得します。</span><span class="sxs-lookup"><span data-stu-id="8ada4-153">Gets the total count for all the records that would have been returned ignoring any take paging/limit clause specified by client or server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>