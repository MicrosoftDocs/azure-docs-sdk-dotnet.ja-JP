<Type Name="IWithCreatableResourceGroup&lt;T&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithCreatableResourceGroup&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IWithCreatableResourceGroup&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCreatableResourceGroup`1&lt;T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithCreatableResourceGroup`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCreatableResourceGroup(Of T)" />
  <TypeSignature Language="F#" Value="type IWithCreatableResourceGroup&lt;'T&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="T"><span data-ttu-id="2347c-101">リソース定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="2347c-101">the next stage of the resource definition</span></span></typeparam>
    <summary>
            <span data-ttu-id="2347c-102">新しい作成可能なリソース グループを指定するを許可するリソース定義します。</span><span class="sxs-lookup"><span data-stu-id="2347c-102">A resource definition allowing a new creatable resource group to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewResourceGroup">
      <MemberSignature Language="C#" Value="public T WithNewResourceGroup (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt; groupDefinition);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T WithNewResourceGroup(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt; groupDefinition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithCreatableResourceGroup`1.WithNewResourceGroup(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewResourceGroup (groupDefinition As ICreatable(Of IResourceGroup)) As T" />
      <MemberSignature Language="F#" Value="abstract member WithNewResourceGroup : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt; -&gt; 'T" Usage="iWithCreatableResourceGroup.WithNewResourceGroup groupDefinition" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupDefinition" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt;" />
      </Parameters>
      <Docs>
        <param name="groupDefinition"><span data-ttu-id="2347c-103">groupDefinition 作成可能な新しいリソース グループの定義</span><span class="sxs-lookup"><span data-stu-id="2347c-103">groupDefinition a creatable definition for a new resource group</span></span></param>
        <summary>
            <span data-ttu-id="2347c-104">指定された定義に基づき、リソースを格納する新しいリソース グループを作成します。</span><span class="sxs-lookup"><span data-stu-id="2347c-104">Creates a new resource group to put the resource in, based on the definition specified.</span></span>
            </summary>
        <returns><span data-ttu-id="2347c-105">リソース定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="2347c-105">the next stage of the resource definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>