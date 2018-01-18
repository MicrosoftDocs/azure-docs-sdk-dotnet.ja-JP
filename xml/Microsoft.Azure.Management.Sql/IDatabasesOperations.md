<Type Name="IDatabasesOperations" FullName="Microsoft.Azure.Management.Sql.IDatabasesOperations">
  <TypeSignature Language="C#" Value="public interface IDatabasesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDatabasesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.IDatabasesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDatabasesOperations" />
  <TypeSignature Language="F#" Value="type IDatabasesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6b86d-101">DatabasesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="6b86d-101">DatabasesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateImportOperationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;&gt; BeginCreateImportOperationWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;&gt; BeginCreateImportOperationWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IDatabasesOperations.BeginCreateImportOperationWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateImportOperationWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;&gt;" Usage="iDatabasesOperations.BeginCreateImportOperationWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6b86d-102">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-102">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6b86d-103">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-103">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6b86d-104">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-104">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="6b86d-105">インポートするデータベースの名前</span><span class="sxs-lookup"><span data-stu-id="6b86d-105">The name of the database to import into</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6b86d-106">データベースに Bacpac をインポートするための必須パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="6b86d-106">The required parameters for importing a Bacpac into a database.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6b86d-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b86d-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6b86d-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b86d-109">既存のデータベースに bacpac をインポートするインポート操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-109">Creates an import operation that imports a bacpac into an existing database.</span></span> <span data-ttu-id="6b86d-110">既存のデータベースを空にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="6b86d-110">The existing database must be empty.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6b86d-111">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6b86d-112">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-112">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6b86d-113">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-113">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.Database parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.Database&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.Database parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IDatabasesOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.Database,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Sql.Models.Database * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;" Usage="iDatabasesOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.Database" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6b86d-114">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-114">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6b86d-115">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-115">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6b86d-116">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-116">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="6b86d-117">処理されるデータベースの名前 (更新または作成した)。</span><span class="sxs-lookup"><span data-stu-id="6b86d-117">The name of the database to be operated on (updated or created).</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6b86d-118">作成またはデータベースの更新の必須パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="6b86d-118">The required parameters for creating or updating a database.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6b86d-119">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-119">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b86d-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6b86d-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b86d-121">新しいデータベースを作成するか、既存のデータベースを更新します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-121">Creates a new database or updates an existing database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6b86d-122">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-122">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6b86d-123">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-123">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6b86d-124">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-124">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginExportWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;&gt; BeginExportWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.ExportRequest parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;&gt; BeginExportWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.ExportRequest parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IDatabasesOperations.BeginExportWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ExportRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginExportWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Sql.Models.ExportRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;&gt;" Usage="iDatabasesOperations.BeginExportWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ExportRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6b86d-125">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-125">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6b86d-126">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-126">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6b86d-127">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-127">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="6b86d-128">エクスポートするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-128">The name of the database to be exported.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6b86d-129">データベースのエクスポートの必要なパラメーター。</span><span class="sxs-lookup"><span data-stu-id="6b86d-129">The required parameters for exporting a database.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6b86d-130">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-130">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b86d-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6b86d-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b86d-132">データベースを bacpac をエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="6b86d-132">Exports a database to a bacpac.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6b86d-133">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-133">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6b86d-134">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-134">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6b86d-135">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-135">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginImportWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;&gt; BeginImportWithHttpMessagesAsync (string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.ImportRequest parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;&gt; BeginImportWithHttpMessagesAsync(string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.ImportRequest parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IDatabasesOperations.BeginImportWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Sql.Models.ImportRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginImportWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Sql.Models.ImportRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;&gt;" Usage="iDatabasesOperations.BeginImportWithHttpMessagesAsync (resourceGroupName, serverName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ImportRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6b86d-136">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-136">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6b86d-137">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-137">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6b86d-138">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-138">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6b86d-139">データベースに Bacpac をインポートするための必須パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="6b86d-139">The required parameters for importing a Bacpac into a database.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6b86d-140">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-140">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b86d-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6b86d-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b86d-142">新しいデータベースに bacpac をインポートします。</span><span class="sxs-lookup"><span data-stu-id="6b86d-142">Imports a bacpac into a new database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6b86d-143">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-143">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6b86d-144">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-144">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6b86d-145">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginPauseWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginPauseWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginPauseWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IDatabasesOperations.BeginPauseWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginPauseWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDatabasesOperations.BeginPauseWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, customHeaders, cancellationToken)" />
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
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6b86d-146">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-146">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6b86d-147">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-147">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6b86d-148">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-148">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="6b86d-149">一時停止する、データ ウェアハウスの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-149">The name of the data warehouse to pause.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6b86d-150">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-150">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b86d-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6b86d-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b86d-152">データ ウェアハウスを一時停止します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-152">Pauses a data warehouse.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6b86d-153">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-153">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6b86d-154">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-154">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginResumeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginResumeWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginResumeWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IDatabasesOperations.BeginResumeWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginResumeWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDatabasesOperations.BeginResumeWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, customHeaders, cancellationToken)" />
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
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6b86d-155">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-155">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6b86d-156">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-156">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6b86d-157">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-157">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="6b86d-158">再開する、データ ウェアハウスの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-158">The name of the data warehouse to resume.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6b86d-159">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-159">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b86d-160">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6b86d-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b86d-161">データ ウェアハウスを再開します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-161">Resumes a data warehouse.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6b86d-162">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-162">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6b86d-163">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-163">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt; BeginUpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.DatabaseUpdate parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.Database&gt;&gt; BeginUpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.DatabaseUpdate parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IDatabasesOperations.BeginUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.DatabaseUpdate,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Sql.Models.DatabaseUpdate * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;" Usage="iDatabasesOperations.BeginUpdateWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6b86d-164">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-164">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6b86d-165">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-165">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6b86d-166">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-166">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="6b86d-167">更新するデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-167">The name of the database to be updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6b86d-168">データベースの更新の必須パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="6b86d-168">The required parameters for updating a database.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6b86d-169">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-169">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b86d-170">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6b86d-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b86d-171">既存のデータベースを更新します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-171">Updates an existing database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6b86d-172">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-172">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6b86d-173">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-173">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6b86d-174">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-174">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateImportOperationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;&gt; CreateImportOperationWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;&gt; CreateImportOperationWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IDatabasesOperations.CreateImportOperationWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateImportOperationWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;&gt;" Usage="iDatabasesOperations.CreateImportOperationWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ImportExtensionRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6b86d-175">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-175">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6b86d-176">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-176">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6b86d-177">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-177">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="6b86d-178">インポートするデータベースの名前</span><span class="sxs-lookup"><span data-stu-id="6b86d-178">The name of the database to import into</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6b86d-179">データベースに Bacpac をインポートするための必須パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="6b86d-179">The required parameters for importing a Bacpac into a database.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6b86d-180">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-180">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b86d-181">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6b86d-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b86d-182">既存のデータベースに bacpac をインポートするインポート操作を作成します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-182">Creates an import operation that imports a bacpac into an existing database.</span></span> <span data-ttu-id="6b86d-183">既存のデータベースを空にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="6b86d-183">The existing database must be empty.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6b86d-184">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-184">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6b86d-185">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-185">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6b86d-186">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-186">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.Database parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.Database&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.Database parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IDatabasesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.Database,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Sql.Models.Database * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;" Usage="iDatabasesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.Database" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6b86d-187">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-187">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6b86d-188">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-188">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6b86d-189">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-189">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="6b86d-190">処理されるデータベースの名前 (更新または作成した)。</span><span class="sxs-lookup"><span data-stu-id="6b86d-190">The name of the database to be operated on (updated or created).</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6b86d-191">作成またはデータベースの更新の必須パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="6b86d-191">The required parameters for creating or updating a database.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6b86d-192">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-192">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b86d-193">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6b86d-193">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b86d-194">新しいデータベースを作成するか、既存のデータベースを更新します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-194">Creates a new database or updates an existing database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6b86d-195">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-195">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6b86d-196">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-196">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6b86d-197">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-197">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IDatabasesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDatabasesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, customHeaders, cancellationToken)" />
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
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6b86d-198">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-198">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6b86d-199">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-199">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6b86d-200">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-200">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="6b86d-201">削除するデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-201">The name of the database to be deleted.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6b86d-202">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-202">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b86d-203">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6b86d-203">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b86d-204">データベースを削除します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-204">Deletes a database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6b86d-205">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-205">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6b86d-206">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-206">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ExportWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;&gt; ExportWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.ExportRequest parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;&gt; ExportWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.ExportRequest parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IDatabasesOperations.ExportWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ExportRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExportWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Sql.Models.ExportRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;&gt;" Usage="iDatabasesOperations.ExportWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ExportRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6b86d-207">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-207">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6b86d-208">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-208">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6b86d-209">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-209">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="6b86d-210">エクスポートするデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-210">The name of the database to be exported.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6b86d-211">データベースのエクスポートの必要なパラメーター。</span><span class="sxs-lookup"><span data-stu-id="6b86d-211">The required parameters for exporting a database.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6b86d-212">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-212">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b86d-213">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6b86d-213">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b86d-214">データベースを bacpac をエクスポートします。</span><span class="sxs-lookup"><span data-stu-id="6b86d-214">Exports a database to a bacpac.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6b86d-215">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-215">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6b86d-216">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-216">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6b86d-217">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-217">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetByElasticPoolWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt; GetByElasticPoolWithHttpMessagesAsync (string resourceGroupName, string serverName, string elasticPoolName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.Database&gt;&gt; GetByElasticPoolWithHttpMessagesAsync(string resourceGroupName, string serverName, string elasticPoolName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IDatabasesOperations.GetByElasticPoolWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetByElasticPoolWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;" Usage="iDatabasesOperations.GetByElasticPoolWithHttpMessagesAsync (resourceGroupName, serverName, elasticPoolName, databaseName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6b86d-218">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-218">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6b86d-219">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-219">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6b86d-220">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-220">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="6b86d-221">取得する弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-221">The name of the elastic pool to be retrieved.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="6b86d-222">取得するデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-222">The name of the database to be retrieved.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6b86d-223">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-223">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b86d-224">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6b86d-224">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b86d-225">エラスティック プール内のデータベースを取得します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-225">Gets a database inside of an elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6b86d-226">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-226">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6b86d-227">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-227">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6b86d-228">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-228">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetByRecommendedElasticPoolWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt; GetByRecommendedElasticPoolWithHttpMessagesAsync (string resourceGroupName, string serverName, string recommendedElasticPoolName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.Database&gt;&gt; GetByRecommendedElasticPoolWithHttpMessagesAsync(string resourceGroupName, string serverName, string recommendedElasticPoolName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IDatabasesOperations.GetByRecommendedElasticPoolWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetByRecommendedElasticPoolWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;" Usage="iDatabasesOperations.GetByRecommendedElasticPoolWithHttpMessagesAsync (resourceGroupName, serverName, recommendedElasticPoolName, databaseName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="recommendedElasticPoolName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6b86d-229">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-229">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6b86d-230">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-230">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6b86d-231">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-231">The name of the server.</span></span>
            </param>
        <param name="recommendedElasticPoolName">
            <span data-ttu-id="6b86d-232">取得する弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-232">The name of the elastic pool to be retrieved.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="6b86d-233">取得するデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-233">The name of the database to be retrieved.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6b86d-234">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-234">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b86d-235">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6b86d-235">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b86d-236">推奨されるエラスティック プール内のデータベースを取得します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-236">Gets a database inside of a recommented elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6b86d-237">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-237">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6b86d-238">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-238">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6b86d-239">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-239">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string expand = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.Database&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string expand, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IDatabasesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;" Usage="iDatabasesOperations.GetWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, expand, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;</ReturnType>
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
            <span data-ttu-id="6b86d-240">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-240">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6b86d-241">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-241">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6b86d-242">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-242">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="6b86d-243">取得するデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-243">The name of the database to be retrieved.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="6b86d-244">コンマ区切りの応答で展開する子オブジェクトの一覧。</span><span class="sxs-lookup"><span data-stu-id="6b86d-244">A comma separated list of child objects to expand in the response.</span></span>
            <span data-ttu-id="6b86d-245">使用可能なプロパティ: serviceTierAdvisors、transparentDataEncryption です。</span><span class="sxs-lookup"><span data-stu-id="6b86d-245">Possible properties: serviceTierAdvisors, transparentDataEncryption.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6b86d-246">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-246">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b86d-247">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6b86d-247">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b86d-248">データベースを取得します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-248">Gets a database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6b86d-249">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-249">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6b86d-250">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-250">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6b86d-251">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-251">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ImportWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;&gt; ImportWithHttpMessagesAsync (string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.ImportRequest parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;&gt; ImportWithHttpMessagesAsync(string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.ImportRequest parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IDatabasesOperations.ImportWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Sql.Models.ImportRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ImportWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Sql.Models.ImportRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;&gt;" Usage="iDatabasesOperations.ImportWithHttpMessagesAsync (resourceGroupName, serverName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.ImportExportResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ImportRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6b86d-252">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-252">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6b86d-253">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-253">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6b86d-254">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-254">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6b86d-255">データベースに Bacpac をインポートするための必須パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="6b86d-255">The required parameters for importing a Bacpac into a database.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6b86d-256">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-256">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b86d-257">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6b86d-257">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b86d-258">新しいデータベースに bacpac をインポートします。</span><span class="sxs-lookup"><span data-stu-id="6b86d-258">Imports a bacpac into a new database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6b86d-259">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-259">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6b86d-260">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-260">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6b86d-261">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-261">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByElasticPoolWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;&gt; ListByElasticPoolWithHttpMessagesAsync (string resourceGroupName, string serverName, string elasticPoolName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;&gt; ListByElasticPoolWithHttpMessagesAsync(string resourceGroupName, string serverName, string elasticPoolName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IDatabasesOperations.ListByElasticPoolWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByElasticPoolWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;&gt;" Usage="iDatabasesOperations.ListByElasticPoolWithHttpMessagesAsync (resourceGroupName, serverName, elasticPoolName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6b86d-262">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-262">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6b86d-263">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-263">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6b86d-264">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-264">The name of the server.</span></span>
            </param>
        <param name="elasticPoolName">
            <span data-ttu-id="6b86d-265">取得する弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-265">The name of the elastic pool to be retrieved.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6b86d-266">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-266">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b86d-267">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6b86d-267">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b86d-268">エラスティック プール内のデータベースの一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-268">Returns a list of databases in an elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6b86d-269">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-269">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6b86d-270">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-270">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6b86d-271">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-271">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByRecommendedElasticPoolWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;&gt; ListByRecommendedElasticPoolWithHttpMessagesAsync (string resourceGroupName, string serverName, string recommendedElasticPoolName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;&gt; ListByRecommendedElasticPoolWithHttpMessagesAsync(string resourceGroupName, string serverName, string recommendedElasticPoolName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IDatabasesOperations.ListByRecommendedElasticPoolWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByRecommendedElasticPoolWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;&gt;" Usage="iDatabasesOperations.ListByRecommendedElasticPoolWithHttpMessagesAsync (resourceGroupName, serverName, recommendedElasticPoolName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="recommendedElasticPoolName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6b86d-272">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-272">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6b86d-273">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-273">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6b86d-274">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-274">The name of the server.</span></span>
            </param>
        <param name="recommendedElasticPoolName">
            <span data-ttu-id="6b86d-275">取得することをお勧め弾力性プールの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-275">The name of the recommended elastic pool to be retrieved.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6b86d-276">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-276">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b86d-277">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6b86d-277">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b86d-278">推奨されるエラスティック プール内のデータベースの一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-278">Returns a list of databases inside a recommented elastic pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6b86d-279">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-279">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6b86d-280">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-280">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6b86d-281">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-281">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByServerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;&gt; ListByServerWithHttpMessagesAsync (string resourceGroupName, string serverName, string expand = null, string filter = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;&gt; ListByServerWithHttpMessagesAsync(string resourceGroupName, string serverName, string expand, string filter, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IDatabasesOperations.ListByServerWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByServerWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;&gt;" Usage="iDatabasesOperations.ListByServerWithHttpMessagesAsync (resourceGroupName, serverName, expand, filter, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6b86d-282">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-282">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6b86d-283">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-283">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6b86d-284">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-284">The name of the server.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="6b86d-285">コンマ区切りの応答で展開する子オブジェクトの一覧。</span><span class="sxs-lookup"><span data-stu-id="6b86d-285">A comma separated list of child objects to expand in the response.</span></span>
            <span data-ttu-id="6b86d-286">使用可能なプロパティ: serviceTierAdvisors、transparentDataEncryption です。</span><span class="sxs-lookup"><span data-stu-id="6b86d-286">Possible properties: serviceTierAdvisors, transparentDataEncryption.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="6b86d-287">返されるデータベースのサブセットを記述する OData フィルター式。</span><span class="sxs-lookup"><span data-stu-id="6b86d-287">An OData filter expression that describes a subset of databases to return.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6b86d-288">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-288">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b86d-289">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6b86d-289">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b86d-290">サーバー内のデータベースの一覧を返します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-290">Returns a list of databases in a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6b86d-291">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-291">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6b86d-292">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-292">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6b86d-293">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-293">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinitionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt;&gt;&gt; ListMetricDefinitionsWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt;&gt;&gt; ListMetricDefinitionsWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IDatabasesOperations.ListMetricDefinitionsWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMetricDefinitionsWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt;&gt;&gt;" Usage="iDatabasesOperations.ListMetricDefinitionsWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.MetricDefinition&gt;&gt;&gt;</ReturnType>
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
            <span data-ttu-id="6b86d-294">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-294">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6b86d-295">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-295">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6b86d-296">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-296">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="6b86d-297">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-297">The name of the database.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6b86d-298">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-298">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b86d-299">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6b86d-299">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b86d-300">データベースのメトリックの定義の返します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-300">Returns database metric definitions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6b86d-301">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-301">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6b86d-302">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-302">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6b86d-303">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-303">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Metric&gt;&gt;&gt; ListMetricsWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, string filter, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.Metric&gt;&gt;&gt; ListMetricsWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, string filter, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IDatabasesOperations.ListMetricsWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMetricsWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.Metric&gt;&gt;&gt;" Usage="iDatabasesOperations.ListMetricsWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, filter, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.Metric&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6b86d-304">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-304">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6b86d-305">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-305">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6b86d-306">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-306">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="6b86d-307">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-307">The name of the database.</span></span>
            </param>
        <param name="filter">
            <span data-ttu-id="6b86d-308">取得するメトリックのサブセットを記述する OData フィルター式。</span><span class="sxs-lookup"><span data-stu-id="6b86d-308">An OData filter expression that describes a subset of metrics to return.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6b86d-309">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-309">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b86d-310">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6b86d-310">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b86d-311">データベースのメトリックの返します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-311">Returns database metrics.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6b86d-312">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-312">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6b86d-313">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-313">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6b86d-314">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-314">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PauseWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; PauseWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; PauseWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IDatabasesOperations.PauseWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PauseWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDatabasesOperations.PauseWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, customHeaders, cancellationToken)" />
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
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6b86d-315">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-315">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6b86d-316">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-316">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6b86d-317">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-317">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="6b86d-318">一時停止する、データ ウェアハウスの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-318">The name of the data warehouse to pause.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6b86d-319">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-319">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b86d-320">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6b86d-320">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b86d-321">データ ウェアハウスを一時停止します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-321">Pauses a data warehouse.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6b86d-322">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-322">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6b86d-323">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-323">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RenameWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; RenameWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.ResourceMoveDefinition parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; RenameWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.ResourceMoveDefinition parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IDatabasesOperations.RenameWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ResourceMoveDefinition,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RenameWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Sql.Models.ResourceMoveDefinition * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDatabasesOperations.RenameWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, parameters, customHeaders, cancellationToken)" />
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
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ResourceMoveDefinition" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6b86d-324">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-324">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6b86d-325">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-325">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6b86d-326">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-326">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="6b86d-327">名前を変更するデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-327">The name of the database to rename.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6b86d-328">リソースは、このデータベースの名前を変更するための定義を移動します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-328">The resource move definition for renaming this database.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6b86d-329">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-329">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b86d-330">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6b86d-330">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b86d-331">データベースの名前を変更します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-331">Renames a database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6b86d-332">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-332">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6b86d-333">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-333">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ResumeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ResumeWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ResumeWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IDatabasesOperations.ResumeWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResumeWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iDatabasesOperations.ResumeWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, customHeaders, cancellationToken)" />
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
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6b86d-334">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-334">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6b86d-335">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-335">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6b86d-336">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-336">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="6b86d-337">再開する、データ ウェアハウスの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-337">The name of the data warehouse to resume.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6b86d-338">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-338">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b86d-339">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6b86d-339">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b86d-340">データ ウェアハウスを再開します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-340">Resumes a data warehouse.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6b86d-341">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-341">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6b86d-342">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-342">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.DatabaseUpdate parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.Database&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.DatabaseUpdate parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IDatabasesOperations.UpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.DatabaseUpdate,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Sql.Models.DatabaseUpdate * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;" Usage="iDatabasesOperations.UpdateWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.Database&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="6b86d-343">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-343">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="6b86d-344">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-344">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="6b86d-345">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-345">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="6b86d-346">更新するデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="6b86d-346">The name of the database to be updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6b86d-347">データベースの更新の必須パラメーターです。</span><span class="sxs-lookup"><span data-stu-id="6b86d-347">The required parameters for updating a database.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="6b86d-348">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-348">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b86d-349">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="6b86d-349">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b86d-350">既存のデータベースを更新します。</span><span class="sxs-lookup"><span data-stu-id="6b86d-350">Updates an existing database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="6b86d-351">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-351">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="6b86d-352">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-352">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6b86d-353">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="6b86d-353">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>