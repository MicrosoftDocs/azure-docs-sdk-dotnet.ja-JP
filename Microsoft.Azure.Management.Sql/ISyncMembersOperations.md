<Type Name="ISyncMembersOperations" FullName="Microsoft.Azure.Management.Sql.ISyncMembersOperations">
  <TypeSignature Language="C#" Value="public interface ISyncMembersOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISyncMembersOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.ISyncMembersOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISyncMembersOperations" />
  <TypeSignature Language="F#" Value="type ISyncMembersOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5551e-101">SyncMembersOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="5551e-101">SyncMembersOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncMembersOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;" Usage="iSyncMembersOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5551e-102">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-102">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="5551e-103">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="5551e-103">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="5551e-104">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-104">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5551e-105">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-105">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="5551e-106">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-106">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="5551e-107">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-107">The name of the sync member.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5551e-108">要求された同期のメンバー リソースの状態。</span><span class="sxs-lookup"><span data-stu-id="5551e-108">The requested sync member resource state.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5551e-109">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5551e-109">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5551e-110">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5551e-110">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5551e-111">作成するか、同期のメンバーを更新します。</span><span class="sxs-lookup"><span data-stu-id="5551e-111">Creates or updates a sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5551e-112">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-112">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5551e-113">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-113">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5551e-114">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-114">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncMembersOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iSyncMembersOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, customHeaders, cancellationToken)" />
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
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5551e-115">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-115">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="5551e-116">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="5551e-116">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="5551e-117">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-117">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5551e-118">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-118">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="5551e-119">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-119">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="5551e-120">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-120">The name of the sync member.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5551e-121">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5551e-121">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5551e-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5551e-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5551e-123">同期のメンバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="5551e-123">Deletes a sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5551e-124">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-124">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5551e-125">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-125">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginRefreshMemberSchemaWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginRefreshMemberSchemaWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginRefreshMemberSchemaWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncMembersOperations.BeginRefreshMemberSchemaWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginRefreshMemberSchemaWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iSyncMembersOperations.BeginRefreshMemberSchemaWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, customHeaders, cancellationToken)" />
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
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5551e-126">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-126">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="5551e-127">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="5551e-127">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="5551e-128">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-128">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5551e-129">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-129">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="5551e-130">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-130">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="5551e-131">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-131">The name of the sync member.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5551e-132">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5551e-132">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5551e-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5551e-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5551e-134">同期メンバー データベース スキーマを更新します。</span><span class="sxs-lookup"><span data-stu-id="5551e-134">Refreshes a sync member database schema.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5551e-135">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-135">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5551e-136">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-136">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt; BeginUpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt; BeginUpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncMembersOperations.BeginUpdateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateWithHttpMessagesAsync : string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;" Usage="iSyncMembersOperations.BeginUpdateWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5551e-137">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-137">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="5551e-138">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="5551e-138">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="5551e-139">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-139">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5551e-140">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-140">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="5551e-141">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-141">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="5551e-142">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-142">The name of the sync member.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5551e-143">要求された同期のメンバー リソースの状態。</span><span class="sxs-lookup"><span data-stu-id="5551e-143">The requested sync member resource state.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5551e-144">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5551e-144">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5551e-145">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5551e-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5551e-146">既存の同期メンバーを更新します。</span><span class="sxs-lookup"><span data-stu-id="5551e-146">Updates an existing sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5551e-147">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-147">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5551e-148">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-148">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5551e-149">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-149">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncMembersOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;" Usage="iSyncMembersOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5551e-150">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-150">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="5551e-151">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="5551e-151">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="5551e-152">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-152">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5551e-153">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-153">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="5551e-154">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-154">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="5551e-155">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-155">The name of the sync member.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5551e-156">要求された同期のメンバー リソースの状態。</span><span class="sxs-lookup"><span data-stu-id="5551e-156">The requested sync member resource state.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5551e-157">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5551e-157">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5551e-158">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5551e-158">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5551e-159">作成するか、同期のメンバーを更新します。</span><span class="sxs-lookup"><span data-stu-id="5551e-159">Creates or updates a sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5551e-160">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-160">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5551e-161">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-161">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5551e-162">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-162">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncMembersOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iSyncMembersOperations.DeleteWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, customHeaders, cancellationToken)" />
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
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5551e-163">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-163">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="5551e-164">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="5551e-164">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="5551e-165">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-165">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5551e-166">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-166">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="5551e-167">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-167">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="5551e-168">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-168">The name of the sync member.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5551e-169">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5551e-169">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5551e-170">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5551e-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5551e-171">同期のメンバーを削除します。</span><span class="sxs-lookup"><span data-stu-id="5551e-171">Deletes a sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5551e-172">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-172">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5551e-173">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-173">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncMembersOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;" Usage="iSyncMembersOperations.GetWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5551e-174">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-174">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="5551e-175">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="5551e-175">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="5551e-176">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-176">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5551e-177">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-177">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="5551e-178">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-178">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="5551e-179">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-179">The name of the sync member.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5551e-180">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5551e-180">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5551e-181">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5551e-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5551e-182">同期のメンバーを取得します。</span><span class="sxs-lookup"><span data-stu-id="5551e-182">Gets a sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5551e-183">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-183">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5551e-184">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-184">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5551e-185">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-185">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListBySyncGroupNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;&gt; ListBySyncGroupNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;&gt; ListBySyncGroupNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncMembersOperations.ListBySyncGroupNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListBySyncGroupNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;&gt;" Usage="iSyncMembersOperations.ListBySyncGroupNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="5551e-186">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5551e-186">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5551e-187">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5551e-187">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5551e-188">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5551e-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5551e-189">リストは、指定された同期グループ内のメンバーを同期します。</span><span class="sxs-lookup"><span data-stu-id="5551e-189">Lists sync members in the given sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5551e-190">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-190">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5551e-191">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-191">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5551e-192">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-192">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListBySyncGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;&gt; ListBySyncGroupWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string syncGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;&gt; ListBySyncGroupWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string syncGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncMembersOperations.ListBySyncGroupWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListBySyncGroupWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;&gt;" Usage="iSyncMembersOperations.ListBySyncGroupWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, syncGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;&gt;</ReturnType>
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
            <span data-ttu-id="5551e-193">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-193">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="5551e-194">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="5551e-194">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="5551e-195">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-195">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5551e-196">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-196">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="5551e-197">同期グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="5551e-197">The name of the sync group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5551e-198">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5551e-198">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5551e-199">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5551e-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5551e-200">リストは、指定された同期グループ内のメンバーを同期します。</span><span class="sxs-lookup"><span data-stu-id="5551e-200">Lists sync members in the given sync group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5551e-201">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-201">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5551e-202">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-202">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5551e-203">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-203">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMemberSchemasNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;&gt; ListMemberSchemasNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;&gt; ListMemberSchemasNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncMembersOperations.ListMemberSchemasNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMemberSchemasNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;&gt;" Usage="iSyncMembersOperations.ListMemberSchemasNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
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
            <span data-ttu-id="5551e-204">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5551e-204">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5551e-205">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5551e-205">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5551e-206">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5551e-206">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5551e-207">同期メンバー データベース スキーマを取得します。</span><span class="sxs-lookup"><span data-stu-id="5551e-207">Gets a sync member database schema.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5551e-208">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-208">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5551e-209">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-209">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5551e-210">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-210">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMemberSchemasWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;&gt; ListMemberSchemasWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;&gt; ListMemberSchemasWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncMembersOperations.ListMemberSchemasWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMemberSchemasWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaProperties&gt;&gt;&gt;" Usage="iSyncMembersOperations.ListMemberSchemasWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, customHeaders, cancellationToken)" />
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
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5551e-211">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-211">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="5551e-212">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="5551e-212">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="5551e-213">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-213">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5551e-214">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-214">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="5551e-215">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-215">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="5551e-216">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-216">The name of the sync member.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5551e-217">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5551e-217">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5551e-218">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5551e-218">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5551e-219">同期メンバー データベース スキーマを取得します。</span><span class="sxs-lookup"><span data-stu-id="5551e-219">Gets a sync member database schema.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5551e-220">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-220">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5551e-221">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-221">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5551e-222">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-222">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RefreshMemberSchemaWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; RefreshMemberSchemaWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; RefreshMemberSchemaWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncMembersOperations.RefreshMemberSchemaWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshMemberSchemaWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iSyncMembersOperations.RefreshMemberSchemaWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, customHeaders, cancellationToken)" />
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
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5551e-223">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-223">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="5551e-224">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="5551e-224">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="5551e-225">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-225">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5551e-226">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-226">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="5551e-227">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-227">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="5551e-228">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-228">The name of the sync member.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5551e-229">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5551e-229">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5551e-230">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5551e-230">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5551e-231">同期メンバー データベース スキーマを更新します。</span><span class="sxs-lookup"><span data-stu-id="5551e-231">Refreshes a sync member database schema.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5551e-232">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-232">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5551e-233">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-233">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, Microsoft.Azure.Management.Sql.Models.SyncMember parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string syncGroupName, string syncMemberName, class Microsoft.Azure.Management.Sql.Models.SyncMember parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ISyncMembersOperations.UpdateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.SyncMember,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * string * string * string * Microsoft.Azure.Management.Sql.Models.SyncMember * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;" Usage="iSyncMembersOperations.UpdateWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, syncGroupName, syncMemberName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.SyncMember&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="syncGroupName" Type="System.String" />
        <Parameter Name="syncMemberName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.SyncMember" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5551e-234">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-234">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="5551e-235">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="5551e-235">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="5551e-236">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-236">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5551e-237">同期グループをホストするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-237">The name of the database on which the sync group is hosted.</span></span>
            </param>
        <param name="syncGroupName">
            <span data-ttu-id="5551e-238">同期のメンバーがホストされている同期グループの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-238">The name of the sync group on which the sync member is hosted.</span></span>
            </param>
        <param name="syncMemberName">
            <span data-ttu-id="5551e-239">同期のメンバーの名前。</span><span class="sxs-lookup"><span data-stu-id="5551e-239">The name of the sync member.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5551e-240">要求された同期のメンバー リソースの状態。</span><span class="sxs-lookup"><span data-stu-id="5551e-240">The requested sync member resource state.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5551e-241">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5551e-241">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5551e-242">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5551e-242">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5551e-243">既存の同期メンバーを更新します。</span><span class="sxs-lookup"><span data-stu-id="5551e-243">Updates an existing sync member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5551e-244">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-244">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5551e-245">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-245">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5551e-246">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5551e-246">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>