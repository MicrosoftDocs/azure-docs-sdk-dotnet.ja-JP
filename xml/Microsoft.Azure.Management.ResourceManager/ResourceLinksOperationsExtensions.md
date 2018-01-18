<Type Name="ResourceLinksOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ResourceLinksOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ResourceLinksOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ResourceLinksOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ResourceLinksOperationsExtensions = class" />
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
            <span data-ttu-id="2afe6-101">ResourceLinksOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="2afe6-101">Extension methods for ResourceLinksOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ResourceLink CreateOrUpdate (this Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, string linkId, Microsoft.Azure.Management.ResourceManager.Models.ResourceLink parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ResourceLink CreateOrUpdate(class Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, string linkId, class Microsoft.Azure.Management.ResourceManager.Models.ResourceLink parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourceLink)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IResourceLinksOperations, linkId As String, parameters As ResourceLink) As ResourceLink" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourceLink -&gt; Microsoft.Azure.Management.ResourceManager.Models.ResourceLink" Usage="Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.CreateOrUpdate (operations, linkId, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ResourceLink</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations" RefType="this" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourceLink" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2afe6-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2afe6-102">The operations group for this extension method.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="2afe6-103">リソースのリンクの完全修飾 ID です。</span><span class="sxs-lookup"><span data-stu-id="2afe6-103">The fully qualified ID of the resource link.</span></span> <span data-ttu-id="2afe6-104">形式を使用して subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/{provider-namespace}/{resource-type}/{resource-name}/Microsoft.Resources/links/{link-name/}。</span><span class="sxs-lookup"><span data-stu-id="2afe6-104">Use the format, /subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/{provider-namespace}/{resource-type}/{resource-name}/Microsoft.Resources/links/{link-name}.</span></span>
            <span data-ttu-id="2afe6-105">たとえば、/subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/myGroup/Microsoft.Web/sites/mySite/Microsoft.Resources/links/myLink</span><span class="sxs-lookup"><span data-stu-id="2afe6-105">For example, /subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/myGroup/Microsoft.Web/sites/mySite/Microsoft.Resources/links/myLink</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2afe6-106">作成またはリソースのリンクを更新するためのパラメーター。</span><span class="sxs-lookup"><span data-stu-id="2afe6-106">Parameters for creating or updating a resource link.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2afe6-107">作成するか、指定されたリソースの間のリソース リンクを更新します。</span><span class="sxs-lookup"><span data-stu-id="2afe6-107">Creates or updates a resource link between the specified resources.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, string linkId, Microsoft.Azure.Management.ResourceManager.Models.ResourceLink parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, string linkId, class Microsoft.Azure.Management.ResourceManager.Models.ResourceLink parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourceLink,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourceLink * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.CreateOrUpdateAsync (operations, linkId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations" RefType="this" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourceLink" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2afe6-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2afe6-108">The operations group for this extension method.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="2afe6-109">リソースのリンクの完全修飾 ID です。</span><span class="sxs-lookup"><span data-stu-id="2afe6-109">The fully qualified ID of the resource link.</span></span> <span data-ttu-id="2afe6-110">形式を使用して subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/{provider-namespace}/{resource-type}/{resource-name}/Microsoft.Resources/links/{link-name/}。</span><span class="sxs-lookup"><span data-stu-id="2afe6-110">Use the format, /subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/{provider-namespace}/{resource-type}/{resource-name}/Microsoft.Resources/links/{link-name}.</span></span>
            <span data-ttu-id="2afe6-111">たとえば、/subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/myGroup/Microsoft.Web/sites/mySite/Microsoft.Resources/links/myLink</span><span class="sxs-lookup"><span data-stu-id="2afe6-111">For example, /subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/myGroup/Microsoft.Web/sites/mySite/Microsoft.Resources/links/myLink</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2afe6-112">作成またはリソースのリンクを更新するためのパラメーター。</span><span class="sxs-lookup"><span data-stu-id="2afe6-112">Parameters for creating or updating a resource link.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2afe6-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2afe6-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2afe6-114">作成するか、指定されたリソースの間のリソース リンクを更新します。</span><span class="sxs-lookup"><span data-stu-id="2afe6-114">Creates or updates a resource link between the specified resources.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, string linkId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, string linkId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.Delete(Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IResourceLinksOperations, linkId As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.Delete (operations, linkId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations" RefType="this" />
        <Parameter Name="linkId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2afe6-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2afe6-115">The operations group for this extension method.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="2afe6-116">リソースのリンクの完全修飾 ID です。</span><span class="sxs-lookup"><span data-stu-id="2afe6-116">The fully qualified ID of the resource link.</span></span> <span data-ttu-id="2afe6-117">形式を使用して subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/{provider-namespace}/{resource-type}/{resource-name}/Microsoft.Resources/links/{link-name/}。</span><span class="sxs-lookup"><span data-stu-id="2afe6-117">Use the format, /subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/{provider-namespace}/{resource-type}/{resource-name}/Microsoft.Resources/links/{link-name}.</span></span>
            <span data-ttu-id="2afe6-118">たとえば、/subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/myGroup/Microsoft.Web/sites/mySite/Microsoft.Resources/links/myLink</span><span class="sxs-lookup"><span data-stu-id="2afe6-118">For example, /subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/myGroup/Microsoft.Web/sites/mySite/Microsoft.Resources/links/myLink</span></span>
            </param>
        <summary>
            <span data-ttu-id="2afe6-119">指定した ID を持つリソースのリンクを削除します</span><span class="sxs-lookup"><span data-stu-id="2afe6-119">Deletes a resource link with the specified ID.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.DeleteAsync (operations, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations" RefType="this" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2afe6-120">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2afe6-120">The operations group for this extension method.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="2afe6-121">リソースのリンクの完全修飾 ID です。</span><span class="sxs-lookup"><span data-stu-id="2afe6-121">The fully qualified ID of the resource link.</span></span> <span data-ttu-id="2afe6-122">形式を使用して subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/{provider-namespace}/{resource-type}/{resource-name}/Microsoft.Resources/links/{link-name/}。</span><span class="sxs-lookup"><span data-stu-id="2afe6-122">Use the format, /subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/{provider-namespace}/{resource-type}/{resource-name}/Microsoft.Resources/links/{link-name}.</span></span>
            <span data-ttu-id="2afe6-123">たとえば、/subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/myGroup/Microsoft.Web/sites/mySite/Microsoft.Resources/links/myLink</span><span class="sxs-lookup"><span data-stu-id="2afe6-123">For example, /subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/myGroup/Microsoft.Web/sites/mySite/Microsoft.Resources/links/myLink</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2afe6-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2afe6-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2afe6-125">指定した ID を持つリソースのリンクを削除します</span><span class="sxs-lookup"><span data-stu-id="2afe6-125">Deletes a resource link with the specified ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ResourceLink Get (this Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, string linkId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ResourceLink Get(class Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, string linkId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.Get(Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IResourceLinksOperations, linkId As String) As ResourceLink" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ResourceLink" Usage="Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.Get (operations, linkId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ResourceLink</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations" RefType="this" />
        <Parameter Name="linkId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2afe6-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2afe6-126">The operations group for this extension method.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="2afe6-127">リソースのリンクの完全修飾 Id です。</span><span class="sxs-lookup"><span data-stu-id="2afe6-127">The fully qualified Id of the resource link.</span></span> <span data-ttu-id="2afe6-128">たとえば、/subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/myGroup/Microsoft.Web/sites/mySite/Microsoft.Resources/links/myLink</span><span class="sxs-lookup"><span data-stu-id="2afe6-128">For example, /subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/myGroup/Microsoft.Web/sites/mySite/Microsoft.Resources/links/myLink</span></span>
            </param>
        <summary>
            <span data-ttu-id="2afe6-129">指定した ID を持つリソースのリンクを取得します。</span><span class="sxs-lookup"><span data-stu-id="2afe6-129">Gets a resource link with the specified ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, string linkId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, string linkId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.GetAsync (operations, linkId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations" RefType="this" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2afe6-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2afe6-130">The operations group for this extension method.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="2afe6-131">リソースのリンクの完全修飾 Id です。</span><span class="sxs-lookup"><span data-stu-id="2afe6-131">The fully qualified Id of the resource link.</span></span> <span data-ttu-id="2afe6-132">たとえば、/subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/myGroup/Microsoft.Web/sites/mySite/Microsoft.Resources/links/myLink</span><span class="sxs-lookup"><span data-stu-id="2afe6-132">For example, /subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/myGroup/Microsoft.Web/sites/mySite/Microsoft.Resources/links/myLink</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2afe6-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2afe6-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2afe6-134">指定した ID を持つリソースのリンクを取得します。</span><span class="sxs-lookup"><span data-stu-id="2afe6-134">Gets a resource link with the specified ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtSourceScope">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt; ListAtSourceScope (this Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, string scope, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt; ListAtSourceScope(class Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, string scope, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.ListAtSourceScope(Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAtSourceScope (operations As IResourceLinksOperations, scope As String, Optional odataQuery As ODataQuery(Of ResourceLinkFilter) = null) As IPage(Of ResourceLink)" />
      <MemberSignature Language="F#" Value="static member ListAtSourceScope : Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.ListAtSourceScope (operations, scope, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2afe6-135">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2afe6-135">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="2afe6-136">リソースのリンクを取得するためのスコープの完全修飾 ID です。</span><span class="sxs-lookup"><span data-stu-id="2afe6-136">The fully qualified ID of the scope for getting the resource links.</span></span> <span data-ttu-id="2afe6-137">たとえば、リソースへのリンクとリソース グループの下の一覧を表示、サブスクリプション/00000000-0000-0000-0000-000000000000/resourceGroups/myGroup にスコープを設定します。</span><span class="sxs-lookup"><span data-stu-id="2afe6-137">For example, to list resource links at and under a resource group, set the scope to /subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/myGroup.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="2afe6-138">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="2afe6-138">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2afe6-139">指定されたソース スコープより下位のリソース リンクの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="2afe6-139">Gets a list of resource links at and below the specified source scope.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtSourceScopeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;&gt; ListAtSourceScopeAsync (this Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, string scope, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;&gt; ListAtSourceScopeAsync(class Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, string scope, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.ListAtSourceScopeAsync(Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAtSourceScopeAsync : Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.ListAtSourceScopeAsync (operations, scope, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions/&lt;ListAtSourceScopeAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2afe6-140">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2afe6-140">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="2afe6-141">リソースのリンクを取得するためのスコープの完全修飾 ID です。</span><span class="sxs-lookup"><span data-stu-id="2afe6-141">The fully qualified ID of the scope for getting the resource links.</span></span> <span data-ttu-id="2afe6-142">たとえば、リソースへのリンクとリソース グループの下の一覧を表示、サブスクリプション/00000000-0000-0000-0000-000000000000/resourceGroups/myGroup にスコープを設定します。</span><span class="sxs-lookup"><span data-stu-id="2afe6-142">For example, to list resource links at and under a resource group, set the scope to /subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/myGroup.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="2afe6-143">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="2afe6-143">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2afe6-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2afe6-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2afe6-145">指定されたソース スコープより下位のリソース リンクの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="2afe6-145">Gets a list of resource links at and below the specified source scope.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtSourceScopeNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt; ListAtSourceScopeNext (this Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt; ListAtSourceScopeNext(class Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.ListAtSourceScopeNext(Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAtSourceScopeNext (operations As IResourceLinksOperations, nextPageLink As String) As IPage(Of ResourceLink)" />
      <MemberSignature Language="F#" Value="static member ListAtSourceScopeNext : Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.ListAtSourceScopeNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2afe6-146">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2afe6-146">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="2afe6-147">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="2afe6-147">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2afe6-148">指定されたソース スコープより下位のリソース リンクの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="2afe6-148">Gets a list of resource links at and below the specified source scope.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtSourceScopeNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;&gt; ListAtSourceScopeNextAsync (this Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;&gt; ListAtSourceScopeNextAsync(class Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.ListAtSourceScopeNextAsync(Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAtSourceScopeNextAsync : Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.ListAtSourceScopeNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions/&lt;ListAtSourceScopeNextAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2afe6-149">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2afe6-149">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="2afe6-150">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="2afe6-150">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2afe6-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2afe6-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2afe6-152">指定されたソース スコープより下位のリソース リンクの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="2afe6-152">Gets a list of resource links at and below the specified source scope.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtSubscription">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt; ListAtSubscription (this Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt; ListAtSubscription(class Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.ListAtSubscription(Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAtSubscription (operations As IResourceLinksOperations, Optional odataQuery As ODataQuery(Of ResourceLinkFilter) = null) As IPage(Of ResourceLink)" />
      <MemberSignature Language="F#" Value="static member ListAtSubscription : Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.ListAtSubscription (operations, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2afe6-153">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2afe6-153">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="2afe6-154">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="2afe6-154">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2afe6-155">サブスクリプションのすべてのリンクされたリソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="2afe6-155">Gets all the linked resources for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtSubscriptionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;&gt; ListAtSubscriptionAsync (this Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;&gt; ListAtSubscriptionAsync(class Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.ListAtSubscriptionAsync(Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAtSubscriptionAsync : Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.ListAtSubscriptionAsync (operations, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions/&lt;ListAtSubscriptionAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLinkFilter&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2afe6-156">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2afe6-156">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="2afe6-157">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="2afe6-157">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2afe6-158">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2afe6-158">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2afe6-159">サブスクリプションのすべてのリンクされたリソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="2afe6-159">Gets all the linked resources for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtSubscriptionNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt; ListAtSubscriptionNext (this Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt; ListAtSubscriptionNext(class Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.ListAtSubscriptionNext(Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAtSubscriptionNext (operations As IResourceLinksOperations, nextPageLink As String) As IPage(Of ResourceLink)" />
      <MemberSignature Language="F#" Value="static member ListAtSubscriptionNext : Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.ListAtSubscriptionNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2afe6-160">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2afe6-160">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="2afe6-161">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="2afe6-161">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2afe6-162">サブスクリプションのすべてのリンクされたリソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="2afe6-162">Gets all the linked resources for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtSubscriptionNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;&gt; ListAtSubscriptionNextAsync (this Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;&gt; ListAtSubscriptionNextAsync(class Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.ListAtSubscriptionNextAsync(Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAtSubscriptionNextAsync : Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions.ListAtSubscriptionNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourceLinksOperationsExtensions/&lt;ListAtSubscriptionNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ResourceLink&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourceLinksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2afe6-163">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="2afe6-163">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="2afe6-164">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="2afe6-164">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2afe6-165">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="2afe6-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2afe6-166">サブスクリプションのすべてのリンクされたリソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="2afe6-166">Gets all the linked resources for the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>