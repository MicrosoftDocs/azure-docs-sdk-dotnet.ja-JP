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
            静的 (Visual Basic では Shared) メソッドを実装するシーケンスを操作のセットを提供<see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />です。
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
        <param name="source"><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />を繰り返し処理します。</param>
        <param name="body">各要素に対して実行するデリゲート<paramref name="source" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            反復処理し、<see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />シーケンスを要素ごとに同期的なデリゲートを呼び出します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />イテレーションの操作を表すです。 イテレーションが完了すると、タスクを完了します。</returns>
        <remarks>このメソッドは、順番に、並列ではなく、要素を処理します。  つまり、メソッドは、シーケンス内の各要素の次の要素を処理する前に、デリゲートの実行を完了します。</remarks>
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
        <param name="source"><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />を繰り返し処理します。</param>
        <param name="body">各要素に対して実行する非同期デリゲート<paramref name="source" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            反復処理し、<see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />シーケンス、各要素に対して非同期デリゲートを呼び出します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />イテレーションの操作を表すです。 イテレーションが完了すると、タスクを完了します。</returns>
        <remarks>このメソッドは、順番に、並列ではなく、要素を処理します。  つまり、シーケンス内の各要素のメソッドは待機非同期デリゲートの次の要素を処理する前にします。</remarks>
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
        <param name="source"><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />を繰り返し処理します。</param>
        <param name="body">各要素に対して実行する非同期デリゲート<paramref name="source" />です。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            反復処理し、<see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />シーケンス、各要素に対して非同期デリゲートを呼び出します。
            </summary>
        <returns>A<see cref="T:System.Threading.Tasks.Task" />イテレーションの操作を表すです。 イテレーションが完了すると、タスクを完了します。</returns>
        <remarks>このメソッドは、順番に、並列ではなく、要素を処理します。  つまり、シーケンス内の各要素のメソッドは待機非同期デリゲートの次の要素を処理する前にします。</remarks>
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
        <param name="source"><see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />からリストを作成します。</param>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> から <see cref="T:System.Collections.Generic.List`1" /> を作成します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task`1" />。 タスクの結果は、<see cref="T:System.Collections.Generic.List`1" />ソース シーケンスのすべての要素を格納します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>