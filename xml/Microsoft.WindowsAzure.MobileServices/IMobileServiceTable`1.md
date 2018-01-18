<Type Name="IMobileServiceTable&lt;T&gt;" FullName="Microsoft.WindowsAzure.MobileServices.IMobileServiceTable&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IMobileServiceTable&lt;T&gt; : Microsoft.WindowsAzure.MobileServices.IMobileServiceTable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMobileServiceTable`1&lt;T&gt; implements class Microsoft.WindowsAzure.MobileServices.IMobileServiceTable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMobileServiceTable(Of T)&#xA;Implements IMobileServiceTable" />
  <TypeSignature Language="F#" Value="type IMobileServiceTable&lt;'T&gt; = interface&#xA;    interface IMobileServiceTable" />
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
      <InterfaceName>Microsoft.WindowsAzure.MobileServices.IMobileServiceTable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T">
            <span data-ttu-id="5eb17-101">(これは、テーブルを意味する) テーブル内のインスタンスの型。</span><span class="sxs-lookup"><span data-stu-id="5eb17-101">The type of instances in the table (which implies the table).</span></span>
            </typeparam>
    <summary>
            <span data-ttu-id="5eb17-102">モバイル サービスのテーブルに対する操作を提供します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-102">Provides operations on a table for a Mobile Service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateQuery">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; CreateQuery ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; CreateQuery() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.CreateQuery" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateQuery () As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : unit -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTable.CreateQuery " />
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
            <span data-ttu-id="5eb17-103">現在のテーブルに対してクエリを作成します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-103">Creates a query for the current table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-104">テーブルに対するクエリ。</span><span class="sxs-lookup"><span data-stu-id="5eb17-104">A query against the table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (T instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(!T instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.DeleteAsync(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteAsync (instance As T) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : 'T -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceTable.DeleteAsync instance" />
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
            <span data-ttu-id="5eb17-105">削除するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="5eb17-105">The instance to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5eb17-106">テーブルからインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-106">Delete an instance from the table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-107">削除が完了したときに完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="5eb17-107">A task that will complete when the delete has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (T instance, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(!T instance, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.DeleteAsync(`0,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteAsync (instance As T, parameters As IDictionary(Of String, String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : 'T * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceTable.DeleteAsync (instance, parameters)" />
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
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="instance"><span data-ttu-id="5eb17-108">削除するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="5eb17-108">The instance to delete.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5eb17-109">ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="5eb17-109">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5eb17-110">テーブルからインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-110">Delete an instance from the table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-111">削除が完了したときに完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="5eb17-111">A task that will complete when the delete has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludeDeleted">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; IncludeDeleted ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; IncludeDeleted() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.IncludeDeleted" />
      <MemberSignature Language="VB.NET" Value="Public Function IncludeDeleted () As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member IncludeDeleted : unit -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTable.IncludeDeleted " />
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
            <span data-ttu-id="5eb17-112">削除されたレコードを取得するクエリを作成します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-112">Creates a query that will ensure it gets the deleted records.</span></span> <span data-ttu-id="5eb17-113">これは、ソフト モバイル サービスで有効にする機能を削除する必要があります。</span><span class="sxs-lookup"><span data-stu-id="5eb17-113">This requires the soft delete feature to be enabled on the Mobile Service.</span></span> <span data-ttu-id="5eb17-114">参照してください<see href="http://go.microsoft.com/fwlink/?LinkId=507647">リンク</see>詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="5eb17-114">Visit <see href="http://go.microsoft.com/fwlink/?LinkId=507647">the link</see> for details.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-115">テーブルに対するクエリ。</span><span class="sxs-lookup"><span data-stu-id="5eb17-115">A query against the table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludeTotalCount">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; IncludeTotalCount ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; IncludeTotalCount() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.IncludeTotalCount" />
      <MemberSignature Language="VB.NET" Value="Public Function IncludeTotalCount () As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member IncludeTotalCount : unit -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTable.IncludeTotalCount " />
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
            <span data-ttu-id="5eb17-116">無視して返されたすべてのレコードがページングを実行/クライアントまたはサーバーで指定された句を制限の合計数を取得するクエリを作成します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-116">Creates a query that will ensure it gets the total count for all the records that would have been returned ignoring any take paging/ limit clause specified by client or server.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-117">テーブルに対するクエリ。</span><span class="sxs-lookup"><span data-stu-id="5eb17-117">A query against the table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task InsertAsync (T instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task InsertAsync(!T instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.InsertAsync(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function InsertAsync (instance As T) As Task" />
      <MemberSignature Language="F#" Value="abstract member InsertAsync : 'T -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceTable.InsertAsync instance" />
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
            <span data-ttu-id="5eb17-118">挿入するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="5eb17-118">The instance to insert.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5eb17-119">新しいインスタンスをテーブルに挿入します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-119">Insert a new instance into the table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-120">挿入が完了したときに完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="5eb17-120">A task that will complete when the insertion has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task InsertAsync (T instance, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task InsertAsync(!T instance, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.InsertAsync(`0,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function InsertAsync (instance As T, parameters As IDictionary(Of String, String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member InsertAsync : 'T * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceTable.InsertAsync (instance, parameters)" />
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
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="instance">
            <span data-ttu-id="5eb17-121">挿入するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="5eb17-121">The instance to insert.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5eb17-122">ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="5eb17-122">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5eb17-123">新しいインスタンスをテーブルに挿入します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-123">Insert a new instance into the table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-124">挿入が完了したときに完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="5eb17-124">A task that will complete when the insertion has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LookupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; LookupAsync (object id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!T&gt; LookupAsync(object id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.LookupAsync(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function LookupAsync (id As Object) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member LookupAsync : obj -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iMobileServiceTable.LookupAsync id" />
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
        <Parameter Name="id" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="id">
            <span data-ttu-id="5eb17-125">インスタンスの id。</span><span class="sxs-lookup"><span data-stu-id="5eb17-125">The id of the instance.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5eb17-126">参照 id によってテーブルからインスタンスです。</span><span class="sxs-lookup"><span data-stu-id="5eb17-126">Lookup an instance from a table by its id.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-127">目的のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="5eb17-127">The desired instance.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LookupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; LookupAsync (object id, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!T&gt; LookupAsync(object id, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.LookupAsync(System.Object,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function LookupAsync (id As Object, parameters As IDictionary(Of String, String)) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member LookupAsync : obj * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iMobileServiceTable.LookupAsync (id, parameters)" />
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
        <Parameter Name="id" Type="System.Object" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id">
            <span data-ttu-id="5eb17-128">インスタンスの id。</span><span class="sxs-lookup"><span data-stu-id="5eb17-128">The id of the instance.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5eb17-129">ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="5eb17-129">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5eb17-130">参照 id によってテーブルからインスタンスです。</span><span class="sxs-lookup"><span data-stu-id="5eb17-130">Lookup an instance from a table by its id.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-131">目的のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="5eb17-131">The desired instance.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrderBy&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; OrderBy&lt;TKey&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,TKey&gt;&gt; keySelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; OrderBy&lt;TKey&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!TKey&gt;&gt; keySelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.OrderBy``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function OrderBy(Of TKey) (keySelector As Expression(Of Func(Of T, TKey))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member OrderBy : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'Key&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTable.OrderBy keySelector" />
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
            <span data-ttu-id="5eb17-132">並べ替え対象のメンバーの型。</span><span class="sxs-lookup"><span data-stu-id="5eb17-132">The type of the member being ordered by.</span></span>
            </typeparam>
        <param name="keySelector">
            <span data-ttu-id="5eb17-133">並べ替えるメンバーを選択する式。</span><span class="sxs-lookup"><span data-stu-id="5eb17-133">The expression selecting the member to order by.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5eb17-134">指定した ascending order 句を適用することにより、クエリを作成します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-134">Creates a query by applying the specified ascending order clause.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-135">テーブルに対するクエリ。</span><span class="sxs-lookup"><span data-stu-id="5eb17-135">A query against the table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrderByDescending&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; OrderByDescending&lt;TKey&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,TKey&gt;&gt; keySelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; OrderByDescending&lt;TKey&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!TKey&gt;&gt; keySelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.OrderByDescending``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function OrderByDescending(Of TKey) (keySelector As Expression(Of Func(Of T, TKey))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member OrderByDescending : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'Key&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTable.OrderByDescending keySelector" />
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
            <span data-ttu-id="5eb17-136">並べ替え対象のメンバーの型。</span><span class="sxs-lookup"><span data-stu-id="5eb17-136">The type of the member being ordered by.</span></span>
            </typeparam>
        <param name="keySelector">
            <span data-ttu-id="5eb17-137">並べ替えるメンバーを選択する式。</span><span class="sxs-lookup"><span data-stu-id="5eb17-137">The expression selecting the member to order by.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5eb17-138">指定した descending order 句を適用することにより、クエリを作成します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-138">Creates a query by applying the specified descending order clause.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-139">テーブルに対するクエリ。</span><span class="sxs-lookup"><span data-stu-id="5eb17-139">A query against the table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;T&gt;&gt; ReadAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;!T&gt;&gt; ReadAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.ReadAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAsync () As Task(Of IEnumerable(Of T))" />
      <MemberSignature Language="F#" Value="abstract member ReadAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;'T&gt;&gt;" Usage="iMobileServiceTable.ReadAsync " />
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
            <span data-ttu-id="5eb17-140">テーブルからインスタンスを返します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-140">Returns instances from a table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-141">テーブルからのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="5eb17-141">Instances from the table.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="5eb17-142">この呼び出しがページングなどを処理しません。</span><span class="sxs-lookup"><span data-stu-id="5eb17-142">This call will not handle paging, etc., for you.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync&lt;U&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;U&gt;&gt; ReadAsync&lt;U&gt; (Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; query);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;!!U&gt;&gt; ReadAsync&lt;U&gt;(class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.ReadAsync``1(Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery{``0})" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAsync(Of U) (query As IMobileServiceTableQuery(Of U)) As Task(Of IEnumerable(Of U))" />
      <MemberSignature Language="F#" Value="abstract member ReadAsync : Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt; -&gt; System.Threading.Tasks.Task&lt;seq&lt;'U&gt;&gt;" Usage="iMobileServiceTable.ReadAsync query" />
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
            <span data-ttu-id="5eb17-143">クエリによって返されるインスタンスの型。</span><span class="sxs-lookup"><span data-stu-id="5eb17-143">The type of instance returned by the query.</span></span>
            </typeparam>
        <param name="query">
            <span data-ttu-id="5eb17-144">クエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-144">The query to execute.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5eb17-145">クエリを使用してテーブルからインスタンスを返します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-145">Returns instances from a table using a query.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-146">テーブルからのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="5eb17-146">Instances from the table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadAsync&lt;U&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;U&gt;&gt; ReadAsync&lt;U&gt; (string query);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;!!U&gt;&gt; ReadAsync&lt;U&gt;(string query) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.ReadAsync``1(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ReadAsync(Of U) (query As String) As Task(Of IEnumerable(Of U))" />
      <MemberSignature Language="F#" Value="abstract member ReadAsync : string -&gt; System.Threading.Tasks.Task&lt;seq&lt;'U&gt;&gt;" Usage="iMobileServiceTable.ReadAsync query" />
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
        <Parameter Name="query" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="U">To be added.</typeparam>
        <param name="query">
            <span data-ttu-id="5eb17-147">クエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-147">A query to execute.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5eb17-148">テーブルに対するクエリを実行します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-148">Executes a query against the table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-149">クエリの終了時に結果と共に返すタスク。</span><span class="sxs-lookup"><span data-stu-id="5eb17-149">A task that will return with results when the query finishes.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RefreshAsync (T instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RefreshAsync(!T instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.RefreshAsync(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function RefreshAsync (instance As T) As Task" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : 'T -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceTable.RefreshAsync instance" />
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
            <span data-ttu-id="5eb17-150">更新するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="5eb17-150">The instance to refresh.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5eb17-151">現在のインスタンスと、テーブルからの最新の値を更新します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-151">Refresh the current instance with the latest values from the table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-152">更新が完了したときに完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="5eb17-152">A task that will complete when the refresh has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RefreshAsync (T instance, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RefreshAsync(!T instance, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.RefreshAsync(`0,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function RefreshAsync (instance As T, parameters As IDictionary(Of String, String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : 'T * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceTable.RefreshAsync (instance, parameters)" />
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
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="instance">
            <span data-ttu-id="5eb17-153">更新するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="5eb17-153">The instance to refresh.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5eb17-154">ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="5eb17-154">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5eb17-155">現在のインスタンスと、テーブルからの最新の値を更新します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-155">Refresh the current instance with the latest values from the table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-156">更新が完了したときに完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="5eb17-156">A task that will complete when the refresh has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Select&lt;U&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;U&gt; Select&lt;U&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,U&gt;&gt; selector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!!U&gt; Select&lt;U&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!U&gt;&gt; selector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.Select``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function Select(Of U) (selector As Expression(Of Func(Of T, U))) As IMobileServiceTableQuery(Of U)" />
      <MemberSignature Language="F#" Value="abstract member Select : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'U&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'U&gt;" Usage="iMobileServiceTable.Select selector" />
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
            <span data-ttu-id="5eb17-157">クエリの射影された結果を表す型。</span><span class="sxs-lookup"><span data-stu-id="5eb17-157">Type representing the projected result of the query.</span></span>
            </typeparam>
        <param name="selector">
            <span data-ttu-id="5eb17-158">selector 関数。</span><span class="sxs-lookup"><span data-stu-id="5eb17-158">The selector function.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5eb17-159">指定した選択を適用することにより、クエリを作成します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-159">Creates a query by applying the specified selection.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-160">テーブルに対するクエリ。</span><span class="sxs-lookup"><span data-stu-id="5eb17-160">A query against the table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Skip">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; Skip (int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; Skip(int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.Skip(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function Skip (count As Integer) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member Skip : int -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTable.Skip count" />
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
            <span data-ttu-id="5eb17-161">skip の数値。</span><span class="sxs-lookup"><span data-stu-id="5eb17-161">The number to skip.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5eb17-162">指定した skip 句を適用することにより、クエリを作成します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-162">Creates a query by applying the specified skip clause.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-163">テーブルに対するクエリ。</span><span class="sxs-lookup"><span data-stu-id="5eb17-163">A query against the table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Take">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; Take (int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; Take(int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.Take(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function Take (count As Integer) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member Take : int -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTable.Take count" />
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
            <span data-ttu-id="5eb17-164">take の数値。</span><span class="sxs-lookup"><span data-stu-id="5eb17-164">The number to take.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5eb17-165">指定した take 句を適用することにより、クエリを作成します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-165">Creates a query by applying the specified take clause.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-166">テーブルに対するクエリ。</span><span class="sxs-lookup"><span data-stu-id="5eb17-166">A query against the table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThenBy&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; ThenBy&lt;TKey&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,TKey&gt;&gt; keySelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; ThenBy&lt;TKey&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!TKey&gt;&gt; keySelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.ThenBy``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function ThenBy(Of TKey) (keySelector As Expression(Of Func(Of T, TKey))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member ThenBy : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'Key&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTable.ThenBy keySelector" />
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
            <span data-ttu-id="5eb17-167">並べ替え対象のメンバーの型。</span><span class="sxs-lookup"><span data-stu-id="5eb17-167">The type of the member being ordered by.</span></span>
            </typeparam>
        <param name="keySelector">
            <span data-ttu-id="5eb17-168">並べ替えるメンバーを選択する式。</span><span class="sxs-lookup"><span data-stu-id="5eb17-168">The expression selecting the member to order by.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5eb17-169">指定した ascending order 句を適用することにより、クエリを作成します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-169">Creates a query by applying the specified ascending order clause.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-170">テーブルに対するクエリ。</span><span class="sxs-lookup"><span data-stu-id="5eb17-170">A query against the table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThenByDescending&lt;TKey&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; ThenByDescending&lt;TKey&gt; (System.Linq.Expressions.Expression&lt;Func&lt;T,TKey&gt;&gt; keySelector);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; ThenByDescending&lt;TKey&gt;(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, !!TKey&gt;&gt; keySelector) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.ThenByDescending``1(System.Linq.Expressions.Expression{System.Func{`0,``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Function ThenByDescending(Of TKey) (keySelector As Expression(Of Func(Of T, TKey))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member ThenByDescending : System.Linq.Expressions.Expression&lt;Func&lt;'T, 'Key&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTable.ThenByDescending keySelector" />
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
            <span data-ttu-id="5eb17-171">並べ替え対象のメンバーの型。</span><span class="sxs-lookup"><span data-stu-id="5eb17-171">The type of the member being ordered by.</span></span>
            </typeparam>
        <param name="keySelector">
            <span data-ttu-id="5eb17-172">並べ替えるメンバーを選択する式。</span><span class="sxs-lookup"><span data-stu-id="5eb17-172">The expression selecting the member to order by.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5eb17-173">指定した descending order 句を適用することにより、クエリを作成します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-173">Creates a query by applying the specified descending order clause.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-174">テーブルに対するクエリ。</span><span class="sxs-lookup"><span data-stu-id="5eb17-174">A query against the table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToEnumerableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;T&gt;&gt; ToEnumerableAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;!T&gt;&gt; ToEnumerableAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.ToEnumerableAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ToEnumerableAsync () As Task(Of IEnumerable(Of T))" />
      <MemberSignature Language="F#" Value="abstract member ToEnumerableAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;'T&gt;&gt;" Usage="iMobileServiceTable.ToEnumerableAsync " />
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
            <span data-ttu-id="5eb17-175">テーブルの要素を非同期に取得します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-175">Gets the elements of the table asynchronously.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-176">テーブル要素のシーケンスとして結果。</span><span class="sxs-lookup"><span data-stu-id="5eb17-176">The table elements results as a sequence.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;T&gt;&gt; ToListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.List`1&lt;!T&gt;&gt; ToListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.ToListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ToListAsync () As Task(Of List(Of T))" />
      <MemberSignature Language="F#" Value="abstract member ToListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;'T&gt;&gt;" Usage="iMobileServiceTable.ToListAsync " />
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
            <span data-ttu-id="5eb17-177">テーブルの要素を非同期に取得し、新しい一覧で、結果を返します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-177">Gets the elements of the table asynchronously and return the results in a new List.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-178">テーブル要素の一覧として結果。</span><span class="sxs-lookup"><span data-stu-id="5eb17-178">The table elements results as a List.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UndeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UndeleteAsync (T instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UndeleteAsync(!T instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.UndeleteAsync(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function UndeleteAsync (instance As T) As Task" />
      <MemberSignature Language="F#" Value="abstract member UndeleteAsync : 'T -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceTable.UndeleteAsync instance" />
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
        <param name="instance"><span data-ttu-id="5eb17-179">テーブルから復元するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="5eb17-179">The instance to undelete from the table.</span></span></param>
        <summary>
            <span data-ttu-id="5eb17-180">削除を取り消します、<paramref name="instance" />テーブルからです。</span><span class="sxs-lookup"><span data-stu-id="5eb17-180">Undeletes an <paramref name="instance" /> from the table.</span></span> <span data-ttu-id="5eb17-181">これは、ソフト モバイル サービスで有効にする機能を削除する必要があります。</span><span class="sxs-lookup"><span data-stu-id="5eb17-181">This requires the soft delete feature to be enabled on the Mobile Service.</span></span> <span data-ttu-id="5eb17-182">参照してください<see href="http://go.microsoft.com/fwlink/?LinkId=507647">リンク</see>詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="5eb17-182">Visit <see href="http://go.microsoft.com/fwlink/?LinkId=507647">the link</see> for details.</span></span>
            </summary>
        <returns><span data-ttu-id="5eb17-183">削除の取り消しが終了するときに完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="5eb17-183">A task that will complete when the undelete finishes.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UndeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UndeleteAsync (T instance, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UndeleteAsync(!T instance, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.UndeleteAsync(`0,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function UndeleteAsync (instance As T, parameters As IDictionary(Of String, String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member UndeleteAsync : 'T * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceTable.UndeleteAsync (instance, parameters)" />
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
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="instance"><span data-ttu-id="5eb17-184">テーブルから復元するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="5eb17-184">The instance to undelete from the table.</span></span></param>
        <param name="parameters">
            <span data-ttu-id="5eb17-185">ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="5eb17-185">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5eb17-186">削除を取り消します、<paramref name="instance" />テーブルからです。</span><span class="sxs-lookup"><span data-stu-id="5eb17-186">Undeletes an <paramref name="instance" /> from the table.</span></span> <span data-ttu-id="5eb17-187">これは、ソフト モバイル サービスで有効にする機能を削除する必要があります。</span><span class="sxs-lookup"><span data-stu-id="5eb17-187">This requires the soft delete feature to be enabled on the Mobile Service.</span></span> <span data-ttu-id="5eb17-188">参照してください<see href="http://go.microsoft.com/fwlink/?LinkId=507647">リンク</see>詳細についてはします。</span><span class="sxs-lookup"><span data-stu-id="5eb17-188">Visit <see href="http://go.microsoft.com/fwlink/?LinkId=507647">the link</see> for details.</span></span>
            </summary>
        <returns><span data-ttu-id="5eb17-189">削除の取り消しが終了するときに完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="5eb17-189">A task that will complete when the undelete finishes.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateAsync (T instance);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateAsync(!T instance) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.UpdateAsync(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateAsync (instance As T) As Task" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : 'T -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceTable.UpdateAsync instance" />
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
            <span data-ttu-id="5eb17-190">更新するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="5eb17-190">The instance to update.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5eb17-191">テーブル内のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-191">Updates an instance in the table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-192">更新プログラムが終了すると完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="5eb17-192">A task that will complete when the update has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateAsync (T instance, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateAsync(!T instance, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.UpdateAsync(`0,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateAsync (instance As T, parameters As IDictionary(Of String, String)) As Task" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : 'T * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceTable.UpdateAsync (instance, parameters)" />
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
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="instance">
            <span data-ttu-id="5eb17-193">更新するインスタンス。</span><span class="sxs-lookup"><span data-stu-id="5eb17-193">The instance to update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5eb17-194">ユーザー定義パラメーターと要求 URI クエリ文字列に含める値のディクショナリ。</span><span class="sxs-lookup"><span data-stu-id="5eb17-194">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5eb17-195">テーブル内のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-195">Updates an instance in the table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-196">更新プログラムが終了すると完了するタスク。</span><span class="sxs-lookup"><span data-stu-id="5eb17-196">A task that will complete when the update has finished.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Where">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; Where (System.Linq.Expressions.Expression&lt;Func&lt;T,bool&gt;&gt; predicate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; Where(class System.Linq.Expressions.Expression`1&lt;class System.Func`2&lt;!T, bool&gt;&gt; predicate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.Where(System.Linq.Expressions.Expression{System.Func{`0,System.Boolean}})" />
      <MemberSignature Language="VB.NET" Value="Public Function Where (predicate As Expression(Of Func(Of T, Boolean))) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member Where : System.Linq.Expressions.Expression&lt;Func&lt;'T, bool&gt;&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTable.Where predicate" />
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
            <span data-ttu-id="5eb17-197">フィルター述語。</span><span class="sxs-lookup"><span data-stu-id="5eb17-197">The filter predicate.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5eb17-198">指定したフィルター述語を適用することにより、クエリを作成します。</span><span class="sxs-lookup"><span data-stu-id="5eb17-198">Creates a query by applying the specified filter predicate.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-199">テーブルに対するクエリ。</span><span class="sxs-lookup"><span data-stu-id="5eb17-199">A query against the table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithParameters">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;T&gt; WithParameters (System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery`1&lt;!T&gt; WithParameters(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1.WithParameters(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithParameters (parameters As IDictionary(Of String, String)) As IMobileServiceTableQuery(Of T)" />
      <MemberSignature Language="F#" Value="abstract member WithParameters : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTableQuery&lt;'T&gt;" Usage="iMobileServiceTable.WithParameters parameters" />
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
            <span data-ttu-id="5eb17-200">適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="5eb17-200">The parameters to apply.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5eb17-201">要求 URI クエリ文字列でユーザー定義のパラメーターとして使用する指定した文字列のキー/値ペアをソース クエリに適用されます。</span><span class="sxs-lookup"><span data-stu-id="5eb17-201">Applies to the source query the specified string key-value pairs to be used as user-defined parameters with the request URI query string.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5eb17-202">作成されたクエリ。</span><span class="sxs-lookup"><span data-stu-id="5eb17-202">The composed query.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>