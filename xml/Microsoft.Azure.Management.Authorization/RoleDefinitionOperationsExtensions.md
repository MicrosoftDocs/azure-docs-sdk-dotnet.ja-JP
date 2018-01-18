<Type Name="RoleDefinitionOperationsExtensions" FullName="Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RoleDefinitionOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RoleDefinitionOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RoleDefinitionOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RoleDefinitionOperationsExtensions = class" />
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
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateResult CreateOrUpdate (this Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, Guid roleDefinitionId, string scope, Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateResult CreateOrUpdate(class Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, valuetype System.Guid roleDefinitionId, string scope, class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations,System.Guid,System.String,Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IRoleDefinitionOperations, roleDefinitionId As Guid, scope As String, parameters As RoleDefinitionCreateOrUpdateParameters) As RoleDefinitionCreateOrUpdateResult" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations * Guid * string * Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateResult" Usage="Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.CreateOrUpdate (operations, roleDefinitionId, scope, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations" RefType="this" />
        <Parameter Name="roleDefinitionId" Type="System.Guid" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c350-101">Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="2c350-101">Reference to the Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations.</span></span>
            </param>
        <param name="roleDefinitionId">
            <span data-ttu-id="2c350-102">必須。</span><span class="sxs-lookup"><span data-stu-id="2c350-102">Required.</span></span> <span data-ttu-id="2c350-103">ロール定義 id。</span><span class="sxs-lookup"><span data-stu-id="2c350-103">Role definition id.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="2c350-104">必須。</span><span class="sxs-lookup"><span data-stu-id="2c350-104">Required.</span></span> <span data-ttu-id="2c350-105">Scope (スコープ)</span><span class="sxs-lookup"><span data-stu-id="2c350-105">Scope</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2c350-106">必須。</span><span class="sxs-lookup"><span data-stu-id="2c350-106">Required.</span></span> <span data-ttu-id="2c350-107">ロールの定義。</span><span class="sxs-lookup"><span data-stu-id="2c350-107">Role definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c350-108">作成するか、ロールの定義を更新します。</span><span class="sxs-lookup"><span data-stu-id="2c350-108">Creates or updates a role definition.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2c350-109">ロールの定義を作成または操作の結果を更新します。</span><span class="sxs-lookup"><span data-stu-id="2c350-109">Role definition create or update operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateResult&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, Guid roleDefinitionId, string scope, Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateResult&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, valuetype System.Guid roleDefinitionId, string scope, class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations,System.Guid,System.String,Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IRoleDefinitionOperations, roleDefinitionId As Guid, scope As String, parameters As RoleDefinitionCreateOrUpdateParameters) As Task(Of RoleDefinitionCreateOrUpdateResult)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations * Guid * string * Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateResult&gt;" Usage="Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.CreateOrUpdateAsync (operations, roleDefinitionId, scope, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations" RefType="this" />
        <Parameter Name="roleDefinitionId" Type="System.Guid" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c350-110">Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="2c350-110">Reference to the Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations.</span></span>
            </param>
        <param name="roleDefinitionId">
            <span data-ttu-id="2c350-111">必須。</span><span class="sxs-lookup"><span data-stu-id="2c350-111">Required.</span></span> <span data-ttu-id="2c350-112">ロール定義 id。</span><span class="sxs-lookup"><span data-stu-id="2c350-112">Role definition id.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="2c350-113">必須。</span><span class="sxs-lookup"><span data-stu-id="2c350-113">Required.</span></span> <span data-ttu-id="2c350-114">Scope (スコープ)</span><span class="sxs-lookup"><span data-stu-id="2c350-114">Scope</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2c350-115">必須。</span><span class="sxs-lookup"><span data-stu-id="2c350-115">Required.</span></span> <span data-ttu-id="2c350-116">ロールの定義。</span><span class="sxs-lookup"><span data-stu-id="2c350-116">Role definition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c350-117">作成するか、ロールの定義を更新します。</span><span class="sxs-lookup"><span data-stu-id="2c350-117">Creates or updates a role definition.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2c350-118">ロールの定義を作成または操作の結果を更新します。</span><span class="sxs-lookup"><span data-stu-id="2c350-118">Role definition create or update operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.RoleDefinitionDeleteResult Delete (this Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, Guid roleDefinitionId, string scope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionDeleteResult Delete(class Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, valuetype System.Guid roleDefinitionId, string scope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.Delete(Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations,System.Guid,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IRoleDefinitionOperations, roleDefinitionId As Guid, scope As String) As RoleDefinitionDeleteResult" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations * Guid * string -&gt; Microsoft.Azure.Management.Authorization.Models.RoleDefinitionDeleteResult" Usage="Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.Delete (operations, roleDefinitionId, scope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.RoleDefinitionDeleteResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations" RefType="this" />
        <Parameter Name="roleDefinitionId" Type="System.Guid" />
        <Parameter Name="scope" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c350-119">Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="2c350-119">Reference to the Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations.</span></span>
            </param>
        <param name="roleDefinitionId">
            <span data-ttu-id="2c350-120">必須。</span><span class="sxs-lookup"><span data-stu-id="2c350-120">Required.</span></span> <span data-ttu-id="2c350-121">ロール定義 id。</span><span class="sxs-lookup"><span data-stu-id="2c350-121">Role definition id.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="2c350-122">必須。</span><span class="sxs-lookup"><span data-stu-id="2c350-122">Required.</span></span> <span data-ttu-id="2c350-123">Scope (スコープ)</span><span class="sxs-lookup"><span data-stu-id="2c350-123">Scope</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c350-124">ロールの定義を削除します。</span><span class="sxs-lookup"><span data-stu-id="2c350-124">Deletes the role definition.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2c350-125">ロールの定義は、操作の結果を削除します。</span><span class="sxs-lookup"><span data-stu-id="2c350-125">Role definition delete operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionDeleteResult&gt; DeleteAsync (this Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, Guid roleDefinitionId, string scope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionDeleteResult&gt; DeleteAsync(class Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, valuetype System.Guid roleDefinitionId, string scope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations,System.Guid,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IRoleDefinitionOperations, roleDefinitionId As Guid, scope As String) As Task(Of RoleDefinitionDeleteResult)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations * Guid * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionDeleteResult&gt;" Usage="Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.DeleteAsync (operations, roleDefinitionId, scope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionDeleteResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations" RefType="this" />
        <Parameter Name="roleDefinitionId" Type="System.Guid" />
        <Parameter Name="scope" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c350-126">Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="2c350-126">Reference to the Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations.</span></span>
            </param>
        <param name="roleDefinitionId">
            <span data-ttu-id="2c350-127">必須。</span><span class="sxs-lookup"><span data-stu-id="2c350-127">Required.</span></span> <span data-ttu-id="2c350-128">ロール定義 id。</span><span class="sxs-lookup"><span data-stu-id="2c350-128">Role definition id.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="2c350-129">必須。</span><span class="sxs-lookup"><span data-stu-id="2c350-129">Required.</span></span> <span data-ttu-id="2c350-130">Scope (スコープ)</span><span class="sxs-lookup"><span data-stu-id="2c350-130">Scope</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c350-131">ロールの定義を削除します。</span><span class="sxs-lookup"><span data-stu-id="2c350-131">Deletes the role definition.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2c350-132">ロールの定義は、操作の結果を削除します。</span><span class="sxs-lookup"><span data-stu-id="2c350-132">Role definition delete operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult Get (this Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, Guid roleDefinitionId, string scope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult Get(class Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, valuetype System.Guid roleDefinitionId, string scope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.Get(Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations,System.Guid,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IRoleDefinitionOperations, roleDefinitionId As Guid, scope As String) As RoleDefinitionGetResult" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations * Guid * string -&gt; Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult" Usage="Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.Get (operations, roleDefinitionId, scope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations" RefType="this" />
        <Parameter Name="roleDefinitionId" Type="System.Guid" />
        <Parameter Name="scope" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c350-133">Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="2c350-133">Reference to the Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations.</span></span>
            </param>
        <param name="roleDefinitionId">
            <span data-ttu-id="2c350-134">必須。</span><span class="sxs-lookup"><span data-stu-id="2c350-134">Required.</span></span> <span data-ttu-id="2c350-135">ロール定義 Id</span><span class="sxs-lookup"><span data-stu-id="2c350-135">Role definition Id</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="2c350-136">必須。</span><span class="sxs-lookup"><span data-stu-id="2c350-136">Required.</span></span> <span data-ttu-id="2c350-137">Scope (スコープ)</span><span class="sxs-lookup"><span data-stu-id="2c350-137">Scope</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c350-138">名前 (GUID) によって、ロールの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="2c350-138">Get role definition by name (GUID).</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2c350-139">ロールの定義は、操作の結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="2c350-139">Role definition get operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt; GetAsync (this Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, Guid roleDefinitionId, string scope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt; GetAsync(class Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, valuetype System.Guid roleDefinitionId, string scope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.GetAsync(Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations,System.Guid,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IRoleDefinitionOperations, roleDefinitionId As Guid, scope As String) As Task(Of RoleDefinitionGetResult)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations * Guid * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt;" Usage="Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.GetAsync (operations, roleDefinitionId, scope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations" RefType="this" />
        <Parameter Name="roleDefinitionId" Type="System.Guid" />
        <Parameter Name="scope" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c350-140">Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="2c350-140">Reference to the Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations.</span></span>
            </param>
        <param name="roleDefinitionId">
            <span data-ttu-id="2c350-141">必須。</span><span class="sxs-lookup"><span data-stu-id="2c350-141">Required.</span></span> <span data-ttu-id="2c350-142">ロール定義 Id</span><span class="sxs-lookup"><span data-stu-id="2c350-142">Role definition Id</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="2c350-143">必須。</span><span class="sxs-lookup"><span data-stu-id="2c350-143">Required.</span></span> <span data-ttu-id="2c350-144">Scope (スコープ)</span><span class="sxs-lookup"><span data-stu-id="2c350-144">Scope</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c350-145">名前 (GUID) によって、ロールの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="2c350-145">Get role definition by name (GUID).</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2c350-146">ロールの定義は、操作の結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="2c350-146">Role definition get operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetById">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult GetById (this Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, string roleDefinitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult GetById(class Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, string roleDefinitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.GetById(Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetById (operations As IRoleDefinitionOperations, roleDefinitionId As String) As RoleDefinitionGetResult" />
      <MemberSignature Language="F#" Value="static member GetById : Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations * string -&gt; Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult" Usage="Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.GetById (operations, roleDefinitionId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations" RefType="this" />
        <Parameter Name="roleDefinitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c350-147">Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="2c350-147">Reference to the Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations.</span></span>
            </param>
        <param name="roleDefinitionId">
            <span data-ttu-id="2c350-148">必須。</span><span class="sxs-lookup"><span data-stu-id="2c350-148">Required.</span></span> <span data-ttu-id="2c350-149">完全修飾のロール定義 Id</span><span class="sxs-lookup"><span data-stu-id="2c350-149">Fully qualified role definition Id</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c350-150">名前 (GUID) によって、ロールの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="2c350-150">Get role definition by name (GUID).</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2c350-151">ロールの定義は、操作の結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="2c350-151">Role definition get operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt; GetByIdAsync (this Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, string roleDefinitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt; GetByIdAsync(class Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, string roleDefinitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.GetByIdAsync(Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetByIdAsync (operations As IRoleDefinitionOperations, roleDefinitionId As String) As Task(Of RoleDefinitionGetResult)" />
      <MemberSignature Language="F#" Value="static member GetByIdAsync : Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt;" Usage="Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.GetByIdAsync (operations, roleDefinitionId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations" RefType="this" />
        <Parameter Name="roleDefinitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c350-152">Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="2c350-152">Reference to the Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations.</span></span>
            </param>
        <param name="roleDefinitionId">
            <span data-ttu-id="2c350-153">必須。</span><span class="sxs-lookup"><span data-stu-id="2c350-153">Required.</span></span> <span data-ttu-id="2c350-154">完全修飾のロール定義 Id</span><span class="sxs-lookup"><span data-stu-id="2c350-154">Fully qualified role definition Id</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c350-155">名前 (GUID) によって、ロールの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="2c350-155">Get role definition by name (GUID).</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2c350-156">ロールの定義は、操作の結果を取得します。</span><span class="sxs-lookup"><span data-stu-id="2c350-156">Role definition get operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Authorization.Models.RoleDefinitionListResult List (this Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, string scope, Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionListResult List(class Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, string scope, class Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.List(Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations,System.String,Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IRoleDefinitionOperations, scope As String, parameters As ListDefinitionFilterParameters) As RoleDefinitionListResult" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations * string * Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters -&gt; Microsoft.Azure.Management.Authorization.Models.RoleDefinitionListResult" Usage="Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.List (operations, scope, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Authorization.Models.RoleDefinitionListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c350-157">Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="2c350-157">Reference to the Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="2c350-158">必須。</span><span class="sxs-lookup"><span data-stu-id="2c350-158">Required.</span></span> <span data-ttu-id="2c350-159">Scope (スコープ)</span><span class="sxs-lookup"><span data-stu-id="2c350-159">Scope</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2c350-160">省略可能。</span><span class="sxs-lookup"><span data-stu-id="2c350-160">Optional.</span></span> <span data-ttu-id="2c350-161">ロール定義のフィルターを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="2c350-161">List role definitions filters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c350-162">スコープで以降に適用されるすべてのロールの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="2c350-162">Get all role definitions that are applicable at scope and above.</span></span>
            <span data-ttu-id="2c350-163">AtScopeAndBelow フィルターを使用して、指定されたスコープの下の検索</span><span class="sxs-lookup"><span data-stu-id="2c350-163">Use atScopeAndBelow filter to search below the given scope as well</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2c350-164">ロール定義の一覧の操作の結果。</span><span class="sxs-lookup"><span data-stu-id="2c350-164">Role definition list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionListResult&gt; ListAsync (this Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, string scope, Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionListResult&gt; ListAsync(class Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations operations, string scope, class Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.ListAsync(Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations,System.String,Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IRoleDefinitionOperations, scope As String, parameters As ListDefinitionFilterParameters) As Task(Of RoleDefinitionListResult)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations * string * Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionListResult&gt;" Usage="Microsoft.Azure.Management.Authorization.RoleDefinitionOperationsExtensions.ListAsync (operations, scope, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c350-165">Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="2c350-165">Reference to the Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="2c350-166">必須。</span><span class="sxs-lookup"><span data-stu-id="2c350-166">Required.</span></span> <span data-ttu-id="2c350-167">Scope (スコープ)</span><span class="sxs-lookup"><span data-stu-id="2c350-167">Scope</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2c350-168">省略可能。</span><span class="sxs-lookup"><span data-stu-id="2c350-168">Optional.</span></span> <span data-ttu-id="2c350-169">ロール定義のフィルターを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="2c350-169">List role definitions filters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c350-170">スコープで以降に適用されるすべてのロールの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="2c350-170">Get all role definitions that are applicable at scope and above.</span></span>
            <span data-ttu-id="2c350-171">AtScopeAndBelow フィルターを使用して、指定されたスコープの下の検索</span><span class="sxs-lookup"><span data-stu-id="2c350-171">Use atScopeAndBelow filter to search below the given scope as well</span></span>
            </summary>
        <returns>
            <span data-ttu-id="2c350-172">ロール定義の一覧の操作の結果。</span><span class="sxs-lookup"><span data-stu-id="2c350-172">Role definition list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>