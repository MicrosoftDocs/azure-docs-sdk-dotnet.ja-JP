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
    <typeparam name="T"><span data-ttu-id="d8bba-101">列挙子の型。</span><span class="sxs-lookup"><span data-stu-id="d8bba-101">The type of the enumerator.</span></span></typeparam>
    <summary>
            <span data-ttu-id="d8bba-102">イテレーションの非同期のメカニズムを公開する列挙子。</span><span class="sxs-lookup"><span data-stu-id="d8bba-102">An enumerator which exposes an asynchronous mechanism for iteration.</span></span>
            
            <span data-ttu-id="d8bba-103">列挙子のインスタンスは、スレッド セーフではありません。</span><span class="sxs-lookup"><span data-stu-id="d8bba-103">Enumerator instances are not threadsafe.</span></span>
            
            <span data-ttu-id="d8bba-104">各列挙子は、サーバーからコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="d8bba-104">Each enumerator fetches the collection from the server.</span></span> <span data-ttu-id="d8bba-105">その結果、各列挙子は、別のデータ (コレクション サイズ、内容など) を確認できます。</span><span class="sxs-lookup"><span data-stu-id="d8bba-105">As a consequence, each enumerator can see different data (collection size, contents, etc.).</span></span>
            
            <span data-ttu-id="d8bba-106">不用意に foreach/ForeachAsync およびその他のコレクションの操作の使用を使用してサーバーからのデータの複数の検索を回避するのに注意してください。</span><span class="sxs-lookup"><span data-stu-id="d8bba-106">Care should be taken to avoid multiple retrievals of the data from the server via casual use of foreach/ForeachAsync and other collection operations.</span></span>
            
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
            <span data-ttu-id="d8bba-107">列挙子の現在位置にあるコレクション内の要素を取得します。</span><span class="sxs-lookup"><span data-stu-id="d8bba-107">Gets the element in the collection at the current position of the enumerator.</span></span>
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
        <param name="cancellationToken"><span data-ttu-id="d8bba-108">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="d8bba-108">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8bba-109">列挙子をコレクションの次の要素に進めるへの非同期呼び出しを開始します。</span><span class="sxs-lookup"><span data-stu-id="d8bba-109">Begins an asynchronous call to advance the enumerator to the next element of the collection.</span></span>
            </summary>
        <returns><span data-ttu-id="d8bba-110">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8bba-110">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
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
        <param name="cancellationToken"><span data-ttu-id="d8bba-111">A<see cref="T:System.Threading.CancellationToken" />非同期操作の有効期間を制御するためです。</span><span class="sxs-lookup"><span data-stu-id="d8bba-111">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8bba-112">初期位置、つまりコレクションの最初の要素の前に、列挙子を設定する非同期呼び出しを開始します。</span><span class="sxs-lookup"><span data-stu-id="d8bba-112">Begins an asynchronous call to set the enumerator to its initial position, which is before the first element in the collection.</span></span>
            </summary>
        <returns><span data-ttu-id="d8bba-113">非同期操作を表す <see cref="T:System.Threading.Tasks.Task" /> オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="d8bba-113">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>