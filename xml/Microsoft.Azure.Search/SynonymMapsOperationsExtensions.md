<Type Name="SynonymMapsOperationsExtensions" FullName="Microsoft.Azure.Search.SynonymMapsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SynonymMapsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SynonymMapsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.SynonymMapsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SynonymMapsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SynonymMapsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e1424-101">Synonymmaps を管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="e1424-101">Operations for managing synonymmaps.</span></span> 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.SynonymMap Create (this Microsoft.Azure.Search.ISynonymMapsOperations operations, Microsoft.Azure.Search.Models.SynonymMap synonymMap, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.SynonymMap Create(class Microsoft.Azure.Search.ISynonymMapsOperations operations, class Microsoft.Azure.Search.Models.SynonymMap synonymMap, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.Create(Microsoft.Azure.Search.ISynonymMapsOperations,Microsoft.Azure.Search.Models.SynonymMap,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Search.ISynonymMapsOperations * Microsoft.Azure.Search.Models.SynonymMap * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.SynonymMap" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.Create (operations, synonymMap, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.SynonymMap</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
        <Parameter Name="synonymMap" Type="Microsoft.Azure.Search.Models.SynonymMap" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e1424-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e1424-102">The operations group for this extension method.</span></span>
            </param>
        <param name="synonymMap">
            <span data-ttu-id="e1424-103">作成するシノニム マップの定義。</span><span class="sxs-lookup"><span data-stu-id="e1424-103">The definition of the synonym map to create.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="e1424-104">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e1424-104">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="e1424-105">新しい Azure Search シノニム マップを作成します。</span><span class="sxs-lookup"><span data-stu-id="e1424-105">Creates a new Azure Search synonym map.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Synonym-Map" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMap&gt; CreateAsync (this Microsoft.Azure.Search.ISynonymMapsOperations operations, Microsoft.Azure.Search.Models.SynonymMap synonymMap, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.SynonymMap&gt; CreateAsync(class Microsoft.Azure.Search.ISynonymMapsOperations operations, class Microsoft.Azure.Search.Models.SynonymMap synonymMap, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.CreateAsync(Microsoft.Azure.Search.ISynonymMapsOperations,Microsoft.Azure.Search.Models.SynonymMap,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Search.ISynonymMapsOperations * Microsoft.Azure.Search.Models.SynonymMap * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.CreateAsync (operations, synonymMap, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.SynonymMapsOperationsExtensions/&lt;CreateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
        <Parameter Name="synonymMap" Type="Microsoft.Azure.Search.Models.SynonymMap" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e1424-106">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e1424-106">The operations group for this extension method.</span></span>
            </param>
        <param name="synonymMap">
            <span data-ttu-id="e1424-107">作成するシノニム マップの定義。</span><span class="sxs-lookup"><span data-stu-id="e1424-107">The definition of the synonym map to create.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="e1424-108">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e1424-108">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e1424-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e1424-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e1424-110">新しい Azure Search シノニム マップを作成します。</span><span class="sxs-lookup"><span data-stu-id="e1424-110">Creates a new Azure Search synonym map.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Synonym-Map" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.SynonymMap CreateOrUpdate (this Microsoft.Azure.Search.ISynonymMapsOperations operations, Microsoft.Azure.Search.Models.SynonymMap synonymMap, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.SynonymMap CreateOrUpdate(class Microsoft.Azure.Search.ISynonymMapsOperations operations, class Microsoft.Azure.Search.Models.SynonymMap synonymMap, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Search.ISynonymMapsOperations,Microsoft.Azure.Search.Models.SynonymMap,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Search.ISynonymMapsOperations * Microsoft.Azure.Search.Models.SynonymMap * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; Microsoft.Azure.Search.Models.SynonymMap" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.CreateOrUpdate (operations, synonymMap, searchRequestOptions, accessCondition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.SynonymMap</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
        <Parameter Name="synonymMap" Type="Microsoft.Azure.Search.Models.SynonymMap" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e1424-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e1424-111">The operations group for this extension method.</span></span>
            </param>
        <param name="synonymMap">
            <span data-ttu-id="e1424-112">作成または更新 synonymmap の定義。</span><span class="sxs-lookup"><span data-stu-id="e1424-112">The definition of the synonymmap to create or update.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="e1424-113">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e1424-113">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="e1424-114">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e1424-114">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="e1424-115">新しい Azure Search synonymmap を作成または、既に存在する場合に、synonymmap を更新します。</span><span class="sxs-lookup"><span data-stu-id="e1424-115">Creates a new Azure Search synonymmap or updates a synonymmap if it already exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.SynonymMap CreateOrUpdate (this Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, Microsoft.Azure.Search.Models.SynonymMap synonymMap, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.SynonymMap CreateOrUpdate(class Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, class Microsoft.Azure.Search.Models.SynonymMap synonymMap, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Search.ISynonymMapsOperations,System.String,Microsoft.Azure.Search.Models.SynonymMap,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Search.ISynonymMapsOperations * string * Microsoft.Azure.Search.Models.SynonymMap * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; Microsoft.Azure.Search.Models.SynonymMap" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.CreateOrUpdate (operations, synonymMapName, synonymMap, searchRequestOptions, accessCondition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.SynonymMap</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
        <Parameter Name="synonymMapName" Type="System.String" />
        <Parameter Name="synonymMap" Type="Microsoft.Azure.Search.Models.SynonymMap" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e1424-116">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e1424-116">The operations group for this extension method.</span></span>
            </param>
        <param name="synonymMapName">
            <span data-ttu-id="e1424-117">作成または更新するシノニム マップの名前。</span><span class="sxs-lookup"><span data-stu-id="e1424-117">The name of the synonym map to create or update.</span></span>
            </param>
        <param name="synonymMap">
            <span data-ttu-id="e1424-118">マップの定義、シノニムを作成または更新します。</span><span class="sxs-lookup"><span data-stu-id="e1424-118">The definition of the synonym map to create or update.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="e1424-119">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e1424-119">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="e1424-120">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e1424-120">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="e1424-121">新しい Azure Search シノニム マップを作成または、既に存在する場合は、シノニム マップを更新します。</span><span class="sxs-lookup"><span data-stu-id="e1424-121">Creates a new Azure Search synonym map or updates a synonym map if it already exists.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Update-Synonym-Map" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMap&gt; CreateOrUpdateAsync (this Microsoft.Azure.Search.ISynonymMapsOperations operations, Microsoft.Azure.Search.Models.SynonymMap synonymMap, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.SynonymMap&gt; CreateOrUpdateAsync(class Microsoft.Azure.Search.ISynonymMapsOperations operations, class Microsoft.Azure.Search.Models.SynonymMap synonymMap, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Search.ISynonymMapsOperations,Microsoft.Azure.Search.Models.SynonymMap,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Search.ISynonymMapsOperations * Microsoft.Azure.Search.Models.SynonymMap * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.CreateOrUpdateAsync (operations, synonymMap, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.SynonymMapsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
        <Parameter Name="synonymMap" Type="Microsoft.Azure.Search.Models.SynonymMap" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e1424-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e1424-122">The operations group for this extension method.</span></span>
            </param>
        <param name="synonymMap">
            <span data-ttu-id="e1424-123">作成または更新 synonymmap の定義。</span><span class="sxs-lookup"><span data-stu-id="e1424-123">The definition of the synonymmap to create or update.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="e1424-124">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e1424-124">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="e1424-125">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e1424-125">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e1424-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e1424-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e1424-127">新しい Azure Search synonymmap を作成または、既に存在する場合に、synonymmap を更新します。</span><span class="sxs-lookup"><span data-stu-id="e1424-127">Creates a new Azure Search synonymmap or updates a synonymmap if it already exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMap&gt; CreateOrUpdateAsync (this Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, Microsoft.Azure.Search.Models.SynonymMap synonymMap, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.SynonymMap&gt; CreateOrUpdateAsync(class Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, class Microsoft.Azure.Search.Models.SynonymMap synonymMap, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Search.ISynonymMapsOperations,System.String,Microsoft.Azure.Search.Models.SynonymMap,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Search.ISynonymMapsOperations * string * Microsoft.Azure.Search.Models.SynonymMap * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.CreateOrUpdateAsync (operations, synonymMapName, synonymMap, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.SynonymMapsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
        <Parameter Name="synonymMapName" Type="System.String" />
        <Parameter Name="synonymMap" Type="Microsoft.Azure.Search.Models.SynonymMap" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e1424-128">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e1424-128">The operations group for this extension method.</span></span>
            </param>
        <param name="synonymMapName">
            <span data-ttu-id="e1424-129">作成または更新するシノニム マップの名前。</span><span class="sxs-lookup"><span data-stu-id="e1424-129">The name of the synonym map to create or update.</span></span>
            </param>
        <param name="synonymMap">
            <span data-ttu-id="e1424-130">マップの定義、シノニムを作成または更新します。</span><span class="sxs-lookup"><span data-stu-id="e1424-130">The definition of the synonym map to create or update.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="e1424-131">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e1424-131">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="e1424-132">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e1424-132">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e1424-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e1424-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e1424-134">新しい Azure Search シノニム マップを作成または、既に存在する場合は、シノニム マップを更新します。</span><span class="sxs-lookup"><span data-stu-id="e1424-134">Creates a new Azure Search synonym map or updates a synonym map if it already exists.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Update-Synonym-Map" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.Delete(Microsoft.Azure.Search.ISynonymMapsOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Search.ISynonymMapsOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; unit" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.Delete (operations, synonymMapName, searchRequestOptions, accessCondition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
        <Parameter Name="synonymMapName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e1424-135">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e1424-135">The operations group for this extension method.</span></span>
            </param>
        <param name="synonymMapName">
            <span data-ttu-id="e1424-136">削除するシノニム マップの名前。</span><span class="sxs-lookup"><span data-stu-id="e1424-136">The name of the synonym map to delete.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="e1424-137">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e1424-137">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="e1424-138">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e1424-138">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="e1424-139">Azure Search シノニム マップを削除します。</span><span class="sxs-lookup"><span data-stu-id="e1424-139">Deletes an Azure Search synonym map.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Delete-Synonym-Map" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.DeleteAsync(Microsoft.Azure.Search.ISynonymMapsOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Search.ISynonymMapsOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.DeleteAsync (operations, synonymMapName, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.SynonymMapsOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
        <Parameter Name="synonymMapName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e1424-140">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e1424-140">The operations group for this extension method.</span></span>
            </param>
        <param name="synonymMapName">
            <span data-ttu-id="e1424-141">削除するシノニム マップの名前。</span><span class="sxs-lookup"><span data-stu-id="e1424-141">The name of the synonym map to delete.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="e1424-142">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e1424-142">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="e1424-143">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e1424-143">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e1424-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e1424-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e1424-145">Azure Search シノニム マップを削除します。</span><span class="sxs-lookup"><span data-stu-id="e1424-145">Deletes an Azure Search synonym map.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Delete-Synonym-Map" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public static bool Exists (this Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool Exists(class Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.Exists(Microsoft.Azure.Search.ISynonymMapsOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Exists : Microsoft.Azure.Search.ISynonymMapsOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; bool" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.Exists (operations, synonymMapName, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
        <Parameter Name="synonymMapName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e1424-146">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e1424-146">The operations group for this extension method.</span></span>
            </param>
        <param name="synonymMapName">
            <span data-ttu-id="e1424-147">シノニムのマップの名前。</span><span class="sxs-lookup"><span data-stu-id="e1424-147">The name of the synonym map.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="e1424-148">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e1424-148">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="e1424-149">シノニムの指定したマップは、Azure Search サービスで存在するかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="e1424-149">Determines whether or not the given synonym map exists in the Azure Search service.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="e1424-150"><c>true</c>シノニム マップが存在する場合<c>false</c>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="e1424-150"><c>true</c> if the synonym map exists; <c>false</c> otherwise.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (this Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.ExistsAsync(Microsoft.Azure.Search.ISynonymMapsOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExistsAsync : Microsoft.Azure.Search.ISynonymMapsOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.ExistsAsync (operations, synonymMapName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.SynonymMapsOperationsExtensions/&lt;ExistsAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
        <Parameter Name="synonymMapName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e1424-151">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e1424-151">The operations group for this extension method.</span></span>
            </param>
        <param name="synonymMapName">
            <span data-ttu-id="e1424-152">シノニムのマップの名前。</span><span class="sxs-lookup"><span data-stu-id="e1424-152">The name of the synonym map.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="e1424-153">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e1424-153">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e1424-154">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e1424-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e1424-155">シノニムの指定したマップは、Azure Search サービスで存在するかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="e1424-155">Determines whether or not the given synonym map exists in the Azure Search service.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="e1424-156"><c>true</c>シノニム マップが存在する場合<c>false</c>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="e1424-156"><c>true</c> if the synonym map exists; <c>false</c> otherwise.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.SynonymMap Get (this Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.SynonymMap Get(class Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.Get(Microsoft.Azure.Search.ISynonymMapsOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Search.ISynonymMapsOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.SynonymMap" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.Get (operations, synonymMapName, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.SynonymMap</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
        <Parameter Name="synonymMapName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e1424-157">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e1424-157">The operations group for this extension method.</span></span>
            </param>
        <param name="synonymMapName">
            <span data-ttu-id="e1424-158">取得するシノニム マップの名前。</span><span class="sxs-lookup"><span data-stu-id="e1424-158">The name of the synonym map to retrieve.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="e1424-159">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e1424-159">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="e1424-160">Azure Search からシノニム マップの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="e1424-160">Retrieves a synonym map definition from Azure Search.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Synonym-Map" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMap&gt; GetAsync (this Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.SynonymMap&gt; GetAsync(class Microsoft.Azure.Search.ISynonymMapsOperations operations, string synonymMapName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.GetAsync(Microsoft.Azure.Search.ISynonymMapsOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Search.ISynonymMapsOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.GetAsync (operations, synonymMapName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.SynonymMapsOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMap&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
        <Parameter Name="synonymMapName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e1424-161">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e1424-161">The operations group for this extension method.</span></span>
            </param>
        <param name="synonymMapName">
            <span data-ttu-id="e1424-162">取得するシノニム マップの名前。</span><span class="sxs-lookup"><span data-stu-id="e1424-162">The name of the synonym map to retrieve.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="e1424-163">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e1424-163">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e1424-164">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e1424-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e1424-165">Azure Search からシノニム マップの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="e1424-165">Retrieves a synonym map definition from Azure Search.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Synonym-Map" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.SynonymMapListResult List (this Microsoft.Azure.Search.ISynonymMapsOperations operations, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.SynonymMapListResult List(class Microsoft.Azure.Search.ISynonymMapsOperations operations, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.List(Microsoft.Azure.Search.ISynonymMapsOperations,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Search.ISynonymMapsOperations * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.SynonymMapListResult" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.List (operations, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.SynonymMapListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e1424-166">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e1424-166">The operations group for this extension method.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="e1424-167">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e1424-167">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="e1424-168">Azure Search サービスの使用可能なシノニムのマップをすべて一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="e1424-168">Lists all synonym maps available for an Azure Search service.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Synonym-Maps" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMapListResult&gt; ListAsync (this Microsoft.Azure.Search.ISynonymMapsOperations operations, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.SynonymMapListResult&gt; ListAsync(class Microsoft.Azure.Search.ISynonymMapsOperations operations, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.SynonymMapsOperationsExtensions.ListAsync(Microsoft.Azure.Search.ISynonymMapsOperations,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Search.ISynonymMapsOperations * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMapListResult&gt;" Usage="Microsoft.Azure.Search.SynonymMapsOperationsExtensions.ListAsync (operations, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.SynonymMapsOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.SynonymMapListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.ISynonymMapsOperations" RefType="this" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e1424-169">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="e1424-169">The operations group for this extension method.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="e1424-170">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="e1424-170">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e1424-171">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e1424-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e1424-172">Azure Search サービスの使用可能なシノニムのマップをすべて一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="e1424-172">Lists all synonym maps available for an Azure Search service.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Synonym-Maps" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>