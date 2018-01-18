<Type Name="PermissionOperationsExtensions" FullName="Microsoft.Azure.Management.Authorization.PermissionOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PermissionOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PermissionOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Authorization.PermissionOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PermissionOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PermissionOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListForResource">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.PermissionGetResult ListForResource (this Microsoft.Azure.Management.Authorization.IPermissionOperations operations, string resourceGroupName, Microsoft.Azure.ResourceIdentity identity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.PermissionGetResult ListForResource(class Microsoft.Azure.Management.Authorization.IPermissionOperations operations, string resourceGroupName, class Microsoft.Azure.ResourceIdentity identity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.PermissionOperationsExtensions.ListForResource(Microsoft.Azure.Management.Authorization.IPermissionOperations,System.String,Microsoft.Azure.ResourceIdentity)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForResource (operations As IPermissionOperations, resourceGroupName As String, identity As ResourceIdentity) As PermissionGetResult" />
      <MemberSignature Language="F#" Value="static member ListForResource : Microsoft.Azure.Management.Authorization.IPermissionOperations * string * Microsoft.Azure.ResourceIdentity -&gt; Microsoft.Azure.Management.Authorization.Models.PermissionGetResult" Usage="Microsoft.Azure.Management.Authorization.PermissionOperationsExtensions.ListForResource (operations, resourceGroupName, identity)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.PermissionGetResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IPermissionOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="identity" Type="Microsoft.Azure.ResourceIdentity" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c961e-101">Microsoft.Azure.Management.Authorization.IPermissionOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c961e-101">Reference to the Microsoft.Azure.Management.Authorization.IPermissionOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c961e-102">必須。</span><span class="sxs-lookup"><span data-stu-id="c961e-102">Required.</span></span> <span data-ttu-id="c961e-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c961e-103">The name of the resource group.</span></span> <span data-ttu-id="c961e-104">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="c961e-104">The name is case insensitive.</span></span>
            </param>
        <param name="identity">
            <span data-ttu-id="c961e-105">必須。</span><span class="sxs-lookup"><span data-stu-id="c961e-105">Required.</span></span> <span data-ttu-id="c961e-106">リソース</span><span class="sxs-lookup"><span data-stu-id="c961e-106">Resource</span></span>
            </param>
        <summary>
            <span data-ttu-id="c961e-107">リソースのアクセス許可を取得します。</span><span class="sxs-lookup"><span data-stu-id="c961e-107">Gets a resource permissions.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c961e-108">権限に関する情報。</span><span class="sxs-lookup"><span data-stu-id="c961e-108">Permissions information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt; ListForResourceAsync (this Microsoft.Azure.Management.Authorization.IPermissionOperations operations, string resourceGroupName, Microsoft.Azure.ResourceIdentity identity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt; ListForResourceAsync(class Microsoft.Azure.Management.Authorization.IPermissionOperations operations, string resourceGroupName, class Microsoft.Azure.ResourceIdentity identity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.PermissionOperationsExtensions.ListForResourceAsync(Microsoft.Azure.Management.Authorization.IPermissionOperations,System.String,Microsoft.Azure.ResourceIdentity)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForResourceAsync (operations As IPermissionOperations, resourceGroupName As String, identity As ResourceIdentity) As Task(Of PermissionGetResult)" />
      <MemberSignature Language="F#" Value="static member ListForResourceAsync : Microsoft.Azure.Management.Authorization.IPermissionOperations * string * Microsoft.Azure.ResourceIdentity -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt;" Usage="Microsoft.Azure.Management.Authorization.PermissionOperationsExtensions.ListForResourceAsync (operations, resourceGroupName, identity)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IPermissionOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="identity" Type="Microsoft.Azure.ResourceIdentity" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c961e-109">Microsoft.Azure.Management.Authorization.IPermissionOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c961e-109">Reference to the Microsoft.Azure.Management.Authorization.IPermissionOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c961e-110">必須。</span><span class="sxs-lookup"><span data-stu-id="c961e-110">Required.</span></span> <span data-ttu-id="c961e-111">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c961e-111">The name of the resource group.</span></span> <span data-ttu-id="c961e-112">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="c961e-112">The name is case insensitive.</span></span>
            </param>
        <param name="identity">
            <span data-ttu-id="c961e-113">必須。</span><span class="sxs-lookup"><span data-stu-id="c961e-113">Required.</span></span> <span data-ttu-id="c961e-114">リソース</span><span class="sxs-lookup"><span data-stu-id="c961e-114">Resource</span></span>
            </param>
        <summary>
            <span data-ttu-id="c961e-115">リソースのアクセス許可を取得します。</span><span class="sxs-lookup"><span data-stu-id="c961e-115">Gets a resource permissions.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c961e-116">権限に関する情報。</span><span class="sxs-lookup"><span data-stu-id="c961e-116">Permissions information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.PermissionGetResult ListForResourceGroup (this Microsoft.Azure.Management.Authorization.IPermissionOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.PermissionGetResult ListForResourceGroup(class Microsoft.Azure.Management.Authorization.IPermissionOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.PermissionOperationsExtensions.ListForResourceGroup(Microsoft.Azure.Management.Authorization.IPermissionOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForResourceGroup (operations As IPermissionOperations, resourceGroupName As String) As PermissionGetResult" />
      <MemberSignature Language="F#" Value="static member ListForResourceGroup : Microsoft.Azure.Management.Authorization.IPermissionOperations * string -&gt; Microsoft.Azure.Management.Authorization.Models.PermissionGetResult" Usage="Microsoft.Azure.Management.Authorization.PermissionOperationsExtensions.ListForResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.PermissionGetResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IPermissionOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c961e-117">Microsoft.Azure.Management.Authorization.IPermissionOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c961e-117">Reference to the Microsoft.Azure.Management.Authorization.IPermissionOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c961e-118">必須。</span><span class="sxs-lookup"><span data-stu-id="c961e-118">Required.</span></span> <span data-ttu-id="c961e-119">アクセス許可を取得するリソース グループの名前です。名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="c961e-119">Name of the resource group to get the permissions for.The name is case insensitive.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c961e-120">リソース グループのアクセス許可を取得します。</span><span class="sxs-lookup"><span data-stu-id="c961e-120">Gets a resource group permissions.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c961e-121">権限に関する情報。</span><span class="sxs-lookup"><span data-stu-id="c961e-121">Permissions information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt; ListForResourceGroupAsync (this Microsoft.Azure.Management.Authorization.IPermissionOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt; ListForResourceGroupAsync(class Microsoft.Azure.Management.Authorization.IPermissionOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.PermissionOperationsExtensions.ListForResourceGroupAsync(Microsoft.Azure.Management.Authorization.IPermissionOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListForResourceGroupAsync (operations As IPermissionOperations, resourceGroupName As String) As Task(Of PermissionGetResult)" />
      <MemberSignature Language="F#" Value="static member ListForResourceGroupAsync : Microsoft.Azure.Management.Authorization.IPermissionOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt;" Usage="Microsoft.Azure.Management.Authorization.PermissionOperationsExtensions.ListForResourceGroupAsync (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IPermissionOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c961e-122">Microsoft.Azure.Management.Authorization.IPermissionOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c961e-122">Reference to the Microsoft.Azure.Management.Authorization.IPermissionOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c961e-123">必須。</span><span class="sxs-lookup"><span data-stu-id="c961e-123">Required.</span></span> <span data-ttu-id="c961e-124">アクセス許可を取得するリソース グループの名前です。名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="c961e-124">Name of the resource group to get the permissions for.The name is case insensitive.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c961e-125">リソース グループのアクセス許可を取得します。</span><span class="sxs-lookup"><span data-stu-id="c961e-125">Gets a resource group permissions.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c961e-126">権限に関する情報。</span><span class="sxs-lookup"><span data-stu-id="c961e-126">Permissions information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>