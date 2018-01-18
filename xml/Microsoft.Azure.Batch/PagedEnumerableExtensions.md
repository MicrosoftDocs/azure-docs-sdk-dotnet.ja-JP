<Type Name="PagedEnumerableExtensions" FullName="Microsoft.Azure.Batch.PagedEnumerableExtensions">
  <TypeSignature Language="C#" Value="public static class PagedEnumerableExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PagedEnumerableExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.PagedEnumerableExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PagedEnumerableExtensions" />
  <TypeSignature Language="F#" Value="type PagedEnumerableExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="42224-101">静的 (Visual Basic では Shared) メソッドを実装するシーケンスを操作のセットを提供<see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />です。</span><span class="sxs-lookup"><span data-stu-id="42224-101">Provides a set of static (Shared in Visual Basic) methods for working with sequences that implement <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ForEachAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ForEachAsync&lt;T&gt; (this Microsoft.Azure.Batch.IPagedEnumerable&lt;T&gt; source, Action&lt;T&gt; body, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ForEachAsync&lt;T&gt;(class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;!!T&gt; source, class System.Action`1&lt;!!T&gt; body, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PagedEnumerableExtensions.ForEachAsync``1(Microsoft.Azure.Batch.IPagedEnumerable{``0},System.Action{``0},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ForEachAsync : Microsoft.Azure.Batch.IPagedEnumerable&lt;'T&gt; * Action&lt;'T&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Batch.PagedEnumerableExtensions.ForEachAsync (source, body, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PagedEnumerableExtensions/&lt;ForEachAsync&gt;d__2`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.Batch.IPagedEnumerable&lt;T&gt;" RefType="this" />
        <Parameter Name="body" Type="System.Action&lt;T&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="source"><span data-ttu-id="42224-102"><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />を繰り返し処理します。</span><span class="sxs-lookup"><span data-stu-id="42224-102">The <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> to iterate over.</span></span></param>
        <param name="body"><span data-ttu-id="42224-103">各要素に対して実行するデリゲート<paramref name="source" />です。</span><span class="sxs-lookup"><span data-stu-id="42224-103">The delegate to execute for each element in <paramref name="source" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="42224-104">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="42224-104">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="42224-105">反復処理し、<see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />シーケンスを要素ごとに同期的なデリゲートを呼び出します。</span><span class="sxs-lookup"><span data-stu-id="42224-105">Iterates over an <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> sequence, invoking a synchronous delegate for each element.</span></span>
            </summary>
        <returns><span data-ttu-id="42224-106">A<see cref="T:System.Threading.Tasks.Task" />イテレーションの操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="42224-106">A <see cref="T:System.Threading.Tasks.Task" /> that represents the iteration operation.</span></span> <span data-ttu-id="42224-107">イテレーションが完了すると、タスクを完了します。</span><span class="sxs-lookup"><span data-stu-id="42224-107">The task completes when iteration is complete.</span></span></returns>
        <remarks><span data-ttu-id="42224-108">このメソッドは、順番に、並列ではなく、要素を処理します。</span><span class="sxs-lookup"><span data-stu-id="42224-108">This method processes elements sequentially, not concurrently.</span></span>  <span data-ttu-id="42224-109">つまり、メソッドは、シーケンス内の各要素の次の要素を処理する前に、デリゲートの実行を完了します。</span><span class="sxs-lookup"><span data-stu-id="42224-109">That is, for each element in the sequence, the method completes execution of the delegate before processing the next element.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ForEachAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ForEachAsync&lt;T&gt; (this Microsoft.Azure.Batch.IPagedEnumerable&lt;T&gt; source, Func&lt;T,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; body, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ForEachAsync&lt;T&gt;(class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;!!T&gt; source, class System.Func`3&lt;!!T, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; body, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PagedEnumerableExtensions.ForEachAsync``1(Microsoft.Azure.Batch.IPagedEnumerable{``0},System.Func{``0,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ForEachAsync : Microsoft.Azure.Batch.IPagedEnumerable&lt;'T&gt; * Func&lt;'T, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Batch.PagedEnumerableExtensions.ForEachAsync (source, body, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PagedEnumerableExtensions/&lt;ForEachAsync&gt;d__1`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.Batch.IPagedEnumerable&lt;T&gt;" RefType="this" />
        <Parameter Name="body" Type="System.Func&lt;T,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="source"><span data-ttu-id="42224-110"><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />を繰り返し処理します。</span><span class="sxs-lookup"><span data-stu-id="42224-110">The <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> to iterate over.</span></span></param>
        <param name="body"><span data-ttu-id="42224-111">各要素に対して実行する非同期デリゲート<paramref name="source" />です。</span><span class="sxs-lookup"><span data-stu-id="42224-111">The asynchronous delegate to execute for each element in <paramref name="source" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="42224-112">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="42224-112">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="42224-113">反復処理し、<see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />シーケンス、各要素に対して非同期デリゲートを呼び出します。</span><span class="sxs-lookup"><span data-stu-id="42224-113">Iterates over an <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> sequence, invoking an asynchronous delegate for each element.</span></span>
            </summary>
        <returns><span data-ttu-id="42224-114">A<see cref="T:System.Threading.Tasks.Task" />イテレーションの操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="42224-114">A <see cref="T:System.Threading.Tasks.Task" /> that represents the iteration operation.</span></span> <span data-ttu-id="42224-115">イテレーションが完了すると、タスクを完了します。</span><span class="sxs-lookup"><span data-stu-id="42224-115">The task completes when iteration is complete.</span></span></returns>
        <remarks><span data-ttu-id="42224-116">このメソッドは、順番に、並列ではなく、要素を処理します。</span><span class="sxs-lookup"><span data-stu-id="42224-116">This method processes elements sequentially, not concurrently.</span></span>  <span data-ttu-id="42224-117">つまり、シーケンス内の各要素のメソッドは待機非同期デリゲートの次の要素を処理する前にします。</span><span class="sxs-lookup"><span data-stu-id="42224-117">That is, for each element in the sequence, the method awaits the asynchronous delegate before processing the next element.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ForEachAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ForEachAsync&lt;T&gt; (this Microsoft.Azure.Batch.IPagedEnumerable&lt;T&gt; source, Func&lt;T,System.Threading.Tasks.Task&gt; body, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ForEachAsync&lt;T&gt;(class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;!!T&gt; source, class System.Func`2&lt;!!T, class System.Threading.Tasks.Task&gt; body, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PagedEnumerableExtensions.ForEachAsync``1(Microsoft.Azure.Batch.IPagedEnumerable{``0},System.Func{``0,System.Threading.Tasks.Task},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ForEachAsync : Microsoft.Azure.Batch.IPagedEnumerable&lt;'T&gt; * Func&lt;'T, System.Threading.Tasks.Task&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Batch.PagedEnumerableExtensions.ForEachAsync (source, body, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PagedEnumerableExtensions/&lt;ForEachAsync&gt;d__0`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.Batch.IPagedEnumerable&lt;T&gt;" RefType="this" />
        <Parameter Name="body" Type="System.Func&lt;T,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="source"><span data-ttu-id="42224-118"><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />を繰り返し処理します。</span><span class="sxs-lookup"><span data-stu-id="42224-118">The <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> to iterate over.</span></span></param>
        <param name="body"><span data-ttu-id="42224-119">各要素に対して実行する非同期デリゲート<paramref name="source" />です。</span><span class="sxs-lookup"><span data-stu-id="42224-119">The asynchronous delegate to execute for each element in <paramref name="source" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="42224-120">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="42224-120">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="42224-121">反復処理し、<see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />シーケンス、各要素に対して非同期デリゲートを呼び出します。</span><span class="sxs-lookup"><span data-stu-id="42224-121">Iterates over an <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> sequence, invoking an asynchronous delegate for each element.</span></span>
            </summary>
        <returns><span data-ttu-id="42224-122">A<see cref="T:System.Threading.Tasks.Task" />イテレーションの操作を表すです。</span><span class="sxs-lookup"><span data-stu-id="42224-122">A <see cref="T:System.Threading.Tasks.Task" /> that represents the iteration operation.</span></span> <span data-ttu-id="42224-123">イテレーションが完了すると、タスクを完了します。</span><span class="sxs-lookup"><span data-stu-id="42224-123">The task completes when iteration is complete.</span></span></returns>
        <remarks><span data-ttu-id="42224-124">このメソッドは、順番に、並列ではなく、要素を処理します。</span><span class="sxs-lookup"><span data-stu-id="42224-124">This method processes elements sequentially, not concurrently.</span></span>  <span data-ttu-id="42224-125">つまり、シーケンス内の各要素のメソッドは待機非同期デリゲートの次の要素を処理する前にします。</span><span class="sxs-lookup"><span data-stu-id="42224-125">That is, for each element in the sequence, the method awaits the asynchronous delegate before processing the next element.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ToListAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;T&gt;&gt; ToListAsync&lt;T&gt; (this Microsoft.Azure.Batch.IPagedEnumerable&lt;T&gt; source, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.List`1&lt;!!T&gt;&gt; ToListAsync&lt;T&gt;(class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;!!T&gt; source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PagedEnumerableExtensions.ToListAsync``1(Microsoft.Azure.Batch.IPagedEnumerable{``0},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ToListAsync : Microsoft.Azure.Batch.IPagedEnumerable&lt;'T&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;'T&gt;&gt;" Usage="Microsoft.Azure.Batch.PagedEnumerableExtensions.ToListAsync (source, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PagedEnumerableExtensions/&lt;ToListAsync&gt;d__3`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.Batch.IPagedEnumerable&lt;T&gt;" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="source"><span data-ttu-id="42224-126"><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />からリストを作成します。</span><span class="sxs-lookup"><span data-stu-id="42224-126">The <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> to create a list from.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="42224-127">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="42224-127">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="42224-128"><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> から <see cref="T:System.Collections.Generic.List`1" /> を作成します。</span><span class="sxs-lookup"><span data-stu-id="42224-128">Creates a <see cref="T:System.Collections.Generic.List`1" /> from an <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />.</span></span>
            </summary>
        <returns><span data-ttu-id="42224-129">非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" />。</span><span class="sxs-lookup"><span data-stu-id="42224-129">A <see cref="T:System.Threading.Tasks.Task`1" /> that represents the asynchronous operation.</span></span> <span data-ttu-id="42224-130">タスクの結果は、<see cref="T:System.Collections.Generic.List`1" />ソース シーケンスのすべての要素を格納します。</span><span class="sxs-lookup"><span data-stu-id="42224-130">The result of the task is a <see cref="T:System.Collections.Generic.List`1" /> containing all elements of the source sequence.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>