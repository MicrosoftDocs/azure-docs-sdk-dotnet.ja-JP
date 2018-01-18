<Type Name="IPermissionOperations" FullName="Microsoft.Azure.Management.Authorization.IPermissionOperations">
  <TypeSignature Language="C#" Value="public interface IPermissionOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPermissionOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Authorization.IPermissionOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPermissionOperations" />
  <TypeSignature Language="F#" Value="type IPermissionOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1923a-101">リソースまたはリソース グループの権限 (詳細については http://TBD を参照してください) を取得します。</span><span class="sxs-lookup"><span data-stu-id="1923a-101">Get resource or resource group permissions  (see http://TBD for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListForResourceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt; ListForResourceAsync (string resourceGroupName, Microsoft.Azure.ResourceIdentity identity, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt; ListForResourceAsync(string resourceGroupName, class Microsoft.Azure.ResourceIdentity identity, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IPermissionOperations.ListForResourceAsync(System.String,Microsoft.Azure.ResourceIdentity,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListForResourceAsync : string * Microsoft.Azure.ResourceIdentity * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt;" Usage="iPermissionOperations.ListForResourceAsync (resourceGroupName, identity, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="identity" Type="Microsoft.Azure.ResourceIdentity" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1923a-102">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1923a-102">The name of the resource group.</span></span> <span data-ttu-id="1923a-103">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1923a-103">The name is case insensitive.</span></span>
            </param>
        <param name="identity">
            <span data-ttu-id="1923a-104">リソース</span><span class="sxs-lookup"><span data-stu-id="1923a-104">Resource</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1923a-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1923a-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1923a-106">リソースのアクセス許可を取得します。</span><span class="sxs-lookup"><span data-stu-id="1923a-106">Gets a resource permissions.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1923a-107">権限に関する情報。</span><span class="sxs-lookup"><span data-stu-id="1923a-107">Permissions information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt; ListForResourceGroupAsync (string resourceGroupName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt; ListForResourceGroupAsync(string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IPermissionOperations.ListForResourceGroupAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListForResourceGroupAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt;" Usage="iPermissionOperations.ListForResourceGroupAsync (resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="1923a-108">アクセス許可を取得するリソース グループの名前です。名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="1923a-108">Name of the resource group to get the permissions for.The name is case insensitive.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1923a-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1923a-109">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1923a-110">リソース グループのアクセス許可を取得します。</span><span class="sxs-lookup"><span data-stu-id="1923a-110">Gets a resource group permissions.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1923a-111">権限に関する情報。</span><span class="sxs-lookup"><span data-stu-id="1923a-111">Permissions information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>