<Type Name="IWithGroup" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithGroup">
  <TypeSignature Language="C#" Value="public interface IWithGroup : Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithExistingResourceGroup&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithGroup implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithExistingResourceGroup`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithGroup" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithGroup&#xA;Implements IWithExistingResourceGroup(Of IWithTemplate)" />
  <TypeSignature Language="F#" Value="type IWithGroup = interface&#xA;    interface IWithExistingResourceGroup&lt;IWithTemplate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithExistingResourceGroup&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="734f8-101">リソース グループを指定するを許可する展開の定義。</span><span class="sxs-lookup"><span data-stu-id="734f8-101">A deployment definition allowing resource group to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewResourceGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate WithNewResourceGroup (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt; groupDefinition);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate WithNewResourceGroup(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt; groupDefinition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithGroup.WithNewResourceGroup(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewResourceGroup (groupDefinition As ICreatable(Of IResourceGroup)) As IWithTemplate" />
      <MemberSignature Language="F#" Value="abstract member WithNewResourceGroup : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt; -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate" Usage="iWithGroup.WithNewResourceGroup groupDefinition" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupDefinition" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt;" />
      </Parameters>
      <Docs>
        <param name="groupDefinition"><span data-ttu-id="734f8-102">groupDefinition 作成可能な新しいリソース グループの定義</span><span class="sxs-lookup"><span data-stu-id="734f8-102">groupDefinition a creatable definition for a new resource group</span></span></param>
        <summary>
            <span data-ttu-id="734f8-103">指定された定義に基づき、リソースを格納する新しいリソース グループを作成します。</span><span class="sxs-lookup"><span data-stu-id="734f8-103">Creates a new resource group to put the resource in, based on the definition specified.</span></span>
            </summary>
        <returns><span data-ttu-id="734f8-104">展開の定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="734f8-104">the next stage of the deployment definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithNewResourceGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate WithNewResourceGroup (string name, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate WithNewResourceGroup(string name, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithGroup.WithNewResourceGroup(System.String,Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region)" />
      <MemberSignature Language="F#" Value="abstract member WithNewResourceGroup : string * Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate" Usage="iWithGroup.WithNewResourceGroup (name, region)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Deployment.Definition.IWithTemplate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="region" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="734f8-105">新しいグループを名前します。</span><span class="sxs-lookup"><span data-stu-id="734f8-105">name the name of the new group</span></span></param>
        <param name="region"><span data-ttu-id="734f8-106">領域内のリソース グループを作成する領域</span><span class="sxs-lookup"><span data-stu-id="734f8-106">region the region to create the resource group in</span></span></param>
        <summary>
            <span data-ttu-id="734f8-107">展開を格納する新しいリソース グループを作成します。</span><span class="sxs-lookup"><span data-stu-id="734f8-107">Creates a new resource group to put the deployment in.</span></span>
            </summary>
        <returns><span data-ttu-id="734f8-108">展開の定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="734f8-108">the next stage of the deployment definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>