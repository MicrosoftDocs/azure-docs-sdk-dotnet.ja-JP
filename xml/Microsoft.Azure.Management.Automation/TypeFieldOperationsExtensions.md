<Type Name="TypeFieldOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.TypeFieldOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TypeFieldOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TypeFieldOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.TypeFieldOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TypeFieldOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TypeFieldOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
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
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse List (this Microsoft.Azure.Management.Automation.ITypeFieldOperations operations, string resourceGroupName, string automationAccount, string moduleName, string typeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse List(class Microsoft.Azure.Management.Automation.ITypeFieldOperations operations, string resourceGroupName, string automationAccount, string moduleName, string typeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.TypeFieldOperationsExtensions.List(Microsoft.Azure.Management.Automation.ITypeFieldOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ITypeFieldOperations, resourceGroupName As String, automationAccount As String, moduleName As String, typeName As String) As TypeFieldListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.ITypeFieldOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse" Usage="Microsoft.Azure.Management.Automation.TypeFieldOperationsExtensions.List (operations, resourceGroupName, automationAccount, moduleName, typeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ITypeFieldOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="moduleName" Type="System.String" />
        <Parameter Name="typeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7fbd7-101">Microsoft.Azure.Management.Automation.ITypeFieldOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="7fbd7-101">Reference to the Microsoft.Azure.Management.Automation.ITypeFieldOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7fbd7-102">必須。</span><span class="sxs-lookup"><span data-stu-id="7fbd7-102">Required.</span></span> <span data-ttu-id="7fbd7-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="7fbd7-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="7fbd7-104">必須。</span><span class="sxs-lookup"><span data-stu-id="7fbd7-104">Required.</span></span> <span data-ttu-id="7fbd7-105">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbd7-105">The automation account name.</span></span>
            </param>
        <param name="moduleName">
            <span data-ttu-id="7fbd7-106">必須。</span><span class="sxs-lookup"><span data-stu-id="7fbd7-106">Required.</span></span> <span data-ttu-id="7fbd7-107">モジュールの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbd7-107">The name of module.</span></span>
            </param>
        <param name="typeName">
            <span data-ttu-id="7fbd7-108">必須。</span><span class="sxs-lookup"><span data-stu-id="7fbd7-108">Required.</span></span> <span data-ttu-id="7fbd7-109">型の名前。</span><span class="sxs-lookup"><span data-stu-id="7fbd7-109">The name of type.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7fbd7-110">モジュール名で識別される指定された型のフィールドの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7fbd7-110">Retrieve a list of fields of a given type identified by module name.</span></span>  <span data-ttu-id="7fbd7-111">(詳細については http://aka.ms/azureautomationsdk/typefieldoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="7fbd7-111">(see http://aka.ms/azureautomationsdk/typefieldoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7fbd7-112">リストのフィールドの操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="7fbd7-112">The response model for the list fields operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.ITypeFieldOperations operations, string resourceGroupName, string automationAccount, string moduleName, string typeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.ITypeFieldOperations operations, string resourceGroupName, string automationAccount, string moduleName, string typeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.TypeFieldOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.ITypeFieldOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As ITypeFieldOperations, resourceGroupName As String, automationAccount As String, moduleName As String, typeName As String) As Task(Of TypeFieldListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.ITypeFieldOperations * string * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.TypeFieldOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount, moduleName, typeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ITypeFieldOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="moduleName" Type="System.String" />
        <Parameter Name="typeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7fbd7-113">Microsoft.Azure.Management.Automation.ITypeFieldOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="7fbd7-113">Reference to the Microsoft.Azure.Management.Automation.ITypeFieldOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7fbd7-114">必須。</span><span class="sxs-lookup"><span data-stu-id="7fbd7-114">Required.</span></span> <span data-ttu-id="7fbd7-115">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="7fbd7-115">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="7fbd7-116">必須。</span><span class="sxs-lookup"><span data-stu-id="7fbd7-116">Required.</span></span> <span data-ttu-id="7fbd7-117">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbd7-117">The automation account name.</span></span>
            </param>
        <param name="moduleName">
            <span data-ttu-id="7fbd7-118">必須。</span><span class="sxs-lookup"><span data-stu-id="7fbd7-118">Required.</span></span> <span data-ttu-id="7fbd7-119">モジュールの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbd7-119">The name of module.</span></span>
            </param>
        <param name="typeName">
            <span data-ttu-id="7fbd7-120">必須。</span><span class="sxs-lookup"><span data-stu-id="7fbd7-120">Required.</span></span> <span data-ttu-id="7fbd7-121">型の名前。</span><span class="sxs-lookup"><span data-stu-id="7fbd7-121">The name of type.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7fbd7-122">モジュール名で識別される指定された型のフィールドの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7fbd7-122">Retrieve a list of fields of a given type identified by module name.</span></span>  <span data-ttu-id="7fbd7-123">(詳細については http://aka.ms/azureautomationsdk/typefieldoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="7fbd7-123">(see http://aka.ms/azureautomationsdk/typefieldoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7fbd7-124">リストのフィールドの操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="7fbd7-124">The response model for the list fields operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>