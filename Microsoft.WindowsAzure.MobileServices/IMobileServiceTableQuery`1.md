<Type Name="IMobileServiceTableQuery&lt;T&gt;" FullName="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IMobileServiceTableQuery&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMobileServiceTableQuery`1&lt;T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMobileServiceTableQuery(Of T)" />
  <TypeSignature Language="F#" Value="type IMobileServiceTableQuery&lt;'T&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <summary>
            <span data-ttu-id="b16e4-101">モバイル サービス テーブルに対して評価可能なクエリを表します。</span><span class="sxs-lookup"><span data-stu-id="b16e4-101">Represents a query that can be evaluated against a Mobile Services table.</span></span> <span data-ttu-id="b16e4-102">MobileServiceTableQuery インスタンスは、(の T)() MobileServiceClient.Query 経由で取得することができます。</span><span class="sxs-lookup"><span data-stu-id="b16e4-102">MobileServiceTableQuery instances can be obtained via MobileServiceClient.Query(of T)().</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="b16e4-103">実装する IQueryable 直接ではなく、MobileServiceTableQuery オブジェクトでサポートする LINQ クエリ パターンの部分を実装しました。</span><span class="sxs-lookup"><span data-stu-id="b16e4-103">Rather than implenting IQueryable directly, we've implemented the portion of the LINQ query pattern we support on MobileServiceTableQuery objects.</span></span>  <span data-ttu-id="b16e4-104">MobileServiceTableQuery インスタンスは、LINQ クエリ操作から iqueryables を作成に使用されます。</span><span class="sxs-lookup"><span data-stu-id="b16e4-104">MobileServiceTableQuery instances are used to build up IQueryables from LINQ query operations.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="IncludeDeleted">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; IncludeDeleted ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; IncludeDeleted() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.IncludeDeleted" />
      <MemberSignature Language="VB.NET" Value="Public Function IncludeDeleted () As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member IncludeDeleted : unit -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTableQuery.IncludeDeleted " />
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
            <span data-ttu-id="b16e4-105">クエリで削除されたレコードを取得することを確認します。</span><span class="sxs-lookup"><span data-stu-id="b16e4-105">Ensure the query will get the deleted records.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b16e4-106">クエリ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="b16e4-106">The query object.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludeTotalCount">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; IncludeTotalCount ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; IncludeTotalCount() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.IncludeTotalCount" />
      <MemberSignature Language="VB.NET" Value="Public Function IncludeTotalCount () As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member IncludeTotalCount : unit -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTableQuery.IncludeTotalCount " />
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
            <span data-ttu-id="b16e4-107">クライアントまたはサーバーで指定された take paging/limit 句を無視することで、返されるすべてのレコードの総数がクエリによって取得されることを確認します。</span><span class="sxs-lookup"><span data-stu-id="b16e4-107">Ensure the query will get the total count for all the records that would have been returned ignoring any take paging/limit clause specified by client or server.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b16e4-108">クエリ オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="b16e4-108">The query object.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrderBy&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; OrderBy&lt;TKey&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,TKey&gt;&gt; keySelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; OrderBy&lt;TKey&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!TKey&gt;&gt; keySelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.OrderBy``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function OrderBy(Of TKey) (keySelector As Expression(Of Func(Of T, TKey))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member OrderBy : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'Key&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTableQuery.OrderBy keySelector" />
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
            <span data-ttu-id="b16e4-109">並べ替え対象のメンバーの型。</span><span class="sxs-lookup"><span data-stu-id="b16e4-109">The type of the member being ordered by.</span></span>
            </typeparam>
        <param name="keySelector">
            <span data-ttu-id="b16e4-110">並べ替えるメンバーを選択する式。</span><span class="sxs-lookup"><span data-stu-id="b16e4-110">The expression selecting the member to order by.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b16e4-111">指定した ascending order 句をソース クエリに適用します。</span><span class="sxs-lookup"><span data-stu-id="b16e4-111">Applies the specified ascending order clause to the source query.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b16e4-112">作成されたクエリ。</span><span class="sxs-lookup"><span data-stu-id="b16e4-112">The composed query.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrderByDescending&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; OrderByDescending&lt;TKey&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,TKey&gt;&gt; keySelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; OrderByDescending&lt;TKey&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!TKey&gt;&gt; keySelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.OrderByDescending``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function OrderByDescending(Of TKey) (keySelector As Expression(Of Func(Of T, TKey))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member OrderByDescending : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'Key&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTableQuery.OrderByDescending keySelector" />
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
            <span data-ttu-id="b16e4-113">並べ替え対象のメンバーの型。</span><span class="sxs-lookup"><span data-stu-id="b16e4-113">The type of the member being ordered by.</span></span>
            </typeparam>
        <param name="keySelector">
            <span data-ttu-id="b16e4-114">並べ替えるメンバーを選択する式。</span><span class="sxs-lookup"><span data-stu-id="b16e4-114">The expression selecting the member to order by.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b16e4-115">指定した descending order 句をソース クエリに適用します。</span><span class="sxs-lookup"><span data-stu-id="b16e4-115">Applies the specified descending order clause to the source query.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b16e4-116">作成されたクエリ。</span><span class="sxs-lookup"><span data-stu-id="b16e4-116">The composed query.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Parameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parameters As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b16e4-117">クエリに含めるユーザー定義のクエリ文字列パラメーター。</span><span class="sxs-lookup"><span data-stu-id="b16e4-117">The user-defined query string parameters to include with the query.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Query">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryable&lt;T&gt; Query { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Linq.IQueryable`1&lt;!T&gt; Query" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.Query" />
      <MemberSignature Language="VB.NET" Value="Public Property Query As IQueryable(Of T)" />
      <MemberSignature Language="F#" Value="member this.Query : System.Linq.IQueryable&lt;'T&gt; with get, set" Usage="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;.Query" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b16e4-118">このクエリに関連付けられている基になる IQueryable を取得します。</span><span class="sxs-lookup"><span data-stu-id="b16e4-118">Gets the underlying IQueryable associated with this query.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestTotalCount">
      <MemberSignature Language="C#" Value="public bool RequestTotalCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequestTotalCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.RequestTotalCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestTotalCount As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequestTotalCount : bool" Usage="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;.RequestTotalCount" />
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
            <span data-ttu-id="b16e4-119">クライアントまたはサーバーで指定された任意の take paging/limit 句を無視して返されたすべてのレコードの合計数をクエリが要求するかどうかを示す値を取得します。</span><span class="sxs-lookup"><span data-stu-id="b16e4-119">Gets a value indicating whether the query will request the total count for all the records that would have been returned ignoring any take paging/limit clause specified by client or server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Select&lt;U&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; Select&lt;U&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,U&gt;&gt; selector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; Select&lt;U&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!U&gt;&gt; selector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.Select``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function Select(Of U) (selector As Expression(Of Func(Of T, U))) As IMobileServiceTableQuery(Of U)" />
      <MemberSignature Language="F#" Value="abstract member Select : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'U&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt;" Usage="iMobileServiceTableQuery.Select selector" />
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
            <span data-ttu-id="b16e4-120">クエリの射影された結果を表す型。</span><span class="sxs-lookup"><span data-stu-id="b16e4-120">Type representing the projected result of the query.</span></span>
            </typeparam>
        <param name="selector">
            <span data-ttu-id="b16e4-121">selector 関数。</span><span class="sxs-lookup"><span data-stu-id="b16e4-121">The selector function.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b16e4-122">指定した選択をソース クエリに適用します。</span><span class="sxs-lookup"><span data-stu-id="b16e4-122">Applies the specified selection to the source query.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b16e4-123">作成されたクエリ。</span><span class="sxs-lookup"><span data-stu-id="b16e4-123">The composed query.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Skip">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; Skip (int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; Skip(int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.Skip(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function Skip (count As Integer) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member Skip : int -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTableQuery.Skip count" />
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
            <span data-ttu-id="b16e4-124">skip の数値。</span><span class="sxs-lookup"><span data-stu-id="b16e4-124">The number to skip.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b16e4-125">指定した skip 句をソース クエリに適用します。</span><span class="sxs-lookup"><span data-stu-id="b16e4-125">Applies the specified skip clause to the source query.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b16e4-126">作成されたクエリ。</span><span class="sxs-lookup"><span data-stu-id="b16e4-126">The composed query.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Table">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTable&lt;T&gt; Table { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1&lt;!T&gt; Table" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.Table" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Table As IMobileServiceTable(Of T)" />
      <MemberSignature Language="F#" Value="member this.Table : Microsoft.WindowsAzure.MobileServices.IMobileServiceTable&lt;'T&gt;" Usage="Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;.Table" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b16e4-127">クエリ対象の MobileServiceTable を取得します。</span><span class="sxs-lookup"><span data-stu-id="b16e4-127">Gets the MobileServiceTable being queried.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Take">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; Take (int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; Take(int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.Take(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function Take (count As Integer) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member Take : int -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTableQuery.Take count" />
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
            <span data-ttu-id="b16e4-128">take の数値。</span><span class="sxs-lookup"><span data-stu-id="b16e4-128">The number to take.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b16e4-129">指定した take 句をソース クエリに適用します。</span><span class="sxs-lookup"><span data-stu-id="b16e4-129">Applies the specified take clause to the source query.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b16e4-130">作成されたクエリ。</span><span class="sxs-lookup"><span data-stu-id="b16e4-130">The composed query.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThenBy&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; ThenBy&lt;TKey&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,TKey&gt;&gt; keySelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; ThenBy&lt;TKey&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!TKey&gt;&gt; keySelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.ThenBy``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function ThenBy(Of TKey) (keySelector As Expression(Of Func(Of T, TKey))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member ThenBy : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'Key&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTableQuery.ThenBy keySelector" />
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
            <span data-ttu-id="b16e4-131">並べ替え対象のメンバーの型。</span><span class="sxs-lookup"><span data-stu-id="b16e4-131">The type of the member being ordered by.</span></span>
            </typeparam>
        <param name="keySelector">
            <span data-ttu-id="b16e4-132">並べ替えるメンバーを選択する式。</span><span class="sxs-lookup"><span data-stu-id="b16e4-132">The expression selecting the member to order by.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b16e4-133">指定した ascending order 句をソース クエリに適用します。</span><span class="sxs-lookup"><span data-stu-id="b16e4-133">Applies the specified ascending order clause to the source query.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b16e4-134">作成されたクエリ。</span><span class="sxs-lookup"><span data-stu-id="b16e4-134">The composed query.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThenByDescending&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; ThenByDescending&lt;TKey&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,TKey&gt;&gt; keySelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; ThenByDescending&lt;TKey&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!TKey&gt;&gt; keySelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.ThenByDescending``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function ThenByDescending(Of TKey) (keySelector As Expression(Of Func(Of T, TKey))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member ThenByDescending : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'Key&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTableQuery.ThenByDescending keySelector" />
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
            <span data-ttu-id="b16e4-135">並べ替え対象のメンバーの型。</span><span class="sxs-lookup"><span data-stu-id="b16e4-135">The type of the member being ordered by.</span></span>
            </typeparam>
        <param name="keySelector">
            <span data-ttu-id="b16e4-136">並べ替えるメンバーを選択する式。</span><span class="sxs-lookup"><span data-stu-id="b16e4-136">The expression selecting the member to order by.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b16e4-137">指定した descending order 句をソース クエリに適用します。</span><span class="sxs-lookup"><span data-stu-id="b16e4-137">Applies the specified descending order clause to the source query.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b16e4-138">作成されたクエリ。</span><span class="sxs-lookup"><span data-stu-id="b16e4-138">The composed query.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;T&gt;&gt; ToEnumerableAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;!T&gt;&gt; ToEnumerableAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.ToEnumerableAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ToEnumerableAsync () As Task(Of IEnumerable(Of T))" />
      <MemberSignature Language="F#" Value="abstract member ToEnumerableAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;'T&gt;&gt;" Usage="iMobileServiceTableQuery.ToEnumerableAsync " />
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
            <span data-ttu-id="b16e4-139">クエリの評価に非同期的にし、結果を返します。</span><span class="sxs-lookup"><span data-stu-id="b16e4-139">Evalute the query asynchronously and return the results.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b16e4-140">評価されたクエリの結果。</span><span class="sxs-lookup"><span data-stu-id="b16e4-140">The evaluated query results.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;T&gt;&gt; ToListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.List`1&lt;!T&gt;&gt; ToListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.ToListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ToListAsync () As Task(Of List(Of T))" />
      <MemberSignature Language="F#" Value="abstract member ToListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;'T&gt;&gt;" Usage="iMobileServiceTableQuery.ToListAsync " />
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
            <span data-ttu-id="b16e4-141">クエリの評価に非同期的にし、新しい一覧に結果を返します。</span><span class="sxs-lookup"><span data-stu-id="b16e4-141">Evalute the query asynchronously and return the results in a new List.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b16e4-142">一覧として評価されたクエリの結果。</span><span class="sxs-lookup"><span data-stu-id="b16e4-142">The evaluated query results as a List.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Where">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; Where (System.Linq.Expressions.Expression&lt;Func&lt;T,bool&gt;&gt; predicate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; Where(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, bool&gt;&gt; predicate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.Where(System.Linq.Expressions.Expression{System.Func{`0,System.Boolean}})" />
      <MemberSignature Language="VB.NET" Value="Public Function Where (predicate As Expression(Of Func(Of T, Boolean))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member Where : System.Linq.Expressions.Expression&lt;Func&lt;'T, bool&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTableQuery.Where predicate" />
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
            <span data-ttu-id="b16e4-143">フィルター述語。</span><span class="sxs-lookup"><span data-stu-id="b16e4-143">The filter predicate.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b16e4-144">ソース クエリを指定したフィルター述語を適用します。</span><span class="sxs-lookup"><span data-stu-id="b16e4-144">Applies the specified filter predicate to the source query.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b16e4-145">作成されたクエリ。</span><span class="sxs-lookup"><span data-stu-id="b16e4-145">The composed query.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithParameters">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; WithParameters (System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; WithParameters(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1.WithParameters(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithParameters (parameters As IDictionary(Of String, String)) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member WithParameters : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTableQuery.WithParameters parameters" />
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
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="b16e4-146">適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="b16e4-146">The parameters to apply.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b16e4-147">要求 URI クエリ文字列でユーザー定義のパラメーターとして使用する指定した文字列のキー/値ペアをソース クエリに適用されます。</span><span class="sxs-lookup"><span data-stu-id="b16e4-147">Applies to the source query the specified string key-value pairs to be used as user-defined parameters with the request URI query string.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b16e4-148">作成されたクエリ。</span><span class="sxs-lookup"><span data-stu-id="b16e4-148">The composed query.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>