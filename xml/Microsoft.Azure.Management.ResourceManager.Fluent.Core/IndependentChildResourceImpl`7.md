<Type Name="IndependentChildResourceImpl&lt;IFluentResourceT,FluentParentModelT,InnerModelT,FluentResourceT,IDefinitionT,IUpdatableT,ManagerT&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl&lt;IFluentResourceT,FluentParentModelT,InnerModelT,FluentResourceT,IDefinitionT,IUpdatableT,ManagerT&gt;">
  <TypeSignature Language="C#" Value="public abstract class IndependentChildResourceImpl&lt;IFluentResourceT,FluentParentModelT,InnerModelT,FluentResourceT,IDefinitionT,IUpdatableT,ManagerT&gt; : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildImpl&lt;IFluentResourceT,FluentParentModelT,InnerModelT,FluentResourceT,IDefinitionT,IUpdatableT,ManagerT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;ManagerT,InnerModelT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;InnerModelT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;ManagerT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild&lt;ManagerT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChildResource&lt;ManagerT,InnerModelT&gt; where IFluentResourceT : class, IDefinitionT where FluentParentModelT : class, IResource, IHasResourceGroup where InnerModelT : Resource where FluentResourceT : IndependentChildResourceImpl&lt;IFluentResourceT,FluentParentModelT,InnerModelT,FluentResourceT,IDefinitionT,IUpdatableT,ManagerT&gt;, IFluentResourceT where IDefinitionT : class where IUpdatableT : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit IndependentChildResourceImpl`7&lt;class (!IDefinitionT) IFluentResourceT, class (class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup) FluentParentModelT, (class Microsoft.Azure.Management.ResourceManager.Fluent.Resource) InnerModelT, (class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl`7&lt;!IFluentResourceT, !FluentParentModelT, !InnerModelT, !FluentResourceT, !IDefinitionT, !IUpdatableT, !ManagerT&gt;, !IFluentResourceT) FluentResourceT, class IDefinitionT, class IUpdatableT, ManagerT&gt; extends Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildImpl`7&lt;!IFluentResourceT, !FluentParentModelT, !InnerModelT, !FluentResourceT, !IDefinitionT, !IUpdatableT, !ManagerT&gt; implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;!ManagerT, !InnerModelT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;!InnerModelT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;!ManagerT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild`1&lt;!ManagerT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChildResource`2&lt;!ManagerT, !InnerModelT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl`7" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class IndependentChildResourceImpl(Of IFluentResourceT, FluentParentModelT, InnerModelT, FluentResourceT, IDefinitionT, IUpdatableT, ManagerT)&#xA;Inherits IndependentChildImpl(Of IFluentResourceT, FluentParentModelT, InnerModelT, FluentResourceT, IDefinitionT, IUpdatableT, ManagerT)&#xA;Implements IGroupableResource(Of ManagerT, InnerModelT), IHasInner(Of InnerModelT), IHasManager(Of ManagerT), IIndependentChild(Of ManagerT), IIndependentChildResource(Of ManagerT, InnerModelT)" />
  <TypeSignature Language="F#" Value="type IndependentChildResourceImpl&lt;#'IDefinitionT, 'FluentParentModelT, 'InnerModelT, 'FluentResourceT, 'IDefinitionT, 'IUpdatableT, 'ManagerT (requires 'FluentParentModelT : null and 'FluentParentModelT :&gt; IResource and 'FluentParentModelT :&gt; IHasResourceGroup and 'InnerModelT :&gt; Resource and 'FluentResourceT :&gt; IndependentChildResourceImpl&lt;#'IDefinitionT, 'FluentParentModelT, 'InnerModelT, 'FluentResourceT, 'IDefinitionT, 'IUpdatableT, 'ManagerT&gt; and 'FluentResourceT :&gt; 'IFluentResourceT and 'IDefinitionT : null and 'IUpdatableT : null)&gt; = class&#xA;    inherit IndependentChildImpl&lt;#'IDefinitionT, 'FluentParentModelT, 'InnerModelT, 'FluentResourceT, 'IDefinitionT, 'IUpdatableT, 'ManagerT (requires 'FluentParentModelT : null and 'FluentParentModelT :&gt; IResource and 'FluentParentModelT :&gt; IHasResourceGroup and 'InnerModelT :&gt; Resource and 'FluentResourceT :&gt; IndependentChildResourceImpl&lt;#'IDefinitionT, 'FluentParentModelT, 'InnerModelT, 'FluentResourceT, 'IDefinitionT, 'IUpdatableT, 'ManagerT&gt; and 'FluentResourceT :&gt; 'IFluentResourceT and 'IDefinitionT : null and 'IUpdatableT : null)&gt;&#xA;    interface IIndependentChildResource&lt;'ManagerT, 'InnerModelT (requires 'InnerModelT :&gt; Resource)&gt;&#xA;    interface IGroupableResource&lt;'ManagerT, 'InnerModelT (requires 'InnerModelT :&gt; Resource)&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;'ManagerT&gt;&#xA;    interface IHasInner&lt;'InnerModelT (requires 'InnerModelT :&gt; Resource)&gt;&#xA;    interface IIndependentChild&lt;'ManagerT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="IFluentResourceT">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
        <BaseTypeName>IDefinitionT</BaseTypeName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="FluentParentModelT">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
        <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource</InterfaceName>
        <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup</InterfaceName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="InnerModelT">
      <Constraints>
        <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="FluentResourceT">
      <Constraints>
        <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl&lt;IFluentResourceT,FluentParentModelT,InnerModelT,FluentResourceT,IDefinitionT,IUpdatableT,ManagerT&gt;</BaseTypeName>
        <BaseTypeName>IFluentResourceT</BaseTypeName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="IDefinitionT">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="IUpdatableT">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="ManagerT" />
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildImpl&lt;IFluentResourceT,FluentParentModelT,InnerModelT,FluentResourceT,IDefinitionT,IUpdatableT,ManagerT&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="IFluentResourceT">IFluentResourceT</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="FluentParentModelT">FluentParentModelT</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="InnerResourceT">InnerModelT</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="FluentResourceT">FluentResourceT</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="IResourceT">IDefinitionT</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="IUpdatableT">IUpdatableT</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="ManagerT">ManagerT</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;ManagerT,InnerModelT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;InnerModelT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;ManagerT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild&lt;ManagerT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChildResource&lt;ManagerT,InnerModelT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="IFluentResourceT">To be added.</typeparam>
    <typeparam name="FluentParentModelT">To be added.</typeparam>
    <typeparam name="InnerModelT">To be added.</typeparam>
    <typeparam name="FluentResourceT">To be added.</typeparam>
    <typeparam name="IDefinitionT">To be added.</typeparam>
    <typeparam name="IUpdatableT">To be added.</typeparam>
    <typeparam name="ManagerT">To be added.</typeparam>
    <summary>
             <span data-ttu-id="84e1d-101">できる CRUDed 個別に親リソースから子リソースの実装です。</span><span class="sxs-lookup"><span data-stu-id="84e1d-101">Implementation for the child resource which can be CRUDed independently from the parent resource.</span></span>
             <span data-ttu-id="84e1d-102">(内部使用のみ)。</span><span class="sxs-lookup"><span data-stu-id="84e1d-102">(internal use only).</span></span>
             </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected IndependentChildResourceImpl (string name, InnerModelT innerObject, ManagerT manager);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string name, !InnerModelT innerObject, !ManagerT manager) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl`7.#ctor(System.String,`2,`6)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (name As String, innerObject As InnerModelT, manager As ManagerT)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl&lt;#'IDefinitionT, 'FluentParentModelT, 'InnerModelT, 'FluentResourceT, 'IDefinitionT, 'IUpdatableT, 'ManagerT (requires 'FluentParentModelT : null and 'FluentParentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource and 'FluentParentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup and 'InnerModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Resource and 'FluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl&lt;#'IDefinitionT, 'FluentParentModelT, 'InnerModelT, 'FluentResourceT, 'IDefinitionT, 'IUpdatableT, 'ManagerT&gt; and 'FluentResourceT :&gt; 'IFluentResourceT and 'IDefinitionT : null and 'IUpdatableT : null)&gt; : string * 'InnerModelT * 'ManagerT -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl&lt;#'IDefinitionT, 'FluentParentModelT, 'InnerModelT, 'FluentResourceT, 'IDefinitionT, 'IUpdatableT, 'ManagerT (requires 'FluentParentModelT : null and 'FluentParentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource and 'FluentParentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup and 'InnerModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Resource and 'FluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl&lt;#'IDefinitionT, 'FluentParentModelT, 'InnerModelT, 'FluentResourceT, 'IDefinitionT, 'IUpdatableT, 'ManagerT&gt; and 'FluentResourceT :&gt; 'IFluentResourceT and 'IDefinitionT : null and 'IUpdatableT : null)&gt;" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl&lt;#'IDefinitionT, 'FluentParentModelT, 'InnerModelT, 'FluentResourceT, 'IDefinitionT, 'IUpdatableT, 'ManagerT (requires 'FluentParentModelT : null and 'FluentParentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource and 'FluentParentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup and 'InnerModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Resource and 'FluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl&lt;#'IDefinitionT, 'FluentParentModelT, 'InnerModelT, 'FluentResourceT, 'IDefinitionT, 'IUpdatableT, 'ManagerT&gt; and 'FluentResourceT :&gt; 'IFluentResourceT and 'IDefinitionT : null and 'IUpdatableT : null)&gt; (name, innerObject, manager)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="innerObject" Type="InnerModelT" />
        <Parameter Name="manager" Type="ManagerT" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="84e1d-103">リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="84e1d-103">The name of the resource.</span></span></param>
        <param name="innerObject"><span data-ttu-id="84e1d-104">内部オブジェクトです。</span><span class="sxs-lookup"><span data-stu-id="84e1d-104">The inner object.</span></span></param>
        <param name="manager">To be added.</param>
        <summary>
             <span data-ttu-id="84e1d-105">CreatableUpdatableImpl の新しいインスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="84e1d-105">Creates a new instance of CreatableUpdatableImpl.</span></span>
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public override string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl`7.Id" />
      <MemberSignature Language="VB.NET" Value="Public Overrides ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl&lt;#'IDefinitionT, 'FluentParentModelT, 'InnerModelT, 'FluentResourceT, 'IDefinitionT, 'IUpdatableT, 'ManagerT (requires 'FluentParentModelT : null and 'FluentParentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource and 'FluentParentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup and 'InnerModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Resource and 'FluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl&lt;#'IDefinitionT, 'FluentParentModelT, 'InnerModelT, 'FluentResourceT, 'IDefinitionT, 'IUpdatableT, 'ManagerT&gt; and 'FluentResourceT :&gt; 'IFluentResourceT and 'IDefinitionT : null and 'IUpdatableT : null)&gt;.Id" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId.Id</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl`7.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl&lt;#'IDefinitionT, 'FluentParentModelT, 'InnerModelT, 'FluentResourceT, 'IDefinitionT, 'IUpdatableT, 'ManagerT (requires 'FluentParentModelT : null and 'FluentParentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource and 'FluentParentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup and 'InnerModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Resource and 'FluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl&lt;#'IDefinitionT, 'FluentParentModelT, 'InnerModelT, 'FluentResourceT, 'IDefinitionT, 'IUpdatableT, 'ManagerT&gt; and 'FluentResourceT :&gt; 'IFluentResourceT and 'IDefinitionT : null and 'IUpdatableT : null)&gt;.Name" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName.Name</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Region">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region Region { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region Region" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl`7.Region" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Region As Region" />
      <MemberSignature Language="F#" Value="member this.Region : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl&lt;#'IDefinitionT, 'FluentParentModelT, 'InnerModelT, 'FluentResourceT, 'IDefinitionT, 'IUpdatableT, 'ManagerT (requires 'FluentParentModelT : null and 'FluentParentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource and 'FluentParentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup and 'InnerModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Resource and 'FluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl&lt;#'IDefinitionT, 'FluentParentModelT, 'InnerModelT, 'FluentResourceT, 'IDefinitionT, 'IUpdatableT, 'ManagerT&gt; and 'FluentResourceT :&gt; 'IFluentResourceT and 'IDefinitionT : null and 'IUpdatableT : null)&gt;.Region" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource.Region</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegionName">
      <MemberSignature Language="C#" Value="public string RegionName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RegionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl`7.RegionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RegionName As String" />
      <MemberSignature Language="F#" Value="member this.RegionName : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl&lt;#'IDefinitionT, 'FluentParentModelT, 'InnerModelT, 'FluentResourceT, 'IDefinitionT, 'IUpdatableT, 'ManagerT (requires 'FluentParentModelT : null and 'FluentParentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource and 'FluentParentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup and 'InnerModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Resource and 'FluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl&lt;#'IDefinitionT, 'FluentParentModelT, 'InnerModelT, 'FluentResourceT, 'IDefinitionT, 'IUpdatableT, 'ManagerT&gt; and 'FluentResourceT :&gt; 'IFluentResourceT and 'IDefinitionT : null and 'IUpdatableT : null)&gt;.RegionName" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource.RegionName</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,string&gt; Tags { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl`7.Tags" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tags As IReadOnlyDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IReadOnlyDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl&lt;#'IDefinitionT, 'FluentParentModelT, 'InnerModelT, 'FluentResourceT, 'IDefinitionT, 'IUpdatableT, 'ManagerT (requires 'FluentParentModelT : null and 'FluentParentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource and 'FluentParentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup and 'InnerModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Resource and 'FluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl&lt;#'IDefinitionT, 'FluentParentModelT, 'InnerModelT, 'FluentResourceT, 'IDefinitionT, 'IUpdatableT, 'ManagerT&gt; and 'FluentResourceT :&gt; 'IFluentResourceT and 'IDefinitionT : null and 'IUpdatableT : null)&gt;.Tags" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource.Tags</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl`7.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl&lt;#'IDefinitionT, 'FluentParentModelT, 'InnerModelT, 'FluentResourceT, 'IDefinitionT, 'IUpdatableT, 'ManagerT (requires 'FluentParentModelT : null and 'FluentParentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource and 'FluentParentModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup and 'InnerModelT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Resource and 'FluentResourceT :&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl&lt;#'IDefinitionT, 'FluentParentModelT, 'InnerModelT, 'FluentResourceT, 'IDefinitionT, 'IUpdatableT, 'ManagerT&gt; and 'FluentResourceT :&gt; 'IFluentResourceT and 'IDefinitionT : null and 'IUpdatableT : null)&gt;.Type" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource.Type</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithExistingParentResource">
      <MemberSignature Language="C#" Value="public override Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;IFluentResourceT&gt; WithExistingParentResource (FluentParentModelT existingParentResource);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;!IFluentResourceT&gt; WithExistingParentResource(!FluentParentModelT existingParentResource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl`7.WithExistingParentResource(`1)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function WithExistingParentResource (existingParentResource As FluentParentModelT) As ICreatable(Of IFluentResourceT)" />
      <MemberSignature Language="F#" Value="override this.WithExistingParentResource : 'FluentParentModelT -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;#'IDefinitionT&gt;" Usage="independentChildResourceImpl.WithExistingParentResource existingParentResource" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;IFluentResourceT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="existingParentResource" Type="FluentParentModelT" />
      </Parameters>
      <Docs>
        <param name="existingParentResource">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithoutTag">
      <MemberSignature Language="C#" Value="public FluentResourceT WithoutTag (string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !FluentResourceT WithoutTag(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl`7.WithoutTag(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutTag (key As String) As FluentResourceT" />
      <MemberSignature Language="F#" Value="member this.WithoutTag : string -&gt; 'FluentResourceT" Usage="independentChildResourceImpl.WithoutTag key" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>FluentResourceT</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="84e1d-106">削除するタグのキー。</span><span class="sxs-lookup"><span data-stu-id="84e1d-106">The key of the tag to remove.</span></span></param>
        <summary>
            <span data-ttu-id="84e1d-107">リソースからタグを削除します。</span><span class="sxs-lookup"><span data-stu-id="84e1d-107">Removes a tag from the resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="84e1d-108">リソース定義または更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="84e1d-108">The next stage of the resource definition/update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithTag">
      <MemberSignature Language="C#" Value="public FluentResourceT WithTag (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !FluentResourceT WithTag(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl`7.WithTag(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTag (key As String, value As String) As FluentResourceT" />
      <MemberSignature Language="F#" Value="member this.WithTag : string * string -&gt; 'FluentResourceT" Usage="independentChildResourceImpl.WithTag (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>FluentResourceT</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="84e1d-109">タグのキー。</span><span class="sxs-lookup"><span data-stu-id="84e1d-109">The key for the tag.</span></span></param>
        <param name="value"><span data-ttu-id="84e1d-110">タグの値です。</span><span class="sxs-lookup"><span data-stu-id="84e1d-110">The value for the tag.</span></span></param>
        <summary>
            <span data-ttu-id="84e1d-111">リソースにタグを追加します。</span><span class="sxs-lookup"><span data-stu-id="84e1d-111">Adds a tag to the resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="84e1d-112">リソース定義または更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="84e1d-112">The next stage of the resource definition/update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithTags">
      <MemberSignature Language="C#" Value="public FluentResourceT WithTags (System.Collections.Generic.IDictionary&lt;string,string&gt; tags);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !FluentResourceT WithTags(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndependentChildResourceImpl`7.WithTags(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTags (tags As IDictionary(Of String, String)) As FluentResourceT" />
      <MemberSignature Language="F#" Value="member this.WithTags : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; 'FluentResourceT" Usage="independentChildResourceImpl.WithTags tags" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>FluentResourceT</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="tags"><span data-ttu-id="84e1d-113">タグのマップです。</span><span class="sxs-lookup"><span data-stu-id="84e1d-113">A Map of tags.</span></span></param>
        <summary>
            <span data-ttu-id="84e1d-114">マップとして、リソースのタグを指定します。</span><span class="sxs-lookup"><span data-stu-id="84e1d-114">Specifies tags for the resource as a Map.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="84e1d-115">リソース定義または更新の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="84e1d-115">The next stage of the resource definition/update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>