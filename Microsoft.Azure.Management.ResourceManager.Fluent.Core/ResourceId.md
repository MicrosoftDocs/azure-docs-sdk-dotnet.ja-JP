<Type Name="ResourceId" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId">
  <TypeSignature Language="C#" Value="public sealed class ResourceId" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ResourceId extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ResourceId" />
  <TypeSignature Language="F#" Value="type ResourceId = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
             <span data-ttu-id="947a0-101">リソース id から自体のインスタンスを作成し、サブスクリプション、リソース グループ、リソース名のようなリソースの情報に簡単にアクセスを付与します。</span><span class="sxs-lookup"><span data-stu-id="947a0-101">Instantiate itself from a resource id, and give easy access to resource information like subscription, resourceGroup, resource name.</span></span>
             </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId FromString (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId FromString(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId.FromString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function FromString (id As String) As ResourceId" />
      <MemberSignature Language="F#" Value="static member FromString : string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId.FromString id" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="947a0-102">リソースです。</span><span class="sxs-lookup"><span data-stu-id="947a0-102">of the resource.</span></span></param>
        <summary>
             <span data-ttu-id="947a0-103">返しますでは、特定のリソース id の ResourceId オブジェクトを解析します。</span><span class="sxs-lookup"><span data-stu-id="947a0-103">Returns parsed ResourceId object for a given resource id.</span></span>
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="947a0-104">ResourceId オブジェクト</span><span class="sxs-lookup"><span data-stu-id="947a0-104">ResourceId object</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="FullResourceType">
      <MemberSignature Language="C#" Value="public string FullResourceType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FullResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId.FullResourceType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FullResourceType As String" />
      <MemberSignature Language="F#" Value="member this.FullResourceType : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId.FullResourceType" />
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
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="947a0-105">リソースの完全な型です。</span><span class="sxs-lookup"><span data-stu-id="947a0-105">Full type of the resource.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId.Id" />
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
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="947a0-106">リソースの id。</span><span class="sxs-lookup"><span data-stu-id="947a0-106">The id of the resource.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId.Name" />
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
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="947a0-107">リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="947a0-107">Name of the resource.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Parent">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId Parent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId Parent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId.Parent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parent As ResourceId" />
      <MemberSignature Language="F#" Value="member this.Parent : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId.Parent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="947a0-108">いずれか、それ以外の場合は null の場合、リソースのリソース id を親します。</span><span class="sxs-lookup"><span data-stu-id="947a0-108">Parent resource id of the resource if any, otherwise null.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ProviderNamespace">
      <MemberSignature Language="C#" Value="public string ProviderNamespace { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProviderNamespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId.ProviderNamespace" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProviderNamespace As String" />
      <MemberSignature Language="F#" Value="member this.ProviderNamespace : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId.ProviderNamespace" />
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
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="947a0-109">プロバイダーの名前です。</span><span class="sxs-lookup"><span data-stu-id="947a0-109">Name of the provider.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroupName">
      <MemberSignature Language="C#" Value="public string ResourceGroupName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId.ResourceGroupName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceGroupName As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGroupName : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId.ResourceGroupName" />
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
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="947a0-110">リソースのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="947a0-110">Resource group name of the resource.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ResourceType">
      <MemberSignature Language="C#" Value="public string ResourceType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId.ResourceType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceType As String" />
      <MemberSignature Language="F#" Value="member this.ResourceType : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId.ResourceType" />
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
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="947a0-111">リソースの種類。</span><span class="sxs-lookup"><span data-stu-id="947a0-111">Type of the resource.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceId.SubscriptionId" />
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
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="947a0-112">リソースのサブスクリプション id です。</span><span class="sxs-lookup"><span data-stu-id="947a0-112">Subscription id of the resource.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>