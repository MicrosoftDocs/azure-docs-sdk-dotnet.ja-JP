<Type Name="IDatasetOperations" FullName="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations">
  <TypeSignature Language="C#" Value="public interface IDatasetOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDatasetOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDatasetOperations" />
  <TypeSignature Language="F#" Value="type IDatasetOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c9b27-101">データセットを管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="c9b27-101">Operations for managing datasets.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.BeginCreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;" Usage="iDatasetOperations.BeginCreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c9b27-102">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c9b27-102">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c9b27-103">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c9b27-103">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c9b27-104">作成またはデータセットを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c9b27-104">The parameters required to create or update a dataset.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9b27-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c9b27-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9b27-106">データセットの新しいインスタンスを作成または既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="c9b27-106">Create a new dataset instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c9b27-107">CreateOrUpdate データセットの操作の応答。</span><span class="sxs-lookup"><span data-stu-id="c9b27-107">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync (string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync(string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.BeginCreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;" Usage="iDatasetOperations.BeginCreateOrUpdateWithRawJsonContentAsync (resourceGroupName, dataFactoryName, datasetName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c9b27-108">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c9b27-108">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c9b27-109">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c9b27-109">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="c9b27-110">一意のデータセットのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c9b27-110">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c9b27-111">作成またはデータセットを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c9b27-111">The parameters required to create or update a dataset.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9b27-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c9b27-112">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9b27-113">データセットの新しいインスタンスを作成または、生の json コンテンツを持つ既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="c9b27-113">Create a new dataset instance or update an existing instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c9b27-114">CreateOrUpdate データセットの操作の応答。</span><span class="sxs-lookup"><span data-stu-id="c9b27-114">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (string resourceGroupName, string dataFactoryName, string datasetName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(string resourceGroupName, string dataFactoryName, string datasetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.BeginDeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="iDatasetOperations.BeginDeleteAsync (resourceGroupName, dataFactoryName, datasetName, cancellationToken)" />
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
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c9b27-115">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c9b27-115">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c9b27-116">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c9b27-116">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="c9b27-117">データセットの名前。</span><span class="sxs-lookup"><span data-stu-id="c9b27-117">Name of the dataset.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9b27-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c9b27-118">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9b27-119">データセットのインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="c9b27-119">Delete a dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c9b27-120">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="c9b27-120">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;" Usage="iDatasetOperations.CreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c9b27-121">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c9b27-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c9b27-122">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c9b27-122">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c9b27-123">作成またはデータセットを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c9b27-123">The parameters required to create or update a dataset.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9b27-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c9b27-124">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9b27-125">データセットの新しいインスタンスを作成または既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="c9b27-125">Create a new dataset instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c9b27-126">CreateOrUpdate データセットの操作の応答。</span><span class="sxs-lookup"><span data-stu-id="c9b27-126">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.CreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;" Usage="iDatasetOperations.CreateOrUpdateWithRawJsonContentAsync (resourceGroupName, dataFactoryName, datasetName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c9b27-127">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c9b27-127">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c9b27-128">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c9b27-128">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="c9b27-129">一意のデータセットのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c9b27-129">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c9b27-130">作成またはデータセットを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c9b27-130">The parameters required to create or update a dataset.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9b27-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c9b27-131">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9b27-132">データセットの新しいインスタンスを作成または、生の json コンテンツを持つ既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="c9b27-132">Create a new dataset instance or update an existing instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c9b27-133">CreateOrUpdate データセットの操作の応答。</span><span class="sxs-lookup"><span data-stu-id="c9b27-133">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (string resourceGroupName, string dataFactoryName, string datasetName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(string resourceGroupName, string dataFactoryName, string datasetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="iDatasetOperations.DeleteAsync (resourceGroupName, dataFactoryName, datasetName, cancellationToken)" />
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
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c9b27-134">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c9b27-134">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c9b27-135">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c9b27-135">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="c9b27-136">データセットの名前。</span><span class="sxs-lookup"><span data-stu-id="c9b27-136">Name of the dataset.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9b27-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c9b27-137">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9b27-138">データセットのインスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="c9b27-138">Delete a dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c9b27-139">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="c9b27-139">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, string datasetName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, string datasetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetGetResponse&gt;" Usage="iDatasetOperations.GetAsync (resourceGroupName, dataFactoryName, datasetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c9b27-140">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c9b27-140">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c9b27-141">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c9b27-141">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="c9b27-142">データセットの名前。</span><span class="sxs-lookup"><span data-stu-id="c9b27-142">Name of the dataset.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9b27-143">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c9b27-143">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9b27-144">データセットのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="c9b27-144">Gets a dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c9b27-145">Get データセットの操作の応答。</span><span class="sxs-lookup"><span data-stu-id="c9b27-145">The Get dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (string operationStatusLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(string operationStatusLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.GetCreateOrUpdateStatusAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCreateOrUpdateStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;" Usage="iDatasetOperations.GetCreateOrUpdateStatusAsync (operationStatusLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationStatusLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationStatusLink">
            <span data-ttu-id="c9b27-146">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="c9b27-146">Location value returned by the Begin operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9b27-147">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c9b27-147">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="c9b27-148">CreateOrUpdate データセットの操作の応答。</span><span class="sxs-lookup"><span data-stu-id="c9b27-148">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt;" Usage="iDatasetOperations.ListAsync (resourceGroupName, dataFactoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c9b27-149">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="c9b27-149">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="c9b27-150">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="c9b27-150">A unique data factory instance name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9b27-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c9b27-151">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9b27-152">次のページへのリンクが、データ ファクトリ内のすべてのデータセットのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="c9b27-152">Gets all the dataset instances in a data factory with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c9b27-153">リストのデータセットの操作の応答。</span><span class="sxs-lookup"><span data-stu-id="c9b27-153">The List datasets operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt;" Usage="iDatasetOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="c9b27-154">[次へ] の [データセット] ページの url です。</span><span class="sxs-lookup"><span data-stu-id="c9b27-154">The url to the next datasets page.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9b27-155">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c9b27-155">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9b27-156">次のページへのリンクを持つデータセットのインスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="c9b27-156">Gets the next page of dataset instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c9b27-157">リストのデータセットの操作の応答。</span><span class="sxs-lookup"><span data-stu-id="c9b27-157">The List datasets operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>