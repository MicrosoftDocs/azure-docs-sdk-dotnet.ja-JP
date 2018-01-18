<Type Name="ISupportsBeginDeletingByName" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBeginDeletingByName">
  <TypeSignature Language="C#" Value="public interface ISupportsBeginDeletingByName" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISupportsBeginDeletingByName" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBeginDeletingByName" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISupportsBeginDeletingByName" />
  <TypeSignature Language="F#" Value="type ISupportsBeginDeletingByName = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9ceba-101">リソースの ID で識別して、Azure からリソースを削除するアクセスを提供します。</span><span class="sxs-lookup"><span data-stu-id="9ceba-101">Provides access to deleting a resource from Azure, identifying it by its resource ID.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginDeleteByName">
      <MemberSignature Language="C#" Value="public void BeginDeleteByName (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void BeginDeleteByName(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBeginDeletingByName.BeginDeleteByName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub BeginDeleteByName (name As String)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteByName : string -&gt; unit" Usage="iSupportsBeginDeletingByName.BeginDeleteByName name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="9ceba-102">削除するリソースの名前</span><span class="sxs-lookup"><span data-stu-id="9ceba-102">the name of the resource to delete</span></span></param>
        <summary>
            <span data-ttu-id="9ceba-103">そのリソース名で識別して、Azure からのリソースの削除を開始します。</span><span class="sxs-lookup"><span data-stu-id="9ceba-103">Begins deleting a resource from Azure, identifying it by its resource name.</span></span> <span data-ttu-id="9ceba-104">Get() が null を返すまで、リソースが維持されます。</span><span class="sxs-lookup"><span data-stu-id="9ceba-104">The resource will stay until get() returns null.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteByNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BeginDeleteByNameAsync (string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task BeginDeleteByNameAsync(string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBeginDeletingByName.BeginDeleteByNameAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteByNameAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iSupportsBeginDeletingByName.BeginDeleteByNameAsync (name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="9ceba-105">削除するリソースの名前</span><span class="sxs-lookup"><span data-stu-id="9ceba-105">the name of the resource to delete</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="9ceba-106">cancellationToken はキャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="9ceba-106">cancellationToken the cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="9ceba-107">そのリソース名で識別して、Azure からのリソースの削除を開始します。</span><span class="sxs-lookup"><span data-stu-id="9ceba-107">Begins deleting a resource from Azure, identifying it by its resource name.</span></span> <span data-ttu-id="9ceba-108">Get() が null を返すまで、リソースが維持されます。</span><span class="sxs-lookup"><span data-stu-id="9ceba-108">The resource will stay until get() returns null.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9ceba-109">非同期操作の await できませんタスク。</span><span class="sxs-lookup"><span data-stu-id="9ceba-109">A await-able Task for asynchronous operation.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>