<Type Name="IHubOperations" FullName="Microsoft.Azure.Management.DataFactories.Core.IHubOperations">
  <TypeSignature Language="C#" Value="public interface IHubOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IHubOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.IHubOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IHubOperations" />
  <TypeSignature Language="F#" Value="type IHubOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0d84f-101">ハブを管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="0d84f-101">Operations for managing hubs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IHubOperations.BeginCreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt;" Usage="iHubOperations.BeginCreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0d84f-102">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="0d84f-102">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0d84f-103">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="0d84f-103">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0d84f-104">作成またはハブを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="0d84f-104">The parameters required to create or update a hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0d84f-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0d84f-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0d84f-106">新しいハブ インスタンスを作成または既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="0d84f-106">Create a new hub instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0d84f-107">作成または更新ハブ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="0d84f-107">The create or update hub operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (string resourceGroupName, string dataFactoryName, string hubName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(string resourceGroupName, string dataFactoryName, string hubName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IHubOperations.BeginDeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="iHubOperations.BeginDeleteAsync (resourceGroupName, dataFactoryName, hubName, cancellationToken)" />
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
        <Parameter Name="hubName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0d84f-108">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="0d84f-108">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0d84f-109">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="0d84f-109">The name of the data factory.</span></span>
            </param>
        <param name="hubName">
            <span data-ttu-id="0d84f-110">ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="0d84f-110">The name of the hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0d84f-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0d84f-111">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0d84f-112">ハブ インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="0d84f-112">Delete a hub instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0d84f-113">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="0d84f-113">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IHubOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt;" Usage="iHubOperations.CreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0d84f-114">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="0d84f-114">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0d84f-115">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="0d84f-115">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0d84f-116">作成またはハブを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="0d84f-116">The parameters required to create or update a hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0d84f-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0d84f-117">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0d84f-118">新しいハブ インスタンスを作成または既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="0d84f-118">Create a new hub instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0d84f-119">作成または更新ハブ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="0d84f-119">The create or update hub operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (string resourceGroupName, string dataFactoryName, string hubName, Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateWithRawJsonContentParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(string resourceGroupName, string dataFactoryName, string hubName, class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateWithRawJsonContentParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IHubOperations.CreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt;" Usage="iHubOperations.CreateOrUpdateWithRawJsonContentAsync (resourceGroupName, dataFactoryName, hubName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="hubName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateWithRawJsonContentParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0d84f-120">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="0d84f-120">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0d84f-121">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="0d84f-121">The name of the data factory.</span></span>
            </param>
        <param name="hubName">
            <span data-ttu-id="0d84f-122">作成または更新するデータ ファクトリのハブの名前。</span><span class="sxs-lookup"><span data-stu-id="0d84f-122">The name of the data factory hub to be created or updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0d84f-123">作成またはハブを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="0d84f-123">The parameters required to create or update a hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0d84f-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0d84f-124">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0d84f-125">新しいハブ インスタンスを作成または既存のインスタンスを更新します。</span><span class="sxs-lookup"><span data-stu-id="0d84f-125">Create a new hub instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0d84f-126">作成または更新ハブ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="0d84f-126">The create or update hub operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (string resourceGroupName, string dataFactoryName, string hubName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(string resourceGroupName, string dataFactoryName, string hubName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IHubOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="iHubOperations.DeleteAsync (resourceGroupName, dataFactoryName, hubName, cancellationToken)" />
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
        <Parameter Name="hubName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0d84f-127">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="0d84f-127">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0d84f-128">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="0d84f-128">The name of the data factory.</span></span>
            </param>
        <param name="hubName">
            <span data-ttu-id="0d84f-129">ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="0d84f-129">The name of the hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0d84f-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0d84f-130">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0d84f-131">ハブ インスタンスを削除します。</span><span class="sxs-lookup"><span data-stu-id="0d84f-131">Delete a hub instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0d84f-132">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="0d84f-132">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, string hubName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.HubGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, string hubName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IHubOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubGetResponse&gt;" Usage="iHubOperations.GetAsync (resourceGroupName, dataFactoryName, hubName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="hubName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0d84f-133">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="0d84f-133">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0d84f-134">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="0d84f-134">The name of the data factory.</span></span>
            </param>
        <param name="hubName">
            <span data-ttu-id="0d84f-135">ハブの名前。</span><span class="sxs-lookup"><span data-stu-id="0d84f-135">The name of the hub.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0d84f-136">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0d84f-136">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0d84f-137">ハブ インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="0d84f-137">Gets a hub instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0d84f-138">Get ハブ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="0d84f-138">The get hub operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (string operationStatusLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(string operationStatusLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IHubOperations.GetCreateOrUpdateStatusAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCreateOrUpdateStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt;" Usage="iHubOperations.GetCreateOrUpdateStatusAsync (operationStatusLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationStatusLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationStatusLink">
            <span data-ttu-id="0d84f-139">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="0d84f-139">Location value returned by the Begin operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0d84f-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0d84f-140">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="0d84f-141">作成または更新ハブ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="0d84f-141">The create or update hub operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.HubListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IHubOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubListResponse&gt;" Usage="iHubOperations.ListAsync (resourceGroupName, dataFactoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="0d84f-142">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="0d84f-142">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="0d84f-143">データ ファクトリの名前。</span><span class="sxs-lookup"><span data-stu-id="0d84f-143">The name of the data factory.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0d84f-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0d84f-144">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0d84f-145">次のページへのリンクがデータ ファクトリのハブ インスタンスの最初のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="0d84f-145">Gets the first page of data factory hub instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0d84f-146">リストのハブ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="0d84f-146">The list hub operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.HubListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IHubOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubListResponse&gt;" Usage="iHubOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.HubListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="0d84f-147">次のデータ ファクトリのハブ ページの url です。</span><span class="sxs-lookup"><span data-stu-id="0d84f-147">The url to the next data factory hubs page.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0d84f-148">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0d84f-148">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0d84f-149">次のページへのリンクがデータ ファクトリのハブ インスタンスの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="0d84f-149">Gets the next page of data factory hub instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="0d84f-150">リストのハブ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="0d84f-150">The list hub operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>