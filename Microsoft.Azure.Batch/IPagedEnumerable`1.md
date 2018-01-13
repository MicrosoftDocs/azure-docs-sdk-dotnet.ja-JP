<Type Name="IPagedEnumerable&lt;T&gt;" FullName="Microsoft.Azure.Batch.IPagedEnumerable&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IPagedEnumerable&lt;T&gt; : System.Collections.Generic.IEnumerable&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPagedEnumerable`1&lt;T&gt; implements class System.Collections.Generic.IEnumerable`1&lt;!T&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPagedEnumerable(Of T)&#xA;Implements IEnumerable(Of T)" />
  <TypeSignature Language="F#" Value="type IPagedEnumerable&lt;'T&gt; = interface&#xA;    interface seq&lt;'T&gt;&#xA;    interface IEnumerable" />
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
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;T&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T"><span data-ttu-id="51bfd-101">列挙するオブジェクトの型。</span><span class="sxs-lookup"><span data-stu-id="51bfd-101">The type of objects to enumerate.</span></span></typeparam>
    <summary>
            <span data-ttu-id="51bfd-102">ページングされたコレクションの列挙子を公開します。</span><span class="sxs-lookup"><span data-stu-id="51bfd-102">Exposes enumerators for a paged collection.</span></span> <span data-ttu-id="51bfd-103">これらの列挙子は、指定した種類のページのコレクションに対する単純な反復処理をサポートします。</span><span class="sxs-lookup"><span data-stu-id="51bfd-103">These enumerators support simple iteration over a paged collection of a specified type.</span></span>
            
            <span data-ttu-id="51bfd-104">ページのコレクションは、Batch Service への 1 つまたは複数の呼び出しによってサポートされます。</span><span class="sxs-lookup"><span data-stu-id="51bfd-104">Paged collections are backed by one or more calls to the Batch Service.</span></span>  
            <span data-ttu-id="51bfd-105">それらの各呼び出しにより、列挙子によって、使用されるデータの可変サイズのページが返すことができます。</span><span class="sxs-lookup"><span data-stu-id="51bfd-105">Each of these calls can return a variable sized page of data which is then consumed by the enumerator.</span></span> 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetPagedEnumerator">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerator&lt;T&gt; GetPagedEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Batch.IPagedEnumerator`1&lt;!T&gt; GetPagedEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.IPagedEnumerable`1.GetPagedEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPagedEnumerator () As IPagedEnumerator(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetPagedEnumerator : unit -&gt; Microsoft.Azure.Batch.IPagedEnumerator&lt;'T&gt;" Usage="iPagedEnumerable.GetPagedEnumerator " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerator&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="51bfd-106">非同期ページのコレクションを反復処理する列挙子を返します。</span><span class="sxs-lookup"><span data-stu-id="51bfd-106">Returns an asynchronous enumerator that iterates through the paged collection.</span></span>
            </summary>
        <returns><span data-ttu-id="51bfd-107">列挙するオブジェクトの型。</span><span class="sxs-lookup"><span data-stu-id="51bfd-107">The type of objects to enumerate.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>