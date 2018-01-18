<Type Name="ResourceGroupsOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ResourceGroupsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ResourceGroupsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ResourceGroupsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ResourceGroupsOperationsExtensions = class" />
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
            <span data-ttu-id="218d3-101">ResourceGroupsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="218d3-101">Extension methods for ResourceGroupsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="218d3-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="218d3-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="218d3-103">削除するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="218d3-103">The name of the resource group to be deleted.</span></span> <span data-ttu-id="218d3-104">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="218d3-104">The name is case insensitive.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="218d3-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="218d3-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="218d3-106">リソース グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="218d3-106">Delete resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckExistenceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; CheckExistenceAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; CheckExistenceAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.CheckExistenceAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckExistenceAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.CheckExistenceAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions/&lt;CheckExistenceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="218d3-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="218d3-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="218d3-108">確認するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="218d3-108">The name of the resource group to check.</span></span> <span data-ttu-id="218d3-109">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="218d3-109">The name is case insensitive.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="218d3-110">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="218d3-110">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="218d3-111">リソース グループが存在するかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="218d3-111">Checks whether resource group exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations * string * Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="218d3-112">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="218d3-112">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="218d3-113">作成または更新するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="218d3-113">The name of the resource group to be created or updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="218d3-114">作成または更新リソース グループのサービス操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="218d3-114">Parameters supplied to the create or update resource group service operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="218d3-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="218d3-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="218d3-116">リソース グループを作成します。</span><span class="sxs-lookup"><span data-stu-id="218d3-116">Create a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.DeleteAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="218d3-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="218d3-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="218d3-118">削除するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="218d3-118">The name of the resource group to be deleted.</span></span> <span data-ttu-id="218d3-119">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="218d3-119">The name is case insensitive.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="218d3-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="218d3-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="218d3-121">リソース グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="218d3-121">Delete resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportTemplateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupExportResultInner&gt; ExportTemplateAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, Microsoft.Azure.Management.ResourceManager.Fluent.Models.ExportTemplateRequestInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupExportResultInner&gt; ExportTemplateAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ExportTemplateRequestInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.ExportTemplateAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Fluent.Models.ExportTemplateRequestInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExportTemplateAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations * string * Microsoft.Azure.Management.ResourceManager.Fluent.Models.ExportTemplateRequestInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupExportResultInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.ExportTemplateAsync (operations, resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions/&lt;ExportTemplateAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupExportResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ExportTemplateRequestInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="218d3-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="218d3-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="218d3-123">作成または更新するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="218d3-123">The name of the resource group to be created or updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="218d3-124">エクスポート テンプレート リソース グループの操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="218d3-124">Parameters supplied to the export template resource group operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="218d3-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="218d3-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="218d3-126">テンプレートとして指定されたリソース グループをキャプチャします。</span><span class="sxs-lookup"><span data-stu-id="218d3-126">Captures the specified resource group as a template.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.GetAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions/&lt;GetAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="218d3-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="218d3-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="218d3-128">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="218d3-128">The name of the resource group to get.</span></span> <span data-ttu-id="218d3-129">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="218d3-129">The name is case insensitive.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="218d3-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="218d3-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="218d3-131">リソース グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="218d3-131">Get a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupFilterInner&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupFilterInner&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupFilterInner},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupFilterInner&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.ListAsync (operations, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions/&lt;ListAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupFilterInner&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="218d3-132">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="218d3-132">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="218d3-133">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="218d3-133">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="218d3-134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="218d3-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="218d3-135">リソース グループのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="218d3-135">Gets a collection of resource groups.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions/&lt;ListNextAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="218d3-136">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="218d3-136">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="218d3-137">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="218d3-137">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="218d3-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="218d3-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="218d3-139">リソース グループのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="218d3-139">Gets a collection of resource groups.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListResourcesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;&gt; ListResourcesAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceFilterInner&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;&gt; ListResourcesAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceFilterInner&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.ListResourcesAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceFilterInner},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListResourcesAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceFilterInner&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.ListResourcesAsync (operations, resourceGroupName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions/&lt;ListResourcesAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceFilterInner&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="218d3-140">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="218d3-140">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="218d3-141">クエリ パラメーター。</span><span class="sxs-lookup"><span data-stu-id="218d3-141">Query parameters.</span></span> <span data-ttu-id="218d3-142">Null が渡される場合は、すべてのリソース グループを返します。</span><span class="sxs-lookup"><span data-stu-id="218d3-142">If null is passed returns all resource groups.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="218d3-143">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="218d3-143">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="218d3-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="218d3-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="218d3-145">すべてのサブスクリプションの下にあるリソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="218d3-145">Get all of the resources under a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListResourcesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;&gt; ListResourcesNextAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;&gt; ListResourcesNextAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.ListResourcesNextAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListResourcesNextAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.ListResourcesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions/&lt;ListResourcesNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.GenericResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="218d3-146">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="218d3-146">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="218d3-147">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="218d3-147">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="218d3-148">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="218d3-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="218d3-149">すべてのサブスクリプションの下にあるリソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="218d3-149">Get all of the resources under a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt; PatchAsync (this Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt; PatchAsync(class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.PatchAsync(Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations,System.String,Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations * string * Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions.PatchAsync (operations, resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroupsOperationsExtensions/&lt;PatchAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroupsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Models.ResourceGroupInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="218d3-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="218d3-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="218d3-151">作成または更新するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="218d3-151">The name of the resource group to be created or updated.</span></span> <span data-ttu-id="218d3-152">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="218d3-152">The name is case insensitive.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="218d3-153">更新状態リソース グループのサービス操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="218d3-153">Parameters supplied to the update state resource group service operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="218d3-154">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="218d3-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="218d3-155">リソース グループは、グループ アドレスに対する単純な PATCH 操作で更新できます。</span><span class="sxs-lookup"><span data-stu-id="218d3-155">Resource groups can be updated through a simple PATCH operation to a group address.</span></span> <span data-ttu-id="218d3-156">要求の形式と同じではリソース グループを作成するためのフィールドが指定されていない場合、現在の値が引き継がれます。</span><span class="sxs-lookup"><span data-stu-id="218d3-156">The format of the request is the same as that for creating a resource groups, though if a field is unspecified current value will be carried over.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>