<Type Name="IGenericResource" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.IGenericResource">
  <TypeSignature Language="C#" Value="public interface IGenericResource : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceManager,Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IGenericResource&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IWithApiVersion&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IGenericResource implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceManager, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.IGenericResource&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IWithApiVersion&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.IGenericResource" />
  <TypeSignature Language="VB.NET" Value="Public Interface IGenericResource&#xA;Implements IGroupableResource(Of IResourceManager, GenericResourceInner), IHasInner(Of GenericResourceInner), IHasManager(Of IResourceManager), IRefreshable(Of IGenericResource), IUpdatable(Of IWithApiVersion)" />
  <TypeSignature Language="F#" Value="type IGenericResource = interface&#xA;    interface IGroupableResource&lt;IResourceManager, GenericResourceInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IResourceManager&gt;&#xA;    interface IHasInner&lt;GenericResourceInner&gt;&#xA;    interface IRefreshable&lt;IGenericResource&gt;&#xA;    interface IUpdatable&lt;IWithApiVersion&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceManager,Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IGenericResource&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.GenericResource.Update.IWithApiVersion&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="a144c-101">Azure の一般的なリソースの変更できないクライアント側表現。</span><span class="sxs-lookup"><span data-stu-id="a144c-101">An immutable client-side representation of an Azure generic resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.IGenericResource.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.IGenericResource.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="a144c-102">リソースの api バージョン</span><span class="sxs-lookup"><span data-stu-id="a144c-102">the api version of the resource</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParentResourceId">
      <MemberSignature Language="C#" Value="public string ParentResourceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ParentResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.IGenericResource.ParentResourceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ParentResourceId As String" />
      <MemberSignature Language="F#" Value="member this.ParentResourceId : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.IGenericResource.ParentResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="a144c-103">この場合、親リソースの id が子リソースです。</span><span class="sxs-lookup"><span data-stu-id="a144c-103">the id of the parent resource if this is a child resource</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Plan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Models.Plan Plan { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Models.Plan Plan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.IGenericResource.Plan" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Plan As Plan" />
      <MemberSignature Language="F#" Value="member this.Plan : Microsoft.Azure.Management.ResourceManager.Fluent.Models.Plan" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.IGenericResource.Plan" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Models.Plan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="a144c-104">リソースの計画</span><span class="sxs-lookup"><span data-stu-id="a144c-104">the plan of the resource</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public object Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.IGenericResource.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As Object" />
      <MemberSignature Language="F#" Value="member this.Properties : obj" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.IGenericResource.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="a144c-105">その他のリソースのプロパティ</span><span class="sxs-lookup"><span data-stu-id="a144c-105">other properties of the resource</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceProviderNamespace">
      <MemberSignature Language="C#" Value="public string ResourceProviderNamespace { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceProviderNamespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.IGenericResource.ResourceProviderNamespace" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceProviderNamespace As String" />
      <MemberSignature Language="F#" Value="member this.ResourceProviderNamespace : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.IGenericResource.ResourceProviderNamespace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="a144c-106">リソース プロバイダーの名前空間</span><span class="sxs-lookup"><span data-stu-id="a144c-106">the namespace of the resource provider</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceType">
      <MemberSignature Language="C#" Value="public string ResourceType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.IGenericResource.ResourceType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceType As String" />
      <MemberSignature Language="F#" Value="member this.ResourceType : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.IGenericResource.ResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value><span data-ttu-id="a144c-107">リソースの種類</span><span class="sxs-lookup"><span data-stu-id="a144c-107">the type of the resource</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>