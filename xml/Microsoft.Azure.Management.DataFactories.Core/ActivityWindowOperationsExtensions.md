<Type Name="ActivityWindowOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ActivityWindowOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ActivityWindowOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ActivityWindowOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ActivityWindowOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
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
    <Member MemberName="ListByDataFactory">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse ListByDataFactory (this Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse ListByDataFactory(class Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListByDataFactory(Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDataFactory (operations As IActivityWindowOperations, parameters As ActivityWindowsByDataFactoryListParameters) As ActivityWindowListResponse" />
      <MemberSignature Language="F#" Value="static member ListByDataFactory : Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListByDataFactory (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9ae15-101">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="9ae15-101">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9ae15-102">必須。</span><span class="sxs-lookup"><span data-stu-id="9ae15-102">Required.</span></span> <span data-ttu-id="9ae15-103">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="9ae15-103">Filter parameters for activity windows list.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9ae15-104">アクティビティの最初のページに、次のページへのリンクに data factory のウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="9ae15-104">Gets the first page of activity window instances for a data factory with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9ae15-105">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="9ae15-105">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDataFactoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListByDataFactoryAsync (this Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListByDataFactoryAsync(class Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListByDataFactoryAsync(Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDataFactoryAsync (operations As IActivityWindowOperations, parameters As ActivityWindowsByDataFactoryListParameters) As Task(Of ActivityWindowListResponse)" />
      <MemberSignature Language="F#" Value="static member ListByDataFactoryAsync : Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListByDataFactoryAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9ae15-106">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="9ae15-106">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9ae15-107">必須。</span><span class="sxs-lookup"><span data-stu-id="9ae15-107">Required.</span></span> <span data-ttu-id="9ae15-108">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="9ae15-108">Filter parameters for activity windows list.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9ae15-109">アクティビティの最初のページに、次のページへのリンクに data factory のウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="9ae15-109">Gets the first page of activity window instances for a data factory with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9ae15-110">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="9ae15-110">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDataset">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse ListByDataset (this Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse ListByDataset(class Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListByDataset(Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDataset (operations As IActivityWindowOperations, parameters As ActivityWindowsByDatasetListParameters) As ActivityWindowListResponse" />
      <MemberSignature Language="F#" Value="static member ListByDataset : Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListByDataset (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9ae15-111">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="9ae15-111">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9ae15-112">必須。</span><span class="sxs-lookup"><span data-stu-id="9ae15-112">Required.</span></span> <span data-ttu-id="9ae15-113">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="9ae15-113">Filter parameters for activity windows list.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9ae15-114">アクティビティの最初のページに、次のページへのリンクを含むデータセットのウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="9ae15-114">Gets the first page of activity window instances for a dataset with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9ae15-115">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="9ae15-115">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatasetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListByDatasetAsync (this Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListByDatasetAsync(class Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListByDatasetAsync(Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDatasetAsync (operations As IActivityWindowOperations, parameters As ActivityWindowsByDatasetListParameters) As Task(Of ActivityWindowListResponse)" />
      <MemberSignature Language="F#" Value="static member ListByDatasetAsync : Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListByDatasetAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9ae15-116">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="9ae15-116">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9ae15-117">必須。</span><span class="sxs-lookup"><span data-stu-id="9ae15-117">Required.</span></span> <span data-ttu-id="9ae15-118">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="9ae15-118">Filter parameters for activity windows list.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9ae15-119">アクティビティの最初のページに、次のページへのリンクを含むデータセットのウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="9ae15-119">Gets the first page of activity window instances for a dataset with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9ae15-120">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="9ae15-120">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByPipeline">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse ListByPipeline (this Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse ListByPipeline(class Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListByPipeline(Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByPipeline (operations As IActivityWindowOperations, parameters As ActivityWindowsByPipelineListParameters) As ActivityWindowListResponse" />
      <MemberSignature Language="F#" Value="static member ListByPipeline : Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListByPipeline (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9ae15-121">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="9ae15-121">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9ae15-122">必須。</span><span class="sxs-lookup"><span data-stu-id="9ae15-122">Required.</span></span> <span data-ttu-id="9ae15-123">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="9ae15-123">Filter parameters for activity windows list.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9ae15-124">次のページへのリンクがパイプラインのアクティビティの最初のページ ウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="9ae15-124">Gets the first page of activity window instances for a pipeline with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9ae15-125">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="9ae15-125">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByPipelineActivity">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse ListByPipelineActivity (this Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse ListByPipelineActivity(class Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListByPipelineActivity(Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByPipelineActivity (operations As IActivityWindowOperations, parameters As ActivityWindowsByActivityListParameters) As ActivityWindowListResponse" />
      <MemberSignature Language="F#" Value="static member ListByPipelineActivity : Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListByPipelineActivity (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9ae15-126">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="9ae15-126">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9ae15-127">必須。</span><span class="sxs-lookup"><span data-stu-id="9ae15-127">Required.</span></span> <span data-ttu-id="9ae15-128">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="9ae15-128">Filter parameters for activity windows list.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9ae15-129">次のページへのリンクがパイプラインのアクティビティのアクティビティの最初のページ ウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="9ae15-129">Gets the first page of activity window instances for a pipeline activity with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9ae15-130">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="9ae15-130">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByPipelineActivityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListByPipelineActivityAsync (this Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListByPipelineActivityAsync(class Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListByPipelineActivityAsync(Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByPipelineActivityAsync (operations As IActivityWindowOperations, parameters As ActivityWindowsByActivityListParameters) As Task(Of ActivityWindowListResponse)" />
      <MemberSignature Language="F#" Value="static member ListByPipelineActivityAsync : Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListByPipelineActivityAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9ae15-131">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="9ae15-131">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9ae15-132">必須。</span><span class="sxs-lookup"><span data-stu-id="9ae15-132">Required.</span></span> <span data-ttu-id="9ae15-133">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="9ae15-133">Filter parameters for activity windows list.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9ae15-134">次のページへのリンクがパイプラインのアクティビティのアクティビティの最初のページ ウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="9ae15-134">Gets the first page of activity window instances for a pipeline activity with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9ae15-135">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="9ae15-135">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByPipelineAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListByPipelineAsync (this Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListByPipelineAsync(class Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListByPipelineAsync(Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByPipelineAsync (operations As IActivityWindowOperations, parameters As ActivityWindowsByPipelineListParameters) As Task(Of ActivityWindowListResponse)" />
      <MemberSignature Language="F#" Value="static member ListByPipelineAsync : Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListByPipelineAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9ae15-136">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="9ae15-136">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9ae15-137">必須。</span><span class="sxs-lookup"><span data-stu-id="9ae15-137">Required.</span></span> <span data-ttu-id="9ae15-138">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="9ae15-138">Filter parameters for activity windows list.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9ae15-139">次のページへのリンクがパイプラインのアクティビティの最初のページ ウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="9ae15-139">Gets the first page of activity window instances for a pipeline with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9ae15-140">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="9ae15-140">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextByDataFactory">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse ListNextByDataFactory (this Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse ListNextByDataFactory(class Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListNextByDataFactory(Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations,System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextByDataFactory (operations As IActivityWindowOperations, nextLink As String, parameters As ActivityWindowsByDataFactoryListParameters) As ActivityWindowListResponse" />
      <MemberSignature Language="F#" Value="static member ListNextByDataFactory : Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations * string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListNextByDataFactory (operations, nextLink, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9ae15-141">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="9ae15-141">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="9ae15-142">必須。</span><span class="sxs-lookup"><span data-stu-id="9ae15-142">Required.</span></span> <span data-ttu-id="9ae15-143">アクティビティの windows の次のページの URL です。</span><span class="sxs-lookup"><span data-stu-id="9ae15-143">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9ae15-144">必須。</span><span class="sxs-lookup"><span data-stu-id="9ae15-144">Required.</span></span> <span data-ttu-id="9ae15-145">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="9ae15-145">Filter parameters for activity windows list.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9ae15-146">アクティビティの次のページに、次のページへのリンクがウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="9ae15-146">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9ae15-147">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="9ae15-147">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextByDataFactoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextByDataFactoryAsync (this Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextByDataFactoryAsync(class Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListNextByDataFactoryAsync(Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations,System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextByDataFactoryAsync (operations As IActivityWindowOperations, nextLink As String, parameters As ActivityWindowsByDataFactoryListParameters) As Task(Of ActivityWindowListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextByDataFactoryAsync : Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations * string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListNextByDataFactoryAsync (operations, nextLink, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9ae15-148">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="9ae15-148">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="9ae15-149">必須。</span><span class="sxs-lookup"><span data-stu-id="9ae15-149">Required.</span></span> <span data-ttu-id="9ae15-150">アクティビティの windows の次のページの URL です。</span><span class="sxs-lookup"><span data-stu-id="9ae15-150">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9ae15-151">必須。</span><span class="sxs-lookup"><span data-stu-id="9ae15-151">Required.</span></span> <span data-ttu-id="9ae15-152">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="9ae15-152">Filter parameters for activity windows list.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9ae15-153">アクティビティの次のページに、次のページへのリンクがウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="9ae15-153">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9ae15-154">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="9ae15-154">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextByDataset">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse ListNextByDataset (this Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse ListNextByDataset(class Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListNextByDataset(Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations,System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextByDataset (operations As IActivityWindowOperations, nextLink As String, parameters As ActivityWindowsByDatasetListParameters) As ActivityWindowListResponse" />
      <MemberSignature Language="F#" Value="static member ListNextByDataset : Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations * string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListNextByDataset (operations, nextLink, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9ae15-155">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="9ae15-155">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="9ae15-156">必須。</span><span class="sxs-lookup"><span data-stu-id="9ae15-156">Required.</span></span> <span data-ttu-id="9ae15-157">アクティビティの windows の次のページの URL です。</span><span class="sxs-lookup"><span data-stu-id="9ae15-157">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9ae15-158">必須。</span><span class="sxs-lookup"><span data-stu-id="9ae15-158">Required.</span></span> <span data-ttu-id="9ae15-159">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="9ae15-159">Filter parameters for activity windows list.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9ae15-160">アクティビティの次のページに、次のページへのリンクがウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="9ae15-160">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9ae15-161">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="9ae15-161">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextByDatasetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextByDatasetAsync (this Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextByDatasetAsync(class Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListNextByDatasetAsync(Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations,System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextByDatasetAsync (operations As IActivityWindowOperations, nextLink As String, parameters As ActivityWindowsByDatasetListParameters) As Task(Of ActivityWindowListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextByDatasetAsync : Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations * string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListNextByDatasetAsync (operations, nextLink, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9ae15-162">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="9ae15-162">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="9ae15-163">必須。</span><span class="sxs-lookup"><span data-stu-id="9ae15-163">Required.</span></span> <span data-ttu-id="9ae15-164">アクティビティの windows の次のページの URL です。</span><span class="sxs-lookup"><span data-stu-id="9ae15-164">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9ae15-165">必須。</span><span class="sxs-lookup"><span data-stu-id="9ae15-165">Required.</span></span> <span data-ttu-id="9ae15-166">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="9ae15-166">Filter parameters for activity windows list.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9ae15-167">アクティビティの次のページに、次のページへのリンクがウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="9ae15-167">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9ae15-168">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="9ae15-168">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextByPipeline">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse ListNextByPipeline (this Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse ListNextByPipeline(class Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListNextByPipeline(Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations,System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextByPipeline (operations As IActivityWindowOperations, nextLink As String, parameters As ActivityWindowsByPipelineListParameters) As ActivityWindowListResponse" />
      <MemberSignature Language="F#" Value="static member ListNextByPipeline : Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations * string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListNextByPipeline (operations, nextLink, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9ae15-169">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="9ae15-169">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="9ae15-170">必須。</span><span class="sxs-lookup"><span data-stu-id="9ae15-170">Required.</span></span> <span data-ttu-id="9ae15-171">アクティビティの windows の次のページの URL です。</span><span class="sxs-lookup"><span data-stu-id="9ae15-171">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9ae15-172">必須。</span><span class="sxs-lookup"><span data-stu-id="9ae15-172">Required.</span></span> <span data-ttu-id="9ae15-173">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="9ae15-173">Filter parameters for activity windows list.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9ae15-174">アクティビティの次のページに、次のページへのリンクがウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="9ae15-174">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9ae15-175">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="9ae15-175">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextByPipelineActivity">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse ListNextByPipelineActivity (this Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse ListNextByPipelineActivity(class Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListNextByPipelineActivity(Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations,System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextByPipelineActivity (operations As IActivityWindowOperations, nextLink As String, parameters As ActivityWindowsByActivityListParameters) As ActivityWindowListResponse" />
      <MemberSignature Language="F#" Value="static member ListNextByPipelineActivity : Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations * string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListNextByPipelineActivity (operations, nextLink, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9ae15-176">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="9ae15-176">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="9ae15-177">必須。</span><span class="sxs-lookup"><span data-stu-id="9ae15-177">Required.</span></span> <span data-ttu-id="9ae15-178">アクティビティの windows の次のページの URL です。</span><span class="sxs-lookup"><span data-stu-id="9ae15-178">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9ae15-179">必須。</span><span class="sxs-lookup"><span data-stu-id="9ae15-179">Required.</span></span> <span data-ttu-id="9ae15-180">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="9ae15-180">Filter parameters for activity windows list.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9ae15-181">アクティビティの次のページに、次のページへのリンクがウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="9ae15-181">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9ae15-182">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="9ae15-182">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextByPipelineActivityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextByPipelineActivityAsync (this Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextByPipelineActivityAsync(class Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListNextByPipelineActivityAsync(Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations,System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextByPipelineActivityAsync (operations As IActivityWindowOperations, nextLink As String, parameters As ActivityWindowsByActivityListParameters) As Task(Of ActivityWindowListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextByPipelineActivityAsync : Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations * string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListNextByPipelineActivityAsync (operations, nextLink, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9ae15-183">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="9ae15-183">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="9ae15-184">必須。</span><span class="sxs-lookup"><span data-stu-id="9ae15-184">Required.</span></span> <span data-ttu-id="9ae15-185">アクティビティの windows の次のページの URL です。</span><span class="sxs-lookup"><span data-stu-id="9ae15-185">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9ae15-186">必須。</span><span class="sxs-lookup"><span data-stu-id="9ae15-186">Required.</span></span> <span data-ttu-id="9ae15-187">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="9ae15-187">Filter parameters for activity windows list.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9ae15-188">アクティビティの次のページに、次のページへのリンクがウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="9ae15-188">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9ae15-189">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="9ae15-189">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextByPipelineAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextByPipelineAsync (this Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextByPipelineAsync(class Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations operations, string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListNextByPipelineAsync(Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations,System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextByPipelineAsync (operations As IActivityWindowOperations, nextLink As String, parameters As ActivityWindowsByPipelineListParameters) As Task(Of ActivityWindowListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextByPipelineAsync : Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations * string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.ActivityWindowOperationsExtensions.ListNextByPipelineAsync (operations, nextLink, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9ae15-190">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="9ae15-190">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="9ae15-191">必須。</span><span class="sxs-lookup"><span data-stu-id="9ae15-191">Required.</span></span> <span data-ttu-id="9ae15-192">アクティビティの windows の次のページの URL です。</span><span class="sxs-lookup"><span data-stu-id="9ae15-192">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="9ae15-193">必須。</span><span class="sxs-lookup"><span data-stu-id="9ae15-193">Required.</span></span> <span data-ttu-id="9ae15-194">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="9ae15-194">Filter parameters for activity windows list.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9ae15-195">アクティビティの次のページに、次のページへのリンクがウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="9ae15-195">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9ae15-196">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="9ae15-196">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>