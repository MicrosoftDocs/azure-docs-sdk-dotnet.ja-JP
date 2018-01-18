<Type Name="ResourceGroupsOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ResourceGroupsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ResourceGroupsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ResourceGroupsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ResourceGroupsOperationsExtensions = class" />
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
            <span data-ttu-id="422e3-101">ResourceGroupsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="422e3-101">Extension methods for ResourceGroupsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IResourceGroupsOperations, resourceGroupName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.BeginDelete (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="422e3-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="422e3-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="422e3-103">削除するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="422e3-103">The name of the resource group to delete.</span></span> <span data-ttu-id="422e3-104">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="422e3-104">The name is case insensitive.</span></span>
            </param>
        <summary>
            <span data-ttu-id="422e3-105">リソース グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="422e3-105">Deletes a resource group.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="422e3-106">リソース グループを削除するとそのすべてのリソースも削除されます。</span><span class="sxs-lookup"><span data-stu-id="422e3-106">When you delete a resource group, all of its resources are also deleted.</span></span>
            <span data-ttu-id="422e3-107">リソース グループを削除すると、すべてのテンプレート デプロイの削除され、現在格納されている操作。</span><span class="sxs-lookup"><span data-stu-id="422e3-107">Deleting a resource group deletes all of its template deployments and currently stored operations.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="422e3-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="422e3-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="422e3-109">削除するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="422e3-109">The name of the resource group to delete.</span></span> <span data-ttu-id="422e3-110">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="422e3-110">The name is case insensitive.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="422e3-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="422e3-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="422e3-112">リソース グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="422e3-112">Deletes a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="422e3-113">リソース グループを削除するとそのすべてのリソースも削除されます。</span><span class="sxs-lookup"><span data-stu-id="422e3-113">When you delete a resource group, all of its resources are also deleted.</span></span>
            <span data-ttu-id="422e3-114">リソース グループを削除すると、すべてのテンプレート デプロイの削除され、現在格納されている操作。</span><span class="sxs-lookup"><span data-stu-id="422e3-114">Deleting a resource group deletes all of its template deployments and currently stored operations.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckExistence">
      <MemberSignature Language="C#" Value="public static bool CheckExistence (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool CheckExistence(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.CheckExistence(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckExistence (operations As IResourceGroupsOperations, resourceGroupName As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member CheckExistence : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string -&gt; bool" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.CheckExistence (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="422e3-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="422e3-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="422e3-116">確認するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="422e3-116">The name of the resource group to check.</span></span> <span data-ttu-id="422e3-117">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="422e3-117">The name is case insensitive.</span></span>
            </param>
        <summary>
            <span data-ttu-id="422e3-118">リソース グループが存在するかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="422e3-118">Checks whether a resource group exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckExistenceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; CheckExistenceAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; CheckExistenceAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.CheckExistenceAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckExistenceAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.CheckExistenceAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;CheckExistenceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="422e3-119">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="422e3-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="422e3-120">確認するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="422e3-120">The name of the resource group to check.</span></span> <span data-ttu-id="422e3-121">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="422e3-121">The name is case insensitive.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="422e3-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="422e3-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="422e3-123">リソース グループが存在するかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="422e3-123">Checks whether a resource group exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup CreateOrUpdate (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup CreateOrUpdate(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IResourceGroupsOperations, resourceGroupName As String, parameters As ResourceGroup) As ResourceGroup" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup -&gt; Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="422e3-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="422e3-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="422e3-125">作成または更新するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="422e3-125">The name of the resource group to create or update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="422e3-126">パラメーターは、作成に指定されたまたはリソース グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="422e3-126">Parameters supplied to the create or update a resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="422e3-127">リソース グループを作成または更新します。</span><span class="sxs-lookup"><span data-stu-id="422e3-127">Creates or updates a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="422e3-128">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="422e3-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="422e3-129">作成または更新するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="422e3-129">The name of the resource group to create or update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="422e3-130">パラメーターは、作成に指定されたまたはリソース グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="422e3-130">Parameters supplied to the create or update a resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="422e3-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="422e3-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="422e3-132">リソース グループを作成または更新します。</span><span class="sxs-lookup"><span data-stu-id="422e3-132">Creates or updates a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.Delete(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IResourceGroupsOperations, resourceGroupName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.Delete (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="422e3-133">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="422e3-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="422e3-134">削除するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="422e3-134">The name of the resource group to delete.</span></span> <span data-ttu-id="422e3-135">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="422e3-135">The name is case insensitive.</span></span>
            </param>
        <summary>
            <span data-ttu-id="422e3-136">リソース グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="422e3-136">Deletes a resource group.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="422e3-137">リソース グループを削除するとそのすべてのリソースも削除されます。</span><span class="sxs-lookup"><span data-stu-id="422e3-137">When you delete a resource group, all of its resources are also deleted.</span></span>
            <span data-ttu-id="422e3-138">リソース グループを削除すると、すべてのテンプレート デプロイの削除され、現在格納されている操作。</span><span class="sxs-lookup"><span data-stu-id="422e3-138">Deleting a resource group deletes all of its template deployments and currently stored operations.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.DeleteAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="422e3-139">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="422e3-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="422e3-140">削除するリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="422e3-140">The name of the resource group to delete.</span></span> <span data-ttu-id="422e3-141">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="422e3-141">The name is case insensitive.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="422e3-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="422e3-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="422e3-143">リソース グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="422e3-143">Deletes a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="422e3-144">リソース グループを削除するとそのすべてのリソースも削除されます。</span><span class="sxs-lookup"><span data-stu-id="422e3-144">When you delete a resource group, all of its resources are also deleted.</span></span>
            <span data-ttu-id="422e3-145">リソース グループを削除すると、すべてのテンプレート デプロイの削除され、現在格納されている操作。</span><span class="sxs-lookup"><span data-stu-id="422e3-145">Deleting a resource group deletes all of its template deployments and currently stored operations.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportTemplate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult ExportTemplate (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult ExportTemplate(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ExportTemplate(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ExportTemplate (operations As IResourceGroupsOperations, resourceGroupName As String, parameters As ExportTemplateRequest) As ResourceGroupExportResult" />
      <MemberSignature Language="F#" Value="static member ExportTemplate : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest -&gt; Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ExportTemplate (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="422e3-146">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="422e3-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="422e3-147">テンプレートとしてエクスポートするリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="422e3-147">The name of the resource group to export as a template.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="422e3-148">テンプレートのエクスポートのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="422e3-148">Parameters for exporting the template.</span></span>
            </param>
        <summary>
            <span data-ttu-id="422e3-149">テンプレートとして指定されたリソース グループをキャプチャします。</span><span class="sxs-lookup"><span data-stu-id="422e3-149">Captures the specified resource group as a template.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportTemplateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult&gt; ExportTemplateAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult&gt; ExportTemplateAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ExportTemplateAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExportTemplateAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ExportTemplateAsync (operations, resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;ExportTemplateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupExportResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ExportTemplateRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="422e3-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="422e3-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="422e3-151">テンプレートとしてエクスポートするリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="422e3-151">The name of the resource group to export as a template.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="422e3-152">テンプレートのエクスポートのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="422e3-152">Parameters for exporting the template.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="422e3-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="422e3-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="422e3-154">テンプレートとして指定されたリソース グループをキャプチャします。</span><span class="sxs-lookup"><span data-stu-id="422e3-154">Captures the specified resource group as a template.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup Get (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup Get(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.Get(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IResourceGroupsOperations, resourceGroupName As String) As ResourceGroup" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.Get (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="422e3-155">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="422e3-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="422e3-156">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="422e3-156">The name of the resource group to get.</span></span> <span data-ttu-id="422e3-157">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="422e3-157">The name is case insensitive.</span></span>
            </param>
        <summary>
            <span data-ttu-id="422e3-158">リソース グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="422e3-158">Gets a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.GetAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="422e3-159">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="422e3-159">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="422e3-160">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="422e3-160">The name of the resource group to get.</span></span> <span data-ttu-id="422e3-161">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="422e3-161">The name is case insensitive.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="422e3-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="422e3-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="422e3-163">リソース グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="422e3-163">Gets a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; List (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; List(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.List(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IResourceGroupsOperations, Optional odataQuery As ODataQuery(Of ResourceGroupFilter) = null) As IPage(Of ResourceGroup)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.List (operations, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="422e3-164">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="422e3-164">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="422e3-165">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="422e3-165">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="422e3-166">サブスクリプションのすべてのリソース グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="422e3-166">Gets all the resource groups for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ListAsync (operations, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;ListAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupFilter&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="422e3-167">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="422e3-167">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="422e3-168">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="422e3-168">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="422e3-169">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="422e3-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="422e3-170">サブスクリプションのすべてのリソース グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="422e3-170">Gets all the resource groups for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; ListNext (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; ListNext(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ListNext(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IResourceGroupsOperations, nextPageLink As String) As IPage(Of ResourceGroup)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="422e3-171">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="422e3-171">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="422e3-172">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="422e3-172">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="422e3-173">サブスクリプションのすべてのリソース グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="422e3-173">Gets all the resource groups for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;ListNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="422e3-174">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="422e3-174">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="422e3-175">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="422e3-175">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="422e3-176">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="422e3-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="422e3-177">サブスクリプションのすべてのリソース グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="422e3-177">Gets all the resource groups for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup Update (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup Update(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.Update(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IResourceGroupsOperations, resourceGroupName As String, parameters As ResourceGroupPatchable) As ResourceGroup" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable -&gt; Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.Update (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="422e3-178">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="422e3-178">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="422e3-179">更新するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="422e3-179">The name of the resource group to update.</span></span> <span data-ttu-id="422e3-180">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="422e3-180">The name is case insensitive.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="422e3-181">リソース グループの更新に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="422e3-181">Parameters supplied to update a resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="422e3-182">リソース グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="422e3-182">Updates a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="422e3-183">リソース グループは、グループ アドレスに対する単純な PATCH 操作で更新できます。</span><span class="sxs-lookup"><span data-stu-id="422e3-183">Resource groups can be updated through a simple PATCH operation to a group address.</span></span> <span data-ttu-id="422e3-184">要求の形式は、リソース グループを作成すると同じです。</span><span class="sxs-lookup"><span data-stu-id="422e3-184">The format of the request is the same as that for creating a resource group.</span></span> <span data-ttu-id="422e3-185">フィールドが指定されていない場合は、現在の値が保持されます。</span><span class="sxs-lookup"><span data-stu-id="422e3-185">If a field is unspecified, the current value is retained.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; UpdateAsync (this Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt; UpdateAsync(class Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions.UpdateAsync (operations, resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceGroupsOperationsExtensions/&lt;UpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourceGroupPatchable" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="422e3-186">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="422e3-186">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="422e3-187">更新するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="422e3-187">The name of the resource group to update.</span></span> <span data-ttu-id="422e3-188">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="422e3-188">The name is case insensitive.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="422e3-189">リソース グループの更新に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="422e3-189">Parameters supplied to update a resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="422e3-190">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="422e3-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="422e3-191">リソース グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="422e3-191">Updates a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="422e3-192">リソース グループは、グループ アドレスに対する単純な PATCH 操作で更新できます。</span><span class="sxs-lookup"><span data-stu-id="422e3-192">Resource groups can be updated through a simple PATCH operation to a group address.</span></span> <span data-ttu-id="422e3-193">要求の形式は、リソース グループを作成すると同じです。</span><span class="sxs-lookup"><span data-stu-id="422e3-193">The format of the request is the same as that for creating a resource group.</span></span> <span data-ttu-id="422e3-194">フィールドが指定されていない場合は、現在の値が保持されます。</span><span class="sxs-lookup"><span data-stu-id="422e3-194">If a field is unspecified, the current value is retained.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>