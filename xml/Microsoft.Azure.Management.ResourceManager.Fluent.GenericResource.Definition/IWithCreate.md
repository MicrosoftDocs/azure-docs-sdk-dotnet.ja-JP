<Type Name="IWithCreate" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Definition.IWithCreate">
  <TypeSignature Language="C#" Value="public interface IWithCreate : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Definition.IWithCreate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IGenericResource&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Definition.IWithParentResource" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCreate implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.IGenericResource&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Definition.IWithParentResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Definition.IWithCreate" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCreate&#xA;Implements ICreatable(Of IGenericResource), IDefinitionWithTags(Of IWithCreate), IWithParentResource" />
  <TypeSignature Language="F#" Value="type IWithCreate = interface&#xA;    interface IWithParentResource&#xA;    interface ICreatable&lt;IGenericResource&gt;&#xA;    interface IIndexable&#xA;    interface IDefinitionWithTags&lt;IWithCreate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IGenericResource&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Definition.IWithParentResource</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="82919-101">新しい展開には、クラウドが指定する省略可能な追加の入力を公開することで、新しいリソースを作成するための十分な入力での定義がします。</span><span class="sxs-lookup"><span data-stu-id="82919-101">A deployment definition with sufficient inputs to create a new resource in the cloud, but exposing additional optional inputs to specify.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithProperties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Definition.IWithCreate WithProperties (object properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Definition.IWithCreate WithProperties(object properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Definition.IWithCreate.WithProperties(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithProperties (properties As Object) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithProperties : obj -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Definition.IWithCreate" Usage="iWithCreate.WithProperties properties" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="82919-102">プロパティのプロパティ オブジェクト</span><span class="sxs-lookup"><span data-stu-id="82919-102">properties the properties object</span></span></param>
        <summary>
            <span data-ttu-id="82919-103">その他のプロパティを指定します。</span><span class="sxs-lookup"><span data-stu-id="82919-103">Specifies other properties.</span></span>
            </summary>
        <returns><span data-ttu-id="82919-104">汎用リソース定義の次のステージ</span><span class="sxs-lookup"><span data-stu-id="82919-104">the next stage of generic resource definition</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>