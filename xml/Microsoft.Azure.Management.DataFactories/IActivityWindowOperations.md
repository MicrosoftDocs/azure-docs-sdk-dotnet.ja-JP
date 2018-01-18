<Type Name="IActivityWindowOperations" FullName="Microsoft.Azure.Management.DataFactories.IActivityWindowOperations">
  <TypeSignature Language="C#" Value="public interface IActivityWindowOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActivityWindowOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActivityWindowOperations" />
  <TypeSignature Language="F#" Value="type IActivityWindowOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="36acd-101">アクティビティ ウィンドウの操作。</span><span class="sxs-lookup"><span data-stu-id="36acd-101">Operations for activity windows.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync (Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations.ListAsync(Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListAsync (parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="36acd-102">パイプラインのアクティビティのパラメーターでアクティビティ windows 一覧。</span><span class="sxs-lookup"><span data-stu-id="36acd-102">Activity windows list by pipeline activity parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="36acd-103">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="36acd-103">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="36acd-104">次のページへのリンクがパイプラインのアクティビティのアクティビティの最初のページ ウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="36acd-104">Gets the first page of activity window instances for a pipeline activity with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="36acd-105">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="36acd-105">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync (Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations.ListAsync(Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListAsync (parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="36acd-106">アクティビティ ウィンドウは、オプションのフィルター パラメーターを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="36acd-106">Activity windows list optional filter parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="36acd-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="36acd-107">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="36acd-108">アクティビティの最初のページに、次のページへのリンクに data factory のウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="36acd-108">Gets the first page of activity window instances for a data factory with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="36acd-109">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="36acd-109">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync (Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations.ListAsync(Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListAsync (parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="36acd-110">データセット パラメーターによってアクティビティ windows 一覧。</span><span class="sxs-lookup"><span data-stu-id="36acd-110">Activity windows list by dataset parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="36acd-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="36acd-111">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="36acd-112">アクティビティの最初のページに、次のページへのリンクを含むデータセットのウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="36acd-112">Gets the first page of activity window instances for a dataset with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="36acd-113">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="36acd-113">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync (Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations.ListAsync(Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListAsync (parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="36acd-114">パイプラインのパラメーターでアクティビティ windows 一覧。</span><span class="sxs-lookup"><span data-stu-id="36acd-114">Activity windows list by pipeline parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="36acd-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="36acd-115">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="36acd-116">次のページへのリンクがパイプラインのアクティビティの最初のページ ウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="36acd-116">Gets the first page of activity window instances for a pipeline with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="36acd-117">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="36acd-117">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync (string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync(string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations.ListNextAsync(System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListNextAsync (nextLink, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="36acd-118">アクティビティの windows の次のページの URL です。</span><span class="sxs-lookup"><span data-stu-id="36acd-118">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="36acd-119">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="36acd-119">Filter parameters for activity windows list.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="36acd-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="36acd-120">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="36acd-121">アクティビティの次のページに、次のページへのリンクがウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="36acd-121">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="36acd-122">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="36acd-122">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync (string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync(string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations.ListNextAsync(System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListNextAsync (nextLink, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="36acd-123">アクティビティの windows の次のページの URL です。</span><span class="sxs-lookup"><span data-stu-id="36acd-123">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="36acd-124">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="36acd-124">Filter parameters for activity windows list.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="36acd-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="36acd-125">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="36acd-126">アクティビティの次のページに、次のページへのリンクがウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="36acd-126">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="36acd-127">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="36acd-127">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync (string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync(string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations.ListNextAsync(System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListNextAsync (nextLink, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="36acd-128">アクティビティの windows の次のページの URL です。</span><span class="sxs-lookup"><span data-stu-id="36acd-128">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="36acd-129">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="36acd-129">Filter parameters for activity windows list.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="36acd-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="36acd-130">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="36acd-131">アクティビティの次のページに、次のページへのリンクがウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="36acd-131">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="36acd-132">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="36acd-132">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync (string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync(string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations.ListNextAsync(System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListNextAsync (nextLink, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="36acd-133">アクティビティの windows の次のページの URL です。</span><span class="sxs-lookup"><span data-stu-id="36acd-133">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="36acd-134">アクティビティ ウィンドウの一覧のフィルタ リングします。</span><span class="sxs-lookup"><span data-stu-id="36acd-134">Filter parameters for activity windows list.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="36acd-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="36acd-135">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="36acd-136">アクティビティの次のページに、次のページへのリンクがウィンドウのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="36acd-136">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="36acd-137">リスト アクティビティ windows 操作応答です。</span><span class="sxs-lookup"><span data-stu-id="36acd-137">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>