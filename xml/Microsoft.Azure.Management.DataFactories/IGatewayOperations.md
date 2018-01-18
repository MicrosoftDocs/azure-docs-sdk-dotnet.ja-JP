<Type Name="IGatewayOperations" FullName="Microsoft.Azure.Management.DataFactories.IGatewayOperations">
  <TypeSignature Language="C#" Value="public interface IGatewayOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IGatewayOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.IGatewayOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IGatewayOperations" />
  <TypeSignature Language="F#" Value="type IGatewayOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="21252-101">データ ファクトリのゲートウェイを管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="21252-101">Operations for managing data factory gateways.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IGatewayOperations.BeginCreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;" Usage="iGatewayOperations.BeginCreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="21252-102">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="21252-102">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="21252-103">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="21252-103">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="21252-104">作成またはデータ ファクトリのゲートウェイを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="21252-104">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="21252-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="21252-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="21252-106">作成またはデータ ファクトリのゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="21252-106">Create or update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="21252-107">作成または更新データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="21252-107">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (string resourceGroupName, string dataFactoryName, string gatewayName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(string resourceGroupName, string dataFactoryName, string gatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IGatewayOperations.BeginDeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="iGatewayOperations.BeginDeleteAsync (resourceGroupName, dataFactoryName, gatewayName, cancellationToken)" />
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
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="21252-108">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="21252-108">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="21252-109">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="21252-109">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="21252-110">削除するゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="21252-110">Name of the gateway to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="21252-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="21252-111">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="21252-112">データ ファクトリのゲートウェイを削除します。</span><span class="sxs-lookup"><span data-stu-id="21252-112">Delete a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="21252-113">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="21252-113">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IGatewayOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;" Usage="iGatewayOperations.CreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="21252-114">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="21252-114">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="21252-115">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="21252-115">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="21252-116">作成またはデータ ファクトリのゲートウェイを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="21252-116">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="21252-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="21252-117">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="21252-118">作成またはデータ ファクトリのゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="21252-118">Create or update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="21252-119">作成または更新データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="21252-119">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string dataFactoryName, string gatewayName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string dataFactoryName, string gatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IGatewayOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iGatewayOperations.DeleteAsync (resourceGroupName, dataFactoryName, gatewayName, cancellationToken)" />
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
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="21252-120">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="21252-120">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="21252-121">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="21252-121">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="21252-122">削除するゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="21252-122">Name of the gateway to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="21252-123">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="21252-123">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="21252-124">データ ファクトリのゲートウェイを削除します。</span><span class="sxs-lookup"><span data-stu-id="21252-124">Delete a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="21252-125">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="21252-125">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, string gatewayName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, string gatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IGatewayOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse&gt;" Usage="iGatewayOperations.GetAsync (resourceGroupName, dataFactoryName, gatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="21252-126">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="21252-126">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="21252-127">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="21252-127">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="21252-128">取得するゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="21252-128">Name of the gateway to get.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="21252-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="21252-129">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="21252-130">データ ファクトリのゲートウェイを取得します。</span><span class="sxs-lookup"><span data-stu-id="21252-130">Gets a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="21252-131">Get データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="21252-131">The Get data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (string operationStatusLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(string operationStatusLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IGatewayOperations.GetCreateOrUpdateStatusAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCreateOrUpdateStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;" Usage="iGatewayOperations.GetCreateOrUpdateStatusAsync (operationStatusLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationStatusLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationStatusLink">
            <span data-ttu-id="21252-132">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="21252-132">Location value returned by the Begin operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="21252-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="21252-133">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="21252-134">Get Operation Status 操作では、指定された操作の状態を返します。</span><span class="sxs-lookup"><span data-stu-id="21252-134">The Get Operation Status operation returns the status of the specified operation.</span></span> <span data-ttu-id="21252-135">非同期操作を呼び出した後に失敗しました。 操作が成功したかどうかを判断する Get Operation Status を呼び出すことができますか、進行中です。</span><span class="sxs-lookup"><span data-stu-id="21252-135">After calling an asynchronous operation, you can call Get Operation Status to determine whether the operation has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="21252-136">作成または更新データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="21252-136">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IGatewayOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse&gt;" Usage="iGatewayOperations.ListAsync (resourceGroupName, dataFactoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="21252-137">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="21252-137">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="21252-138">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="21252-138">A unique data factory instance name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="21252-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="21252-139">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="21252-140">データ ファクトリの下にあるすべてのゲートウェイを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="21252-140">List all gateways under a data factory.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="21252-141">一覧データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="21252-141">The List data factory gateways operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthKeysAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse&gt; ListAuthKeysAsync (string resourceGroupName, string dataFactoryName, string gatewayName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse&gt; ListAuthKeysAsync(string resourceGroupName, string dataFactoryName, string gatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IGatewayOperations.ListAuthKeysAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAuthKeysAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse&gt;" Usage="iGatewayOperations.ListAuthKeysAsync (resourceGroupName, dataFactoryName, gatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="21252-142">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="21252-142">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="21252-143">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="21252-143">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="21252-144">認証キーの一覧表示するゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="21252-144">The name of the gateway to list auth keys.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="21252-145">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="21252-145">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="21252-146">ゲートウェイの認証キーの一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="21252-146">List auth keys of the gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="21252-147">一覧データ ファクトリのゲートウェイ認証キーの操作の応答です。</span><span class="sxs-lookup"><span data-stu-id="21252-147">The List data factory gateway auth keys operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateAuthKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse&gt; RegenerateAuthKeyAsync (string resourceGroupName, string dataFactoryName, string gatewayName, Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse&gt; RegenerateAuthKeyAsync(string resourceGroupName, string dataFactoryName, string gatewayName, class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IGatewayOperations.RegenerateAuthKeyAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateAuthKeyAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse&gt;" Usage="iGatewayOperations.RegenerateAuthKeyAsync (resourceGroupName, dataFactoryName, gatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="21252-148">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="21252-148">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="21252-149">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="21252-149">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="21252-150">認証キーを再生成しているゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="21252-150">The name of the gateway to regenerate auth key.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="21252-151">再生成するゲートウェイ認証キーの名前。</span><span class="sxs-lookup"><span data-stu-id="21252-151">Name of the gateway auth key to be regenerated.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="21252-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="21252-152">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="21252-153">ゲートウェイ認証キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="21252-153">Regenerate gateway auth key.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="21252-154">再生成のゲートウェイ認証キー操作応答です。</span><span class="sxs-lookup"><span data-stu-id="21252-154">The regenerate gateway auth key operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse&gt; RegenerateKeyAsync (string resourceGroupName, string dataFactoryName, string gatewayName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse&gt; RegenerateKeyAsync(string resourceGroupName, string dataFactoryName, string gatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IGatewayOperations.RegenerateKeyAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateKeyAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse&gt;" Usage="iGatewayOperations.RegenerateKeyAsync (resourceGroupName, dataFactoryName, gatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="21252-155">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="21252-155">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="21252-156">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="21252-156">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="21252-157">キーを再生成しているゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="21252-157">The name of the gateway to regenerate key.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="21252-158">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="21252-158">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="21252-159">ゲートウェイのキーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="21252-159">Regenerate gateway key.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="21252-160">再生成するゲートウェイのキー操作応答です。</span><span class="sxs-lookup"><span data-stu-id="21252-160">The regenerate gateway key operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveConnectionInfoAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse&gt; RetrieveConnectionInfoAsync (string resourceGroupName, string dataFactoryName, string gatewayName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse&gt; RetrieveConnectionInfoAsync(string resourceGroupName, string dataFactoryName, string gatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IGatewayOperations.RetrieveConnectionInfoAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RetrieveConnectionInfoAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse&gt;" Usage="iGatewayOperations.RetrieveConnectionInfoAsync (resourceGroupName, dataFactoryName, gatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="gatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="21252-161">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="21252-161">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="21252-162">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="21252-162">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="21252-163">ゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="21252-163">Name of the gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="21252-164">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="21252-164">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="21252-165">ゲートウェイの接続情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="21252-165">Retrieve gateway connection information.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="21252-166">ゲートウェイの接続情報を取得する操作応答です。</span><span class="sxs-lookup"><span data-stu-id="21252-166">The retrieve gateway connection information operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; UpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; UpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IGatewayOperations.UpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;" Usage="iGatewayOperations.UpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="21252-167">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="21252-167">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="21252-168">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="21252-168">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="21252-169">作成またはデータ ファクトリのゲートウェイを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="21252-169">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="21252-170">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="21252-170">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="21252-171">データ ファクトリのゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="21252-171">Update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="21252-172">作成または更新データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="21252-172">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>