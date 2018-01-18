<Type Name="IndexesOperationsExtensions" FullName="Microsoft.Azure.Search.IndexesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class IndexesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit IndexesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.IndexesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module IndexesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type IndexesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="38523-101">インデックスを管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="38523-101">Operations for managing indexes.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Index-operations" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Analyze">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.AnalyzeResult Analyze (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.AnalyzeRequest request, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.AnalyzeResult Analyze(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.AnalyzeRequest request, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.Analyze(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.AnalyzeRequest,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Analyze : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.AnalyzeRequest * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.AnalyzeResult" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.Analyze (operations, indexName, request, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AnalyzeResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="request" Type="Microsoft.Azure.Search.Models.AnalyzeRequest" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="38523-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="38523-102">The operations group for this extension method.</span></span>
            </param>
        <param name="indexName">
            <span data-ttu-id="38523-103">アナライザーのテスト対象のインデックスの名前。</span><span class="sxs-lookup"><span data-stu-id="38523-103">The name of the index for which to test an analyzer.</span></span>
            </param>
        <param name="request">
            <span data-ttu-id="38523-104">テキストやアナライザー、分析コンポーネントをテストします。</span><span class="sxs-lookup"><span data-stu-id="38523-104">The text and analyzer or analysis components to test.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="38523-105">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="38523-105">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="38523-106">アナライザーがトークンにテキストを分割する方法を示しています。</span><span class="sxs-lookup"><span data-stu-id="38523-106">Shows how an analyzer breaks text into tokens.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/test-analyzer" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AnalyzeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.AnalyzeResult&gt; AnalyzeAsync (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.AnalyzeRequest request, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.AnalyzeResult&gt; AnalyzeAsync(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.AnalyzeRequest request, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.AnalyzeAsync(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.AnalyzeRequest,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AnalyzeAsync : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.AnalyzeRequest * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.AnalyzeResult&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.AnalyzeAsync (operations, indexName, request, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;AnalyzeAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.AnalyzeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="request" Type="Microsoft.Azure.Search.Models.AnalyzeRequest" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="38523-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="38523-107">The operations group for this extension method.</span></span>
            </param>
        <param name="indexName">
            <span data-ttu-id="38523-108">アナライザーのテスト対象のインデックスの名前。</span><span class="sxs-lookup"><span data-stu-id="38523-108">The name of the index for which to test an analyzer.</span></span>
            </param>
        <param name="request">
            <span data-ttu-id="38523-109">テキストやアナライザー、分析コンポーネントをテストします。</span><span class="sxs-lookup"><span data-stu-id="38523-109">The text and analyzer or analysis components to test.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="38523-110">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="38523-110">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="38523-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="38523-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="38523-112">アナライザーがトークンにテキストを分割する方法を示しています。</span><span class="sxs-lookup"><span data-stu-id="38523-112">Shows how an analyzer breaks text into tokens.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/test-analyzer" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.Index Create (this Microsoft.Azure.Search.IIndexesOperations operations, Microsoft.Azure.Search.Models.Index index, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.Index Create(class Microsoft.Azure.Search.IIndexesOperations operations, class Microsoft.Azure.Search.Models.Index index, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.Create(Microsoft.Azure.Search.IIndexesOperations,Microsoft.Azure.Search.Models.Index,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Search.IIndexesOperations * Microsoft.Azure.Search.Models.Index * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.Index" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.Create (operations, index, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.Index</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="index" Type="Microsoft.Azure.Search.Models.Index" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="38523-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="38523-113">The operations group for this extension method.</span></span>
            </param>
        <param name="index">
            <span data-ttu-id="38523-114">作成するインデックスの定義。</span><span class="sxs-lookup"><span data-stu-id="38523-114">The definition of the index to create.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="38523-115">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="38523-115">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="38523-116">新しい Azure Search インデックスを作成します。</span><span class="sxs-lookup"><span data-stu-id="38523-116">Creates a new Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt; CreateAsync (this Microsoft.Azure.Search.IIndexesOperations operations, Microsoft.Azure.Search.Models.Index index, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.Index&gt; CreateAsync(class Microsoft.Azure.Search.IIndexesOperations operations, class Microsoft.Azure.Search.Models.Index index, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.CreateAsync(Microsoft.Azure.Search.IIndexesOperations,Microsoft.Azure.Search.Models.Index,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Search.IIndexesOperations * Microsoft.Azure.Search.Models.Index * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.CreateAsync (operations, index, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;CreateAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="index" Type="Microsoft.Azure.Search.Models.Index" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="38523-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="38523-117">The operations group for this extension method.</span></span>
            </param>
        <param name="index">
            <span data-ttu-id="38523-118">作成するインデックスの定義。</span><span class="sxs-lookup"><span data-stu-id="38523-118">The definition of the index to create.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="38523-119">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="38523-119">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="38523-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="38523-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="38523-121">新しい Azure Search インデックスを作成します。</span><span class="sxs-lookup"><span data-stu-id="38523-121">Creates a new Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.Index CreateOrUpdate (this Microsoft.Azure.Search.IIndexesOperations operations, Microsoft.Azure.Search.Models.Index index, Nullable&lt;bool&gt; allowIndexDowntime = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.Index CreateOrUpdate(class Microsoft.Azure.Search.IIndexesOperations operations, class Microsoft.Azure.Search.Models.Index index, valuetype System.Nullable`1&lt;bool&gt; allowIndexDowntime, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Search.IIndexesOperations,Microsoft.Azure.Search.Models.Index,System.Nullable{System.Boolean},Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Search.IIndexesOperations * Microsoft.Azure.Search.Models.Index * Nullable&lt;bool&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; Microsoft.Azure.Search.Models.Index" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.CreateOrUpdate (operations, index, allowIndexDowntime, searchRequestOptions, accessCondition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.Index</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="index" Type="Microsoft.Azure.Search.Models.Index" />
        <Parameter Name="allowIndexDowntime" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="38523-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="38523-122">The operations group for this extension method.</span></span>
            </param>
        <param name="index">
            <span data-ttu-id="38523-123">インデックスを作成または更新の定義。</span><span class="sxs-lookup"><span data-stu-id="38523-123">The definition of the index to create or update.</span></span>
            </param>
        <param name="allowIndexDowntime">
            <span data-ttu-id="38523-124">で数秒以上のオフラインのインデックスを取得することにより、インデックスに追加する新しいアナライザー、されなければ、トークンのフィルターまたは char フィルターできます。</span><span class="sxs-lookup"><span data-stu-id="38523-124">Allows new analyzers, tokenizers, token filters, or char filters to be added to an index by taking the index offline for at least a few seconds.</span></span> <span data-ttu-id="38523-125">これにより、インデックスの作成とクエリの要求が失敗が一時的にさせます。</span><span class="sxs-lookup"><span data-stu-id="38523-125">This temporarily causes indexing and query requests to fail.</span></span> <span data-ttu-id="38523-126">インデックスを更新すると、インデックスのパフォーマンスと書き込み可用性が数分にわたり損なわれる場合があります。インデックスが非常に大きい場合、その時間も長くなります。</span><span class="sxs-lookup"><span data-stu-id="38523-126">Performance and write availability of the index can be impaired for several minutes after the index is updated, or longer for very large indexes.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="38523-127">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="38523-127">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="38523-128">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="38523-128">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="38523-129">新しい Azure Search インデックスを作成または、既に存在する場合、インデックスを更新します。</span><span class="sxs-lookup"><span data-stu-id="38523-129">Creates a new Azure Search index or updates an index if it already exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.Index CreateOrUpdate (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.Index index, Nullable&lt;bool&gt; allowIndexDowntime = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.Index CreateOrUpdate(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.Index index, valuetype System.Nullable`1&lt;bool&gt; allowIndexDowntime, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.Index,System.Nullable{System.Boolean},Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.Index * Nullable&lt;bool&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; Microsoft.Azure.Search.Models.Index" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.CreateOrUpdate (operations, indexName, index, allowIndexDowntime, searchRequestOptions, accessCondition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.Index</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="index" Type="Microsoft.Azure.Search.Models.Index" />
        <Parameter Name="allowIndexDowntime" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="38523-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="38523-130">The operations group for this extension method.</span></span>
            </param>
        <param name="indexName">
            <span data-ttu-id="38523-131">インデックスを作成または更新の定義。</span><span class="sxs-lookup"><span data-stu-id="38523-131">The definition of the index to create or update.</span></span>
            </param>
        <param name="index">
            <span data-ttu-id="38523-132">インデックスを作成または更新の定義。</span><span class="sxs-lookup"><span data-stu-id="38523-132">The definition of the index to create or update.</span></span>
            </param>
        <param name="allowIndexDowntime">
            <span data-ttu-id="38523-133">で数秒以上のオフラインのインデックスを取得することにより、インデックスに追加する新しいアナライザー、されなければ、トークンのフィルターまたは char フィルターできます。</span><span class="sxs-lookup"><span data-stu-id="38523-133">Allows new analyzers, tokenizers, token filters, or char filters to be added to an index by taking the index offline for at least a few seconds.</span></span>
            <span data-ttu-id="38523-134">これにより、インデックスの作成とクエリの要求が失敗が一時的にさせます。</span><span class="sxs-lookup"><span data-stu-id="38523-134">This temporarily causes indexing and query requests to fail.</span></span> <span data-ttu-id="38523-135">インデックスを更新すると、インデックスのパフォーマンスと書き込み可用性が数分にわたり損なわれる場合があります。インデックスが非常に大きい場合、その時間も長くなります。</span><span class="sxs-lookup"><span data-stu-id="38523-135">Performance and write availability of the index can be impaired for several minutes after the index is updated, or longer for very large indexes.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="38523-136">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="38523-136">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="38523-137">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="38523-137">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="38523-138">新しい Azure Search インデックスを作成または、既に存在する場合、インデックスを更新します。</span><span class="sxs-lookup"><span data-stu-id="38523-138">Creates a new Azure Search index or updates an index if it already exists.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Update-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt; CreateOrUpdateAsync (this Microsoft.Azure.Search.IIndexesOperations operations, Microsoft.Azure.Search.Models.Index index, Nullable&lt;bool&gt; allowIndexDowntime = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.Index&gt; CreateOrUpdateAsync(class Microsoft.Azure.Search.IIndexesOperations operations, class Microsoft.Azure.Search.Models.Index index, valuetype System.Nullable`1&lt;bool&gt; allowIndexDowntime, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Search.IIndexesOperations,Microsoft.Azure.Search.Models.Index,System.Nullable{System.Boolean},Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Search.IIndexesOperations * Microsoft.Azure.Search.Models.Index * Nullable&lt;bool&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.CreateOrUpdateAsync (operations, index, allowIndexDowntime, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="index" Type="Microsoft.Azure.Search.Models.Index" />
        <Parameter Name="allowIndexDowntime" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="38523-139">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="38523-139">The operations group for this extension method.</span></span>
            </param>
        <param name="index">
            <span data-ttu-id="38523-140">インデックスを作成または更新の定義。</span><span class="sxs-lookup"><span data-stu-id="38523-140">The definition of the index to create or update.</span></span>
            </param>
        <param name="allowIndexDowntime">
            <span data-ttu-id="38523-141">で数秒以上のオフラインのインデックスを取得することにより、インデックスに追加する新しいアナライザー、されなければ、トークンのフィルターまたは char フィルターできます。</span><span class="sxs-lookup"><span data-stu-id="38523-141">Allows new analyzers, tokenizers, token filters, or char filters to be added to an index by taking the index offline for at least a few seconds.</span></span> <span data-ttu-id="38523-142">これにより、インデックスの作成とクエリの要求が失敗が一時的にさせます。</span><span class="sxs-lookup"><span data-stu-id="38523-142">This temporarily causes indexing and query requests to fail.</span></span> <span data-ttu-id="38523-143">インデックスを更新すると、インデックスのパフォーマンスと書き込み可用性が数分にわたり損なわれる場合があります。インデックスが非常に大きい場合、その時間も長くなります。</span><span class="sxs-lookup"><span data-stu-id="38523-143">Performance and write availability of the index can be impaired for several minutes after the index is updated, or longer for very large indexes.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="38523-144">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="38523-144">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="38523-145">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="38523-145">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="38523-146">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="38523-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="38523-147">新しい Azure Search インデックスを作成または、既に存在する場合、インデックスを更新します。</span><span class="sxs-lookup"><span data-stu-id="38523-147">Creates a new Azure Search index or updates an index if it already exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt; CreateOrUpdateAsync (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.Index index, Nullable&lt;bool&gt; allowIndexDowntime = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.Index&gt; CreateOrUpdateAsync(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.Index index, valuetype System.Nullable`1&lt;bool&gt; allowIndexDowntime, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.Index,System.Nullable{System.Boolean},Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.Index * Nullable&lt;bool&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.CreateOrUpdateAsync (operations, indexName, index, allowIndexDowntime, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="index" Type="Microsoft.Azure.Search.Models.Index" />
        <Parameter Name="allowIndexDowntime" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="38523-148">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="38523-148">The operations group for this extension method.</span></span>
            </param>
        <param name="indexName">
            <span data-ttu-id="38523-149">インデックスを作成または更新の定義。</span><span class="sxs-lookup"><span data-stu-id="38523-149">The definition of the index to create or update.</span></span>
            </param>
        <param name="index">
            <span data-ttu-id="38523-150">インデックスを作成または更新の定義。</span><span class="sxs-lookup"><span data-stu-id="38523-150">The definition of the index to create or update.</span></span>
            </param>
        <param name="allowIndexDowntime">
            <span data-ttu-id="38523-151">で数秒以上のオフラインのインデックスを取得することにより、インデックスに追加する新しいアナライザー、されなければ、トークンのフィルターまたは char フィルターできます。</span><span class="sxs-lookup"><span data-stu-id="38523-151">Allows new analyzers, tokenizers, token filters, or char filters to be added to an index by taking the index offline for at least a few seconds.</span></span>
            <span data-ttu-id="38523-152">これにより、インデックスの作成とクエリの要求が失敗が一時的にさせます。</span><span class="sxs-lookup"><span data-stu-id="38523-152">This temporarily causes indexing and query requests to fail.</span></span> <span data-ttu-id="38523-153">インデックスを更新すると、インデックスのパフォーマンスと書き込み可用性が数分にわたり損なわれる場合があります。インデックスが非常に大きい場合、その時間も長くなります。</span><span class="sxs-lookup"><span data-stu-id="38523-153">Performance and write availability of the index can be impaired for several minutes after the index is updated, or longer for very large indexes.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="38523-154">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="38523-154">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="38523-155">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="38523-155">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="38523-156">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="38523-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="38523-157">新しい Azure Search インデックスを作成または、既に存在する場合、インデックスを更新します。</span><span class="sxs-lookup"><span data-stu-id="38523-157">Creates a new Azure Search index or updates an index if it already exists.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Update-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.Delete(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; unit" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.Delete (operations, indexName, searchRequestOptions, accessCondition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="38523-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="38523-158">The operations group for this extension method.</span></span>
            </param>
        <param name="indexName">
            <span data-ttu-id="38523-159">削除するインデックスの名前。</span><span class="sxs-lookup"><span data-stu-id="38523-159">The name of the index to delete.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="38523-160">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="38523-160">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="38523-161">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="38523-161">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="38523-162">Azure Search インデックスとが含まれているすべてのドキュメントを削除します。</span><span class="sxs-lookup"><span data-stu-id="38523-162">Deletes an Azure Search index and all the documents it contains.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Delete-Index" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.DeleteAsync(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.DeleteAsync (operations, indexName, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;DeleteAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="38523-163">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="38523-163">The operations group for this extension method.</span></span>
            </param>
        <param name="indexName">
            <span data-ttu-id="38523-164">削除するインデックスの名前。</span><span class="sxs-lookup"><span data-stu-id="38523-164">The name of the index to delete.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="38523-165">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="38523-165">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="38523-166">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="38523-166">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="38523-167">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="38523-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="38523-168">Azure Search インデックスとが含まれているすべてのドキュメントを削除します。</span><span class="sxs-lookup"><span data-stu-id="38523-168">Deletes an Azure Search index and all the documents it contains.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Delete-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public static bool Exists (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool Exists(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.Exists(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Exists : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; bool" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.Exists (operations, indexName, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="38523-169">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="38523-169">The operations group for this extension method.</span></span>
            </param>
        <param name="indexName">
            <span data-ttu-id="38523-170">インデックスの名前。</span><span class="sxs-lookup"><span data-stu-id="38523-170">The name of the index.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="38523-171">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="38523-171">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="38523-172">Azure Search サービスに指定されたインデックスが存在するかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="38523-172">Determines whether or not the given index exists in the Azure Search service.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="38523-173"><c>true</c>インデックスが存在する場合<c>false</c>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="38523-173"><c>true</c> if the index exists; <c>false</c> otherwise.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.ExistsAsync(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExistsAsync : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.ExistsAsync (operations, indexName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;ExistsAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="38523-174">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="38523-174">The operations group for this extension method.</span></span>
            </param>
        <param name="indexName">
            <span data-ttu-id="38523-175">インデックスの名前。</span><span class="sxs-lookup"><span data-stu-id="38523-175">The name of the index.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="38523-176">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="38523-176">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="38523-177">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="38523-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="38523-178">Azure Search サービスに指定されたインデックスが存在するかどうかを判断します。</span><span class="sxs-lookup"><span data-stu-id="38523-178">Determines whether or not the given index exists in the Azure Search service.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="38523-179"><c>true</c>インデックスが存在する場合<c>false</c>それ以外の場合。</span><span class="sxs-lookup"><span data-stu-id="38523-179"><c>true</c> if the index exists; <c>false</c> otherwise.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.Index Get (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.Index Get(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.Get(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.Index" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.Get (operations, indexName, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.Index</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="38523-180">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="38523-180">The operations group for this extension method.</span></span>
            </param>
        <param name="indexName">
            <span data-ttu-id="38523-181">取得するインデックスの名前。</span><span class="sxs-lookup"><span data-stu-id="38523-181">The name of the index to retrieve.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="38523-182">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="38523-182">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="38523-183">Azure Search からインデックス定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="38523-183">Retrieves an index definition from Azure Search.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt; GetAsync (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.Index&gt; GetAsync(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.GetAsync(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.GetAsync (operations, indexName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;GetAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="38523-184">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="38523-184">The operations group for this extension method.</span></span>
            </param>
        <param name="indexName">
            <span data-ttu-id="38523-185">取得するインデックスの名前。</span><span class="sxs-lookup"><span data-stu-id="38523-185">The name of the index to retrieve.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="38523-186">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="38523-186">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="38523-187">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="38523-187">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="38523-188">Azure Search からインデックス定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="38523-188">Retrieves an index definition from Azure Search.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatistics">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexGetStatisticsResult GetStatistics (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexGetStatisticsResult GetStatistics(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.GetStatistics(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member GetStatistics : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.IndexGetStatisticsResult" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.GetStatistics (operations, indexName, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexGetStatisticsResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="38523-189">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="38523-189">The operations group for this extension method.</span></span>
            </param>
        <param name="indexName">
            <span data-ttu-id="38523-190">統計情報を取得する対象のインデックスの名前。</span><span class="sxs-lookup"><span data-stu-id="38523-190">The name of the index for which to retrieve statistics.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="38523-191">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="38523-191">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="38523-192">ドキュメントの数と記憶域の使用状況を含む、指定したインデックスの統計を返します。</span><span class="sxs-lookup"><span data-stu-id="38523-192">Returns statistics for the given index, including a document count and storage usage.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Index-Statistics" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatisticsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexGetStatisticsResult&gt; GetStatisticsAsync (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.IndexGetStatisticsResult&gt; GetStatisticsAsync(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.GetStatisticsAsync(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStatisticsAsync : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexGetStatisticsResult&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.GetStatisticsAsync (operations, indexName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;GetStatisticsAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexGetStatisticsResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="38523-193">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="38523-193">The operations group for this extension method.</span></span>
            </param>
        <param name="indexName">
            <span data-ttu-id="38523-194">統計情報を取得する対象のインデックスの名前。</span><span class="sxs-lookup"><span data-stu-id="38523-194">The name of the index for which to retrieve statistics.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="38523-195">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="38523-195">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="38523-196">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="38523-196">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="38523-197">ドキュメントの数と記憶域の使用状況を含む、指定したインデックスの統計を返します。</span><span class="sxs-lookup"><span data-stu-id="38523-197">Returns statistics for the given index, including a document count and storage usage.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Index-Statistics" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexListResult List (this Microsoft.Azure.Search.IIndexesOperations operations, string select = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexListResult List(class Microsoft.Azure.Search.IIndexesOperations operations, string select, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.List(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.IndexListResult" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.List (operations, select, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="38523-198">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="38523-198">The operations group for this extension method.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="38523-199">取得するインデックスの定義のプロパティを選択します。</span><span class="sxs-lookup"><span data-stu-id="38523-199">Selects which properties of the index definitions to retrieve.</span></span> <span data-ttu-id="38523-200">JSON プロパティ名のコンマ区切りリストとして指定または ' \*' のすべてのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="38523-200">Specified as a comma-separated list of JSON property names, or '\*' for all properties.</span></span>
            <span data-ttu-id="38523-201">既定値は、すべてのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="38523-201">The default is all properties.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="38523-202">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="38523-202">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="38523-203">Azure Search サービスの使用可能なすべてのインデックスを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="38523-203">Lists all indexes available for an Azure Search service.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Indexes" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexListResult&gt; ListAsync (this Microsoft.Azure.Search.IIndexesOperations operations, string select = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.IndexListResult&gt; ListAsync(class Microsoft.Azure.Search.IIndexesOperations operations, string select, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.ListAsync(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexListResult&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.ListAsync (operations, select, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;ListAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="38523-204">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="38523-204">The operations group for this extension method.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="38523-205">取得するインデックスの定義のプロパティを選択します。</span><span class="sxs-lookup"><span data-stu-id="38523-205">Selects which properties of the index definitions to retrieve.</span></span> <span data-ttu-id="38523-206">JSON プロパティ名のコンマ区切りリストとして指定または ' \*' のすべてのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="38523-206">Specified as a comma-separated list of JSON property names, or '\*' for all properties.</span></span>
            <span data-ttu-id="38523-207">既定値は、すべてのプロパティです。</span><span class="sxs-lookup"><span data-stu-id="38523-207">The default is all properties.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="38523-208">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="38523-208">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="38523-209">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="38523-209">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="38523-210">Azure Search サービスの使用可能なすべてのインデックスを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="38523-210">Lists all indexes available for an Azure Search service.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Indexes" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNames">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;string&gt; ListNames (this Microsoft.Azure.Search.IIndexesOperations operations, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;string&gt; ListNames(class Microsoft.Azure.Search.IIndexesOperations operations, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.ListNames(Microsoft.Azure.Search.IIndexesOperations,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member ListNames : Microsoft.Azure.Search.IIndexesOperations * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.ListNames (operations, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="38523-211">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="38523-211">The operations group for this extension method.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="38523-212">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="38523-212">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="38523-213">Azure Search サービスの使用可能なすべてのインデックスの名前を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="38523-213">Lists the names of all indexes available for an Azure Search service.</span></span> <span data-ttu-id="38523-214">このときに使用 List() の代わりにのみ必要なインデックスを作成する名前。</span><span class="sxs-lookup"><span data-stu-id="38523-214">Use this instead of List() when you only need index names.</span></span> <span data-ttu-id="38523-215">帯域幅とリソースの使用率は、検索サービスに多数のインデックスがある場合に特にに保存されます。</span><span class="sxs-lookup"><span data-stu-id="38523-215">It will save bandwidth and resource utilization, especially if your Search Service has many indexes.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Indexes" /></summary>
        <returns>
            <span data-ttu-id="38523-216">Search サービスのすべてのインデックス名の一覧。</span><span class="sxs-lookup"><span data-stu-id="38523-216">The list of all index names for the search service.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNamesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;string&gt;&gt; ListNamesAsync (this Microsoft.Azure.Search.IIndexesOperations operations, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;string&gt;&gt; ListNamesAsync(class Microsoft.Azure.Search.IIndexesOperations operations, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.ListNamesAsync(Microsoft.Azure.Search.IIndexesOperations,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNamesAsync : Microsoft.Azure.Search.IIndexesOperations * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;string&gt;&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.ListNamesAsync (operations, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;ListNamesAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="38523-217">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="38523-217">The operations group for this extension method.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="38523-218">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="38523-218">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="38523-219">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="38523-219">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="38523-220">Azure Search サービスの使用可能なすべてのインデックスの名前を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="38523-220">Lists the names of all indexes available for an Azure Search service.</span></span> <span data-ttu-id="38523-221">このときに使用 List() の代わりにのみ必要なインデックスを作成する名前。</span><span class="sxs-lookup"><span data-stu-id="38523-221">Use this instead of List() when you only need index names.</span></span> <span data-ttu-id="38523-222">帯域幅とリソースの使用率は、検索サービスに多数のインデックスがある場合に特にに保存されます。</span><span class="sxs-lookup"><span data-stu-id="38523-222">It will save bandwidth and resource utilization, especially if your Search Service has many indexes.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Indexes" /></summary>
        <returns>
            <span data-ttu-id="38523-223">Search サービスのすべてのインデックス名の一覧。</span><span class="sxs-lookup"><span data-stu-id="38523-223">The list of all index names for the search service.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>