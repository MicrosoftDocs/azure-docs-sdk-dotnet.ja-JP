<Type Name="ISyncGroupsOperations" FullName="Microsoft.Azure.Management.Sql.ISyncGroupsOperations">
  <TypeSignature Language="C#" Value="public interface ISyncGroupsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISyncGroupsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.ISyncGroupsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISyncGroupsOperations" />
  <TypeSignature Language="F#" Value="type ISyncGroupsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fbf5d-101">SyncGroupsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-101">SyncGroupsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string syncGroupName, Microsoft.Azure.Management.Sql.Models.SyncGroup parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string syncGroupName, class Microsoft.Azure.Management.Sql.Models.SyncGroup parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncGroupsOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncGroup,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncGroup * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt;" Usage="iSyncGroupsOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, syncGroupName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncGroup" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fbf5d-102">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-102">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fbf5d-103">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-103">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fbf5d-104">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-104">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fbf5d-105">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-105">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="fbf5d-106">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-106">The name of the sync group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fbf5d-107">要求された同期グループのリソースの状態。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-107">The requested sync group resource state.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbf5d-108">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-108">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbf5d-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbf5d-110">作成するか、同期グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-110">Creates or updates a sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbf5d-111">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fbf5d-112">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-112">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbf5d-113">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-113">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string syncGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncGroupsOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iSyncGroupsOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, syncGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fbf5d-114">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-114">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fbf5d-115">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-115">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fbf5d-116">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-116">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fbf5d-117">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-117">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="fbf5d-118">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-118">The name of the sync group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbf5d-119">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-119">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbf5d-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbf5d-121">同期グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-121">Deletes a sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbf5d-122">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-122">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbf5d-123">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-123">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginRefreshHubSchemaWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginRefreshHubSchemaWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginRefreshHubSchemaWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string syncGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncGroupsOperations.BeginRefreshHubSchemaWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginRefreshHubSchemaWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iSyncGroupsOperations.BeginRefreshHubSchemaWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, syncGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fbf5d-124">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-124">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fbf5d-125">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-125">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fbf5d-126">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-126">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fbf5d-127">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-127">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="fbf5d-128">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-128">The name of the sync group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbf5d-129">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-129">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbf5d-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbf5d-131">ハブ データベース スキーマを更新します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-131">Refreshes a hub database schema.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbf5d-132">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-132">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbf5d-133">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-133">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt; BeginUpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string syncGroupName, Microsoft.Azure.Management.Sql.Models.SyncGroup parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt; BeginUpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string syncGroupName, class Microsoft.Azure.Management.Sql.Models.SyncGroup parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncGroupsOperations.BeginUpdateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncGroup,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncGroup * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt;" Usage="iSyncGroupsOperations.BeginUpdateWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, syncGroupName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncGroup" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fbf5d-134">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-134">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fbf5d-135">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-135">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fbf5d-136">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-136">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fbf5d-137">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-137">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="fbf5d-138">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-138">The name of the sync group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fbf5d-139">要求された同期グループのリソースの状態。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-139">The requested sync group resource state.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbf5d-140">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-140">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbf5d-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbf5d-142">同期グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-142">Updates a sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbf5d-143">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-143">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fbf5d-144">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-144">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbf5d-145">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CancelSyncWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; CancelSyncWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; CancelSyncWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string syncGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncGroupsOperations.CancelSyncWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CancelSyncWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iSyncGroupsOperations.CancelSyncWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, syncGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fbf5d-146">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-146">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fbf5d-147">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-147">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fbf5d-148">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-148">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fbf5d-149">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-149">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="fbf5d-150">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-150">The name of the sync group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbf5d-151">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-151">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbf5d-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbf5d-153">同期グループの同期をキャンセルします。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-153">Cancels a sync group synchronization.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbf5d-154">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-154">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbf5d-155">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-155">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string syncGroupName, Microsoft.Azure.Management.Sql.Models.SyncGroup parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string syncGroupName, class Microsoft.Azure.Management.Sql.Models.SyncGroup parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncGroupsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncGroup,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncGroup * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt;" Usage="iSyncGroupsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, syncGroupName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncGroup" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fbf5d-156">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-156">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fbf5d-157">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-157">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fbf5d-158">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-158">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fbf5d-159">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-159">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="fbf5d-160">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-160">The name of the sync group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fbf5d-161">要求された同期グループのリソースの状態。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-161">The requested sync group resource state.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbf5d-162">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-162">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbf5d-163">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbf5d-164">作成するか、同期グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-164">Creates or updates a sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbf5d-165">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-165">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fbf5d-166">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-166">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbf5d-167">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-167">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string syncGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncGroupsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iSyncGroupsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, syncGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fbf5d-168">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-168">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fbf5d-169">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-169">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fbf5d-170">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-170">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fbf5d-171">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-171">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="fbf5d-172">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-172">The name of the sync group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbf5d-173">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-173">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbf5d-174">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbf5d-175">同期グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-175">Deletes a sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbf5d-176">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-176">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbf5d-177">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-177">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string syncGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncGroupsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt;" Usage="iSyncGroupsOperations.GetWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, syncGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fbf5d-178">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-178">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fbf5d-179">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-179">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fbf5d-180">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-180">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fbf5d-181">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-181">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="fbf5d-182">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-182">The name of the sync group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbf5d-183">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-183">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbf5d-184">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-184">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbf5d-185">同期グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-185">Gets a sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbf5d-186">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-186">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fbf5d-187">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-187">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbf5d-188">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-188">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabaseNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt;&gt; ListByDatabaseNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt;&gt; ListByDatabaseNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncGroupsOperations.ListByDatabaseNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByDatabaseNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt;&gt;" Usage="iSyncGroupsOperations.ListByDatabaseNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="fbf5d-189">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-189">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbf5d-190">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-190">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbf5d-191">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-191">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbf5d-192">リストは、ハブ データベースの下のグループを同期します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-192">Lists sync groups under a hub database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbf5d-193">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-193">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fbf5d-194">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-194">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbf5d-195">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-195">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByDatabaseWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt;&gt; ListByDatabaseWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt;&gt; ListByDatabaseWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncGroupsOperations.ListByDatabaseWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByDatabaseWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt;&gt;" Usage="iSyncGroupsOperations.ListByDatabaseWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fbf5d-196">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-196">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fbf5d-197">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-197">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fbf5d-198">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-198">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fbf5d-199">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-199">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbf5d-200">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-200">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbf5d-201">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-201">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbf5d-202">リストは、ハブ データベースの下のグループを同期します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-202">Lists sync groups under a hub database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbf5d-203">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-203">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fbf5d-204">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-204">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbf5d-205">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-205">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListHubSchemasNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;&gt; ListHubSchemasNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;&gt; ListHubSchemasNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncGroupsOperations.ListHubSchemasNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListHubSchemasNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;&gt;" Usage="iSyncGroupsOperations.ListHubSchemasNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="fbf5d-206">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-206">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbf5d-207">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-207">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbf5d-208">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-208">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbf5d-209">ハブ データベース スキーマのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-209">Gets a collection of hub database schemas.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbf5d-210">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-210">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fbf5d-211">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-211">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbf5d-212">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-212">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListHubSchemasWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;&gt; ListHubSchemasWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;&gt; ListHubSchemasWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string syncGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncGroupsOperations.ListHubSchemasWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListHubSchemasWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;&gt;" Usage="iSyncGroupsOperations.ListHubSchemasWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, syncGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fbf5d-213">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-213">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fbf5d-214">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-214">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fbf5d-215">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-215">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fbf5d-216">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-216">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="fbf5d-217">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-217">The name of the sync group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbf5d-218">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-218">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbf5d-219">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-219">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbf5d-220">ハブ データベース スキーマのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-220">Gets a collection of hub database schemas.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbf5d-221">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-221">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fbf5d-222">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-222">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbf5d-223">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-223">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListLogsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;&gt;&gt; ListLogsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;&gt;&gt; ListLogsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncGroupsOperations.ListLogsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListLogsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;&gt;&gt;" Usage="iSyncGroupsOperations.ListLogsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="fbf5d-224">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-224">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbf5d-225">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-225">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbf5d-226">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-226">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbf5d-227">同期グループのログのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-227">Gets a collection of sync group logs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbf5d-228">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-228">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fbf5d-229">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-229">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbf5d-230">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-230">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListLogsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;&gt;&gt; ListLogsWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string syncGroupName, string startTime, string endTime, string type, string continuationToken = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;&gt;&gt; ListLogsWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string syncGroupName, string startTime, string endTime, string type, string continuationToken, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncGroupsOperations.ListLogsWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListLogsWithHttpMessagesAsync : string * string * string * string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;&gt;&gt;" Usage="iSyncGroupsOperations.ListLogsWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, syncGroupName, startTime, endTime, type, continuationToken, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncGroupLogProperties&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fbf5d-231">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-231">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fbf5d-232">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-232">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fbf5d-233">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-233">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fbf5d-234">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-234">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="fbf5d-235">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-235">The name of the sync group.</span></span>
            </param>
        <param name="startTime">
            <span data-ttu-id="fbf5d-236">この時点以降後に生成されたログを取得します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-236">Get logs generated after this time.</span></span>
            </param>
        <param name="endTime">
            <span data-ttu-id="fbf5d-237">この時刻より前に生成されたログを取得します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-237">Get logs generated before this time.</span></span>
            </param>
        <param name="type">
            <span data-ttu-id="fbf5d-238">取得するログの種類。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-238">The types of logs to retrieve.</span></span> <span data-ttu-id="fbf5d-239">使用可能な値が含まれます: 'すべて'、'Error'、'警告'、'成功'</span><span class="sxs-lookup"><span data-stu-id="fbf5d-239">Possible values include: 'All', 'Error', 'Warning', 'Success'</span></span>
            </param>
        <param name="continuationToken">
            <span data-ttu-id="fbf5d-240">この操作の継続トークンです。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-240">The continuation token for this operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbf5d-241">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-241">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbf5d-242">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-242">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbf5d-243">同期グループのログのコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-243">Gets a collection of sync group logs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbf5d-244">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-244">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fbf5d-245">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-245">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbf5d-246">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-246">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListSyncDatabaseIdsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;&gt;&gt; ListSyncDatabaseIdsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;&gt;&gt; ListSyncDatabaseIdsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncGroupsOperations.ListSyncDatabaseIdsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSyncDatabaseIdsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;&gt;&gt;" Usage="iSyncGroupsOperations.ListSyncDatabaseIdsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="fbf5d-247">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-247">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbf5d-248">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-248">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbf5d-249">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-249">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbf5d-250">データベースの id 同期のコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-250">Gets a collection of sync database ids.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbf5d-251">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-251">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fbf5d-252">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-252">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbf5d-253">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-253">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListSyncDatabaseIdsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;&gt;&gt; ListSyncDatabaseIdsWithHttpMessagesAsync (string locationName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;&gt;&gt; ListSyncDatabaseIdsWithHttpMessagesAsync(string locationName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncGroupsOperations.ListSyncDatabaseIdsWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSyncDatabaseIdsWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;&gt;&gt;" Usage="iSyncGroupsOperations.ListSyncDatabaseIdsWithHttpMessagesAsync (locationName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncDatabaseIdProperties&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="locationName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="locationName">
            <span data-ttu-id="fbf5d-254">リソースがある領域の名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-254">The name of the region where the resource is located.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbf5d-255">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-255">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbf5d-256">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-256">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbf5d-257">データベースの id 同期のコレクションを取得します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-257">Gets a collection of sync database ids.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbf5d-258">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-258">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fbf5d-259">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-259">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbf5d-260">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-260">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RefreshHubSchemaWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; RefreshHubSchemaWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; RefreshHubSchemaWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string syncGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncGroupsOperations.RefreshHubSchemaWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshHubSchemaWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iSyncGroupsOperations.RefreshHubSchemaWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, syncGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fbf5d-261">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-261">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fbf5d-262">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-262">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fbf5d-263">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-263">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fbf5d-264">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-264">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="fbf5d-265">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-265">The name of the sync group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbf5d-266">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-266">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbf5d-267">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-267">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbf5d-268">ハブ データベース スキーマを更新します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-268">Refreshes a hub database schema.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbf5d-269">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-269">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbf5d-270">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-270">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="TriggerSyncWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; TriggerSyncWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; TriggerSyncWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string syncGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncGroupsOperations.TriggerSyncWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TriggerSyncWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iSyncGroupsOperations.TriggerSyncWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, syncGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fbf5d-271">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-271">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fbf5d-272">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-272">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fbf5d-273">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-273">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fbf5d-274">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-274">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="fbf5d-275">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-275">The name of the sync group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbf5d-276">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-276">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbf5d-277">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-277">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbf5d-278">同期グループの同期をトリガーします。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-278">Triggers a sync group synchronization.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbf5d-279">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-279">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbf5d-280">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-280">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string syncGroupName, Microsoft.Azure.Management.Sql.Models.SyncGroup parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string syncGroupName, class Microsoft.Azure.Management.Sql.Models.SyncGroup parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncGroupsOperations.UpdateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncGroup,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncGroup * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt;" Usage="iSyncGroupsOperations.UpdateWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, syncGroupName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncGroup" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="fbf5d-281">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-281">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fbf5d-282">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-282">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="fbf5d-283">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-283">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="fbf5d-284">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-284">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="fbf5d-285">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-285">The name of the sync group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fbf5d-286">要求された同期グループのリソースの状態。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-286">The requested sync group resource state.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fbf5d-287">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-287">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbf5d-288">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-288">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbf5d-289">同期グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-289">Updates a sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fbf5d-290">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-290">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fbf5d-291">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-291">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fbf5d-292">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fbf5d-292">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>