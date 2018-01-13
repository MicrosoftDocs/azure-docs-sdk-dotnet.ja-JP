<Type Name="IMobileServiceSyncTable&lt;T&gt;" FullName="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IMobileServiceSyncTable&lt;T&gt; : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMobileServiceSyncTable`1&lt;T&gt; implements class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMobileServiceSyncTable(Of T)&#xA;Implements IMobileServiceSyncTable" />
  <TypeSignature Language="F#" Value="type IMobileServiceSyncTable&lt;'T&gt; = interface&#xA;    interface IMobileServiceSyncTable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <summary>
            <span data-ttu-id="42147-101">ローカル テーブルでの操作を提供します。</span><span class="sxs-lookup"><span data-stu-id="42147-101">Provides operations on local table.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateQuery">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; CreateQuery ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; CreateQuery() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.CreateQuery" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateQuery () As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : unit -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceSyncTable.CreateQuery " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="42147-102">現在のテーブルに対してクエリを作成します。</span><span class="sxs-lookup"><span data-stu-id="42147-102">Creates a query for the current table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42147-103">テーブルに対するクエリ。</span><span class="sxs-lookup"><span data-stu-id="42147-103">A query against the table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (T instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(!T instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.DeleteAsync(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteAsync (instance As T) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : 'T -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncTable.DeleteAsync instance" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="instance" Type="T" />
      </Parameters>
      <Docs>
        <param name="instance">
            <span data-ttu-id="42147-104">テーブルから削除するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="42147-104">The instance to delete from the table.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42147-105">削除、<paramref name="instance" />テーブルからです。</span><span class="sxs-lookup"><span data-stu-id="42147-105">Deletes an <paramref name="instance" /> from the table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42147-106">削除の終了時に完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="42147-106">A task that will complete when the delete finishes.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludeTotalCount">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; IncludeTotalCount ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; IncludeTotalCount() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.IncludeTotalCount" />
      <MemberSignature Language="VB.NET" Value="Public Function IncludeTotalCount () As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member IncludeTotalCount : unit -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceSyncTable.IncludeTotalCount " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="42147-107">無視して返されたすべてのレコードがページングを実行/クライアントまたはサーバーで指定された句を制限の合計数を取得するクエリを作成します。</span><span class="sxs-lookup"><span data-stu-id="42147-107">Creates a query that will ensure it gets the total count for all the records that would have been returned ignoring any take paging/ limit clause specified by client or server.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42147-108">テーブルに対するクエリ。</span><span class="sxs-lookup"><span data-stu-id="42147-108">A query against the table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task InsertAsync (T instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task InsertAsync(!T instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.InsertAsync(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function InsertAsync (instance As T) As Task" />
      <MemberSignature Language="F#" Value="abstract member InsertAsync : 'T -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncTable.InsertAsync instance" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="instance" Type="T" />
      </Parameters>
      <Docs>
        <param name="instance">
            <span data-ttu-id="42147-109">テーブルに挿入するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="42147-109">The instance to insert into the table.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42147-110">挿入、<paramref name="instance" />テーブルにします。</span><span class="sxs-lookup"><span data-stu-id="42147-110">Inserts an <paramref name="instance" /> into the table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42147-111">挿入の終了時に完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="42147-111">A task that will complete when the insert finishes.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LookupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; LookupAsync (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!T&gt; LookupAsync(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.LookupAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function LookupAsync (id As String) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member LookupAsync : string -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iMobileServiceSyncTable.LookupAsync id" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">
            <span data-ttu-id="42147-112">インスタンスの id。</span><span class="sxs-lookup"><span data-stu-id="42147-112">The id of the instance.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42147-113">参照 id によってテーブルからインスタンスです。</span><span class="sxs-lookup"><span data-stu-id="42147-113">Lookup an instance from a table by its id.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42147-114">目的のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="42147-114">The desired instance.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrderBy&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; OrderBy&lt;TKey&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,TKey&gt;&gt; keySelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; OrderBy&lt;TKey&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!TKey&gt;&gt; keySelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.OrderBy``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function OrderBy(Of TKey) (keySelector As Expression(Of Func(Of T, TKey))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member OrderBy : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'Key&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceSyncTable.OrderBy keySelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="keySelector" Type="System.Linq.Expressions.Expression&lt;System.Func&lt;T,TKey&gt;&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">
            <span data-ttu-id="42147-115">並べ替え対象のメンバーの型。</span><span class="sxs-lookup"><span data-stu-id="42147-115">The type of the member being ordered by.</span></span>
            </typeparam>
        <param name="keySelector">
            <span data-ttu-id="42147-116">並べ替えるメンバーを選択する式。</span><span class="sxs-lookup"><span data-stu-id="42147-116">The expression selecting the member to order by.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42147-117">指定した ascending order 句を適用することにより、クエリを作成します。</span><span class="sxs-lookup"><span data-stu-id="42147-117">Creates a query by applying the specified ascending order clause.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42147-118">テーブルに対するクエリ。</span><span class="sxs-lookup"><span data-stu-id="42147-118">A query against the table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrderByDescending&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; OrderByDescending&lt;TKey&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,TKey&gt;&gt; keySelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; OrderByDescending&lt;TKey&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!TKey&gt;&gt; keySelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.OrderByDescending``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function OrderByDescending(Of TKey) (keySelector As Expression(Of Func(Of T, TKey))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member OrderByDescending : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'Key&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceSyncTable.OrderByDescending keySelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="keySelector" Type="System.Linq.Expressions.Expression&lt;System.Func&lt;T,TKey&gt;&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">
            <span data-ttu-id="42147-119">並べ替え対象のメンバーの型。</span><span class="sxs-lookup"><span data-stu-id="42147-119">The type of the member being ordered by.</span></span>
            </typeparam>
        <param name="keySelector">
            <span data-ttu-id="42147-120">並べ替えるメンバーを選択する式。</span><span class="sxs-lookup"><span data-stu-id="42147-120">The expression selecting the member to order by.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42147-121">指定した descending order 句を適用することにより、クエリを作成します。</span><span class="sxs-lookup"><span data-stu-id="42147-121">Creates a query by applying the specified descending order clause.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42147-122">テーブルに対するクエリ。</span><span class="sxs-lookup"><span data-stu-id="42147-122">A query against the table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PullAsync&lt;U&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PullAsync&lt;U&gt; (string queryId, Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; query, bool pushOtherTables, System.Threading.CancellationToken cancellationToken, Microsoft.WindowsAzure.MobileServices.Sync.PullOptions pullOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PullAsync&lt;U&gt;(string queryId, class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; query, bool pushOtherTables, valuetype System.Threading.CancellationToken cancellationToken, class Microsoft.WindowsAzure.MobileServices.Sync.PullOptions pullOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.PullAsync``1(System.String,Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{``0},System.Boolean,System.Threading.CancellationToken,Microsoft.WindowsAzure.MobileServices.Sync.PullOptions)" />
      <MemberSignature Language="F#" Value="abstract member PullAsync : string * Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt; * bool * System.Threading.CancellationToken * Microsoft.WindowsAzure.MobileServices.Sync.PullOptions -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncTable.PullAsync (queryId, query, pushOtherTables, cancellationToken, pullOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt;" />
        <Parameter Name="pushOtherTables" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="pullOptions" Type="Microsoft.WindowsAzure.MobileServices.Sync.PullOptions" />
      </Parameters>
      <Docs>
        <typeparam name="U">To be added.</typeparam>
        <param name="queryId">
            <span data-ttu-id="42147-123">一意にこのクエリを識別し、同期状態を追跡するために使用する文字列。</span><span class="sxs-lookup"><span data-stu-id="42147-123">A string that uniquely identifies this query and is used to keep track of its sync state.</span></span> <span data-ttu-id="42147-124">このパラメーターを指定すること、同じキーを再度使用されるたびに増分同期を有効にします。</span><span class="sxs-lookup"><span data-stu-id="42147-124">Supplying this parameter enables incremental sync whenever the same key is used again.</span></span>
            </param>
        <param name="query">
            <span data-ttu-id="42147-125">リモート テーブルからプルする項目を決定する OData クエリ。</span><span class="sxs-lookup"><span data-stu-id="42147-125">An OData query that determines which items to pull from the remote table.</span></span>
            </param>
        <param name="pushOtherTables">
            <span data-ttu-id="42147-126">このテーブルがダーティの場合は、他のテーブルをプッシュします。</span><span class="sxs-lookup"><span data-stu-id="42147-126">Push other tables if this table is dirty</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="42147-127"><see cref="T:System.Threading.CancellationToken" />観察するトークン</span><span class="sxs-lookup"><span data-stu-id="42147-127">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span>
            </param>
        <param name="pullOptions">
            <span data-ttu-id="42147-128">リモート テーブルからデータをプルする方法を決定する PullOptions</span><span class="sxs-lookup"><span data-stu-id="42147-128">PullOptions that determine how to pull data from the remote table</span></span>
            </param>
        <summary>
            <span data-ttu-id="42147-129">関連付けられているリモート テーブルから特定のクエリに一致するすべての項目を取得します。</span><span class="sxs-lookup"><span data-stu-id="42147-129">Pulls all items that match the given query from the associated remote table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42147-130">完了するタスクをプル操作が完了するとします。</span><span class="sxs-lookup"><span data-stu-id="42147-130">A task that completes when pull operation has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeAsync&lt;U&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PurgeAsync&lt;U&gt; (string queryId, Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; query, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PurgeAsync&lt;U&gt;(string queryId, class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; query, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.PurgeAsync``1(System.String,Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{``0},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeAsync : string * Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncTable.PurgeAsync (queryId, query, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="U">To be added.</typeparam>
        <param name="queryId">
            <span data-ttu-id="42147-131">一意にこのクエリを識別し、同期状態を追跡するために使用する文字列。</span><span class="sxs-lookup"><span data-stu-id="42147-131">A string that uniquely identifies this query and is used to keep track of its sync state.</span></span> <span data-ttu-id="42147-132">このパラメーターを指定すると、クエリの差分同期状態がリセットされます。</span><span class="sxs-lookup"><span data-stu-id="42147-132">Supplying this parameter resets the incremental sync state for the query.</span></span>
            </param>
        <param name="query"><span data-ttu-id="42147-133">削除する項目を決定する OData クエリ。</span><span class="sxs-lookup"><span data-stu-id="42147-133">An OData query that determines which items to delete.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="42147-134"><see cref="T:System.Threading.CancellationToken" />観察するトークン</span><span class="sxs-lookup"><span data-stu-id="42147-134">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span>
            </param>
        <summary>
            <span data-ttu-id="42147-135">クエリに一致するローカル テーブル内のすべての項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="42147-135">Deletes all the items in local table that match the query.</span></span>
            </summary>
        <returns><span data-ttu-id="42147-136">ときに完了するタスクをパージ操作が完了します。</span><span class="sxs-lookup"><span data-stu-id="42147-136">A task that completes when purge operation has finished.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeAsync&lt;U&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PurgeAsync&lt;U&gt; (string queryId, Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; query, bool force, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PurgeAsync&lt;U&gt;(string queryId, class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; query, bool force, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.PurgeAsync``1(System.String,Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{``0},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeAsync : string * Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt; * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncTable.PurgeAsync (queryId, query, force, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="queryId" Type="System.String" />
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt;" />
        <Parameter Name="force" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="U">To be added.</typeparam>
        <param name="queryId">
            <span data-ttu-id="42147-137">一意にこのクエリを識別し、同期状態を追跡するために使用する文字列。</span><span class="sxs-lookup"><span data-stu-id="42147-137">A string that uniquely identifies this query and is used to keep track of its sync state.</span></span> <span data-ttu-id="42147-138">このパラメーターを指定すると、クエリの差分同期状態がリセットされます。</span><span class="sxs-lookup"><span data-stu-id="42147-138">Supplying this parameter resets the incremental sync state for the query.</span></span>
            </param>
        <param name="query"><span data-ttu-id="42147-139">削除する項目を決定する OData クエリ。</span><span class="sxs-lookup"><span data-stu-id="42147-139">An OData query that determines which items to delete.</span></span></param>
        <param name="force"><span data-ttu-id="42147-140">保留中の操作を破棄することによって、消去を強制します。</span><span class="sxs-lookup"><span data-stu-id="42147-140">Force the purge by discarding the pending operations.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="42147-141"><see cref="T:System.Threading.CancellationToken" />観察するトークン</span><span class="sxs-lookup"><span data-stu-id="42147-141">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span>
            </param>
        <summary>
            <span data-ttu-id="42147-142">クエリに一致するローカル テーブル内のすべての項目を削除します。</span><span class="sxs-lookup"><span data-stu-id="42147-142">Deletes all the items in local table that match the query.</span></span>
            </summary>
        <returns><span data-ttu-id="42147-143">ときに完了するタスクをパージ操作が完了します。</span><span class="sxs-lookup"><span data-stu-id="42147-143">A task that completes when purge operation has finished.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;T&gt;&gt; ReadAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;!T&gt;&gt; ReadAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.ReadAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAsync () As Task(Of IEnumerable(Of T))" />
      <MemberSignature Language="F#" Value="abstract member ReadAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;'T&gt;&gt;" Usage="iMobileServiceSyncTable.ReadAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="42147-144">テーブルからインスタンスを返します。</span><span class="sxs-lookup"><span data-stu-id="42147-144">Returns instances from a table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42147-145">テーブルからのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="42147-145">Instances from the table.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="42147-146">この呼び出しがページングなどを処理しません。</span><span class="sxs-lookup"><span data-stu-id="42147-146">This call will not handle paging, etc., for you.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync&lt;U&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;U&gt;&gt; ReadAsync&lt;U&gt; (Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; query);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;!!U&gt;&gt; ReadAsync&lt;U&gt;(class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.ReadAsync``1(Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{``0})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAsync(Of U) (query As IMobileServiceTableQuery(Of U)) As Task(Of IEnumerable(Of U))" />
      <MemberSignature Language="F#" Value="abstract member ReadAsync : Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt; -&gt; System.Threading.Tasks.Task&lt;seq&lt;'U&gt;&gt;" Usage="iMobileServiceSyncTable.ReadAsync query" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;U&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="U">
            <span data-ttu-id="42147-147">クエリによって返されるインスタンスの型。</span><span class="sxs-lookup"><span data-stu-id="42147-147">The type of instance returned by the query.</span></span>
            </typeparam>
        <param name="query">
            <span data-ttu-id="42147-148">クエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="42147-148">The query to execute.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42147-149">クエリに基づいているテーブルからインスタンスを返します。</span><span class="sxs-lookup"><span data-stu-id="42147-149">Returns instances from a table based on a query.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42147-150">テーブルからのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="42147-150">Instances from the table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RefreshAsync (T instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RefreshAsync(!T instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.RefreshAsync(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function RefreshAsync (instance As T) As Task" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : 'T -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncTable.RefreshAsync instance" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="instance" Type="T" />
      </Parameters>
      <Docs>
        <param name="instance">
            <span data-ttu-id="42147-151">更新するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="42147-151">The instance to refresh.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42147-152">現在のインスタンスと、ローカル テーブルからの最新の値を更新します。</span><span class="sxs-lookup"><span data-stu-id="42147-152">Refresh the current instance with the latest values from the local table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42147-153">更新が完了したときに完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="42147-153">A task that will complete when the refresh has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Select&lt;U&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; Select&lt;U&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,U&gt;&gt; selector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; Select&lt;U&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!U&gt;&gt; selector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.Select``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function Select(Of U) (selector As Expression(Of Func(Of T, U))) As IMobileServiceTableQuery(Of U)" />
      <MemberSignature Language="F#" Value="abstract member Select : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'U&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt;" Usage="iMobileServiceSyncTable.Select selector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="selector" Type="System.Linq.Expressions.Expression&lt;System.Func&lt;T,U&gt;&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="U">
            <span data-ttu-id="42147-154">クエリの射影された結果を表す型。</span><span class="sxs-lookup"><span data-stu-id="42147-154">Type representing the projected result of the query.</span></span>
            </typeparam>
        <param name="selector">
            <span data-ttu-id="42147-155">selector 関数。</span><span class="sxs-lookup"><span data-stu-id="42147-155">The selector function.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42147-156">指定した選択を適用することにより、クエリを作成します。</span><span class="sxs-lookup"><span data-stu-id="42147-156">Creates a query by applying the specified selection.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42147-157">テーブルに対するクエリ。</span><span class="sxs-lookup"><span data-stu-id="42147-157">A query against the table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Skip">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; Skip (int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; Skip(int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.Skip(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function Skip (count As Integer) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member Skip : int -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceSyncTable.Skip count" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="count">
            <span data-ttu-id="42147-158">skip の数値。</span><span class="sxs-lookup"><span data-stu-id="42147-158">The number to skip.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42147-159">指定した skip 句を適用することにより、クエリを作成します。</span><span class="sxs-lookup"><span data-stu-id="42147-159">Creates a query by applying the specified skip clause.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42147-160">テーブルに対するクエリ。</span><span class="sxs-lookup"><span data-stu-id="42147-160">A query against the table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Take">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; Take (int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; Take(int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.Take(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function Take (count As Integer) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member Take : int -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceSyncTable.Take count" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="count">
            <span data-ttu-id="42147-161">take の数値。</span><span class="sxs-lookup"><span data-stu-id="42147-161">The number to take.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42147-162">指定した take 句を適用することにより、クエリを作成します。</span><span class="sxs-lookup"><span data-stu-id="42147-162">Creates a query by applying the specified take clause.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42147-163">テーブルに対するクエリ。</span><span class="sxs-lookup"><span data-stu-id="42147-163">A query against the table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThenBy&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; ThenBy&lt;TKey&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,TKey&gt;&gt; keySelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; ThenBy&lt;TKey&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!TKey&gt;&gt; keySelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.ThenBy``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function ThenBy(Of TKey) (keySelector As Expression(Of Func(Of T, TKey))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member ThenBy : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'Key&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceSyncTable.ThenBy keySelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="keySelector" Type="System.Linq.Expressions.Expression&lt;System.Func&lt;T,TKey&gt;&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">
            <span data-ttu-id="42147-164">並べ替え対象のメンバーの型。</span><span class="sxs-lookup"><span data-stu-id="42147-164">The type of the member being ordered by.</span></span>
            </typeparam>
        <param name="keySelector">
            <span data-ttu-id="42147-165">並べ替えるメンバーを選択する式。</span><span class="sxs-lookup"><span data-stu-id="42147-165">The expression selecting the member to order by.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42147-166">指定した ascending order 句を適用することにより、クエリを作成します。</span><span class="sxs-lookup"><span data-stu-id="42147-166">Creates a query by applying the specified ascending order clause.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42147-167">テーブルに対するクエリ。</span><span class="sxs-lookup"><span data-stu-id="42147-167">A query against the table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThenByDescending&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; ThenByDescending&lt;TKey&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,TKey&gt;&gt; keySelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; ThenByDescending&lt;TKey&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!TKey&gt;&gt; keySelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.ThenByDescending``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function ThenByDescending(Of TKey) (keySelector As Expression(Of Func(Of T, TKey))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member ThenByDescending : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'Key&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceSyncTable.ThenByDescending keySelector" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TKey" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="keySelector" Type="System.Linq.Expressions.Expression&lt;System.Func&lt;T,TKey&gt;&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TKey">
            <span data-ttu-id="42147-168">並べ替え対象のメンバーの型。</span><span class="sxs-lookup"><span data-stu-id="42147-168">The type of the member being ordered by.</span></span>
            </typeparam>
        <param name="keySelector">
            <span data-ttu-id="42147-169">並べ替えるメンバーを選択する式。</span><span class="sxs-lookup"><span data-stu-id="42147-169">The expression selecting the member to order by.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42147-170">指定した descending order 句を適用することにより、クエリを作成します。</span><span class="sxs-lookup"><span data-stu-id="42147-170">Creates a query by applying the specified descending order clause.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42147-171">テーブルに対するクエリ。</span><span class="sxs-lookup"><span data-stu-id="42147-171">A query against the table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;T&gt;&gt; ToEnumerableAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;!T&gt;&gt; ToEnumerableAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.ToEnumerableAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ToEnumerableAsync () As Task(Of IEnumerable(Of T))" />
      <MemberSignature Language="F#" Value="abstract member ToEnumerableAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;'T&gt;&gt;" Usage="iMobileServiceSyncTable.ToEnumerableAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="42147-172">テーブルの要素を非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="42147-172">Gets the elements of the table asynchronously.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42147-173">テーブル要素のシーケンスとして結果。</span><span class="sxs-lookup"><span data-stu-id="42147-173">The table elements results as a sequence.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;T&gt;&gt; ToListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.List`1&lt;!T&gt;&gt; ToListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.ToListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ToListAsync () As Task(Of List(Of T))" />
      <MemberSignature Language="F#" Value="abstract member ToListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;'T&gt;&gt;" Usage="iMobileServiceSyncTable.ToListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="42147-174">テーブルの要素を非同期に取得し、新しい一覧で、結果を返します。</span><span class="sxs-lookup"><span data-stu-id="42147-174">Gets the elements of the table asynchronously and return the results in a new List.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42147-175">テーブル要素の一覧として結果。</span><span class="sxs-lookup"><span data-stu-id="42147-175">The table elements results as a List.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateAsync (T instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateAsync(!T instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.UpdateAsync(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateAsync (instance As T) As Task" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : 'T -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncTable.UpdateAsync instance" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="instance" Type="T" />
      </Parameters>
      <Docs>
        <param name="instance">
            <span data-ttu-id="42147-176">テーブルで更新するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="42147-176">The instance to update in the table.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42147-177">更新プログラム、<paramref name="instance" />テーブルにします。</span><span class="sxs-lookup"><span data-stu-id="42147-177">Updates an <paramref name="instance" /> in the table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42147-178">更新プログラムが終了するときに完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="42147-178">A task that will complete when the update finishes.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Where">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; Where (System.Linq.Expressions.Expression&lt;Func&lt;T,bool&gt;&gt; predicate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; Where(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, bool&gt;&gt; predicate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1.Where(System.Linq.Expressions.Expression{System.Func{`0,System.Boolean}})" />
      <MemberSignature Language="VB.NET" Value="Public Function Where (predicate As Expression(Of Func(Of T, Boolean))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member Where : System.Linq.Expressions.Expression&lt;Func&lt;'T, bool&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceSyncTable.Where predicate" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="predicate" Type="System.Linq.Expressions.Expression&lt;System.Func&lt;T,System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="predicate">
            <span data-ttu-id="42147-179">フィルター述語。</span><span class="sxs-lookup"><span data-stu-id="42147-179">The filter predicate.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42147-180">指定したフィルター述語を適用することにより、クエリを作成します。</span><span class="sxs-lookup"><span data-stu-id="42147-180">Creates a query by applying the specified filter predicate.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42147-181">テーブルに対するクエリ。</span><span class="sxs-lookup"><span data-stu-id="42147-181">A query against the table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>