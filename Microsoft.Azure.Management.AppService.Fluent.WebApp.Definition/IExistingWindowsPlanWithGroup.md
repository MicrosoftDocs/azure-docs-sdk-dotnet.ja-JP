<Type Name="IExistingWindowsPlanWithGroup" FullName="Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IExistingWindowsPlanWithGroup">
  <TypeSignature Language="C#" Value="public interface IExistingWindowsPlanWithGroup" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IExistingWindowsPlanWithGroup" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IExistingWindowsPlanWithGroup" />
  <TypeSignature Language="VB.NET" Value="Public Interface IExistingWindowsPlanWithGroup" />
  <TypeSignature Language="F#" Value="type IExistingWindowsPlanWithGroup = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3bda3-101">新しい app service プランが作成されるときに指定するリソース グループを許可する web アプリケーションの定義。</span><span class="sxs-lookup"><span data-stu-id="3bda3-101">A web app definition allowing resource group to be specified when a new app service plan is to be created.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingResourceGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate WithExistingResourceGroup (Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup group);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate WithExistingResourceGroup(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup group) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IExistingWindowsPlanWithGroup.WithExistingResourceGroup(Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingResourceGroup (group As IResourceGroup) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingResourceGroup : Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate" Usage="iExistingWindowsPlanWithGroup.WithExistingResourceGroup group" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="group" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup" />
      </Parameters>
      <Docs>
        <param name="group"><span data-ttu-id="3bda3-102">既存のリソース グループにリソースを記述します。</span><span class="sxs-lookup"><span data-stu-id="3bda3-102">An existing resource group to put the resource in.</span></span></param>
        <summary>
            <span data-ttu-id="3bda3-103">既存のリソース グループ リソースに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="3bda3-103">Associates the resource with an existing resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="3bda3-104">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="3bda3-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingResourceGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate WithExistingResourceGroup (string groupName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate WithExistingResourceGroup(string groupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IExistingWindowsPlanWithGroup.WithExistingResourceGroup(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingResourceGroup (groupName As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingResourceGroup : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate" Usage="iExistingWindowsPlanWithGroup.WithExistingResourceGroup groupName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="groupName"><span data-ttu-id="3bda3-105">このリソースを格納する既存のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="3bda3-105">The name of an existing resource group to put this resource in.</span></span></param>
        <summary>
            <span data-ttu-id="3bda3-106">既存のリソース グループ リソースに関連付けます。</span><span class="sxs-lookup"><span data-stu-id="3bda3-106">Associates the resource with an existing resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="3bda3-107">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="3bda3-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewResourceGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate WithNewResourceGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate WithNewResourceGroup() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IExistingWindowsPlanWithGroup.WithNewResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewResourceGroup () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewResourceGroup : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate" Usage="iExistingWindowsPlanWithGroup.WithNewResourceGroup " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3bda3-108">リソースを格納する新しいリソース グループを作成します。</span><span class="sxs-lookup"><span data-stu-id="3bda3-108">Creates a new resource group to put the resource in.</span></span>
            <span data-ttu-id="3bda3-109">グループは、リソースと同じ場所に作成されます。</span><span class="sxs-lookup"><span data-stu-id="3bda3-109">The group will be created in the same location as the resource.</span></span>
            <span data-ttu-id="3bda3-110">グループの名前は自動的に、リソース名から派生します。</span><span class="sxs-lookup"><span data-stu-id="3bda3-110">The group's name is automatically derived from the resource's name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="3bda3-111">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="3bda3-111">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewResourceGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate WithNewResourceGroup (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt; groupDefinition);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate WithNewResourceGroup(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt; groupDefinition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IExistingWindowsPlanWithGroup.WithNewResourceGroup(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewResourceGroup (groupDefinition As ICreatable(Of IResourceGroup)) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewResourceGroup : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate" Usage="iExistingWindowsPlanWithGroup.WithNewResourceGroup groupDefinition" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupDefinition" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt;" />
      </Parameters>
      <Docs>
        <param name="groupDefinition"><span data-ttu-id="3bda3-112">新しいリソース グループに対して作成可能な定義です。</span><span class="sxs-lookup"><span data-stu-id="3bda3-112">A creatable definition for a new resource group.</span></span></param>
        <summary>
            <span data-ttu-id="3bda3-113">指定された定義に基づき、リソースを格納する新しいリソース グループを作成します。</span><span class="sxs-lookup"><span data-stu-id="3bda3-113">Creates a new resource group to put the resource in, based on the definition specified.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="3bda3-114">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="3bda3-114">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewResourceGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate WithNewResourceGroup (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate WithNewResourceGroup(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IExistingWindowsPlanWithGroup.WithNewResourceGroup(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewResourceGroup (name As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewResourceGroup : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate" Usage="iExistingWindowsPlanWithGroup.WithNewResourceGroup name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="3bda3-115">新しいグループの名前。</span><span class="sxs-lookup"><span data-stu-id="3bda3-115">The name of the new group.</span></span></param>
        <summary>
            <span data-ttu-id="3bda3-116">リソースを格納する新しいリソース グループを作成します。</span><span class="sxs-lookup"><span data-stu-id="3bda3-116">Creates a new resource group to put the resource in.</span></span>
            <span data-ttu-id="3bda3-117">グループは、リソースと同じ場所に作成されます。</span><span class="sxs-lookup"><span data-stu-id="3bda3-117">The group will be created in the same location as the resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="3bda3-118">定義の次のステージ。</span><span class="sxs-lookup"><span data-stu-id="3bda3-118">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>