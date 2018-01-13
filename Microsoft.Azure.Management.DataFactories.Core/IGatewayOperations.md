<Type Name="IGatewayOperations" FullName="Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations">
  <TypeSignature Language="C#" Value="public interface IGatewayOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IGatewayOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IGatewayOperations" />
  <TypeSignature Language="F#" Value="type IGatewayOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="34cb3-101">データ ファクトリのゲートウェイを管理するための操作です。</span><span class="sxs-lookup"><span data-stu-id="34cb3-101">Operations for managing data factory gateways.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.BeginCreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters,System.Threading.CancellationToken)" />
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
            <span data-ttu-id="34cb3-102">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="34cb3-102">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="34cb3-103">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="34cb3-103">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="34cb3-104">作成またはデータ ファクトリのゲートウェイを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="34cb3-104">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="34cb3-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="34cb3-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="34cb3-106">作成またはデータ ファクトリのゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="34cb3-106">Create or update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="34cb3-107">作成または更新データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="34cb3-107">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (string resourceGroupName, string dataFactoryName, string gatewayName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(string resourceGroupName, string dataFactoryName, string gatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.BeginDeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
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
            <span data-ttu-id="34cb3-108">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="34cb3-108">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="34cb3-109">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="34cb3-109">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="34cb3-110">削除するゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="34cb3-110">Name of the gateway to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="34cb3-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="34cb3-111">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="34cb3-112">データ ファクトリのゲートウェイを削除します。</span><span class="sxs-lookup"><span data-stu-id="34cb3-112">Delete a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="34cb3-113">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="34cb3-113">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters,System.Threading.CancellationToken)" />
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
            <span data-ttu-id="34cb3-114">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="34cb3-114">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="34cb3-115">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="34cb3-115">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="34cb3-116">作成またはデータ ファクトリのゲートウェイを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="34cb3-116">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="34cb3-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="34cb3-117">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="34cb3-118">作成またはデータ ファクトリのゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="34cb3-118">Create or update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="34cb3-119">作成または更新データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="34cb3-119">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string dataFactoryName, string gatewayName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string dataFactoryName, string gatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
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
            <span data-ttu-id="34cb3-120">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="34cb3-120">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="34cb3-121">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="34cb3-121">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="34cb3-122">削除するゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="34cb3-122">Name of the gateway to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="34cb3-123">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="34cb3-123">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="34cb3-124">データ ファクトリのゲートウェイを削除します。</span><span class="sxs-lookup"><span data-stu-id="34cb3-124">Delete a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="34cb3-125">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="34cb3-125">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, string gatewayName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, string gatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
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
            <span data-ttu-id="34cb3-126">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="34cb3-126">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="34cb3-127">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="34cb3-127">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="34cb3-128">取得するゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="34cb3-128">Name of the gateway to get.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="34cb3-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="34cb3-129">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="34cb3-130">データ ファクトリのゲートウェイを取得します。</span><span class="sxs-lookup"><span data-stu-id="34cb3-130">Gets a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="34cb3-131">Get データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="34cb3-131">The Get data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (string operationStatusLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(string operationStatusLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.GetCreateOrUpdateStatusAsync(System.String,System.Threading.CancellationToken)" />
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
            <span data-ttu-id="34cb3-132">Begin 操作によって返される location 値です。</span><span class="sxs-lookup"><span data-stu-id="34cb3-132">Location value returned by the Begin operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="34cb3-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="34cb3-133">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="34cb3-134">Get Operation Status 操作では、指定された操作の状態を返します。</span><span class="sxs-lookup"><span data-stu-id="34cb3-134">The Get Operation Status operation returns the status of the specified operation.</span></span> <span data-ttu-id="34cb3-135">非同期操作を呼び出した後に失敗しました。 操作が成功したかどうかを判断する Get Operation Status を呼び出すことができますか、進行中です。</span><span class="sxs-lookup"><span data-stu-id="34cb3-135">After calling an asynchronous operation, you can call Get Operation Status to determine whether the operation has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="34cb3-136">作成または更新データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="34cb3-136">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
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
            <span data-ttu-id="34cb3-137">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="34cb3-137">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="34cb3-138">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="34cb3-138">A unique data factory instance name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="34cb3-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="34cb3-139">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="34cb3-140">データ ファクトリの下にあるすべてのゲートウェイを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="34cb3-140">List all gateways under a data factory.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="34cb3-141">一覧データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="34cb3-141">The List data factory gateways operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthKeysAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse&gt; ListAuthKeysAsync (string resourceGroupName, string dataFactoryName, string gatewayName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayListAuthKeysResponse&gt; ListAuthKeysAsync(string resourceGroupName, string dataFactoryName, string gatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.ListAuthKeysAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
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
            <span data-ttu-id="34cb3-142">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="34cb3-142">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="34cb3-143">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="34cb3-143">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="34cb3-144">認証キーの一覧表示するゲートウェイの名前。</span><span class="sxs-lookup"><span data-stu-id="34cb3-144">The name of the gateway to list auth keys.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="34cb3-145">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="34cb3-145">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="34cb3-146">ゲートウェイ認証キーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="34cb3-146">List gateway authentication keys.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="34cb3-147">一覧のゲートウェイ認証キーの操作の応答です。</span><span class="sxs-lookup"><span data-stu-id="34cb3-147">The list gateway auth keys operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateAuthKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse&gt; RegenerateAuthKeyAsync (string resourceGroupName, string dataFactoryName, string gatewayName, Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyResponse&gt; RegenerateAuthKeyAsync(string resourceGroupName, string dataFactoryName, string gatewayName, class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.RegenerateAuthKeyAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateAuthKeyParameters,System.Threading.CancellationToken)" />
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
            <span data-ttu-id="34cb3-148">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="34cb3-148">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="34cb3-149">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="34cb3-149">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="34cb3-150">キーを再生成しているゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="34cb3-150">The name of the gateway to regenerate key.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="34cb3-151">再生成する認証キーの名前。</span><span class="sxs-lookup"><span data-stu-id="34cb3-151">The name of the authentication key to be regenerated.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="34cb3-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="34cb3-152">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="34cb3-153">ゲートウェイ認証キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="34cb3-153">Regenerate gateway authentication key.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="34cb3-154">再生成のゲートウェイ認証キー操作応答です。</span><span class="sxs-lookup"><span data-stu-id="34cb3-154">The regenerate gateway auth key operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse&gt; RegenerateKeyAsync (string resourceGroupName, string dataFactoryName, string gatewayName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayRegenerateKeyResponse&gt; RegenerateKeyAsync(string resourceGroupName, string dataFactoryName, string gatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.RegenerateKeyAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
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
            <span data-ttu-id="34cb3-155">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="34cb3-155">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="34cb3-156">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="34cb3-156">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="34cb3-157">キーを再生成しているゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="34cb3-157">The name of the gateway to regenerate key.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="34cb3-158">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="34cb3-158">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="34cb3-159">ゲートウェイのキーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="34cb3-159">Regenerate gateway key.</span></span> <span data-ttu-id="34cb3-160">この API は廃止されており、RegenerateAuthKey を代わりに使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="34cb3-160">This API has been deprecated and RegenerateAuthKey should be used instead.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="34cb3-161">再生成するゲートウェイのキー操作応答です。</span><span class="sxs-lookup"><span data-stu-id="34cb3-161">The regenerate gateway key operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveConnectionInfoAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse&gt; RetrieveConnectionInfoAsync (string resourceGroupName, string dataFactoryName, string gatewayName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayConnectionInfoRetrieveResponse&gt; RetrieveConnectionInfoAsync(string resourceGroupName, string dataFactoryName, string gatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.RetrieveConnectionInfoAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
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
            <span data-ttu-id="34cb3-162">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="34cb3-162">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="34cb3-163">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="34cb3-163">A unique data factory instance name.</span></span>
            </param>
        <param name="gatewayName">
            <span data-ttu-id="34cb3-164">ゲートウェイの名前です。</span><span class="sxs-lookup"><span data-stu-id="34cb3-164">Name of the gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="34cb3-165">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="34cb3-165">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="34cb3-166">ゲートウェイの接続情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="34cb3-166">Retrieve gateway connection information.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="34cb3-167">ゲートウェイの接続情報を取得する操作応答です。</span><span class="sxs-lookup"><span data-stu-id="34cb3-167">The retrieve gateway connection information operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; UpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateResponse&gt; UpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IGatewayOperations.UpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.GatewayCreateOrUpdateParameters,System.Threading.CancellationToken)" />
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
            <span data-ttu-id="34cb3-168">データ ファクトリのリソース グループ名。</span><span class="sxs-lookup"><span data-stu-id="34cb3-168">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="34cb3-169">一意のデータ ファクトリのインスタンス名です。</span><span class="sxs-lookup"><span data-stu-id="34cb3-169">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="34cb3-170">作成またはデータ ファクトリのゲートウェイを更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="34cb3-170">The parameters required to create or update a data factory gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="34cb3-171">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="34cb3-171">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="34cb3-172">データ ファクトリのゲートウェイを更新します。</span><span class="sxs-lookup"><span data-stu-id="34cb3-172">Update a data factory gateway.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="34cb3-173">作成または更新データ ファクトリ ゲートウェイ操作の応答。</span><span class="sxs-lookup"><span data-stu-id="34cb3-173">The create or update data factory gateway operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>