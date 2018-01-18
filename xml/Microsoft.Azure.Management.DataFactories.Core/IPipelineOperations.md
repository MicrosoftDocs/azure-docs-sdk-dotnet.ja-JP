<Type Name="IPipelineOperations" FullName="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations">
  <TypeSignature Language="C#" Value="public interface IPipelineOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPipelineOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPipelineOperations" />
  <TypeSignature Language="F#" Value="type IPipelineOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4ae1f-101">パイプラインを管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-101">Operations for managing pipelines.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.BeginCreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;" Usage="iPipelineOperations.BeginCreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4ae1f-102">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-102">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4ae1f-103">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-103">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4ae1f-104">作成またはパイプラインを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-104">The parameters required to create or update a pipeline.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4ae1f-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4ae1f-106">作成またはパイプライン インスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-106">Create or update a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4ae1f-107">作成または更新パイプライン操作応答です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-107">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync (string resourceGroupName, string dataFactoryName, string dataPipelineName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync(string resourceGroupName, string dataFactoryName, string dataPipelineName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.BeginCreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;" Usage="iPipelineOperations.BeginCreateOrUpdateWithRawJsonContentAsync (resourceGroupName, dataFactoryName, dataPipelineName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4ae1f-108">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-108">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4ae1f-109">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-109">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="4ae1f-110">パイプラインの一意のインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-110">A unique pipeline instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4ae1f-111">パイプラインを作成するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-111">The parameters required to create a pipeline.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4ae1f-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-112">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4ae1f-113">生の json コンテンツを持つ新しいパイプライン インスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-113">Create a new pipeline instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4ae1f-114">作成または更新パイプライン操作応答です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-114">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (string resourceGroupName, string dataFactoryName, string dataPipelineName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(string resourceGroupName, string dataFactoryName, string dataPipelineName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.BeginDeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="iPipelineOperations.BeginDeleteAsync (resourceGroupName, dataFactoryName, dataPipelineName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4ae1f-115">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-115">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4ae1f-116">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-116">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="4ae1f-117">データ パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-117">Name of the data pipeline.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4ae1f-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-118">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4ae1f-119">パイプラインのインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-119">Delete a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4ae1f-120">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-120">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;" Usage="iPipelineOperations.CreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4ae1f-121">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4ae1f-122">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-122">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4ae1f-123">作成またはパイプラインを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-123">The parameters required to create or update a pipeline.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4ae1f-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-124">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4ae1f-125">作成またはパイプライン インスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-125">Create or update a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4ae1f-126">作成または更新パイプライン操作応答です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-126">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (string resourceGroupName, string dataFactoryName, string dataPipelineName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(string resourceGroupName, string dataFactoryName, string dataPipelineName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.CreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;" Usage="iPipelineOperations.CreateOrUpdateWithRawJsonContentAsync (resourceGroupName, dataFactoryName, dataPipelineName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4ae1f-127">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-127">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4ae1f-128">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-128">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="4ae1f-129">パイプラインの一意のインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-129">A unique pipeline instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4ae1f-130">作成またはパイプラインを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-130">The parameters required to create or update a pipeline.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4ae1f-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-131">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4ae1f-132">生の json コンテンツを持つ新しいパイプライン インスタンスを作成します。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-132">Create a new pipeline instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4ae1f-133">作成または更新パイプライン操作応答です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-133">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (string resourceGroupName, string dataFactoryName, string dataPipelineName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(string resourceGroupName, string dataFactoryName, string dataPipelineName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="iPipelineOperations.DeleteAsync (resourceGroupName, dataFactoryName, dataPipelineName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4ae1f-134">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-134">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4ae1f-135">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-135">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="4ae1f-136">データ パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-136">Name of the data pipeline.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4ae1f-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-137">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4ae1f-138">パイプラインのインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-138">Delete a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4ae1f-139">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-139">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, string dataPipelineName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, string dataPipelineName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse&gt;" Usage="iPipelineOperations.GetAsync (resourceGroupName, dataFactoryName, dataPipelineName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4ae1f-140">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-140">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4ae1f-141">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-141">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="4ae1f-142">データ パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-142">Name of the data pipeline.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4ae1f-143">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-143">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4ae1f-144">パイプライン インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-144">Gets a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4ae1f-145">Get パイプライン操作応答です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-145">The Get pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (string operationStatusLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(string operationStatusLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.GetCreateOrUpdateStatusAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCreateOrUpdateStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;" Usage="iPipelineOperations.GetCreateOrUpdateStatusAsync (operationStatusLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationStatusLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationStatusLink">
            <span data-ttu-id="4ae1f-146">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-146">Location value returned by the Begin operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4ae1f-147">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-147">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="4ae1f-148">作成または更新パイプライン操作応答です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-148">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt;" Usage="iPipelineOperations.ListAsync (resourceGroupName, dataFactoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4ae1f-149">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-149">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4ae1f-150">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-150">A unique data factory instance name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4ae1f-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-151">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4ae1f-152">次のページへのリンクを持つパイプライン インスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-152">Gets the first page of pipeline instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4ae1f-153">リストのパイプライン操作の応答。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-153">The List pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt;" Usage="iPipelineOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="4ae1f-154">パイプラインの次のページの url です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-154">The url to the next pipelines page.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4ae1f-155">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-155">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4ae1f-156">次のページへのリンクを持つパイプライン インスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-156">Gets the next page of pipeline instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4ae1f-157">リストのパイプライン操作の応答。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-157">The List pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync (string resourceGroupName, string dataFactoryName, string dataPipelineName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync(string resourceGroupName, string dataFactoryName, string dataPipelineName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.ResumeAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResumeAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iPipelineOperations.ResumeAsync (resourceGroupName, dataFactoryName, dataPipelineName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4ae1f-158">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-158">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4ae1f-159">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-159">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="4ae1f-160">データ パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-160">Name of the data pipeline.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4ae1f-161">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-161">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4ae1f-162">中断されたパイプラインが再開されます。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-162">Resume a suspended pipeline.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4ae1f-163">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="4ae1f-163">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetActivePeriodAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; SetActivePeriodAsync (string resourceGroupName, string dataFactoryName, string dataPipelineName, Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; SetActivePeriodAsync(string resourceGroupName, string dataFactoryName, string dataPipelineName, class Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.SetActivePeriodAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetActivePeriodAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iPipelineOperations.SetActivePeriodAsync (resourceGroupName, dataFactoryName, dataPipelineName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4ae1f-164">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-164">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4ae1f-165">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-165">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="4ae1f-166">データ パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-166">Name of the data pipeline.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4ae1f-167">パイプラインのアクティブな期間を設定するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-167">Parameters required to set the active period of a pipeline.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4ae1f-168">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-168">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4ae1f-169">パイプラインのアクティブな期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-169">Sets the active period of a pipeline.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4ae1f-170">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="4ae1f-170">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync (string resourceGroupName, string dataFactoryName, string dataPipelineName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync(string resourceGroupName, string dataFactoryName, string dataPipelineName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.SuspendAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SuspendAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iPipelineOperations.SuspendAsync (resourceGroupName, dataFactoryName, dataPipelineName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4ae1f-171">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-171">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="4ae1f-172">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-172">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="4ae1f-173">データ パイプラインの名前です。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-173">Name of the data pipeline.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4ae1f-174">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-174">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4ae1f-175">実行中のパイプラインを中断します。</span><span class="sxs-lookup"><span data-stu-id="4ae1f-175">Suspend a running pipeline.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4ae1f-176">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="4ae1f-176">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>