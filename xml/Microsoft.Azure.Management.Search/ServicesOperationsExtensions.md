<Type Name="ServicesOperationsExtensions" FullName="Microsoft.Azure.Management.Search.ServicesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ServicesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServicesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Search.ServicesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ServicesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ServicesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0a74d-101">ServicesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="0a74d-101">Extension methods for ServicesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckNameAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput CheckNameAvailability (this Microsoft.Azure.Management.Search.IServicesOperations operations, string name, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput CheckNameAvailability(class Microsoft.Azure.Management.Search.IServicesOperations operations, string name, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.CheckNameAvailability(Microsoft.Azure.Management.Search.IServicesOperations,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailability : Microsoft.Azure.Management.Search.IServicesOperations * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.CheckNameAvailability (operations, name, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0a74d-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0a74d-102">The operations group for this extension method.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="0a74d-103">検証する検索サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="0a74d-103">The Search service name to validate.</span></span> <span data-ttu-id="0a74d-104">検索サービス名は、小文字、数字、ダッシュのみを含める必要があります、最初の 2 つ、または最後の 1 文字としてダッシュを使用することはできません、連続するダッシュ文字を含めることはできません、および 2 ~ 60 文字の長さの間である必要がありますをします。</span><span class="sxs-lookup"><span data-stu-id="0a74d-104">Search service names must only contain lowercase letters, digits or dashes, cannot use dash as the first two or last one characters, cannot contain consecutive dashes, and must be between 2 and 60 characters in length.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="0a74d-105">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="0a74d-105">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="0a74d-106">指定した検索サービス名が使用できるかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="0a74d-106">Checks whether or not the given Search service name is available for use.</span></span>
            <span data-ttu-id="0a74d-107">サービス URI の一部であるために、検索サービス名がグローバルに一意にする必要があります (https://&lt;名前&gt;。 &lt;name&gt;.search.windows.net)。</span><span class="sxs-lookup"><span data-stu-id="0a74d-107">Search service names must be globally unique since they are part of the service URI (https://&lt;name&gt;.search.windows.net).</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput&gt; CheckNameAvailabilityAsync (this Microsoft.Azure.Management.Search.IServicesOperations operations, string name, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput&gt; CheckNameAvailabilityAsync(class Microsoft.Azure.Management.Search.IServicesOperations operations, string name, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.CheckNameAvailabilityAsync(Microsoft.Azure.Management.Search.IServicesOperations,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityAsync : Microsoft.Azure.Management.Search.IServicesOperations * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput&gt;" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.CheckNameAvailabilityAsync (operations, name, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.ServicesOperationsExtensions/&lt;CheckNameAvailabilityAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0a74d-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0a74d-108">The operations group for this extension method.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="0a74d-109">検証する検索サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="0a74d-109">The Search service name to validate.</span></span> <span data-ttu-id="0a74d-110">検索サービス名は、小文字、数字、ダッシュのみを含める必要があります、最初の 2 つ、または最後の 1 文字としてダッシュを使用することはできません、連続するダッシュ文字を含めることはできません、および 2 ~ 60 文字の長さの間である必要がありますをします。</span><span class="sxs-lookup"><span data-stu-id="0a74d-110">Search service names must only contain lowercase letters, digits or dashes, cannot use dash as the first two or last one characters, cannot contain consecutive dashes, and must be between 2 and 60 characters in length.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="0a74d-111">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="0a74d-111">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0a74d-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0a74d-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0a74d-113">指定した検索サービス名が使用できるかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="0a74d-113">Checks whether or not the given Search service name is available for use.</span></span>
            <span data-ttu-id="0a74d-114">サービス URI の一部であるために、検索サービス名がグローバルに一意にする必要があります (https://&lt;名前&gt;。 &lt;name&gt;.search.windows.net)。</span><span class="sxs-lookup"><span data-stu-id="0a74d-114">Search service names must be globally unique since they are part of the service URI (https://&lt;name&gt;.search.windows.net).</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Search.Models.SearchService CreateOrUpdate (this Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchService service, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Search.Models.SearchService CreateOrUpdate(class Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchService service, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Search.IServicesOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchService,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Search.IServicesOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchService * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; Microsoft.Azure.Management.Search.Models.SearchService" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, searchServiceName, service, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Search.Models.SearchService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="service" Type="Microsoft.Azure.Management.Search.Models.SearchService" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0a74d-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0a74d-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0a74d-116">現在のサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0a74d-116">The name of the resource group within the current subscription.</span></span> <span data-ttu-id="0a74d-117">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="0a74d-117">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="0a74d-118">Azure Search サービスを作成または更新の名前。</span><span class="sxs-lookup"><span data-stu-id="0a74d-118">The name of the Azure Search service to create or update.</span></span> <span data-ttu-id="0a74d-119">検索サービス名は、小文字、数字、ダッシュのみを含める必要があります、最初の 2 つ、または最後の 1 文字としてダッシュを使用することはできません、連続するダッシュ文字を含めることはできません、および 2 ~ 60 文字の長さの間である必要がありますをします。</span><span class="sxs-lookup"><span data-stu-id="0a74d-119">Search service names must only contain lowercase letters, digits or dashes, cannot use dash as the first two or last one characters, cannot contain consecutive dashes, and must be between 2 and 60 characters in length.</span></span> <span data-ttu-id="0a74d-120">サービス URI の一部であるために、検索サービス名がグローバルに一意にする必要があります (https://&lt;名前&gt;。 &lt;name&gt;.search.windows.net)。</span><span class="sxs-lookup"><span data-stu-id="0a74d-120">Search service names must be globally unique since they are part of the service URI (https://&lt;name&gt;.search.windows.net).</span></span> <span data-ttu-id="0a74d-121">サービスの作成後は、サービス名を変更できません。</span><span class="sxs-lookup"><span data-stu-id="0a74d-121">You cannot change the service name after the service is created.</span></span>
            </param>
        <param name="service">
            <span data-ttu-id="0a74d-122">Search サービスを作成または更新の定義。</span><span class="sxs-lookup"><span data-stu-id="0a74d-122">The definition of the Search service to create or update.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="0a74d-123">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="0a74d-123">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="0a74d-124">作成するか、特定のリソース グループ内の Search サービスを更新します。</span><span class="sxs-lookup"><span data-stu-id="0a74d-124">Creates or updates a Search service in the given resource group.</span></span> <span data-ttu-id="0a74d-125">Search サービスが既に存在する場合、すべてのプロパティが指定された値で更新されます。</span><span class="sxs-lookup"><span data-stu-id="0a74d-125">If the Search service already exists, all properties will be updated with the given values.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchService service, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Search.Models.SearchService&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchService service, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Search.IServicesOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchService,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Search.IServicesOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchService * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, searchServiceName, service, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.ServicesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="service" Type="Microsoft.Azure.Management.Search.Models.SearchService" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0a74d-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0a74d-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0a74d-127">現在のサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0a74d-127">The name of the resource group within the current subscription.</span></span> <span data-ttu-id="0a74d-128">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="0a74d-128">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="0a74d-129">Azure Search サービスを作成または更新の名前。</span><span class="sxs-lookup"><span data-stu-id="0a74d-129">The name of the Azure Search service to create or update.</span></span> <span data-ttu-id="0a74d-130">検索サービス名は、小文字、数字、ダッシュのみを含める必要があります、最初の 2 つ、または最後の 1 文字としてダッシュを使用することはできません、連続するダッシュ文字を含めることはできません、および 2 ~ 60 文字の長さの間である必要がありますをします。</span><span class="sxs-lookup"><span data-stu-id="0a74d-130">Search service names must only contain lowercase letters, digits or dashes, cannot use dash as the first two or last one characters, cannot contain consecutive dashes, and must be between 2 and 60 characters in length.</span></span> <span data-ttu-id="0a74d-131">サービス URI の一部であるために、検索サービス名がグローバルに一意にする必要があります (https://&lt;名前&gt;。 &lt;name&gt;.search.windows.net)。</span><span class="sxs-lookup"><span data-stu-id="0a74d-131">Search service names must be globally unique since they are part of the service URI (https://&lt;name&gt;.search.windows.net).</span></span> <span data-ttu-id="0a74d-132">サービスの作成後は、サービス名を変更できません。</span><span class="sxs-lookup"><span data-stu-id="0a74d-132">You cannot change the service name after the service is created.</span></span>
            </param>
        <param name="service">
            <span data-ttu-id="0a74d-133">Search サービスを作成または更新の定義。</span><span class="sxs-lookup"><span data-stu-id="0a74d-133">The definition of the Search service to create or update.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="0a74d-134">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="0a74d-134">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0a74d-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0a74d-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0a74d-136">作成するか、特定のリソース グループ内の Search サービスを更新します。</span><span class="sxs-lookup"><span data-stu-id="0a74d-136">Creates or updates a Search service in the given resource group.</span></span> <span data-ttu-id="0a74d-137">Search サービスが既に存在する場合、すべてのプロパティが指定された値で更新されます。</span><span class="sxs-lookup"><span data-stu-id="0a74d-137">If the Search service already exists, all properties will be updated with the given values.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.Delete(Microsoft.Azure.Management.Search.IServicesOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Search.IServicesOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; unit" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.Delete (operations, resourceGroupName, searchServiceName, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0a74d-138">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0a74d-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0a74d-139">現在のサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0a74d-139">The name of the resource group within the current subscription.</span></span> <span data-ttu-id="0a74d-140">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="0a74d-140">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="0a74d-141">指定されたリソース グループに関連付けられている Azure Search サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="0a74d-141">The name of the Azure Search service associated with the specified resource group.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="0a74d-142">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="0a74d-142">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="0a74d-143">関連付けられているリソースと、特定のリソース グループ内の Search サービスを削除します。</span><span class="sxs-lookup"><span data-stu-id="0a74d-143">Deletes a Search service in the given resource group, along with its associated resources.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Search.IServicesOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Search.IServicesOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.DeleteAsync (operations, resourceGroupName, searchServiceName, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.ServicesOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0a74d-144">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0a74d-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0a74d-145">現在のサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0a74d-145">The name of the resource group within the current subscription.</span></span> <span data-ttu-id="0a74d-146">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="0a74d-146">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="0a74d-147">指定されたリソース グループに関連付けられている Azure Search サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="0a74d-147">The name of the Azure Search service associated with the specified resource group.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="0a74d-148">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="0a74d-148">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0a74d-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0a74d-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0a74d-150">関連付けられているリソースと、特定のリソース グループ内の Search サービスを削除します。</span><span class="sxs-lookup"><span data-stu-id="0a74d-150">Deletes a Search service in the given resource group, along with its associated resources.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Search.Models.SearchService Get (this Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Search.Models.SearchService Get(class Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.Get(Microsoft.Azure.Management.Search.IServicesOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Search.IServicesOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; Microsoft.Azure.Management.Search.Models.SearchService" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.Get (operations, resourceGroupName, searchServiceName, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Search.Models.SearchService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0a74d-151">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0a74d-151">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0a74d-152">現在のサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0a74d-152">The name of the resource group within the current subscription.</span></span> <span data-ttu-id="0a74d-153">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="0a74d-153">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="0a74d-154">指定されたリソース グループに関連付けられている Azure Search サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="0a74d-154">The name of the Azure Search service associated with the specified resource group.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="0a74d-155">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="0a74d-155">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="0a74d-156">指定したリソース グループ内の指定した名前で検索サービスを取得します。</span><span class="sxs-lookup"><span data-stu-id="0a74d-156">Gets the Search service with the given name in the given resource group.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt; GetAsync (this Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Search.Models.SearchService&gt; GetAsync(class Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Search.IServicesOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Search.IServicesOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.GetAsync (operations, resourceGroupName, searchServiceName, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.ServicesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0a74d-157">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0a74d-157">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0a74d-158">現在のサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0a74d-158">The name of the resource group within the current subscription.</span></span> <span data-ttu-id="0a74d-159">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="0a74d-159">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="0a74d-160">指定されたリソース グループに関連付けられている Azure Search サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="0a74d-160">The name of the Azure Search service associated with the specified resource group.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="0a74d-161">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="0a74d-161">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0a74d-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0a74d-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0a74d-163">指定したリソース グループ内の指定した名前で検索サービスを取得します。</span><span class="sxs-lookup"><span data-stu-id="0a74d-163">Gets the Search service with the given name in the given resource group.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt; ListByResourceGroup (this Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Search.Models.SearchService&gt; ListByResourceGroup(class Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Search.IServicesOperations,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Search.IServicesOperations * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; seq&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0a74d-164">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0a74d-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0a74d-165">現在のサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0a74d-165">The name of the resource group within the current subscription.</span></span> <span data-ttu-id="0a74d-166">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="0a74d-166">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="0a74d-167">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="0a74d-167">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="0a74d-168">指定したリソース グループ内のすべての検索サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="0a74d-168">Gets a list of all Search services in the given resource group.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Search.Models.SearchService&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Search.IServicesOperations,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Search.IServicesOperations * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;&gt;" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.ServicesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="0a74d-169">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="0a74d-169">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0a74d-170">現在のサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="0a74d-170">The name of the resource group within the current subscription.</span></span> <span data-ttu-id="0a74d-171">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="0a74d-171">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="0a74d-172">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="0a74d-172">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0a74d-173">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0a74d-173">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0a74d-174">指定したリソース グループ内のすべての検索サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="0a74d-174">Gets a list of all Search services in the given resource group.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>