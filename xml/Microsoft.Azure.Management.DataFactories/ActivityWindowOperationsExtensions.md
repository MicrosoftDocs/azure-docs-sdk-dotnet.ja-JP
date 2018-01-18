<Type Name="ActivityWindowOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ActivityWindowOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ActivityWindowOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions" />
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
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse List (this Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse List(class Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.List(Microsoft.Azure.Management.DataFactories.IActivityWindowOperations,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IActivityWindowOperations, parameters As ActivityWindowsByActivityListParameters) As ActivityWindowListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactories.IActivityWindowOperations * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse" Usage="Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.List (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityWindowOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22ecd-101">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="22ecd-101">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="22ecd-102">必須。</span><span class="sxs-lookup"><span data-stu-id="22ecd-102">Required.</span></span> <span data-ttu-id="22ecd-103">パイプラインのアクティビティのパラメーターでアクティビティ windows 一覧。</span><span class="sxs-lookup"><span data-stu-id="22ecd-103">Activity windows list by pipeline activity parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="22ecd-104">次のページへのリンクがパイプラインのアクティビティのアクティビティの最初のページ ウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="22ecd-104">Gets the first page of activity window instances for a pipeline activity with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="22ecd-105">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="22ecd-105">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse List (this Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse List(class Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.List(Microsoft.Azure.Management.DataFactories.IActivityWindowOperations,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IActivityWindowOperations, parameters As ActivityWindowsByDataFactoryListParameters) As ActivityWindowListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactories.IActivityWindowOperations * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse" Usage="Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.List (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityWindowOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22ecd-106">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="22ecd-106">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="22ecd-107">必須。</span><span class="sxs-lookup"><span data-stu-id="22ecd-107">Required.</span></span> <span data-ttu-id="22ecd-108">アクティビティ ウィンドウは、オプションのフィルター パラメーターを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="22ecd-108">Activity windows list optional filter parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="22ecd-109">アクティビティの最初のページに、次のページへのリンクに data factory のウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="22ecd-109">Gets the first page of activity window instances for a data factory with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="22ecd-110">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="22ecd-110">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse List (this Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse List(class Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.List(Microsoft.Azure.Management.DataFactories.IActivityWindowOperations,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IActivityWindowOperations, parameters As ActivityWindowsByDatasetListParameters) As ActivityWindowListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactories.IActivityWindowOperations * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse" Usage="Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.List (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityWindowOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22ecd-111">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="22ecd-111">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="22ecd-112">必須。</span><span class="sxs-lookup"><span data-stu-id="22ecd-112">Required.</span></span> <span data-ttu-id="22ecd-113">データセット パラメーターによってアクティビティ windows 一覧。</span><span class="sxs-lookup"><span data-stu-id="22ecd-113">Activity windows list by dataset parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="22ecd-114">アクティビティの最初のページに、次のページへのリンクを含むデータセットのウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="22ecd-114">Gets the first page of activity window instances for a dataset with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="22ecd-115">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="22ecd-115">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse List (this Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse List(class Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.List(Microsoft.Azure.Management.DataFactories.IActivityWindowOperations,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IActivityWindowOperations, parameters As ActivityWindowsByPipelineListParameters) As ActivityWindowListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactories.IActivityWindowOperations * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse" Usage="Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.List (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityWindowOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22ecd-116">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="22ecd-116">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="22ecd-117">必須。</span><span class="sxs-lookup"><span data-stu-id="22ecd-117">Required.</span></span> <span data-ttu-id="22ecd-118">パイプラインのパラメーターでアクティビティ windows 一覧。</span><span class="sxs-lookup"><span data-stu-id="22ecd-118">Activity windows list by pipeline parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="22ecd-119">次のページへのリンクがパイプラインのアクティビティの最初のページ ウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="22ecd-119">Gets the first page of activity window instances for a pipeline with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="22ecd-120">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="22ecd-120">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync (this Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactories.IActivityWindowOperations,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IActivityWindowOperations, parameters As ActivityWindowsByActivityListParameters) As Task(Of ActivityWindowListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactories.IActivityWindowOperations * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.ListAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityWindowOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22ecd-121">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="22ecd-121">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="22ecd-122">必須。</span><span class="sxs-lookup"><span data-stu-id="22ecd-122">Required.</span></span> <span data-ttu-id="22ecd-123">パイプラインのアクティビティのパラメーターでアクティビティ windows 一覧。</span><span class="sxs-lookup"><span data-stu-id="22ecd-123">Activity windows list by pipeline activity parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="22ecd-124">次のページへのリンクがパイプラインのアクティビティのアクティビティの最初のページ ウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="22ecd-124">Gets the first page of activity window instances for a pipeline activity with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="22ecd-125">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="22ecd-125">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync (this Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactories.IActivityWindowOperations,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IActivityWindowOperations, parameters As ActivityWindowsByDataFactoryListParameters) As Task(Of ActivityWindowListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactories.IActivityWindowOperations * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.ListAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityWindowOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22ecd-126">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="22ecd-126">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="22ecd-127">必須。</span><span class="sxs-lookup"><span data-stu-id="22ecd-127">Required.</span></span> <span data-ttu-id="22ecd-128">アクティビティ ウィンドウは、オプションのフィルター パラメーターを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="22ecd-128">Activity windows list optional filter parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="22ecd-129">アクティビティの最初のページに、次のページへのリンクに data factory のウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="22ecd-129">Gets the first page of activity window instances for a data factory with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="22ecd-130">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="22ecd-130">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync (this Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactories.IActivityWindowOperations,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IActivityWindowOperations, parameters As ActivityWindowsByDatasetListParameters) As Task(Of ActivityWindowListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactories.IActivityWindowOperations * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.ListAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityWindowOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22ecd-131">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="22ecd-131">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="22ecd-132">必須。</span><span class="sxs-lookup"><span data-stu-id="22ecd-132">Required.</span></span> <span data-ttu-id="22ecd-133">データセット パラメーターによってアクティビティ windows 一覧。</span><span class="sxs-lookup"><span data-stu-id="22ecd-133">Activity windows list by dataset parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="22ecd-134">アクティビティの最初のページに、次のページへのリンクを含むデータセットのウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="22ecd-134">Gets the first page of activity window instances for a dataset with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="22ecd-135">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="22ecd-135">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync (this Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactories.IActivityWindowOperations,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IActivityWindowOperations, parameters As ActivityWindowsByPipelineListParameters) As Task(Of ActivityWindowListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactories.IActivityWindowOperations * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.ListAsync (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityWindowOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22ecd-136">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="22ecd-136">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="22ecd-137">必須。</span><span class="sxs-lookup"><span data-stu-id="22ecd-137">Required.</span></span> <span data-ttu-id="22ecd-138">パイプラインのパラメーターでアクティビティ windows 一覧。</span><span class="sxs-lookup"><span data-stu-id="22ecd-138">Activity windows list by pipeline parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="22ecd-139">次のページへのリンクがパイプラインのアクティビティの最初のページ ウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="22ecd-139">Gets the first page of activity window instances for a pipeline with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="22ecd-140">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="22ecd-140">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByPipelineActivity">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse ListByPipelineActivity (this Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse ListByPipelineActivity(class Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.ListByPipelineActivity(Microsoft.Azure.Management.DataFactories.IActivityWindowOperations,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByPipelineActivity (operations As IActivityWindowOperations, parameters As ActivityWindowsByActivityListParameters) As ActivityWindowListResponse" />
      <MemberSignature Language="F#" Value="static member ListByPipelineActivity : Microsoft.Azure.Management.DataFactories.IActivityWindowOperations * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse" Usage="Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.ListByPipelineActivity (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityWindowOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22ecd-141">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="22ecd-141">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="22ecd-142">必須。</span><span class="sxs-lookup"><span data-stu-id="22ecd-142">Required.</span></span> <span data-ttu-id="22ecd-143">パイプラインのアクティビティのパラメーターでアクティビティ windows 一覧。</span><span class="sxs-lookup"><span data-stu-id="22ecd-143">Activity windows list by pipeline activity parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="22ecd-144">代わりにリスト (ActivityWindowsByActivityListParameters パラメーター) を使用します。</span><span class="sxs-lookup"><span data-stu-id="22ecd-144">Use List(ActivityWindowsByActivityListParameters parameters) instead.</span></span> <span data-ttu-id="22ecd-145">これは間もなく廃止される予定です。</span><span class="sxs-lookup"><span data-stu-id="22ecd-145">This will be deprecated soon.</span></span>
            <span data-ttu-id="22ecd-146">次のページへのリンクがパイプラインのアクティビティのアクティビティの最初のページ ウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="22ecd-146">Gets the first page of activity window instances for a pipeline activity with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="22ecd-147">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="22ecd-147">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse ListNext (this Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse ListNext(class Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.ListNext(Microsoft.Azure.Management.DataFactories.IActivityWindowOperations,System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IActivityWindowOperations, nextLink As String, parameters As ActivityWindowsByActivityListParameters) As ActivityWindowListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataFactories.IActivityWindowOperations * string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse" Usage="Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.ListNext (operations, nextLink, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityWindowOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22ecd-148">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="22ecd-148">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="22ecd-149">必須。</span><span class="sxs-lookup"><span data-stu-id="22ecd-149">Required.</span></span> <span data-ttu-id="22ecd-150">アクティビティの windows の次のページの URL です。</span><span class="sxs-lookup"><span data-stu-id="22ecd-150">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="22ecd-151">必須。</span><span class="sxs-lookup"><span data-stu-id="22ecd-151">Required.</span></span> <span data-ttu-id="22ecd-152">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="22ecd-152">Filter parameters for activity windows list.</span></span>
            </param>
        <summary>
            <span data-ttu-id="22ecd-153">アクティビティの次のページに、次のページへのリンクがウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="22ecd-153">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="22ecd-154">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="22ecd-154">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse ListNext (this Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse ListNext(class Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.ListNext(Microsoft.Azure.Management.DataFactories.IActivityWindowOperations,System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IActivityWindowOperations, nextLink As String, parameters As ActivityWindowsByDataFactoryListParameters) As ActivityWindowListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataFactories.IActivityWindowOperations * string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse" Usage="Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.ListNext (operations, nextLink, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityWindowOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22ecd-155">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="22ecd-155">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="22ecd-156">必須。</span><span class="sxs-lookup"><span data-stu-id="22ecd-156">Required.</span></span> <span data-ttu-id="22ecd-157">アクティビティの windows の次のページの URL です。</span><span class="sxs-lookup"><span data-stu-id="22ecd-157">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="22ecd-158">必須。</span><span class="sxs-lookup"><span data-stu-id="22ecd-158">Required.</span></span> <span data-ttu-id="22ecd-159">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="22ecd-159">Filter parameters for activity windows list.</span></span>
            </param>
        <summary>
            <span data-ttu-id="22ecd-160">アクティビティの次のページに、次のページへのリンクがウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="22ecd-160">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="22ecd-161">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="22ecd-161">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse ListNext (this Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse ListNext(class Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.ListNext(Microsoft.Azure.Management.DataFactories.IActivityWindowOperations,System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IActivityWindowOperations, nextLink As String, parameters As ActivityWindowsByDatasetListParameters) As ActivityWindowListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataFactories.IActivityWindowOperations * string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse" Usage="Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.ListNext (operations, nextLink, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityWindowOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22ecd-162">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="22ecd-162">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="22ecd-163">必須。</span><span class="sxs-lookup"><span data-stu-id="22ecd-163">Required.</span></span> <span data-ttu-id="22ecd-164">アクティビティの windows の次のページの URL です。</span><span class="sxs-lookup"><span data-stu-id="22ecd-164">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="22ecd-165">必須。</span><span class="sxs-lookup"><span data-stu-id="22ecd-165">Required.</span></span> <span data-ttu-id="22ecd-166">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="22ecd-166">Filter parameters for activity windows list.</span></span>
            </param>
        <summary>
            <span data-ttu-id="22ecd-167">アクティビティの次のページに、次のページへのリンクがウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="22ecd-167">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="22ecd-168">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="22ecd-168">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse ListNext (this Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse ListNext(class Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.ListNext(Microsoft.Azure.Management.DataFactories.IActivityWindowOperations,System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IActivityWindowOperations, nextLink As String, parameters As ActivityWindowsByPipelineListParameters) As ActivityWindowListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataFactories.IActivityWindowOperations * string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse" Usage="Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.ListNext (operations, nextLink, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityWindowOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22ecd-169">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="22ecd-169">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="22ecd-170">必須。</span><span class="sxs-lookup"><span data-stu-id="22ecd-170">Required.</span></span> <span data-ttu-id="22ecd-171">アクティビティの windows の次のページの URL です。</span><span class="sxs-lookup"><span data-stu-id="22ecd-171">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="22ecd-172">必須。</span><span class="sxs-lookup"><span data-stu-id="22ecd-172">Required.</span></span> <span data-ttu-id="22ecd-173">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="22ecd-173">Filter parameters for activity windows list.</span></span>
            </param>
        <summary>
            <span data-ttu-id="22ecd-174">アクティビティの次のページに、次のページへのリンクがウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="22ecd-174">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="22ecd-175">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="22ecd-175">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataFactories.IActivityWindowOperations,System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IActivityWindowOperations, nextLink As String, parameters As ActivityWindowsByActivityListParameters) As Task(Of ActivityWindowListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataFactories.IActivityWindowOperations * string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.ListNextAsync (operations, nextLink, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityWindowOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22ecd-176">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="22ecd-176">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="22ecd-177">必須。</span><span class="sxs-lookup"><span data-stu-id="22ecd-177">Required.</span></span> <span data-ttu-id="22ecd-178">アクティビティの windows の次のページの URL です。</span><span class="sxs-lookup"><span data-stu-id="22ecd-178">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="22ecd-179">必須。</span><span class="sxs-lookup"><span data-stu-id="22ecd-179">Required.</span></span> <span data-ttu-id="22ecd-180">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="22ecd-180">Filter parameters for activity windows list.</span></span>
            </param>
        <summary>
            <span data-ttu-id="22ecd-181">アクティビティの次のページに、次のページへのリンクがウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="22ecd-181">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="22ecd-182">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="22ecd-182">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataFactories.IActivityWindowOperations,System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IActivityWindowOperations, nextLink As String, parameters As ActivityWindowsByDataFactoryListParameters) As Task(Of ActivityWindowListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataFactories.IActivityWindowOperations * string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.ListNextAsync (operations, nextLink, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityWindowOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22ecd-183">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="22ecd-183">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="22ecd-184">必須。</span><span class="sxs-lookup"><span data-stu-id="22ecd-184">Required.</span></span> <span data-ttu-id="22ecd-185">アクティビティの windows の次のページの URL です。</span><span class="sxs-lookup"><span data-stu-id="22ecd-185">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="22ecd-186">必須。</span><span class="sxs-lookup"><span data-stu-id="22ecd-186">Required.</span></span> <span data-ttu-id="22ecd-187">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="22ecd-187">Filter parameters for activity windows list.</span></span>
            </param>
        <summary>
            <span data-ttu-id="22ecd-188">アクティビティの次のページに、次のページへのリンクがウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="22ecd-188">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="22ecd-189">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="22ecd-189">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataFactories.IActivityWindowOperations,System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IActivityWindowOperations, nextLink As String, parameters As ActivityWindowsByDatasetListParameters) As Task(Of ActivityWindowListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataFactories.IActivityWindowOperations * string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.ListNextAsync (operations, nextLink, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityWindowOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22ecd-190">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="22ecd-190">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="22ecd-191">必須。</span><span class="sxs-lookup"><span data-stu-id="22ecd-191">Required.</span></span> <span data-ttu-id="22ecd-192">アクティビティの windows の次のページの URL です。</span><span class="sxs-lookup"><span data-stu-id="22ecd-192">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="22ecd-193">必須。</span><span class="sxs-lookup"><span data-stu-id="22ecd-193">Required.</span></span> <span data-ttu-id="22ecd-194">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="22ecd-194">Filter parameters for activity windows list.</span></span>
            </param>
        <summary>
            <span data-ttu-id="22ecd-195">アクティビティの次のページに、次のページへのリンクがウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="22ecd-195">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="22ecd-196">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="22ecd-196">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.DataFactories.IActivityWindowOperations operations, string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataFactories.IActivityWindowOperations,System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IActivityWindowOperations, nextLink As String, parameters As ActivityWindowsByPipelineListParameters) As Task(Of ActivityWindowListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataFactories.IActivityWindowOperations * string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.ActivityWindowOperationsExtensions.ListNextAsync (operations, nextLink, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IActivityWindowOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22ecd-197">Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="22ecd-197">Reference to the Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="22ecd-198">必須。</span><span class="sxs-lookup"><span data-stu-id="22ecd-198">Required.</span></span> <span data-ttu-id="22ecd-199">アクティビティの windows の次のページの URL です。</span><span class="sxs-lookup"><span data-stu-id="22ecd-199">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="22ecd-200">必須。</span><span class="sxs-lookup"><span data-stu-id="22ecd-200">Required.</span></span> <span data-ttu-id="22ecd-201">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="22ecd-201">Filter parameters for activity windows list.</span></span>
            </param>
        <summary>
            <span data-ttu-id="22ecd-202">アクティビティの次のページに、次のページへのリンクがウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="22ecd-202">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="22ecd-203">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="22ecd-203">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>