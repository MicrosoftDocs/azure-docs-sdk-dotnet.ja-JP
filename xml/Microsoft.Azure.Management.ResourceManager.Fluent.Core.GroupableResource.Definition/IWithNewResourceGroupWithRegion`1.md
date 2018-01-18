<Type Name="IWithNewResourceGroupWithRegion&lt;T&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithNewResourceGroupWithRegion&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IWithNewResourceGroupWithRegion&lt;T&gt; : Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithCreatableResourceGroup&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNewResourceGroupWithRegion`1&lt;T&gt; implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithCreatableResourceGroup`1&lt;!T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithNewResourceGroupWithRegion`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNewResourceGroupWithRegion(Of T)&#xA;Implements IWithCreatableResourceGroup(Of T)" />
  <TypeSignature Language="F#" Value="type IWithNewResourceGroupWithRegion&lt;'T&gt; = interface&#xA;    interface IWithCreatableResourceGroup&lt;'T&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithCreatableResourceGroup&lt;T&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T"><span data-ttu-id="2cc7d-101">リソース定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="2cc7d-101">the next stage of the resource definition</span></span></typeparam>
    <summary>
            <span data-ttu-id="2cc7d-102">別のリージョンに作成される新しいリソース グループを許可するリソース定義します。</span><span class="sxs-lookup"><span data-stu-id="2cc7d-102">A resource definition allowing a new resource group to be created in a different region.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewResourceGroup">
      <MemberSignature Language="C#" Value="public T WithNewResourceGroup (Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T WithNewResourceGroup(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithNewResourceGroupWithRegion`1.WithNewResourceGroup(Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region)" />
      <MemberSignature Language="F#" Value="abstract member WithNewResourceGroup : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region -&gt; 'T" Usage="iWithNewResourceGroupWithRegion.WithNewResourceGroup region" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="region" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region" />
      </Parameters>
      <Docs>
        <param name="region"><span data-ttu-id="2cc7d-103">領域を作成するリソース グループが必要な領域</span><span class="sxs-lookup"><span data-stu-id="2cc7d-103">region the region where resource group needs to be created</span></span></param>
        <summary>
            <span data-ttu-id="2cc7d-104">リソースを格納する新しいリソース グループを作成します。</span><span class="sxs-lookup"><span data-stu-id="2cc7d-104">Creates a new resource group to put the resource in.</span></span>
            <span data-ttu-id="2cc7d-105">グループは、リソースと同じ場所に作成されます。</span><span class="sxs-lookup"><span data-stu-id="2cc7d-105">The group will be created in the same location as the resource.</span></span>
            <span data-ttu-id="2cc7d-106">グループの名前は自動的に、リソース名から派生します。</span><span class="sxs-lookup"><span data-stu-id="2cc7d-106">The group's name is automatically derived from the resource's name.</span></span>
            </summary>
        <returns><span data-ttu-id="2cc7d-107">リソース定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="2cc7d-107">the next stage of the resource definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithNewResourceGroup">
      <MemberSignature Language="C#" Value="public T WithNewResourceGroup (string name, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T WithNewResourceGroup(string name, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithNewResourceGroupWithRegion`1.WithNewResourceGroup(System.String,Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region)" />
      <MemberSignature Language="F#" Value="abstract member WithNewResourceGroup : string * Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region -&gt; 'T" Usage="iWithNewResourceGroupWithRegion.WithNewResourceGroup (name, region)" />
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
        <Parameter Name="region" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="2cc7d-108">新しいグループを名前します。</span><span class="sxs-lookup"><span data-stu-id="2cc7d-108">name the name of the new group</span></span></param>
        <param name="region"><span data-ttu-id="2cc7d-109">領域を作成するリソース グループが必要な領域</span><span class="sxs-lookup"><span data-stu-id="2cc7d-109">region the region where resource group needs to be created</span></span></param>
        <summary>
            <span data-ttu-id="2cc7d-110">リソースを格納する新しいリソース グループを作成します。</span><span class="sxs-lookup"><span data-stu-id="2cc7d-110">Creates a new resource group to put the resource in.</span></span>
            <span data-ttu-id="2cc7d-111">グループは、リソースと同じ場所に作成されます。</span><span class="sxs-lookup"><span data-stu-id="2cc7d-111">The group will be created in the same location as the resource.</span></span>
            </summary>
        <returns><span data-ttu-id="2cc7d-112">リソース定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="2cc7d-112">the next stage of the resource definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>