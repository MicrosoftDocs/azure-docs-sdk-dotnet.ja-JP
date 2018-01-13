<Type Name="IPagedEnumerator&lt;T&gt;" FullName="Microsoft.Azure.Batch.IPagedEnumerator&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IPagedEnumerator&lt;T&gt; : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPagedEnumerator`1&lt;T&gt; implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.IPagedEnumerator`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPagedEnumerator(Of T)&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IPagedEnumerator&lt;'T&gt; = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T">列挙子の型。</typeparam>
    <summary>
            イテレーションの非同期のメカニズムを公開する列挙子。
            
            列挙子のインスタンスは、スレッド セーフではありません。
            
            各列挙子は、サーバーからコレクションを取得します。 その結果、各列挙子は、別のデータ (コレクション サイズ、内容など) を確認できます。
            
            不用意に foreach/ForeachAsync およびその他のコレクションの操作の使用を使用してサーバーからのデータの複数の検索を回避するのに注意してください。
            
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Current">
      <MemberSignature Language="C#" Value="public T Current { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !T Current" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.IPagedEnumerator`1.Current" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Current As T" />
      <MemberSignature Language="F#" Value="member this.Current : 'T" Usage="Microsoft.Azure.Batch.IPagedEnumerator&lt;'T&gt;.Current" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            列挙子の現在位置にあるコレクション内の要素を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MoveNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; MoveNextAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; MoveNextAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.IPagedEnumerator`1.MoveNextAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member MoveNextAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iPagedEnumerator.MoveNextAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            列挙子をコレクションの次の要素に進めるへの非同期呼び出しを開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ResetAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ResetAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.IPagedEnumerator`1.ResetAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResetAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iPagedEnumerator.ResetAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</param>
        <summary>
            初期位置、つまりコレクションの最初の要素の前に、列挙子を設定する非同期呼び出しを開始します。
            </summary>
        <returns>非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>