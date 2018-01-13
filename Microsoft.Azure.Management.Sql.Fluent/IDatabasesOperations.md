<Type Name="IDatabasesOperations" FullName="Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations">
  <TypeSignature Language="C#" Value="public interface IDatabasesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDatabasesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDatabasesOperations" />
  <TypeSignature Language="F#" Value="type IDatabasesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="342f7-101">DatabasesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="342f7-101">DatabasesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;" Usage="iDatabasesOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="342f7-102">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-102">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="342f7-103">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="342f7-103">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="342f7-104">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-104">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="342f7-105">処理される Azure SQL データベースの名前 (更新または作成した)。</span><span class="sxs-lookup"><span data-stu-id="342f7-105">The name of the Azure SQL database to be operated on (updated or created).</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="342f7-106">作成またはデータベースの更新の必須パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="342f7-106">The required parameters for creating or updating a database.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="342f7-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="342f7-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="342f7-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="342f7-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="342f7-109">新しい Azure SQL データベースを作成または既存の Azure SQL データベースを更新します。</span><span class="sxs-lookup"><span data-stu-id="342f7-109">Creates a new Azure SQL database or updates an existing Azure SQL database.</span></span> <span data-ttu-id="342f7-110">場所は、要求本文に必要なプロパティと、SQL server の場所と同じにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="342f7-110">Location is a required property in the request body, and it must be the same as the location of the SQL server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="342f7-111">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="342f7-112">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-112">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="342f7-113">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-113">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginFailoverReplicationLinkAllowDataLossWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginFailoverReplicationLinkAllowDataLossWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string linkId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginFailoverReplicationLinkAllowDataLossWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string linkId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations.BeginFailoverReplicationLinkAllowDataLossWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginFailoverReplicationLinkAllowDataLossWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDatabasesOperations.BeginFailoverReplicationLinkAllowDataLossWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, linkId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="342f7-114">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-114">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="342f7-115">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="342f7-115">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="342f7-116">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-116">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="342f7-117">フェールオーバーを行うレプリケーション リンクがある Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-117">The name of the Azure SQL database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="342f7-118">フェールオーバーを行うレプリケーション リンクの ID です。</span><span class="sxs-lookup"><span data-stu-id="342f7-118">The ID of the replication link to be failed over.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="342f7-119">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="342f7-119">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="342f7-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="342f7-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="342f7-121">強制フェールオーバー データの損失になる可能性があります指定された ID と Azure SQL データベース レプリケーション リンクを実行します。</span><span class="sxs-lookup"><span data-stu-id="342f7-121">Force failover the Azure SQL database replication link with the given ID which may result in data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="342f7-122">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-122">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="342f7-123">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-123">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginFailoverReplicationLinkWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginFailoverReplicationLinkWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string linkId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginFailoverReplicationLinkWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string linkId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations.BeginFailoverReplicationLinkWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginFailoverReplicationLinkWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDatabasesOperations.BeginFailoverReplicationLinkWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, linkId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="342f7-124">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-124">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="342f7-125">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="342f7-125">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="342f7-126">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-126">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="342f7-127">フェールオーバーを行うレプリケーション リンクがある Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-127">The name of the Azure SQL database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="342f7-128">フェールオーバーを行うレプリケーション リンクの ID です。</span><span class="sxs-lookup"><span data-stu-id="342f7-128">The ID of the replication link to be failed over.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="342f7-129">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="342f7-129">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="342f7-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="342f7-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="342f7-131">その ID を持つフェールオーバー Azure SQL データベース レプリケーション リンク</span><span class="sxs-lookup"><span data-stu-id="342f7-131">Failover the Azure SQL database replication link with the given ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="342f7-132">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-132">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="342f7-133">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-133">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginPauseDataWarehouseWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginPauseDataWarehouseWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginPauseDataWarehouseWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations.BeginPauseDataWarehouseWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginPauseDataWarehouseWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDatabasesOperations.BeginPauseDataWarehouseWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
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
            <span data-ttu-id="342f7-134">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-134">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="342f7-135">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="342f7-135">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="342f7-136">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-136">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="342f7-137">一時停止する Azure SQL Data Warehouse データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-137">The name of the Azure SQL Data Warehouse database to pause.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="342f7-138">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="342f7-138">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="342f7-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="342f7-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="342f7-140">Azure SQL Data Warehouse データベースを一時停止します。</span><span class="sxs-lookup"><span data-stu-id="342f7-140">Pause an Azure SQL Data Warehouse database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="342f7-141">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-141">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="342f7-142">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-142">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginResumeDataWarehouseWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginResumeDataWarehouseWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginResumeDataWarehouseWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations.BeginResumeDataWarehouseWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginResumeDataWarehouseWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDatabasesOperations.BeginResumeDataWarehouseWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
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
            <span data-ttu-id="342f7-143">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-143">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="342f7-144">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="342f7-144">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="342f7-145">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-145">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="342f7-146">再開する Azure SQL Data Warehouse データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-146">The name of the Azure SQL Data Warehouse database to resume.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="342f7-147">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="342f7-147">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="342f7-148">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="342f7-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="342f7-149">Azure SQL Data Warehouse データベースを再開します。</span><span class="sxs-lookup"><span data-stu-id="342f7-149">Resume an Azure SQL Data Warehouse database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="342f7-150">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-150">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="342f7-151">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-151">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateTransparentDataEncryptionConfigurationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt;&gt; CreateOrUpdateTransparentDataEncryptionConfigurationWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates&gt; status = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt;&gt; CreateOrUpdateTransparentDataEncryptionConfigurationWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates&gt; status, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations.CreateOrUpdateTransparentDataEncryptionConfigurationWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateTransparentDataEncryptionConfigurationWithHttpMessagesAsync : string * string * string * Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt;&gt;" Usage="iDatabasesOperations.CreateOrUpdateTransparentDataEncryptionConfigurationWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, status, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionStates&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="342f7-152">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-152">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="342f7-153">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="342f7-153">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="342f7-154">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-154">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="342f7-155">透過的なデータ暗号化を適用するための設定、Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-155">The name of the Azure SQL database for which setting the Transparent Data Encryption applies.</span></span>
            </param>
        <param name="status">
            <span data-ttu-id="342f7-156">Azure SQL データベース透過的なデータ暗号化の状態です。</span><span class="sxs-lookup"><span data-stu-id="342f7-156">The status of the Azure SQL Database Transparent Data Encryption.</span></span>
            <span data-ttu-id="342f7-157">使用可能な値が含まれます: 'Enabled'、'Disabled'</span><span class="sxs-lookup"><span data-stu-id="342f7-157">Possible values include: 'Enabled', 'Disabled'</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="342f7-158">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="342f7-158">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="342f7-159">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="342f7-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="342f7-160">作成するか、Azure SQL データベース透過的なデータ暗号化操作を更新します。</span><span class="sxs-lookup"><span data-stu-id="342f7-160">Creates or updates an Azure SQL Database Transparent Data Encryption Operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="342f7-161">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-161">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="342f7-162">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-162">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="342f7-163">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-163">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;" Usage="iDatabasesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="342f7-164">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-164">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="342f7-165">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="342f7-165">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="342f7-166">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-166">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="342f7-167">処理される Azure SQL データベースの名前 (更新または作成した)。</span><span class="sxs-lookup"><span data-stu-id="342f7-167">The name of the Azure SQL database to be operated on (updated or created).</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="342f7-168">作成またはデータベースの更新の必須パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="342f7-168">The required parameters for creating or updating a database.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="342f7-169">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="342f7-169">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="342f7-170">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="342f7-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="342f7-171">新しい Azure SQL データベースを作成または既存の Azure SQL データベースを更新します。</span><span class="sxs-lookup"><span data-stu-id="342f7-171">Creates a new Azure SQL database or updates an existing Azure SQL database.</span></span> <span data-ttu-id="342f7-172">場所は、要求本文に必要なプロパティと、SQL server の場所と同じにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="342f7-172">Location is a required property in the request body, and it must be the same as the location of the SQL server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="342f7-173">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-173">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="342f7-174">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-174">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="342f7-175">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-175">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteReplicationLinkWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteReplicationLinkWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string linkId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteReplicationLinkWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string linkId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations.DeleteReplicationLinkWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteReplicationLinkWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDatabasesOperations.DeleteReplicationLinkWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, linkId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="342f7-176">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-176">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="342f7-177">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="342f7-177">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="342f7-178">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-178">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="342f7-179">削除するレプリケーション リンクがある Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-179">The name of the Azure SQL database that has the replication link to be dropped.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="342f7-180">削除するレプリケーション リンクの ID です。</span><span class="sxs-lookup"><span data-stu-id="342f7-180">The ID of the replication link to be deleted.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="342f7-181">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="342f7-181">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="342f7-182">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="342f7-182">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="342f7-183">指定された ID と Azure SQL データベース レプリケーション リンクを削除します</span><span class="sxs-lookup"><span data-stu-id="342f7-183">Deletes the Azure SQL database replication link with the given ID.</span></span>
            <span data-ttu-id="342f7-184">フェールオーバー中には実行できません。</span><span class="sxs-lookup"><span data-stu-id="342f7-184">Cannot be done during failover.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="342f7-185">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-185">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="342f7-186">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-186">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDatabasesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
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
            <span data-ttu-id="342f7-187">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-187">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="342f7-188">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="342f7-188">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="342f7-189">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-189">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="342f7-190">削除する Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-190">The name of the Azure SQL database to be deleted.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="342f7-191">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="342f7-191">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="342f7-192">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="342f7-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="342f7-193">Azure SQL データベースを削除します。</span><span class="sxs-lookup"><span data-stu-id="342f7-193">Deletes an Azure SQL database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="342f7-194">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-194">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="342f7-195">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-195">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="FailoverReplicationLinkAllowDataLossWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; FailoverReplicationLinkAllowDataLossWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string linkId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; FailoverReplicationLinkAllowDataLossWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string linkId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations.FailoverReplicationLinkAllowDataLossWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member FailoverReplicationLinkAllowDataLossWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDatabasesOperations.FailoverReplicationLinkAllowDataLossWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, linkId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="342f7-196">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-196">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="342f7-197">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="342f7-197">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="342f7-198">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-198">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="342f7-199">フェールオーバーを行うレプリケーション リンクがある Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-199">The name of the Azure SQL database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="342f7-200">フェールオーバーを行うレプリケーション リンクの ID です。</span><span class="sxs-lookup"><span data-stu-id="342f7-200">The ID of the replication link to be failed over.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="342f7-201">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="342f7-201">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="342f7-202">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="342f7-202">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="342f7-203">強制フェールオーバー データの損失になる可能性があります指定された ID と Azure SQL データベース レプリケーション リンクを実行します。</span><span class="sxs-lookup"><span data-stu-id="342f7-203">Force failover the Azure SQL database replication link with the given ID which may result in data loss.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="342f7-204">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-204">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="342f7-205">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-205">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="FailoverReplicationLinkWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; FailoverReplicationLinkWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string linkId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; FailoverReplicationLinkWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string linkId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations.FailoverReplicationLinkWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member FailoverReplicationLinkWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDatabasesOperations.FailoverReplicationLinkWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, linkId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="342f7-206">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-206">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="342f7-207">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="342f7-207">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="342f7-208">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-208">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="342f7-209">フェールオーバーを行うレプリケーション リンクがある Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-209">The name of the Azure SQL database that has the replication link to be failed over.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="342f7-210">フェールオーバーを行うレプリケーション リンクの ID です。</span><span class="sxs-lookup"><span data-stu-id="342f7-210">The ID of the replication link to be failed over.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="342f7-211">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="342f7-211">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="342f7-212">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="342f7-212">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="342f7-213">その ID を持つフェールオーバー Azure SQL データベース レプリケーション リンク</span><span class="sxs-lookup"><span data-stu-id="342f7-213">Failover the Azure SQL database replication link with the given ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="342f7-214">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-214">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="342f7-215">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-215">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicationLinkWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;&gt; GetReplicationLinkWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string linkId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;&gt; GetReplicationLinkWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string linkId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations.GetReplicationLinkWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetReplicationLinkWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;&gt;" Usage="iDatabasesOperations.GetReplicationLinkWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, linkId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="linkId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="342f7-216">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-216">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="342f7-217">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="342f7-217">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="342f7-218">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-218">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="342f7-219">リンクを取得する Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-219">The name of the Azure SQL database to get the link for.</span></span>
            </param>
        <param name="linkId">
            <span data-ttu-id="342f7-220">レプリケーション リンク ID を取得します。</span><span class="sxs-lookup"><span data-stu-id="342f7-220">The replication link ID to be retrieved.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="342f7-221">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="342f7-221">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="342f7-222">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="342f7-222">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="342f7-223">Azure SQL データベース レプリケーション リンクに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="342f7-223">Gets information about an Azure SQL database replication link.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="342f7-224">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-224">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="342f7-225">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-225">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="342f7-226">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-226">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceTierAdvisorWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;&gt; GetServiceTierAdvisorWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string serviceTierAdvisorName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;&gt; GetServiceTierAdvisorWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string serviceTierAdvisorName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations.GetServiceTierAdvisorWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceTierAdvisorWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;&gt;" Usage="iDatabasesOperations.GetServiceTierAdvisorWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, serviceTierAdvisorName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="serviceTierAdvisorName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="342f7-227">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-227">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="342f7-228">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="342f7-228">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="342f7-229">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-229">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="342f7-230">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-230">The name of database.</span></span>
            </param>
        <param name="serviceTierAdvisorName">
            <span data-ttu-id="342f7-231">サービス層アドバイザーの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-231">The name of service tier advisor.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="342f7-232">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="342f7-232">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="342f7-233">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="342f7-233">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="342f7-234">サービス層アドバイザーに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="342f7-234">Gets information about a service tier advisor.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="342f7-235">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-235">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="342f7-236">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-236">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="342f7-237">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-237">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetTransparentDataEncryptionConfigurationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt;&gt; GetTransparentDataEncryptionConfigurationWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt;&gt; GetTransparentDataEncryptionConfigurationWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations.GetTransparentDataEncryptionConfigurationWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTransparentDataEncryptionConfigurationWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt;&gt;" Usage="iDatabasesOperations.GetTransparentDataEncryptionConfigurationWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionInner&gt;&gt;</ReturnType>
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
            <span data-ttu-id="342f7-238">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-238">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="342f7-239">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="342f7-239">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="342f7-240">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-240">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="342f7-241">透過的なデータ暗号化を適用する Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-241">The name of the Azure SQL database for which the Transparent Data Encryption applies.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="342f7-242">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="342f7-242">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="342f7-243">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="342f7-243">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="342f7-244">Azure SQL データベースの透過的なデータ暗号化応答を取得します。</span><span class="sxs-lookup"><span data-stu-id="342f7-244">Gets an Azure SQL Database Transparent Data Encryption Response.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="342f7-245">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-245">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="342f7-246">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-246">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="342f7-247">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-247">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string expand = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string expand, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;" Usage="iDatabasesOperations.GetWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, expand, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="342f7-248">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-248">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="342f7-249">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="342f7-249">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="342f7-250">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-250">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="342f7-251">取得する Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-251">The name of the Azure SQL database to be retrieved.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="342f7-252">コンマ区切りの応答で展開する子オブジェクトの一覧です。</span><span class="sxs-lookup"><span data-stu-id="342f7-252">The comma separated list of child objects to expand in the response.</span></span> <span data-ttu-id="342f7-253">使用可能なプロパティ: serviceTierAdvisors、upgradeHint、transparentDataEncryption です。</span><span class="sxs-lookup"><span data-stu-id="342f7-253">Possible properties: serviceTierAdvisors, upgradeHint, transparentDataEncryption.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="342f7-254">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="342f7-254">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="342f7-255">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="342f7-255">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="342f7-256">Azure SQL データベースに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="342f7-256">Gets information about an Azure SQL database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="342f7-257">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-257">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="342f7-258">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-258">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="342f7-259">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-259">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByServerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;&gt; ListByServerWithHttpMessagesAsync (string resourceGroupName, string serverName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;&gt; ListByServerWithHttpMessagesAsync(string resourceGroupName, string serverName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations.ListByServerWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByServerWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;&gt;" Usage="iDatabasesOperations.ListByServerWithHttpMessagesAsync (resourceGroupName, serverName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="342f7-260">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-260">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="342f7-261">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="342f7-261">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="342f7-262">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-262">The name of the Azure SQL server.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="342f7-263">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="342f7-263">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="342f7-264">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="342f7-264">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="342f7-265">Azure SQL データベースに関する情報を返します。</span><span class="sxs-lookup"><span data-stu-id="342f7-265">Returns information about an Azure SQL database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="342f7-266">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-266">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="342f7-267">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-267">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="342f7-268">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-268">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListReplicationLinksWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;&gt;&gt; ListReplicationLinksWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;&gt;&gt; ListReplicationLinksWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations.ListReplicationLinksWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListReplicationLinksWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;&gt;&gt;" Usage="iDatabasesOperations.ListReplicationLinksWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner&gt;&gt;&gt;</ReturnType>
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
            <span data-ttu-id="342f7-269">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-269">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="342f7-270">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="342f7-270">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="342f7-271">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-271">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="342f7-272">リンクを取得する Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-272">The name of the Azure SQL database to retrieve links for.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="342f7-273">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="342f7-273">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="342f7-274">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="342f7-274">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="342f7-275">Azure SQL データベース レプリケーション リンクに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="342f7-275">Gets information about Azure SQL database replication links.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="342f7-276">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-276">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="342f7-277">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-277">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="342f7-278">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-278">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListRestorePointsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner&gt;&gt;&gt; ListRestorePointsWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner&gt;&gt;&gt; ListRestorePointsWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations.ListRestorePointsWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListRestorePointsWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner&gt;&gt;&gt;" Usage="iDatabasesOperations.ListRestorePointsWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.RestorePointInner&gt;&gt;&gt;</ReturnType>
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
            <span data-ttu-id="342f7-279">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-279">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="342f7-280">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="342f7-280">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="342f7-281">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-281">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="342f7-282">使用可能な取得する対象の Azure SQL データベースの名前は、ポイントを復元します。</span><span class="sxs-lookup"><span data-stu-id="342f7-282">The name of the Azure SQL database from which to retrieve available restore points.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="342f7-283">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="342f7-283">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="342f7-284">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="342f7-284">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="342f7-285">Azure SQL データベースの一覧を返しますでは、ポイントを復元します。</span><span class="sxs-lookup"><span data-stu-id="342f7-285">Returns a list of Azure SQL database restore points.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="342f7-286">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-286">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="342f7-287">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-287">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="342f7-288">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-288">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListServiceTierAdvisorsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;&gt;&gt; ListServiceTierAdvisorsWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;&gt;&gt; ListServiceTierAdvisorsWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations.ListServiceTierAdvisorsWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListServiceTierAdvisorsWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;&gt;&gt;" Usage="iDatabasesOperations.ListServiceTierAdvisorsWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceTierAdvisorInner&gt;&gt;&gt;</ReturnType>
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
            <span data-ttu-id="342f7-289">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-289">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="342f7-290">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="342f7-290">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="342f7-291">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-291">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="342f7-292">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-292">The name of database.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="342f7-293">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="342f7-293">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="342f7-294">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="342f7-294">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="342f7-295">指定したデータベースのサービス層アドバイザーに関する情報を返します。</span><span class="sxs-lookup"><span data-stu-id="342f7-295">Returns information about service tier advisors for specified database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="342f7-296">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-296">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="342f7-297">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-297">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="342f7-298">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-298">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListTransparentDataEncryptionActivityWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity&gt;&gt;&gt; ListTransparentDataEncryptionActivityWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity&gt;&gt;&gt; ListTransparentDataEncryptionActivityWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations.ListTransparentDataEncryptionActivityWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTransparentDataEncryptionActivityWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity&gt;&gt;&gt;" Usage="iDatabasesOperations.ListTransparentDataEncryptionActivityWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.TransparentDataEncryptionActivity&gt;&gt;&gt;</ReturnType>
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
            <span data-ttu-id="342f7-299">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-299">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="342f7-300">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="342f7-300">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="342f7-301">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-301">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="342f7-302">透過的なデータ暗号化を適用する Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-302">The name of the Azure SQL database for which the Transparent Data Encryption applies.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="342f7-303">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="342f7-303">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="342f7-304">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="342f7-304">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="342f7-305">Azure SQL データベース透過的なデータの暗号化活動応答を返します。</span><span class="sxs-lookup"><span data-stu-id="342f7-305">Returns an Azure SQL Database Transparent Data Encryption Activity Response.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="342f7-306">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-306">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="342f7-307">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-307">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="342f7-308">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-308">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric&gt;&gt;&gt; ListUsagesWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric&gt;&gt;&gt; ListUsagesWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations.ListUsagesWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListUsagesWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric&gt;&gt;&gt;" Usage="iDatabasesOperations.ListUsagesWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.DatabaseMetric&gt;&gt;&gt;</ReturnType>
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
            <span data-ttu-id="342f7-309">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-309">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="342f7-310">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="342f7-310">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="342f7-311">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-311">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="342f7-312">Azure SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-312">The name of the Azure SQL database.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="342f7-313">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="342f7-313">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="342f7-314">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="342f7-314">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="342f7-315">Azure SQL データベースの使用状況に関する情報を返します。</span><span class="sxs-lookup"><span data-stu-id="342f7-315">Returns information about Azure SQL database usages.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="342f7-316">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-316">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="342f7-317">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-317">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="342f7-318">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-318">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PauseDataWarehouseWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; PauseDataWarehouseWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; PauseDataWarehouseWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations.PauseDataWarehouseWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PauseDataWarehouseWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDatabasesOperations.PauseDataWarehouseWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
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
            <span data-ttu-id="342f7-319">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-319">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="342f7-320">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="342f7-320">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="342f7-321">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-321">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="342f7-322">一時停止する Azure SQL Data Warehouse データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-322">The name of the Azure SQL Data Warehouse database to pause.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="342f7-323">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="342f7-323">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="342f7-324">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="342f7-324">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="342f7-325">Azure SQL Data Warehouse データベースを一時停止します。</span><span class="sxs-lookup"><span data-stu-id="342f7-325">Pause an Azure SQL Data Warehouse database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="342f7-326">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-326">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="342f7-327">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-327">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ResumeDataWarehouseWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ResumeDataWarehouseWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ResumeDataWarehouseWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.IDatabasesOperations.ResumeDataWarehouseWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResumeDataWarehouseWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDatabasesOperations.ResumeDataWarehouseWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
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
            <span data-ttu-id="342f7-328">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-328">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="342f7-329">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="342f7-329">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="342f7-330">Azure SQL サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-330">The name of the Azure SQL server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="342f7-331">再開する Azure SQL Data Warehouse データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="342f7-331">The name of the Azure SQL Data Warehouse database to resume.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="342f7-332">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="342f7-332">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="342f7-333">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="342f7-333">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="342f7-334">Azure SQL Data Warehouse データベースを再開します。</span><span class="sxs-lookup"><span data-stu-id="342f7-334">Resume an Azure SQL Data Warehouse database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="342f7-335">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-335">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="342f7-336">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="342f7-336">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>