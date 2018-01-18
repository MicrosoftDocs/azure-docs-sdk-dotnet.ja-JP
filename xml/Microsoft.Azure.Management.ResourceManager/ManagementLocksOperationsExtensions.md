<Type Name="ManagementLocksOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ManagementLocksOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ManagementLocksOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ManagementLocksOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ManagementLocksOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7c8ab-101">ManagementLocksOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-101">Extension methods for ManagementLocksOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAtResourceGroupLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject CreateOrUpdateAtResourceGroupLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject CreateOrUpdateAtResourceGroupLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtResourceGroupLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAtResourceGroupLevel (operations As IManagementLocksOperations, resourceGroupName As String, lockName As String, parameters As ManagementLockObject) As ManagementLockObject" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAtResourceGroupLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtResourceGroupLevel (operations, resourceGroupName, lockName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7c8ab-103">ロックするリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-103">The name of the resource group to lock.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="7c8ab-104">ロックの名前です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-104">The lock name.</span></span> <span data-ttu-id="7c8ab-105">ロック名は 260 文字の最大値にできます。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-105">The lock name can be a maximum of 260 characters.</span></span> <span data-ttu-id="7c8ab-106">含めることができない&lt;、 &gt; %、 &amp;、: \, ?、/、いずれかの制御文字またはします。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-106">It cannot contain &lt;, &gt; %, &amp;, :, \, ?, /, or any control characters.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7c8ab-107">管理ロックのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-107">The management lock parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-108">作成するか、リソース グループ レベルの管理ロックを更新します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-108">Creates or updates a management lock at the resource group level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7c8ab-109">親スコープでロックを適用すると、すべての子リソースは同じロックを継承します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-109">When you apply a lock at a parent scope, all child resources inherit the same lock.</span></span> <span data-ttu-id="7c8ab-110">管理ロックを作成するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-110">To create management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="7c8ab-111">組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-111">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAtResourceGroupLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; CreateOrUpdateAtResourceGroupLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; CreateOrUpdateAtResourceGroupLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtResourceGroupLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAtResourceGroupLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtResourceGroupLevelAsync (operations, resourceGroupName, lockName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;CreateOrUpdateAtResourceGroupLevelAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-112">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-112">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7c8ab-113">ロックするリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-113">The name of the resource group to lock.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="7c8ab-114">ロックの名前です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-114">The lock name.</span></span> <span data-ttu-id="7c8ab-115">ロック名は 260 文字の最大値にできます。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-115">The lock name can be a maximum of 260 characters.</span></span> <span data-ttu-id="7c8ab-116">含めることができない&lt;、 &gt; %、 &amp;、: \, ?、/、いずれかの制御文字またはします。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-116">It cannot contain &lt;, &gt; %, &amp;, :, \, ?, /, or any control characters.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7c8ab-117">管理ロックのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-117">The management lock parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c8ab-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-119">作成するか、リソース グループ レベルの管理ロックを更新します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-119">Creates or updates a management lock at the resource group level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7c8ab-120">親スコープでロックを適用すると、すべての子リソースは同じロックを継承します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-120">When you apply a lock at a parent scope, all child resources inherit the same lock.</span></span> <span data-ttu-id="7c8ab-121">管理ロックを作成するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-121">To create management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="7c8ab-122">組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-122">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAtResourceLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject CreateOrUpdateAtResourceLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject CreateOrUpdateAtResourceLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtResourceLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAtResourceLevel (operations As IManagementLocksOperations, resourceGroupName As String, resourceProviderNamespace As String, parentResourcePath As String, resourceType As String, resourceName As String, lockName As String, parameters As ManagementLockObject) As ManagementLockObject" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAtResourceLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * string * string * string * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtResourceLevel (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, lockName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-123">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7c8ab-124">ロック リソースを含む、リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-124">The name of the resource group containing the resource to lock.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="7c8ab-125">リソース プロバイダーの名前空間のリソースをロックします。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-125">The resource provider namespace of the resource to lock.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="7c8ab-126">親のリソース id です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-126">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="7c8ab-127">ロックするリソースのリソースの種類。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-127">The resource type of the resource to lock.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="7c8ab-128">ロックするリソースの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-128">The name of the resource to lock.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="7c8ab-129">ロックの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-129">The name of lock.</span></span> <span data-ttu-id="7c8ab-130">ロック名は 260 文字の最大値にできます。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-130">The lock name can be a maximum of 260 characters.</span></span> <span data-ttu-id="7c8ab-131">含めることができない&lt;、 &gt; %、 &amp;、: \, ?、/、いずれかの制御文字またはします。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-131">It cannot contain &lt;, &gt; %, &amp;, :, \, ?, /, or any control characters.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7c8ab-132">作成または管理ロックを更新するためのパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-132">Parameters for creating or updating a  management lock.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-133">作成するか、リソース レベルまたはリソースの下の任意のレベルでの管理ロックを更新します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-133">Creates or updates a management lock at the resource level or any level below the resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7c8ab-134">親スコープでロックを適用すると、すべての子リソースは同じロックを継承します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-134">When you apply a lock at a parent scope, all child resources inherit the same lock.</span></span> <span data-ttu-id="7c8ab-135">管理ロックを作成するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-135">To create management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="7c8ab-136">組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-136">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAtResourceLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; CreateOrUpdateAtResourceLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; CreateOrUpdateAtResourceLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtResourceLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAtResourceLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * string * string * string * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtResourceLevelAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, lockName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;CreateOrUpdateAtResourceLevelAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-137">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7c8ab-138">ロック リソースを含む、リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-138">The name of the resource group containing the resource to lock.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="7c8ab-139">リソース プロバイダーの名前空間のリソースをロックします。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-139">The resource provider namespace of the resource to lock.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="7c8ab-140">親のリソース id です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-140">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="7c8ab-141">ロックするリソースのリソースの種類。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-141">The resource type of the resource to lock.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="7c8ab-142">ロックするリソースの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-142">The name of the resource to lock.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="7c8ab-143">ロックの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-143">The name of lock.</span></span> <span data-ttu-id="7c8ab-144">ロック名は 260 文字の最大値にできます。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-144">The lock name can be a maximum of 260 characters.</span></span> <span data-ttu-id="7c8ab-145">含めることができない&lt;、 &gt; %、 &amp;、: \, ?、/、いずれかの制御文字またはします。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-145">It cannot contain &lt;, &gt; %, &amp;, :, \, ?, /, or any control characters.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7c8ab-146">作成または管理ロックを更新するためのパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-146">Parameters for creating or updating a  management lock.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c8ab-147">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-148">作成するか、リソース レベルまたはリソースの下の任意のレベルでの管理ロックを更新します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-148">Creates or updates a management lock at the resource level or any level below the resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7c8ab-149">親スコープでロックを適用すると、すべての子リソースは同じロックを継承します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-149">When you apply a lock at a parent scope, all child resources inherit the same lock.</span></span> <span data-ttu-id="7c8ab-150">管理ロックを作成するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-150">To create management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="7c8ab-151">組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-151">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAtSubscriptionLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject CreateOrUpdateAtSubscriptionLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject CreateOrUpdateAtSubscriptionLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtSubscriptionLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAtSubscriptionLevel (operations As IManagementLocksOperations, lockName As String, parameters As ManagementLockObject) As ManagementLockObject" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAtSubscriptionLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtSubscriptionLevel (operations, lockName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-152">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-152">The operations group for this extension method.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="7c8ab-153">ロックの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-153">The name of lock.</span></span> <span data-ttu-id="7c8ab-154">ロック名は 260 文字の最大値にできます。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-154">The lock name can be a maximum of 260 characters.</span></span> <span data-ttu-id="7c8ab-155">含めることができない&lt;、 &gt; %、 &amp;、: \, ?、/、いずれかの制御文字またはします。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-155">It cannot contain &lt;, &gt; %, &amp;, :, \, ?, /, or any control characters.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7c8ab-156">管理ロックのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-156">The management lock parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-157">作成するか、サブスクリプション レベルでの管理ロックを更新します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-157">Creates or updates a management lock at the subscription level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7c8ab-158">親スコープでロックを適用すると、すべての子リソースは同じロックを継承します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-158">When you apply a lock at a parent scope, all child resources inherit the same lock.</span></span> <span data-ttu-id="7c8ab-159">管理ロックを作成するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-159">To create management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="7c8ab-160">組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-160">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAtSubscriptionLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; CreateOrUpdateAtSubscriptionLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; CreateOrUpdateAtSubscriptionLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtSubscriptionLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAtSubscriptionLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtSubscriptionLevelAsync (operations, lockName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;CreateOrUpdateAtSubscriptionLevelAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-161">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-161">The operations group for this extension method.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="7c8ab-162">ロックの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-162">The name of lock.</span></span> <span data-ttu-id="7c8ab-163">ロック名は 260 文字の最大値にできます。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-163">The lock name can be a maximum of 260 characters.</span></span> <span data-ttu-id="7c8ab-164">含めることができない&lt;、 &gt; %、 &amp;、: \, ?、/、いずれかの制御文字またはします。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-164">It cannot contain &lt;, &gt; %, &amp;, :, \, ?, /, or any control characters.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7c8ab-165">管理ロックのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-165">The management lock parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c8ab-166">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-167">作成するか、サブスクリプション レベルでの管理ロックを更新します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-167">Creates or updates a management lock at the subscription level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7c8ab-168">親スコープでロックを適用すると、すべての子リソースは同じロックを継承します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-168">When you apply a lock at a parent scope, all child resources inherit the same lock.</span></span> <span data-ttu-id="7c8ab-169">管理ロックを作成するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-169">To create management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="7c8ab-170">組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-170">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateByScope">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject CreateOrUpdateByScope (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject CreateOrUpdateByScope(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateByScope(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateByScope (operations As IManagementLocksOperations, scope As String, lockName As String, parameters As ManagementLockObject) As ManagementLockObject" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateByScope : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateByScope (operations, scope, lockName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-171">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-171">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="7c8ab-172">ロックのスコープです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-172">The scope for the lock.</span></span> <span data-ttu-id="7c8ab-173">割り当てのスコープを提供するときに使用して 'のサブスクリプション/{subscriptionid}' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' のリソース グループのサブスクリプションの場合と 'サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/providers/{resourceProviderNamespace}/{parentResourcePathIfPresent}/{resourcetype}/{resourcename}' のリソース。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-173">When providing a scope for the assignment, use '/subscriptions/{subscriptionId}' for subscriptions, '/subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}' for resource groups, and '/subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{parentResourcePathIfPresent}/{resourceType}/{resourceName}' for resources.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="7c8ab-174">ロックの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-174">The name of lock.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7c8ab-175">作成または管理ロック パラメーターを更新します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-175">Create or update management lock parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-176">作成またはスコープでの管理ロックを更新します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-176">Create or update a management lock by scope.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateByScopeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; CreateOrUpdateByScopeAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; CreateOrUpdateByScopeAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateByScopeAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateByScopeAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateByScopeAsync (operations, scope, lockName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;CreateOrUpdateByScopeAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-177">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-177">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="7c8ab-178">ロックのスコープです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-178">The scope for the lock.</span></span> <span data-ttu-id="7c8ab-179">割り当てのスコープを提供するときに使用して 'のサブスクリプション/{subscriptionid}' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' のリソース グループのサブスクリプションの場合と 'サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/providers/{resourceProviderNamespace}/{parentResourcePathIfPresent}/{resourcetype}/{resourcename}' のリソース。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-179">When providing a scope for the assignment, use '/subscriptions/{subscriptionId}' for subscriptions, '/subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}' for resource groups, and '/subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{parentResourcePathIfPresent}/{resourceType}/{resourceName}' for resources.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="7c8ab-180">ロックの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-180">The name of lock.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="7c8ab-181">作成または管理ロック パラメーターを更新します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-181">Create or update management lock parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c8ab-182">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-182">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-183">作成またはスコープでの管理ロックを更新します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-183">Create or update a management lock by scope.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAtResourceGroupLevel">
      <MemberSignature Language="C#" Value="public static void DeleteAtResourceGroupLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteAtResourceGroupLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtResourceGroupLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteAtResourceGroupLevel (operations As IManagementLocksOperations, resourceGroupName As String, lockName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteAtResourceGroupLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtResourceGroupLevel (operations, resourceGroupName, lockName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-184">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-184">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7c8ab-185">ロックを含むリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-185">The name of the resource group containing the lock.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="7c8ab-186">削除するロックの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-186">The name of lock to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-187">リソース グループ レベルでの管理ロックを削除します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-187">Deletes a management lock at the resource group level.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="7c8ab-188">管理ロックを削除するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-188">To delete management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="7c8ab-189">組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-189">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAtResourceGroupLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAtResourceGroupLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAtResourceGroupLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtResourceGroupLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAtResourceGroupLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtResourceGroupLevelAsync (operations, resourceGroupName, lockName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;DeleteAtResourceGroupLevelAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-190">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7c8ab-191">ロックを含むリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-191">The name of the resource group containing the lock.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="7c8ab-192">削除するロックの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-192">The name of lock to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c8ab-193">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-193">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-194">リソース グループ レベルでの管理ロックを削除します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-194">Deletes a management lock at the resource group level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7c8ab-195">管理ロックを削除するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-195">To delete management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="7c8ab-196">組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-196">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAtResourceLevel">
      <MemberSignature Language="C#" Value="public static void DeleteAtResourceLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteAtResourceLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtResourceLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteAtResourceLevel (operations As IManagementLocksOperations, resourceGroupName As String, resourceProviderNamespace As String, parentResourcePath As String, resourceType As String, resourceName As String, lockName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteAtResourceLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtResourceLevel (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, lockName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-197">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-197">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7c8ab-198">削除すると、ロック リソースを含む、リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-198">The name of the resource group containing the resource with the lock to delete.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="7c8ab-199">リソース プロバイダーの名前空間を削除するロックを持つリソースのです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-199">The resource provider namespace of the resource with the lock to delete.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="7c8ab-200">親のリソース id です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-200">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="7c8ab-201">削除するロックを持つリソースのリソースの種類。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-201">The resource type of the resource with the lock to delete.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="7c8ab-202">ロックを削除すると、リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-202">The name of the resource with the lock to delete.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="7c8ab-203">削除するロックの名前です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-203">The name of the lock to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-204">リソースまたはリソースの下の任意のレベルのロックの管理を削除します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-204">Deletes the management lock of a resource or any level below the resource.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="7c8ab-205">管理ロックを削除するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-205">To delete management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="7c8ab-206">組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-206">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAtResourceLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAtResourceLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAtResourceLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtResourceLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAtResourceLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtResourceLevelAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, lockName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;DeleteAtResourceLevelAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-207">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-207">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7c8ab-208">削除すると、ロック リソースを含む、リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-208">The name of the resource group containing the resource with the lock to delete.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="7c8ab-209">リソース プロバイダーの名前空間を削除するロックを持つリソースのです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-209">The resource provider namespace of the resource with the lock to delete.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="7c8ab-210">親のリソース id です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-210">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="7c8ab-211">削除するロックを持つリソースのリソースの種類。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-211">The resource type of the resource with the lock to delete.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="7c8ab-212">ロックを削除すると、リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-212">The name of the resource with the lock to delete.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="7c8ab-213">削除するロックの名前です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-213">The name of the lock to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c8ab-214">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-214">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-215">リソースまたはリソースの下の任意のレベルのロックの管理を削除します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-215">Deletes the management lock of a resource or any level below the resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7c8ab-216">管理ロックを削除するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-216">To delete management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="7c8ab-217">組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-217">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAtSubscriptionLevel">
      <MemberSignature Language="C#" Value="public static void DeleteAtSubscriptionLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteAtSubscriptionLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtSubscriptionLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteAtSubscriptionLevel (operations As IManagementLocksOperations, lockName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteAtSubscriptionLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtSubscriptionLevel (operations, lockName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="lockName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-218">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-218">The operations group for this extension method.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="7c8ab-219">削除するロックの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-219">The name of lock to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-220">サブスクリプション レベルでの管理ロックを削除します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-220">Deletes the management lock at the subscription level.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="7c8ab-221">管理ロックを削除するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-221">To delete management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="7c8ab-222">組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-222">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAtSubscriptionLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAtSubscriptionLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAtSubscriptionLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtSubscriptionLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAtSubscriptionLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtSubscriptionLevelAsync (operations, lockName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;DeleteAtSubscriptionLevelAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-223">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-223">The operations group for this extension method.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="7c8ab-224">削除するロックの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-224">The name of lock to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c8ab-225">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-225">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-226">サブスクリプション レベルでの管理ロックを削除します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-226">Deletes the management lock at the subscription level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="7c8ab-227">管理ロックを削除するには、Microsoft.Authorization/* または Microsoft.Authorization/locks/* アクションへのアクセスが必要です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-227">To delete management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="7c8ab-228">組み込みロールのうち、所有者とユーザー アクセス管理者にのみこれらのアクションが許可されています。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-228">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteByScope">
      <MemberSignature Language="C#" Value="public static void DeleteByScope (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteByScope(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteByScope(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteByScope (operations As IManagementLocksOperations, scope As String, lockName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteByScope : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteByScope (operations, scope, lockName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-229">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-229">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="7c8ab-230">ロックのスコープです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-230">The scope for the lock.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="7c8ab-231">ロックの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-231">The name of lock.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-232">スコープでの管理ロックを削除します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-232">Delete a management lock by scope.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteByScopeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteByScopeAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteByScopeAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteByScopeAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteByScopeAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteByScopeAsync (operations, scope, lockName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;DeleteByScopeAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-233">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-233">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="7c8ab-234">ロックのスコープです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-234">The scope for the lock.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="7c8ab-235">ロックの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-235">The name of lock.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c8ab-236">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-236">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-237">スコープでの管理ロックを削除します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-237">Delete a management lock by scope.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAtResourceGroupLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject GetAtResourceGroupLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject GetAtResourceGroupLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtResourceGroupLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAtResourceGroupLevel (operations As IManagementLocksOperations, resourceGroupName As String, lockName As String) As ManagementLockObject" />
      <MemberSignature Language="F#" Value="static member GetAtResourceGroupLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtResourceGroupLevel (operations, resourceGroupName, lockName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-238">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-238">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7c8ab-239">ロックされているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-239">The name of the locked resource group.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="7c8ab-240">取得するロックの名前です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-240">The name of the lock to get.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-241">リソース グループ レベルでの管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-241">Gets a management lock at the resource group level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAtResourceGroupLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; GetAtResourceGroupLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; GetAtResourceGroupLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtResourceGroupLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAtResourceGroupLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtResourceGroupLevelAsync (operations, resourceGroupName, lockName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;GetAtResourceGroupLevelAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-242">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-242">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7c8ab-243">ロックされているリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-243">The name of the locked resource group.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="7c8ab-244">取得するロックの名前です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-244">The name of the lock to get.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c8ab-245">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-245">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-246">リソース グループ レベルでの管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-246">Gets a management lock at the resource group level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAtResourceLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject GetAtResourceLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject GetAtResourceLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtResourceLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAtResourceLevel (operations As IManagementLocksOperations, resourceGroupName As String, resourceProviderNamespace As String, parentResourcePath As String, resourceType As String, resourceName As String, lockName As String) As ManagementLockObject" />
      <MemberSignature Language="F#" Value="static member GetAtResourceLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtResourceLevel (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, lockName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-247">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-247">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7c8ab-248">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-248">The name of the resource group.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="7c8ab-249">リソース プロバイダーの名前空間です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-249">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="7c8ab-250">SQL データベースと同様に、一部のサービスで必要な追加のパスのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-250">An extra path parameter needed in some services, like SQL Databases.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="7c8ab-251">リソースの型。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-251">The type of the resource.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="7c8ab-252">リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-252">The name of the resource.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="7c8ab-253">ロックの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-253">The name of lock.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-254">リソースまたはリソースの下の任意のレベルの管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-254">Get the management lock of a resource or any level below resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAtResourceLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; GetAtResourceLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; GetAtResourceLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtResourceLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAtResourceLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtResourceLevelAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, lockName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;GetAtResourceLevelAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-255">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-255">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7c8ab-256">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-256">The name of the resource group.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="7c8ab-257">リソース プロバイダーの名前空間です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-257">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="7c8ab-258">SQL データベースと同様に、一部のサービスで必要な追加のパスのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-258">An extra path parameter needed in some services, like SQL Databases.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="7c8ab-259">リソースの型。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-259">The type of the resource.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="7c8ab-260">リソースの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-260">The name of the resource.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="7c8ab-261">ロックの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-261">The name of lock.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c8ab-262">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-262">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-263">リソースまたはリソースの下の任意のレベルの管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-263">Get the management lock of a resource or any level below resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAtSubscriptionLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject GetAtSubscriptionLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject GetAtSubscriptionLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtSubscriptionLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAtSubscriptionLevel (operations As IManagementLocksOperations, lockName As String) As ManagementLockObject" />
      <MemberSignature Language="F#" Value="static member GetAtSubscriptionLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtSubscriptionLevel (operations, lockName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="lockName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-264">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-264">The operations group for this extension method.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="7c8ab-265">取得するロックの名前です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-265">The name of the lock to get.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-266">サブスクリプション レベルでの管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-266">Gets a management lock at the subscription level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAtSubscriptionLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; GetAtSubscriptionLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; GetAtSubscriptionLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtSubscriptionLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAtSubscriptionLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtSubscriptionLevelAsync (operations, lockName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;GetAtSubscriptionLevelAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-267">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-267">The operations group for this extension method.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="7c8ab-268">取得するロックの名前です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-268">The name of the lock to get.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c8ab-269">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-269">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-270">サブスクリプション レベルでの管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-270">Gets a management lock at the subscription level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByScope">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject GetByScope (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject GetByScope(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetByScope(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetByScope (operations As IManagementLocksOperations, scope As String, lockName As String) As ManagementLockObject" />
      <MemberSignature Language="F#" Value="static member GetByScope : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetByScope (operations, scope, lockName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-271">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-271">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="7c8ab-272">ロックのスコープです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-272">The scope for the lock.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="7c8ab-273">ロックの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-273">The name of lock.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-274">スコープでの管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-274">Get a management lock by scope.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByScopeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; GetByScopeAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; GetByScopeAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetByScopeAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetByScopeAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetByScopeAsync (operations, scope, lockName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;GetByScopeAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-275">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-275">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="7c8ab-276">ロックのスコープです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-276">The scope for the lock.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="7c8ab-277">ロックの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-277">The name of lock.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c8ab-278">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-278">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-279">スコープでの管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-279">Get a management lock by scope.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceGroupLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtResourceGroupLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtResourceGroupLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceGroupLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAtResourceGroupLevel (operations As IManagementLocksOperations, resourceGroupName As String, Optional odataQuery As ODataQuery(Of ManagementLockObject) = null) As IPage(Of ManagementLockObject)" />
      <MemberSignature Language="F#" Value="static member ListAtResourceGroupLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceGroupLevel (operations, resourceGroupName, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-280">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-280">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7c8ab-281">取得するロックを含むリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-281">The name of the resource group containing the locks to get.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="7c8ab-282">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-282">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-283">リソース グループのすべての管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-283">Gets all the management locks for a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceGroupLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtResourceGroupLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtResourceGroupLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceGroupLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAtResourceGroupLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceGroupLevelAsync (operations, resourceGroupName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;ListAtResourceGroupLevelAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-284">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-284">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7c8ab-285">取得するロックを含むリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-285">The name of the resource group containing the locks to get.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="7c8ab-286">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-286">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c8ab-287">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-287">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-288">リソース グループのすべての管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-288">Gets all the management locks for a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceGroupLevelNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtResourceGroupLevelNext (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtResourceGroupLevelNext(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceGroupLevelNext(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAtResourceGroupLevelNext (operations As IManagementLocksOperations, nextPageLink As String) As IPage(Of ManagementLockObject)" />
      <MemberSignature Language="F#" Value="static member ListAtResourceGroupLevelNext : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceGroupLevelNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-289">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-289">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7c8ab-290">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-290">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-291">リソース グループのすべての管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-291">Gets all the management locks for a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceGroupLevelNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtResourceGroupLevelNextAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtResourceGroupLevelNextAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceGroupLevelNextAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAtResourceGroupLevelNextAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceGroupLevelNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;ListAtResourceGroupLevelNextAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-292">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-292">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7c8ab-293">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-293">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c8ab-294">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-294">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-295">リソース グループのすべての管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-295">Gets all the management locks for a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtResourceLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtResourceLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAtResourceLevel (operations As IManagementLocksOperations, resourceGroupName As String, resourceProviderNamespace As String, parentResourcePath As String, resourceType As String, resourceName As String, Optional odataQuery As ODataQuery(Of ManagementLockObject) = null) As IPage(Of ManagementLockObject)" />
      <MemberSignature Language="F#" Value="static member ListAtResourceLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceLevel (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-296">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-296">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7c8ab-297">ロックされたリソースを含むリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-297">The name of the resource group containing the locked resource.</span></span> <span data-ttu-id="7c8ab-298">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-298">The name is case insensitive.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="7c8ab-299">リソース プロバイダーの名前空間です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-299">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="7c8ab-300">親のリソース id です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-300">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="7c8ab-301">ロックされたリソースのリソースの種類。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-301">The resource type of the locked resource.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="7c8ab-302">ロックされたリソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-302">The name of the locked resource.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="7c8ab-303">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-303">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-304">リソースまたはリソースの下の任意のレベルのすべての管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-304">Gets all the management locks for a resource or any level below resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtResourceLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtResourceLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAtResourceLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceLevelAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;ListAtResourceLevelAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-305">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-305">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7c8ab-306">ロックされたリソースを含むリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-306">The name of the resource group containing the locked resource.</span></span> <span data-ttu-id="7c8ab-307">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-307">The name is case insensitive.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="7c8ab-308">リソース プロバイダーの名前空間です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-308">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="7c8ab-309">親のリソース id です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-309">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="7c8ab-310">ロックされたリソースのリソースの種類。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-310">The resource type of the locked resource.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="7c8ab-311">ロックされたリソースの名前です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-311">The name of the locked resource.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="7c8ab-312">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-312">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c8ab-313">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-313">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-314">リソースまたはリソースの下の任意のレベルのすべての管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-314">Gets all the management locks for a resource or any level below resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceLevelNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtResourceLevelNext (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtResourceLevelNext(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceLevelNext(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAtResourceLevelNext (operations As IManagementLocksOperations, nextPageLink As String) As IPage(Of ManagementLockObject)" />
      <MemberSignature Language="F#" Value="static member ListAtResourceLevelNext : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceLevelNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-315">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-315">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7c8ab-316">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-316">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-317">リソースまたはリソースの下の任意のレベルのすべての管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-317">Gets all the management locks for a resource or any level below resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceLevelNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtResourceLevelNextAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtResourceLevelNextAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceLevelNextAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAtResourceLevelNextAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceLevelNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;ListAtResourceLevelNextAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-318">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-318">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7c8ab-319">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-319">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c8ab-320">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-320">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-321">リソースまたはリソースの下の任意のレベルのすべての管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-321">Gets all the management locks for a resource or any level below resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtSubscriptionLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtSubscriptionLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtSubscriptionLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtSubscriptionLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAtSubscriptionLevel (operations As IManagementLocksOperations, Optional odataQuery As ODataQuery(Of ManagementLockObject) = null) As IPage(Of ManagementLockObject)" />
      <MemberSignature Language="F#" Value="static member ListAtSubscriptionLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtSubscriptionLevel (operations, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-322">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-322">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="7c8ab-323">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-323">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-324">サブスクリプションのすべての管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-324">Gets all the management locks for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtSubscriptionLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtSubscriptionLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtSubscriptionLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtSubscriptionLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAtSubscriptionLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtSubscriptionLevelAsync (operations, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;ListAtSubscriptionLevelAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-325">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-325">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="7c8ab-326">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-326">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c8ab-327">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-327">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-328">サブスクリプションのすべての管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-328">Gets all the management locks for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtSubscriptionLevelNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtSubscriptionLevelNext (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtSubscriptionLevelNext(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtSubscriptionLevelNext(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAtSubscriptionLevelNext (operations As IManagementLocksOperations, nextPageLink As String) As IPage(Of ManagementLockObject)" />
      <MemberSignature Language="F#" Value="static member ListAtSubscriptionLevelNext : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtSubscriptionLevelNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-329">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-329">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7c8ab-330">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-330">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-331">サブスクリプションのすべての管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-331">Gets all the management locks for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtSubscriptionLevelNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtSubscriptionLevelNextAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtSubscriptionLevelNextAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtSubscriptionLevelNextAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAtSubscriptionLevelNextAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtSubscriptionLevelNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;ListAtSubscriptionLevelNextAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7c8ab-332">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-332">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7c8ab-333">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-333">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c8ab-334">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-334">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c8ab-335">サブスクリプションのすべての管理ロックを取得します。</span><span class="sxs-lookup"><span data-stu-id="7c8ab-335">Gets all the management locks for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>