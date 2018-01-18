<Type Name="ISupportsListing&lt;T&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface ISupportsListing&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISupportsListing`1&lt;T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISupportsListing(Of T)" />
  <TypeSignature Language="F#" Value="type ISupportsListing&lt;'T&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;T&gt; List ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!T&gt; List() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing`1.List" />
      <MemberSignature Language="VB.NET" Value="Public Function List () As IEnumerable(Of T)" />
      <MemberSignature Language="F#" Value="abstract member List : unit -&gt; seq&lt;'T&gt;" Usage="iSupportsListing.List " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="54d80-101">現在選択されているサブスクリプションで指定した型のすべてのリソースを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="54d80-101">Lists all the resources of the specified type in the currently selected subscription.</span></span>
            </summary>
        <returns><span data-ttu-id="54d80-102">リソースの一覧</span><span class="sxs-lookup"><span data-stu-id="54d80-102">list of resources</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;T&gt;&gt; ListAsync (bool loadAllPages = true, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection`1&lt;!T&gt;&gt; ListAsync(bool loadAllPages, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing`1.ListAsync(System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;'T&gt;&gt;" Usage="iSupportsListing.ListAsync (loadAllPages, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="loadAllPages" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="loadAllPages">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="54d80-103">現在選択されているサブスクリプションで指定した型のすべてのリソースを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="54d80-103">Lists all the resources of the specified type in the currently selected subscription.</span></span>
            </summary>
        <returns><span data-ttu-id="54d80-104">リソースの一覧</span><span class="sxs-lookup"><span data-stu-id="54d80-104">list of resources</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>