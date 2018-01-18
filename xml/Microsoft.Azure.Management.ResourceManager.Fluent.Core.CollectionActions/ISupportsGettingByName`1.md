<Type Name="ISupportsGettingByName&lt;T&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByName&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface ISupportsGettingByName&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISupportsGettingByName`1&lt;T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByName`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISupportsGettingByName(Of T)" />
  <TypeSignature Language="F#" Value="type ISupportsGettingByName&lt;'T&gt; = interface" />
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
    <Member MemberName="GetByName">
      <MemberSignature Language="C#" Value="public T GetByName (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T GetByName(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByName`1.GetByName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetByName (name As String) As T" />
      <MemberSignature Language="F#" Value="abstract member GetByName : string -&gt; 'T" Usage="iSupportsGettingByName.GetByName name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="fbdc6-101">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="fbdc6-101">name the name of the resource.</span></span> <span data-ttu-id="fbdc6-102">(注、これは、リソース ID ではありません)</span><span class="sxs-lookup"><span data-stu-id="fbdc6-102">(Note, this is not the resource ID.)</span></span></param>
        <summary>
            <span data-ttu-id="fbdc6-103">現在のリソース グループ内のリソース名に基づく Azure からのリソースに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="fbdc6-103">Gets the information about a resource from Azure based on the resource name within the current resource group.</span></span>
            </summary>
        <returns><span data-ttu-id="fbdc6-104">リソースの変更できない表現</span><span class="sxs-lookup"><span data-stu-id="fbdc6-104">an immutable representation of the resource</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetByNameAsync (string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!T&gt; GetByNameAsync(string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByName`1.GetByNameAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetByNameAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iSupportsGettingByName.GetByNameAsync (name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="fbdc6-105">リソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="fbdc6-105">name the name of the resource.</span></span> <span data-ttu-id="fbdc6-106">(注、これは、リソース ID ではありません)</span><span class="sxs-lookup"><span data-stu-id="fbdc6-106">(Note, this is not the resource ID.)</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="fbdc6-107">cancellationToken はキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="fbdc6-107">cancellationToken the cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="fbdc6-108">現在のリソース グループ内のリソース名に基づく Azure からのリソースに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="fbdc6-108">Gets the information about a resource from Azure based on the resource name within the current resource group.</span></span>
            </summary>
        <returns><span data-ttu-id="fbdc6-109">リソースの変更できない表現</span><span class="sxs-lookup"><span data-stu-id="fbdc6-109">an immutable representation of the resource</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>