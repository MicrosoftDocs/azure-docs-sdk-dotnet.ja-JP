<Type Name="AdminKeysOperationsExtensions" FullName="Microsoft.Azure.Management.Search.AdminKeysOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AdminKeysOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AdminKeysOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Search.AdminKeysOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AdminKeysOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AdminKeysOperationsExtensions = class" />
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
            <span data-ttu-id="b6fe6-101">AdminKeysOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-101">Extension methods for AdminKeysOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Search.Models.AdminKeyResult Get (this Microsoft.Azure.Management.Search.IAdminKeysOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Search.Models.AdminKeyResult Get(class Microsoft.Azure.Management.Search.IAdminKeysOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.AdminKeysOperationsExtensions.Get(Microsoft.Azure.Management.Search.IAdminKeysOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Search.IAdminKeysOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; Microsoft.Azure.Management.Search.Models.AdminKeyResult" Usage="Microsoft.Azure.Management.Search.AdminKeysOperationsExtensions.Get (operations, resourceGroupName, searchServiceName, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Search.Models.AdminKeyResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IAdminKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b6fe6-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b6fe6-103">現在のサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-103">The name of the resource group within the current subscription.</span></span> <span data-ttu-id="b6fe6-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="b6fe6-105">指定されたリソース グループに関連付けられている Azure Search サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-105">The name of the Azure Search service associated with the specified resource group.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="b6fe6-106">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="b6fe6-106">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="b6fe6-107">プライマリおよびセカンダリ管理に指定された Azure Search サービスの API キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-107">Gets the primary and secondary admin API keys for the specified Azure Search service.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.AdminKeyResult&gt; GetAsync (this Microsoft.Azure.Management.Search.IAdminKeysOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Search.Models.AdminKeyResult&gt; GetAsync(class Microsoft.Azure.Management.Search.IAdminKeysOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.AdminKeysOperationsExtensions.GetAsync(Microsoft.Azure.Management.Search.IAdminKeysOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Search.IAdminKeysOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.AdminKeyResult&gt;" Usage="Microsoft.Azure.Management.Search.AdminKeysOperationsExtensions.GetAsync (operations, resourceGroupName, searchServiceName, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.AdminKeysOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.AdminKeyResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IAdminKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b6fe6-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b6fe6-109">現在のサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-109">The name of the resource group within the current subscription.</span></span> <span data-ttu-id="b6fe6-110">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-110">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="b6fe6-111">指定されたリソース グループに関連付けられている Azure Search サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-111">The name of the Azure Search service associated with the specified resource group.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="b6fe6-112">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="b6fe6-112">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b6fe6-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b6fe6-114">プライマリおよびセカンダリ管理に指定された Azure Search サービスの API キーを取得します。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-114">Gets the primary and secondary admin API keys for the specified Azure Search service.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Regenerate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Search.Models.AdminKeyResult Regenerate (this Microsoft.Azure.Management.Search.IAdminKeysOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.AdminKeyKind keyKind, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Search.Models.AdminKeyResult Regenerate(class Microsoft.Azure.Management.Search.IAdminKeysOperations operations, string resourceGroupName, string searchServiceName, valuetype Microsoft.Azure.Management.Search.Models.AdminKeyKind keyKind, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.AdminKeysOperationsExtensions.Regenerate(Microsoft.Azure.Management.Search.IAdminKeysOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.AdminKeyKind,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Regenerate : Microsoft.Azure.Management.Search.IAdminKeysOperations * string * string * Microsoft.Azure.Management.Search.Models.AdminKeyKind * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; Microsoft.Azure.Management.Search.Models.AdminKeyResult" Usage="Microsoft.Azure.Management.Search.AdminKeysOperationsExtensions.Regenerate (operations, resourceGroupName, searchServiceName, keyKind, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Search.Models.AdminKeyResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IAdminKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="keyKind" Type="Microsoft.Azure.Management.Search.Models.AdminKeyKind" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b6fe6-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b6fe6-116">現在のサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-116">The name of the resource group within the current subscription.</span></span> <span data-ttu-id="b6fe6-117">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-117">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="b6fe6-118">指定されたリソース グループに関連付けられている Azure Search サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-118">The name of the Azure Search service associated with the specified resource group.</span></span>
            </param>
        <param name="keyKind">
            <span data-ttu-id="b6fe6-119">再生成するキーを指定します。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-119">Specifies which key to regenerate.</span></span> <span data-ttu-id="b6fe6-120">有効な値には、'primary' および 'セカンダリ' が含まれます。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-120">Valid values include 'primary' and 'secondary'.</span></span> <span data-ttu-id="b6fe6-121">使用可能な値が含まれます 'primary'、'セカンダリ'。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-121">Possible values include: 'primary', 'secondary'</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="b6fe6-122">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="b6fe6-122">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="b6fe6-123">プライマリまたはセカンダリの管理者 API キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-123">Regenerates either the primary or secondary admin API key.</span></span> <span data-ttu-id="b6fe6-124">一度に再生成できるのは 1 つのキーのみです。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-124">You can only regenerate one key at a time.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.AdminKeyResult&gt; RegenerateAsync (this Microsoft.Azure.Management.Search.IAdminKeysOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.AdminKeyKind keyKind, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Search.Models.AdminKeyResult&gt; RegenerateAsync(class Microsoft.Azure.Management.Search.IAdminKeysOperations operations, string resourceGroupName, string searchServiceName, valuetype Microsoft.Azure.Management.Search.Models.AdminKeyKind keyKind, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.AdminKeysOperationsExtensions.RegenerateAsync(Microsoft.Azure.Management.Search.IAdminKeysOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.AdminKeyKind,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateAsync : Microsoft.Azure.Management.Search.IAdminKeysOperations * string * string * Microsoft.Azure.Management.Search.Models.AdminKeyKind * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.AdminKeyResult&gt;" Usage="Microsoft.Azure.Management.Search.AdminKeysOperationsExtensions.RegenerateAsync (operations, resourceGroupName, searchServiceName, keyKind, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.AdminKeysOperationsExtensions/&lt;RegenerateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.AdminKeyResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IAdminKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="keyKind" Type="Microsoft.Azure.Management.Search.Models.AdminKeyKind" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b6fe6-125">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-125">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b6fe6-126">現在のサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-126">The name of the resource group within the current subscription.</span></span> <span data-ttu-id="b6fe6-127">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-127">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="b6fe6-128">指定されたリソース グループに関連付けられている Azure Search サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-128">The name of the Azure Search service associated with the specified resource group.</span></span>
            </param>
        <param name="keyKind">
            <span data-ttu-id="b6fe6-129">再生成するキーを指定します。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-129">Specifies which key to regenerate.</span></span> <span data-ttu-id="b6fe6-130">有効な値には、'primary' および 'セカンダリ' が含まれます。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-130">Valid values include 'primary' and 'secondary'.</span></span> <span data-ttu-id="b6fe6-131">使用可能な値が含まれます 'primary'、'セカンダリ'。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-131">Possible values include: 'primary', 'secondary'</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="b6fe6-132">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="b6fe6-132">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b6fe6-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b6fe6-134">プライマリまたはセカンダリの管理者 API キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-134">Regenerates either the primary or secondary admin API key.</span></span> <span data-ttu-id="b6fe6-135">一度に再生成できるのは 1 つのキーのみです。</span><span class="sxs-lookup"><span data-stu-id="b6fe6-135">You can only regenerate one key at a time.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>