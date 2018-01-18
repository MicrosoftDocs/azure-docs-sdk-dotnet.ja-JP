<Type Name="IStorageInsightsOperations" FullName="Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations">
  <TypeSignature Language="C#" Value="public interface IStorageInsightsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStorageInsightsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStorageInsightsOperations" />
  <TypeSignature Language="F#" Value="type IStorageInsightsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="83bee-101">StorageInsightsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="83bee-101">StorageInsightsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string workspaceName, string storageInsightName, Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string workspaceName, string storageInsightName, class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt;" Usage="iStorageInsightsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, workspaceName, storageInsightName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="storageInsightName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="83bee-102">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="83bee-102">The name of the resource group to get.</span></span> <span data-ttu-id="83bee-103">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="83bee-103">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="83bee-104">StorageInsightsConfigs リソースを格納するログ分析ワークスペースの名前</span><span class="sxs-lookup"><span data-stu-id="83bee-104">Log Analytics Workspace name that will contain the storageInsightsConfigs resource</span></span>
            </param>
        <param name="storageInsightName">
            <span data-ttu-id="83bee-105">StorageInsightsConfigs リソースの名前</span><span class="sxs-lookup"><span data-stu-id="83bee-105">Name of the storageInsightsConfigs resource</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="83bee-106">作成または記憶域の洞察を更新するために必要なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="83bee-106">The parameters required to create or update a storage insight.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="83bee-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="83bee-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="83bee-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="83bee-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="83bee-109">作成または記憶域の洞察を更新します。</span><span class="sxs-lookup"><span data-stu-id="83bee-109">Create or update a storage insight.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="83bee-110">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="83bee-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="83bee-111">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="83bee-111">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="83bee-112">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="83bee-112">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string workspaceName, string storageInsightName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string workspaceName, string storageInsightName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iStorageInsightsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, workspaceName, storageInsightName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="storageInsightName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="83bee-113">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="83bee-113">The name of the resource group to get.</span></span> <span data-ttu-id="83bee-114">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="83bee-114">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="83bee-115">ログ分析ワークスペース名 storageInsightsConfigs リソースを含む</span><span class="sxs-lookup"><span data-stu-id="83bee-115">Log Analytics Workspace name that contains the storageInsightsConfigs resource</span></span>
            </param>
        <param name="storageInsightName">
            <span data-ttu-id="83bee-116">StorageInsightsConfigs リソースの名前</span><span class="sxs-lookup"><span data-stu-id="83bee-116">Name of the storageInsightsConfigs resource</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="83bee-117">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="83bee-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="83bee-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="83bee-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="83bee-119">StorageInsightsConfigs リソースを削除します。</span><span class="sxs-lookup"><span data-stu-id="83bee-119">Deletes a storageInsightsConfigs resource</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="83bee-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="83bee-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="83bee-121">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="83bee-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string workspaceName, string storageInsightName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string workspaceName, string storageInsightName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt;" Usage="iStorageInsightsOperations.GetWithHttpMessagesAsync (resourceGroupName, workspaceName, storageInsightName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="storageInsightName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="83bee-122">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="83bee-122">The name of the resource group to get.</span></span> <span data-ttu-id="83bee-123">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="83bee-123">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="83bee-124">ログ分析ワークスペース名 storageInsightsConfigs リソースを含む</span><span class="sxs-lookup"><span data-stu-id="83bee-124">Log Analytics Workspace name that contains the storageInsightsConfigs resource</span></span>
            </param>
        <param name="storageInsightName">
            <span data-ttu-id="83bee-125">StorageInsightsConfigs リソースの名前</span><span class="sxs-lookup"><span data-stu-id="83bee-125">Name of the storageInsightsConfigs resource</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="83bee-126">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="83bee-126">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="83bee-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="83bee-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="83bee-128">ストレージ インサイト インスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="83bee-128">Gets a storage insight instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="83bee-129">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="83bee-129">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="83bee-130">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="83bee-130">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="83bee-131">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="83bee-131">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspaceNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt;&gt; ListByWorkspaceNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt;&gt; ListByWorkspaceNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations.ListByWorkspaceNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByWorkspaceNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt;&gt;" Usage="iStorageInsightsOperations.ListByWorkspaceNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="83bee-132">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="83bee-132">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="83bee-133">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="83bee-133">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="83bee-134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="83bee-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="83bee-135">ワークスペース内で記憶域 insight インスタンスが一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="83bee-135">Lists the storage insight instances within a workspace</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="83bee-136">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="83bee-136">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="83bee-137">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="83bee-137">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="83bee-138">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="83bee-138">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspaceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt;&gt; ListByWorkspaceWithHttpMessagesAsync (string resourceGroupName, string workspaceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt;&gt; ListByWorkspaceWithHttpMessagesAsync(string resourceGroupName, string workspaceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.IStorageInsightsOperations.ListByWorkspaceWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByWorkspaceWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt;&gt;" Usage="iStorageInsightsOperations.ListByWorkspaceWithHttpMessagesAsync (resourceGroupName, workspaceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.OperationalInsights.Models.StorageInsight&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="83bee-139">取得するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="83bee-139">The name of the resource group to get.</span></span> <span data-ttu-id="83bee-140">名前は大文字小文字を区別します。</span><span class="sxs-lookup"><span data-stu-id="83bee-140">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="83bee-141">StorageInsightsConfigs リソースを格納するログ分析ワークスペースの名前</span><span class="sxs-lookup"><span data-stu-id="83bee-141">Log Analytics Workspace name that will contain the storageInsightsConfigs resource</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="83bee-142">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="83bee-142">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="83bee-143">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="83bee-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="83bee-144">ワークスペース内で記憶域 insight インスタンスが一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="83bee-144">Lists the storage insight instances within a workspace</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="83bee-145">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="83bee-145">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="83bee-146">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="83bee-146">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="83bee-147">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="83bee-147">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>