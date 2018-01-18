<Type Name="ChildResource&lt;InnerT,ParentImplT,IParentT&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource&lt;InnerT,ParentImplT,IParentT&gt;">
  <TypeSignature Language="C#" Value="public abstract class ChildResource&lt;InnerT,ParentImplT,IParentT&gt; : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndexableWrapper&lt;InnerT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;IParentT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;IParentT&gt; where ParentImplT : IParentT" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ChildResource`3&lt;InnerT, (!IParentT) ParentImplT, IParentT&gt; extends Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndexableWrapper`1&lt;!InnerT&gt; implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;!IParentT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;!IParentT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource`3" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ChildResource(Of InnerT, ParentImplT, IParentT)&#xA;Inherits IndexableWrapper(Of InnerT)&#xA;Implements IChildResource(Of IParentT), IHasParent(Of IParentT)" />
  <TypeSignature Language="F#" Value="type ChildResource&lt;'InnerT, #'IParentT, 'IParentT&gt; = class&#xA;    inherit IndexableWrapper&lt;'InnerT&gt;&#xA;    interface IChildResource&lt;'IParentT&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;'IParentT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="InnerT" />
    <TypeParameter Name="ParentImplT">
      <Constraints>
        <BaseTypeName>IParentT</BaseTypeName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="IParentT" />
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IndexableWrapper&lt;InnerT&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="InnerT">InnerT</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;IParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;IParentT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="InnerT"><span data-ttu-id="b7446-101">Azure 内部の子のクラス型</span><span class="sxs-lookup"><span data-stu-id="b7446-101">Azure inner child class type</span></span></typeparam>
    <typeparam name="ParentImplT"><span data-ttu-id="b7446-102">親 fluent インターフェイスの実装</span><span class="sxs-lookup"><span data-stu-id="b7446-102">Parent fluent interface implementation</span></span></typeparam>
    <typeparam name="IParentT"><span data-ttu-id="b7446-103">親 fluent インターフェイス</span><span class="sxs-lookup"><span data-stu-id="b7446-103">Parent fluent interface</span></span></typeparam>
    <summary>
            <span data-ttu-id="b7446-104">子リソースの抽象実装。</span><span class="sxs-lookup"><span data-stu-id="b7446-104">Child resource abstract implementation.</span></span>
            <span data-ttu-id="b7446-105">(内部使用のみ)</span><span class="sxs-lookup"><span data-stu-id="b7446-105">(Internal use only)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChildResource (InnerT innerObject, ParentImplT parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(!InnerT innerObject, !ParentImplT parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource`3.#ctor(`0,`1)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (innerObject As InnerT, parent As ParentImplT)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource&lt;'InnerT, #'IParentT, 'IParentT&gt; : 'InnerT * 'ParentImplT -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource&lt;'InnerT, #'IParentT, 'IParentT&gt;" Usage="new Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource&lt;'InnerT, #'IParentT, 'IParentT&gt; (innerObject, parent)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="innerObject" Type="InnerT" />
        <Parameter Name="parent" Type="ParentImplT" />
      </Parameters>
      <Docs>
        <param name="innerObject">To be added.</param>
        <param name="parent">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName.Name">
      <MemberSignature Language="C#" Value="string Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName.Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName.Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource`3.Microsoft#Azure#Management#ResourceManager#Fluent#Core#IHasName#Name" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property Name As String Implements IHasName.Name" />
      <MemberSignature Language="F#" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource&lt;'InnerT, #'IParentT, 'IParentT&gt;.Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName.Name" />
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
    <Member MemberName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;IParentT&gt;.Parent">
      <MemberSignature Language="C#" Value="IParentT Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;IParentT&gt;.Parent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !IParentT Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;IParentT&gt;.Parent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource`3.Microsoft#Azure#Management#ResourceManager#Fluent#Core#IHasParent&lt;IParentT&gt;#Parent" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property Parent As IParentT Implements IHasParent(Of IParentT).Parent" />
      <MemberSignature Language="F#" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource&lt;'InnerT, #'IParentT, 'IParentT&gt;.Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;IParentT&gt;.Parent" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1.Parent</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>IParentT</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="b7446-106">親 fluent インターフェイス</span><span class="sxs-lookup"><span data-stu-id="b7446-106">the parent fluent interface</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public abstract string Name ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string Name() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource`3.Name" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function Name () As String" />
      <MemberSignature Language="F#" Value="abstract member Name : unit -&gt; string" Usage="childResource.Name " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parent">
      <MemberSignature Language="C#" Value="public ParentImplT Parent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !ParentImplT Parent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource`3.Parent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parent As ParentImplT" />
      <MemberSignature Language="F#" Value="member this.Parent : 'ParentImplT" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource&lt;'InnerT, #'IParentT, 'IParentT&gt;.Parent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>ParentImplT</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b7446-107">参照を取得します親の実装にこれはによって使用子リソース impls 子リソース impl を親で保持されている子リソースのコレクションに追加する方法など、親のメソッドを呼び出します。</span><span class="sxs-lookup"><span data-stu-id="b7446-107">Gets the reference to the parent implementation, this is used by the child resource impls to invoke methods in the parent such as method to add the child resource impl to collection of child resources maintained by the parent.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>