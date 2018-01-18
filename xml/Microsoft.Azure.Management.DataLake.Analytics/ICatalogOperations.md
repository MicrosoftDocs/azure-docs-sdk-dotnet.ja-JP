<Type Name="ICatalogOperations" FullName="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations">
  <TypeSignature Language="C#" Value="public interface ICatalogOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICatalogOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICatalogOperations" />
  <TypeSignature Language="F#" Value="type ICatalogOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5d4a6-101">CatalogOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-101">CatalogOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateCredentialWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; CreateCredentialWithHttpMessagesAsync (string accountName, string databaseName, string credentialName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; CreateCredentialWithHttpMessagesAsync(string accountName, string databaseName, string credentialName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.CreateCredentialWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateCredentialWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iCatalogOperations.CreateCredentialWithHttpMessagesAsync (accountName, databaseName, credentialName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-102">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-102">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-103">資格情報を作成するためのデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-103">The name of the database in which to create the credential.</span></span> <span data-ttu-id="5d4a6-104">注: これは、外部データベース名はなく、新しい資格情報オブジェクトを含む既存の U SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-104">Note: This is NOT an external database name, but the name of an existing U-SQL database that should contain the new credential object.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="5d4a6-105">資格情報の名前です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-105">The name of the credential.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5d4a6-106">資格情報 (名前とパスワード) を作成するために必要なパラメーター</span><span class="sxs-lookup"><span data-stu-id="5d4a6-106">The parameters required to create the credential (name and password)</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-109">指定されたデータベースで外部データ ソースを使用する指定された資格情報を作成します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-109">Creates the specified credential for use with external data sources in the specified database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-110">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; CreateSecretWithHttpMessagesAsync (string accountName, string databaseName, string secretName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; CreateSecretWithHttpMessagesAsync(string accountName, string databaseName, string secretName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.CreateSecretWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateSecretWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iCatalogOperations.CreateSecretWithHttpMessagesAsync (accountName, databaseName, secretName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-112">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-112">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-113">シークレットを作成するデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-113">The name of the database in which to create the secret.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="5d4a6-114">シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-114">The name of the secret.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5d4a6-115">(名前とパスワード) のシークレットの作成に必要なパラメーター</span><span class="sxs-lookup"><span data-stu-id="5d4a6-115">The parameters required to create the secret (name and password)</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-116">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-116">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-118">指定されたデータベースで外部データ ソースを使用する指定されたシークレットを作成します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-118">Creates the specified secret for use with external data sources in the specified database.</span></span> <span data-ttu-id="5d4a6-119">これは廃止されており、次のリリースで削除される予定です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-119">This is deprecated and will be removed in the next release.</span></span> <span data-ttu-id="5d4a6-120">CreateCredential を使用してください。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-120">Please use CreateCredential instead.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-121">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-121">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-122">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-122">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteAllSecretsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteAllSecretsWithHttpMessagesAsync (string accountName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteAllSecretsWithHttpMessagesAsync(string accountName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.DeleteAllSecretsWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAllSecretsWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iCatalogOperations.DeleteAllSecretsWithHttpMessagesAsync (accountName, databaseName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-123">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-123">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-124">シークレットを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-124">The name of the database containing the secret.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-125">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-125">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-127">指定されたデータベース内のすべてのシークレットを削除します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-127">Deletes all secrets in the specified database.</span></span> <span data-ttu-id="5d4a6-128">これは廃止されており、次のリリースで削除される予定です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-128">This is deprecated and will be removed in the next release.</span></span> <span data-ttu-id="5d4a6-129">今後、のみを削除してください DeleteCredential を使用して個別の資格情報</span><span class="sxs-lookup"><span data-stu-id="5d4a6-129">In the future, please only drop individual credentials using DeleteCredential</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-130">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-130">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-131">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-131">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteCredentialWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteCredentialWithHttpMessagesAsync (string accountName, string databaseName, string credentialName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters parameters = null, Nullable&lt;bool&gt; cascade = false, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteCredentialWithHttpMessagesAsync(string accountName, string databaseName, string credentialName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters parameters, valuetype System.Nullable`1&lt;bool&gt; cascade, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.DeleteCredentialWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteCredentialWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iCatalogOperations.DeleteCredentialWithHttpMessagesAsync (accountName, databaseName, credentialName, parameters, cascade, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters" />
        <Parameter Name="cascade" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-132">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-132">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-133">資格情報を含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-133">The name of the database containing the credential.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="5d4a6-134">削除する資格情報の名前</span><span class="sxs-lookup"><span data-stu-id="5d4a6-134">The name of the credential to delete</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5d4a6-135">現在のユーザーがアカウント所有者ではない場合、資格情報を削除するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-135">The parameters to delete a credential if the current user is not the account owner.</span></span>
            </param>
        <param name="cascade">
            <span data-ttu-id="5d4a6-136">かどうか、削除があります (資格情報だけでなく、資格情報に依存するすべてのリソースを削除) する連鎖削除を示すか。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-136">Indicates if the delete should be a cascading delete (which deletes all resources dependent on the credential as well as the credential) or not.</span></span> <span data-ttu-id="5d4a6-137">場合は、資格情報に依存するすべてのリソースがある場合、false は失敗します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-137">If false will fail if there are any resources relying on the credential.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-138">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-138">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-140">指定されたデータベースで指定された資格情報を削除します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-140">Deletes the specified credential in the specified database</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-141">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-141">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-142">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-142">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteSecretWithHttpMessagesAsync (string accountName, string databaseName, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteSecretWithHttpMessagesAsync(string accountName, string databaseName, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.DeleteSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteSecretWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iCatalogOperations.DeleteSecretWithHttpMessagesAsync (accountName, databaseName, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-143">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-143">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-144">シークレットを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-144">The name of the database containing the secret.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="5d4a6-145">削除するシークレットの名前</span><span class="sxs-lookup"><span data-stu-id="5d4a6-145">The name of the secret to delete</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-146">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-146">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-147">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-148">指定されたデータベースで指定されたシークレットを削除します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-148">Deletes the specified secret in the specified database.</span></span> <span data-ttu-id="5d4a6-149">これは廃止されており、次のリリースで削除される予定です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-149">This is deprecated and will be removed in the next release.</span></span> <span data-ttu-id="5d4a6-150">DeleteCredential を使用してください。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-150">Please use DeleteCredential instead.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-151">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-151">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-152">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-152">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetAssemblyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt;&gt; GetAssemblyWithHttpMessagesAsync (string accountName, string databaseName, string assemblyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt;&gt; GetAssemblyWithHttpMessagesAsync(string accountName, string databaseName, string assemblyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.GetAssemblyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAssemblyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt;&gt;" Usage="iCatalogOperations.GetAssemblyWithHttpMessagesAsync (accountName, databaseName, assemblyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="assemblyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-153">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-153">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-154">アセンブリを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-154">The name of the database containing the assembly.</span></span>
            </param>
        <param name="assemblyName">
            <span data-ttu-id="5d4a6-155">アセンブリの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-155">The name of the assembly.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-156">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-156">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-157">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-158">Data Lake Analytics カタログから指定したアセンブリを取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-158">Retrieves the specified assembly from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-159">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-159">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-160">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-160">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-161">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-161">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetCredentialWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt; GetCredentialWithHttpMessagesAsync (string accountName, string databaseName, string credentialName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt; GetCredentialWithHttpMessagesAsync(string accountName, string databaseName, string credentialName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.GetCredentialWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCredentialWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt;" Usage="iCatalogOperations.GetCredentialWithHttpMessagesAsync (accountName, databaseName, credentialName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-162">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-162">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-163">スキーマを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-163">The name of the database containing the schema.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="5d4a6-164">資格情報の名前です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-164">The name of the credential.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-165">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-165">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-166">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-167">Data Lake Analytics カタログから指定された資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-167">Retrieves the specified credential from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-168">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-168">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-169">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-169">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-170">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-170">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDatabaseWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt; GetDatabaseWithHttpMessagesAsync (string accountName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt; GetDatabaseWithHttpMessagesAsync(string accountName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.GetDatabaseWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDatabaseWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt;" Usage="iCatalogOperations.GetDatabaseWithHttpMessagesAsync (accountName, databaseName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-171">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-171">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-172">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-172">The name of the database.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-173">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-173">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-174">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-175">Data Lake Analytics カタログから、指定されたデータベースを取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-175">Retrieves the specified database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-176">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-176">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-177">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-177">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-178">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-178">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetExternalDataSourceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt; GetExternalDataSourceWithHttpMessagesAsync (string accountName, string databaseName, string externalDataSourceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt; GetExternalDataSourceWithHttpMessagesAsync(string accountName, string databaseName, string externalDataSourceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.GetExternalDataSourceWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetExternalDataSourceWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt;" Usage="iCatalogOperations.GetExternalDataSourceWithHttpMessagesAsync (accountName, databaseName, externalDataSourceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="externalDataSourceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-179">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-179">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-180">外部データ ソースを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-180">The name of the database containing the external data source.</span></span>
            </param>
        <param name="externalDataSourceName">
            <span data-ttu-id="5d4a6-181">外部データ ソースの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-181">The name of the external data source.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-182">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-182">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-183">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-183">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-184">Data Lake Analytics カタログから、指定された外部データ ソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-184">Retrieves the specified external data source from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-185">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-185">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-186">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-186">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-187">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-187">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPackageWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt; GetPackageWithHttpMessagesAsync (string accountName, string databaseName, string schemaName, string packageName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt; GetPackageWithHttpMessagesAsync(string accountName, string databaseName, string schemaName, string packageName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.GetPackageWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPackageWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt;" Usage="iCatalogOperations.GetPackageWithHttpMessagesAsync (accountName, databaseName, schemaName, packageName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="packageName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-188">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-188">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-189">パッケージを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-189">The name of the database containing the package.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="5d4a6-190">パッケージを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-190">The name of the schema containing the package.</span></span>
            </param>
        <param name="packageName">
            <span data-ttu-id="5d4a6-191">パッケージの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-191">The name of the package.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-192">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-192">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-193">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-193">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-194">Data Lake Analytics カタログから指定したパッケージを取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-194">Retrieves the specified package from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-195">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-195">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-196">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-196">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-197">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-197">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetProcedureWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt; GetProcedureWithHttpMessagesAsync (string accountName, string databaseName, string schemaName, string procedureName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt; GetProcedureWithHttpMessagesAsync(string accountName, string databaseName, string schemaName, string procedureName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.GetProcedureWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetProcedureWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt;" Usage="iCatalogOperations.GetProcedureWithHttpMessagesAsync (accountName, databaseName, schemaName, procedureName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="procedureName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-198">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-198">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-199">プロシージャを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-199">The name of the database containing the procedure.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="5d4a6-200">プロシージャを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-200">The name of the schema containing the procedure.</span></span>
            </param>
        <param name="procedureName">
            <span data-ttu-id="5d4a6-201">プロシージャの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-201">The name of the procedure.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-202">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-202">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-203">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-203">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-204">Data Lake Analytics カタログから、指定したプロシージャを取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-204">Retrieves the specified procedure from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-205">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-205">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-206">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-206">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-207">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-207">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetSchemaWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt; GetSchemaWithHttpMessagesAsync (string accountName, string databaseName, string schemaName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt; GetSchemaWithHttpMessagesAsync(string accountName, string databaseName, string schemaName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.GetSchemaWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSchemaWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt;" Usage="iCatalogOperations.GetSchemaWithHttpMessagesAsync (accountName, databaseName, schemaName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-208">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-208">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-209">スキーマを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-209">The name of the database containing the schema.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="5d4a6-210">スキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-210">The name of the schema.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-211">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-211">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-212">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-212">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-213">Data Lake Analytics カタログから、指定したスキーマを取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-213">Retrieves the specified schema from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-214">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-214">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-215">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-215">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-216">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-216">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret&gt;&gt; GetSecretWithHttpMessagesAsync (string accountName, string databaseName, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret&gt;&gt; GetSecretWithHttpMessagesAsync(string accountName, string databaseName, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.GetSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecretWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret&gt;&gt;" Usage="iCatalogOperations.GetSecretWithHttpMessagesAsync (accountName, databaseName, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-217">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-217">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-218">シークレットを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-218">The name of the database containing the secret.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="5d4a6-219">取得するシークレットの名前</span><span class="sxs-lookup"><span data-stu-id="5d4a6-219">The name of the secret to get</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-220">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-220">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-221">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-221">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-222">指定されたデータベースで、指定されたシークレットを取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-222">Gets the specified secret in the specified database.</span></span> <span data-ttu-id="5d4a6-223">これは廃止されており、次のリリースで削除される予定です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-223">This is deprecated and will be removed in the next release.</span></span> <span data-ttu-id="5d4a6-224">GetCredential を使用してください。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-224">Please use GetCredential instead.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-225">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-225">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-226">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-226">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-227">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-227">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetTablePartitionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt; GetTablePartitionWithHttpMessagesAsync (string accountName, string databaseName, string schemaName, string tableName, string partitionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt; GetTablePartitionWithHttpMessagesAsync(string accountName, string databaseName, string schemaName, string tableName, string partitionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.GetTablePartitionWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTablePartitionWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt;" Usage="iCatalogOperations.GetTablePartitionWithHttpMessagesAsync (accountName, databaseName, schemaName, tableName, partitionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="partitionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-228">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-228">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-229">パーティションを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-229">The name of the database containing the partition.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="5d4a6-230">パーティションを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-230">The name of the schema containing the partition.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="5d4a6-231">パーティションを含むテーブルの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-231">The name of the table containing the partition.</span></span>
            </param>
        <param name="partitionName">
            <span data-ttu-id="5d4a6-232">テーブルのパーティションの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-232">The name of the table partition.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-233">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-233">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-234">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-234">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-235">Data Lake Analytics カタログから指定したテーブルのパーティションを取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-235">Retrieves the specified table partition from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-236">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-236">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-237">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-237">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-238">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-238">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetTableStatisticWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt; GetTableStatisticWithHttpMessagesAsync (string accountName, string databaseName, string schemaName, string tableName, string statisticsName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt; GetTableStatisticWithHttpMessagesAsync(string accountName, string databaseName, string schemaName, string tableName, string statisticsName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.GetTableStatisticWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTableStatisticWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;" Usage="iCatalogOperations.GetTableStatisticWithHttpMessagesAsync (accountName, databaseName, schemaName, tableName, statisticsName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="statisticsName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-239">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-239">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-240">統計情報を含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-240">The name of the database containing the statistics.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="5d4a6-241">統計情報を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-241">The name of the schema containing the statistics.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="5d4a6-242">統計情報を含むテーブルの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-242">The name of the table containing the statistics.</span></span>
            </param>
        <param name="statisticsName">
            <span data-ttu-id="5d4a6-243">テーブルの統計情報の名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-243">The name of the table statistics.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-244">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-244">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-245">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-245">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-246">Data Lake Analytics カタログから指定したテーブルの統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-246">Retrieves the specified table statistics from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-247">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-247">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-248">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-248">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-249">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-249">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetTableTypeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt; GetTableTypeWithHttpMessagesAsync (string accountName, string databaseName, string schemaName, string tableTypeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt; GetTableTypeWithHttpMessagesAsync(string accountName, string databaseName, string schemaName, string tableTypeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.GetTableTypeWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTableTypeWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt;" Usage="iCatalogOperations.GetTableTypeWithHttpMessagesAsync (accountName, databaseName, schemaName, tableTypeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableTypeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-250">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-250">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-251">テーブル型を含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-251">The name of the database containing the table type.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="5d4a6-252">テーブル型を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-252">The name of the schema containing the table type.</span></span>
            </param>
        <param name="tableTypeName">
            <span data-ttu-id="5d4a6-253">取得するテーブルの型の名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-253">The name of the table type to retrieve.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-254">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-254">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-255">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-255">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-256">Data Lake Analytics カタログから、指定されたテーブル型を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-256">Retrieves the specified table type from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-257">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-257">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-258">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-258">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-259">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-259">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetTableValuedFunctionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt; GetTableValuedFunctionWithHttpMessagesAsync (string accountName, string databaseName, string schemaName, string tableValuedFunctionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt; GetTableValuedFunctionWithHttpMessagesAsync(string accountName, string databaseName, string schemaName, string tableValuedFunctionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.GetTableValuedFunctionWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTableValuedFunctionWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;" Usage="iCatalogOperations.GetTableValuedFunctionWithHttpMessagesAsync (accountName, databaseName, schemaName, tableValuedFunctionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableValuedFunctionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-260">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-260">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-261">テーブル値関数を含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-261">The name of the database containing the table valued function.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="5d4a6-262">テーブル値関数を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-262">The name of the schema containing the table valued function.</span></span>
            </param>
        <param name="tableValuedFunctionName">
            <span data-ttu-id="5d4a6-263">TableValuedFunction の名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-263">The name of the tableValuedFunction.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-264">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-264">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-265">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-265">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-266">Data Lake Analytics カタログから、指定したテーブル値関数を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-266">Retrieves the specified table valued function from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-267">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-267">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-268">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-268">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-269">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-269">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetTableWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt; GetTableWithHttpMessagesAsync (string accountName, string databaseName, string schemaName, string tableName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt; GetTableWithHttpMessagesAsync(string accountName, string databaseName, string schemaName, string tableName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.GetTableWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTableWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;" Usage="iCatalogOperations.GetTableWithHttpMessagesAsync (accountName, databaseName, schemaName, tableName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-270">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-270">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-271">テーブルを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-271">The name of the database containing the table.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="5d4a6-272">テーブルを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-272">The name of the schema containing the table.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="5d4a6-273">テーブルの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-273">The name of the table.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-274">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-274">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-275">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-275">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-276">Data Lake Analytics カタログから、指定したテーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-276">Retrieves the specified table from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-277">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-277">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-278">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-278">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-279">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-279">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetViewWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt; GetViewWithHttpMessagesAsync (string accountName, string databaseName, string schemaName, string viewName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt; GetViewWithHttpMessagesAsync(string accountName, string databaseName, string schemaName, string viewName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.GetViewWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetViewWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;" Usage="iCatalogOperations.GetViewWithHttpMessagesAsync (accountName, databaseName, schemaName, viewName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="viewName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-280">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-280">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-281">ビューを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-281">The name of the database containing the view.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="5d4a6-282">ビューを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-282">The name of the schema containing the view.</span></span>
            </param>
        <param name="viewName">
            <span data-ttu-id="5d4a6-283">ビューの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-283">The name of the view.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-284">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-284">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-285">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-285">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-286">Data Lake Analytics カタログから、指定されたビューを取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-286">Retrieves the specified view from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-287">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-287">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-288">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-288">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-289">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-289">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAssembliesNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;&gt;&gt; ListAssembliesNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;&gt;&gt; ListAssembliesNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListAssembliesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAssembliesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;&gt;&gt;" Usage="iCatalogOperations.ListAssembliesNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="5d4a6-290">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-290">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-291">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-291">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-292">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-292">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-293">Data Lake Analytics カタログからのアセンブリの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-293">Retrieves the list of assemblies from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-294">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-294">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-295">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-295">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-296">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-296">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAssembliesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;&gt;&gt; ListAssembliesWithHttpMessagesAsync (string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;&gt;&gt; ListAssembliesWithHttpMessagesAsync(string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListAssembliesWithHttpMessagesAsync(System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly},System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAssembliesWithHttpMessagesAsync : string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt; * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;&gt;&gt;" Usage="iCatalogOperations.ListAssembliesWithHttpMessagesAsync (accountName, databaseName, odataQuery, select, count, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-297">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-297">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-298">アセンブリを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-298">The name of the database containing the assembly.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="5d4a6-299">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-299">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="5d4a6-300">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-300">OData Select statement.</span></span> <span data-ttu-id="5d4a6-301">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-301">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span>
            <span data-ttu-id="5d4a6-302">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-302">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="5d4a6-303">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-303">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="5d4a6-304">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-304">Optional.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-305">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-305">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-306">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-306">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-307">Data Lake Analytics カタログからのアセンブリの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-307">Retrieves the list of assemblies from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-308">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-308">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-309">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-309">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-310">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-310">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListCredentialsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt;&gt; ListCredentialsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt;&gt; ListCredentialsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListCredentialsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListCredentialsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt;&gt;" Usage="iCatalogOperations.ListCredentialsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="5d4a6-311">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-311">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-312">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-312">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-313">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-313">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-314">Data Lake Analytics カタログの資格情報の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-314">Retrieves the list of credentials from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-315">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-315">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-316">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-316">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-317">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-317">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListCredentialsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt;&gt; ListCredentialsWithHttpMessagesAsync (string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt;&gt; ListCredentialsWithHttpMessagesAsync(string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListCredentialsWithHttpMessagesAsync(System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential},System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListCredentialsWithHttpMessagesAsync : string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt;&gt;" Usage="iCatalogOperations.ListCredentialsWithHttpMessagesAsync (accountName, databaseName, odataQuery, select, count, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-318">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-318">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-319">スキーマを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-319">The name of the database containing the schema.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="5d4a6-320">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-320">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="5d4a6-321">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-321">OData Select statement.</span></span> <span data-ttu-id="5d4a6-322">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-322">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span>
            <span data-ttu-id="5d4a6-323">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-323">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="5d4a6-324">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-324">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="5d4a6-325">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-325">Optional.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-326">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-326">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-327">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-327">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-328">Data Lake Analytics カタログの資格情報の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-328">Retrieves the list of credentials from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-329">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-329">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-330">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-330">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-331">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-331">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListDatabasesNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt;&gt; ListDatabasesNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt;&gt; ListDatabasesNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListDatabasesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListDatabasesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt;&gt;" Usage="iCatalogOperations.ListDatabasesNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="5d4a6-332">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-332">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-333">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-333">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-334">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-334">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-335">Data Lake Analytics カタログからのデータベースの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-335">Retrieves the list of databases from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-336">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-336">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-337">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-337">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-338">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-338">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListDatabasesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt;&gt; ListDatabasesWithHttpMessagesAsync (string accountName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt;&gt; ListDatabasesWithHttpMessagesAsync(string accountName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListDatabasesWithHttpMessagesAsync(System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase},System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListDatabasesWithHttpMessagesAsync : string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt;&gt;" Usage="iCatalogOperations.ListDatabasesWithHttpMessagesAsync (accountName, odataQuery, select, count, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-339">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-339">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="5d4a6-340">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-340">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="5d4a6-341">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-341">OData Select statement.</span></span> <span data-ttu-id="5d4a6-342">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-342">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span>
            <span data-ttu-id="5d4a6-343">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-343">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="5d4a6-344">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-344">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="5d4a6-345">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-345">Optional.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-346">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-346">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-347">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-347">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-348">Data Lake Analytics カタログからのデータベースの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-348">Retrieves the list of databases from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-349">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-349">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-350">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-350">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-351">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-351">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListExternalDataSourcesNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt;&gt; ListExternalDataSourcesNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt;&gt; ListExternalDataSourcesNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListExternalDataSourcesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListExternalDataSourcesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt;&gt;" Usage="iCatalogOperations.ListExternalDataSourcesNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="5d4a6-352">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-352">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-353">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-353">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-354">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-354">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-355">Data Lake Analytics カタログから外部データ ソースの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-355">Retrieves the list of external data sources from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-356">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-356">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-357">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-357">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-358">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-358">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListExternalDataSourcesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt;&gt; ListExternalDataSourcesWithHttpMessagesAsync (string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt;&gt; ListExternalDataSourcesWithHttpMessagesAsync(string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListExternalDataSourcesWithHttpMessagesAsync(System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource},System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListExternalDataSourcesWithHttpMessagesAsync : string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt;&gt;" Usage="iCatalogOperations.ListExternalDataSourcesWithHttpMessagesAsync (accountName, databaseName, odataQuery, select, count, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-359">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-359">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-360">外部データ ソースを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-360">The name of the database containing the external data sources.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="5d4a6-361">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-361">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="5d4a6-362">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-362">OData Select statement.</span></span> <span data-ttu-id="5d4a6-363">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-363">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span>
            <span data-ttu-id="5d4a6-364">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-364">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="5d4a6-365">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-365">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="5d4a6-366">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-366">Optional.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-367">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-367">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-368">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-368">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-369">Data Lake Analytics カタログから外部データ ソースの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-369">Retrieves the list of external data sources from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-370">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-370">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-371">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-371">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-372">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-372">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListPackagesNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt;&gt; ListPackagesNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt;&gt; ListPackagesNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListPackagesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListPackagesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt;&gt;" Usage="iCatalogOperations.ListPackagesNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="5d4a6-373">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-373">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-374">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-374">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-375">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-375">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-376">Data Lake Analytics カタログからのパッケージの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-376">Retrieves the list of packages from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-377">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-377">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-378">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-378">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-379">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-379">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListPackagesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt;&gt; ListPackagesWithHttpMessagesAsync (string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt;&gt; ListPackagesWithHttpMessagesAsync(string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListPackagesWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage},System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListPackagesWithHttpMessagesAsync : string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt;&gt;" Usage="iCatalogOperations.ListPackagesWithHttpMessagesAsync (accountName, databaseName, schemaName, odataQuery, select, count, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-380">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-380">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-381">パッケージを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-381">The name of the database containing the packages.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="5d4a6-382">パッケージを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-382">The name of the schema containing the packages.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="5d4a6-383">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-383">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="5d4a6-384">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-384">OData Select statement.</span></span> <span data-ttu-id="5d4a6-385">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-385">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span>
            <span data-ttu-id="5d4a6-386">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-386">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="5d4a6-387">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-387">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="5d4a6-388">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-388">Optional.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-389">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-389">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-390">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-390">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-391">Data Lake Analytics カタログからのパッケージの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-391">Retrieves the list of packages from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-392">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-392">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-393">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-393">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-394">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-394">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListProceduresNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt;&gt; ListProceduresNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt;&gt; ListProceduresNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListProceduresNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListProceduresNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt;&gt;" Usage="iCatalogOperations.ListProceduresNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="5d4a6-395">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-395">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-396">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-396">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-397">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-397">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-398">Data Lake Analytics カタログからプロシージャの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-398">Retrieves the list of procedures from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-399">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-399">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-400">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-400">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-401">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-401">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListProceduresWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt;&gt; ListProceduresWithHttpMessagesAsync (string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt;&gt; ListProceduresWithHttpMessagesAsync(string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListProceduresWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure},System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListProceduresWithHttpMessagesAsync : string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt;&gt;" Usage="iCatalogOperations.ListProceduresWithHttpMessagesAsync (accountName, databaseName, schemaName, odataQuery, select, count, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-402">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-402">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-403">手順を含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-403">The name of the database containing the procedures.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="5d4a6-404">手順を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-404">The name of the schema containing the procedures.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="5d4a6-405">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-405">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="5d4a6-406">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-406">OData Select statement.</span></span> <span data-ttu-id="5d4a6-407">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-407">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span>
            <span data-ttu-id="5d4a6-408">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-408">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="5d4a6-409">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-409">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="5d4a6-410">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-410">Optional.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-411">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-411">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-412">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-412">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-413">Data Lake Analytics カタログからプロシージャの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-413">Retrieves the list of procedures from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-414">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-414">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-415">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-415">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-416">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-416">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListSchemasNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt;&gt; ListSchemasNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt;&gt; ListSchemasNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListSchemasNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSchemasNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt;&gt;" Usage="iCatalogOperations.ListSchemasNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="5d4a6-417">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-417">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-418">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-418">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-419">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-419">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-420">Data Lake Analytics カタログからスキーマの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-420">Retrieves the list of schemas from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-421">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-421">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-422">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-422">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-423">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-423">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListSchemasWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt;&gt; ListSchemasWithHttpMessagesAsync (string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt;&gt; ListSchemasWithHttpMessagesAsync(string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListSchemasWithHttpMessagesAsync(System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema},System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSchemasWithHttpMessagesAsync : string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt;&gt;" Usage="iCatalogOperations.ListSchemasWithHttpMessagesAsync (accountName, databaseName, odataQuery, select, count, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-424">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-424">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-425">スキーマを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-425">The name of the database containing the schema.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="5d4a6-426">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-426">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="5d4a6-427">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-427">OData Select statement.</span></span> <span data-ttu-id="5d4a6-428">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-428">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span>
            <span data-ttu-id="5d4a6-429">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-429">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="5d4a6-430">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-430">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="5d4a6-431">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-431">Optional.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-432">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-432">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-433">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-433">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-434">Data Lake Analytics カタログからスキーマの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-434">Retrieves the list of schemas from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-435">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-435">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-436">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-436">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-437">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-437">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListTablePartitionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt;&gt; ListTablePartitionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt;&gt; ListTablePartitionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListTablePartitionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTablePartitionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt;&gt;" Usage="iCatalogOperations.ListTablePartitionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="5d4a6-438">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-438">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-439">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-439">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-440">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-440">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-441">Data Lake Analytics カタログからテーブルのパーティションの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-441">Retrieves the list of table partitions from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-442">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-442">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-443">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-443">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-444">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-444">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListTablePartitionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt;&gt; ListTablePartitionsWithHttpMessagesAsync (string accountName, string databaseName, string schemaName, string tableName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt;&gt; ListTablePartitionsWithHttpMessagesAsync(string accountName, string databaseName, string schemaName, string tableName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListTablePartitionsWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition},System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTablePartitionsWithHttpMessagesAsync : string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt;&gt;" Usage="iCatalogOperations.ListTablePartitionsWithHttpMessagesAsync (accountName, databaseName, schemaName, tableName, odataQuery, select, count, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-445">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-445">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-446">パーティションを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-446">The name of the database containing the partitions.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="5d4a6-447">パーティションを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-447">The name of the schema containing the partitions.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="5d4a6-448">パーティションを含むテーブルの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-448">The name of the table containing the partitions.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="5d4a6-449">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-449">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="5d4a6-450">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-450">OData Select statement.</span></span> <span data-ttu-id="5d4a6-451">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-451">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span>
            <span data-ttu-id="5d4a6-452">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-452">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="5d4a6-453">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-453">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="5d4a6-454">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-454">Optional.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-455">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-455">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-456">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-456">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-457">Data Lake Analytics カタログからテーブルのパーティションの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-457">Retrieves the list of table partitions from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-458">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-458">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-459">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-459">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-460">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-460">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListTablesByDatabaseNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;&gt; ListTablesByDatabaseNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;&gt; ListTablesByDatabaseNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListTablesByDatabaseNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesByDatabaseNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;&gt;" Usage="iCatalogOperations.ListTablesByDatabaseNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="5d4a6-461">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-461">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-462">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-462">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-463">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-463">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-464">Data Lake Analytics カタログから、データベース内のすべてのテーブルの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-464">Retrieves the list of all tables in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-465">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-465">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-466">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-466">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-467">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-467">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListTablesByDatabaseWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;&gt; ListTablesByDatabaseWithHttpMessagesAsync (string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, Nullable&lt;bool&gt; basic = false, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;&gt; ListTablesByDatabaseWithHttpMessagesAsync(string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Nullable`1&lt;bool&gt; basic, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListTablesByDatabaseWithHttpMessagesAsync(System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable},System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesByDatabaseWithHttpMessagesAsync : string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;&gt;" Usage="iCatalogOperations.ListTablesByDatabaseWithHttpMessagesAsync (accountName, databaseName, odataQuery, select, count, basic, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="basic" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-468">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-468">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-469">テーブルを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-469">The name of the database containing the tables.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="5d4a6-470">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-470">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="5d4a6-471">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-471">OData Select statement.</span></span> <span data-ttu-id="5d4a6-472">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-472">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span>
            <span data-ttu-id="5d4a6-473">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-473">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="5d4a6-474">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-474">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="5d4a6-475">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-475">Optional.</span></span>
            </param>
        <param name="basic">
            <span data-ttu-id="5d4a6-476">基本的なスイッチでは、テーブルを一覧表示するときに返される情報のレベルを示します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-476">The basic switch indicates what level of information to return when listing tables.</span></span> <span data-ttu-id="5d4a6-477">基本的な場合は true、のみ database_name、schema_name、table_name と各、それ以外の場合のテーブルのすべてのメタデータが返されるテーブルのバージョンが返されます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-477">When basic is true, only database_name, schema_name, table_name and version are returned for each table, otherwise all table metadata is returned.</span></span> <span data-ttu-id="5d4a6-478">既定では false</span><span class="sxs-lookup"><span data-stu-id="5d4a6-478">By default, it is false</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-479">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-479">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-480">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-480">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-481">Data Lake Analytics カタログから、データベース内のすべてのテーブルの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-481">Retrieves the list of all tables in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-482">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-482">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-483">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-483">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-484">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-484">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListTablesNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;&gt; ListTablesNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;&gt; ListTablesNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListTablesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;&gt;" Usage="iCatalogOperations.ListTablesNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="5d4a6-485">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-485">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-486">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-486">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-487">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-487">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-488">Data Lake Analytics カタログからテーブルの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-488">Retrieves the list of tables from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-489">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-489">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-490">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-490">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-491">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-491">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsByDatabaseAndSchemaNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;&gt; ListTableStatisticsByDatabaseAndSchemaNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;&gt; ListTableStatisticsByDatabaseAndSchemaNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListTableStatisticsByDatabaseAndSchemaNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTableStatisticsByDatabaseAndSchemaNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;&gt;" Usage="iCatalogOperations.ListTableStatisticsByDatabaseAndSchemaNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="5d4a6-492">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-492">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-493">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-493">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-494">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-494">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-495">Data Lake Analytics カタログから、指定したスキーマ内のすべてのテーブル統計の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-495">Retrieves the list of all table statistics within the specified schema from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-496">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-496">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-497">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-497">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-498">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-498">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsByDatabaseAndSchemaWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;&gt; ListTableStatisticsByDatabaseAndSchemaWithHttpMessagesAsync (string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;&gt; ListTableStatisticsByDatabaseAndSchemaWithHttpMessagesAsync(string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListTableStatisticsByDatabaseAndSchemaWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics},System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTableStatisticsByDatabaseAndSchemaWithHttpMessagesAsync : string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;&gt;" Usage="iCatalogOperations.ListTableStatisticsByDatabaseAndSchemaWithHttpMessagesAsync (accountName, databaseName, schemaName, odataQuery, select, count, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-499">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-499">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-500">統計情報を含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-500">The name of the database containing the statistics.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="5d4a6-501">統計情報を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-501">The name of the schema containing the statistics.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="5d4a6-502">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-502">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="5d4a6-503">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-503">OData Select statement.</span></span> <span data-ttu-id="5d4a6-504">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-504">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span>
            <span data-ttu-id="5d4a6-505">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-505">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="5d4a6-506">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-506">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="5d4a6-507">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-507">Optional.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-508">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-508">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-509">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-509">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-510">Data Lake Analytics カタログから、指定したスキーマ内のすべてのテーブル統計の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-510">Retrieves the list of all table statistics within the specified schema from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-511">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-511">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-512">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-512">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-513">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-513">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsByDatabaseNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;&gt; ListTableStatisticsByDatabaseNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;&gt; ListTableStatisticsByDatabaseNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListTableStatisticsByDatabaseNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTableStatisticsByDatabaseNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;&gt;" Usage="iCatalogOperations.ListTableStatisticsByDatabaseNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="5d4a6-514">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-514">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-515">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-515">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-516">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-516">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-517">Data Lake Analytics カタログから、データベース内のすべての統計情報の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-517">Retrieves the list of all statistics in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-518">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-518">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-519">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-519">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-520">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-520">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsByDatabaseWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;&gt; ListTableStatisticsByDatabaseWithHttpMessagesAsync (string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;&gt; ListTableStatisticsByDatabaseWithHttpMessagesAsync(string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListTableStatisticsByDatabaseWithHttpMessagesAsync(System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics},System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTableStatisticsByDatabaseWithHttpMessagesAsync : string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;&gt;" Usage="iCatalogOperations.ListTableStatisticsByDatabaseWithHttpMessagesAsync (accountName, databaseName, odataQuery, select, count, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-521">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-521">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-522">テーブルの統計情報を含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-522">The name of the database containing the table statistics.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="5d4a6-523">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-523">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="5d4a6-524">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-524">OData Select statement.</span></span> <span data-ttu-id="5d4a6-525">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-525">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span>
            <span data-ttu-id="5d4a6-526">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-526">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="5d4a6-527">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-527">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="5d4a6-528">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-528">Optional.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-529">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-529">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-530">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-530">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-531">Data Lake Analytics カタログから、データベース内のすべての統計情報の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-531">Retrieves the list of all statistics in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-532">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-532">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-533">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-533">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-534">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-534">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;&gt; ListTableStatisticsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;&gt; ListTableStatisticsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListTableStatisticsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTableStatisticsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;&gt;" Usage="iCatalogOperations.ListTableStatisticsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="5d4a6-535">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-535">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-536">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-536">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-537">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-537">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-538">Data Lake Analytics カタログからテーブルの統計情報の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-538">Retrieves the list of table statistics from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-539">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-539">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-540">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-540">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-541">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-541">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;&gt; ListTableStatisticsWithHttpMessagesAsync (string accountName, string databaseName, string schemaName, string tableName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;&gt; ListTableStatisticsWithHttpMessagesAsync(string accountName, string databaseName, string schemaName, string tableName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListTableStatisticsWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics},System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTableStatisticsWithHttpMessagesAsync : string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;&gt;" Usage="iCatalogOperations.ListTableStatisticsWithHttpMessagesAsync (accountName, databaseName, schemaName, tableName, odataQuery, select, count, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-542">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-542">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-543">統計情報を含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-543">The name of the database containing the statistics.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="5d4a6-544">統計情報を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-544">The name of the schema containing the statistics.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="5d4a6-545">統計情報を含むテーブルの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-545">The name of the table containing the statistics.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="5d4a6-546">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-546">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="5d4a6-547">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-547">OData Select statement.</span></span> <span data-ttu-id="5d4a6-548">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-548">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span>
            <span data-ttu-id="5d4a6-549">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-549">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="5d4a6-550">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-550">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="5d4a6-551">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-551">Optional.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-552">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-552">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-553">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-553">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-554">Data Lake Analytics カタログからテーブルの統計情報の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-554">Retrieves the list of table statistics from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-555">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-555">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-556">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-556">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-557">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-557">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListTablesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;&gt; ListTablesWithHttpMessagesAsync (string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, Nullable&lt;bool&gt; basic = false, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;&gt; ListTablesWithHttpMessagesAsync(string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Nullable`1&lt;bool&gt; basic, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListTablesWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable},System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesWithHttpMessagesAsync : string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;&gt;" Usage="iCatalogOperations.ListTablesWithHttpMessagesAsync (accountName, databaseName, schemaName, odataQuery, select, count, basic, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="basic" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-558">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-558">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-559">テーブルを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-559">The name of the database containing the tables.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="5d4a6-560">テーブルを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-560">The name of the schema containing the tables.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="5d4a6-561">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-561">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="5d4a6-562">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-562">OData Select statement.</span></span> <span data-ttu-id="5d4a6-563">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-563">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span>
            <span data-ttu-id="5d4a6-564">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-564">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="5d4a6-565">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-565">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="5d4a6-566">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-566">Optional.</span></span>
            </param>
        <param name="basic">
            <span data-ttu-id="5d4a6-567">基本的なスイッチでは、テーブルを一覧表示するときに返される情報のレベルを示します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-567">The basic switch indicates what level of information to return when listing tables.</span></span> <span data-ttu-id="5d4a6-568">基本的な場合は true、のみ database_name、schema_name、table_name と各、それ以外の場合のテーブルのすべてのメタデータが返されるテーブルのバージョンが返されます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-568">When basic is true, only database_name, schema_name, table_name and version are returned for each table, otherwise all table metadata is returned.</span></span> <span data-ttu-id="5d4a6-569">既定では false です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-569">By default, it is false.</span></span>
            <span data-ttu-id="5d4a6-570">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-570">Optional.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-571">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-571">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-572">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-572">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-573">Data Lake Analytics カタログからテーブルの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-573">Retrieves the list of tables from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-574">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-574">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-575">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-575">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-576">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-576">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListTableTypesNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt;&gt; ListTableTypesNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt;&gt; ListTableTypesNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListTableTypesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTableTypesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt;&gt;" Usage="iCatalogOperations.ListTableTypesNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="5d4a6-577">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-577">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-578">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-578">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-579">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-579">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-580">Data Lake Analytics カタログからテーブルの種類の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-580">Retrieves the list of table types from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-581">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-581">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-582">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-582">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-583">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-583">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListTableTypesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt;&gt; ListTableTypesWithHttpMessagesAsync (string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt;&gt; ListTableTypesWithHttpMessagesAsync(string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListTableTypesWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType},System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTableTypesWithHttpMessagesAsync : string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt;&gt;" Usage="iCatalogOperations.ListTableTypesWithHttpMessagesAsync (accountName, databaseName, schemaName, odataQuery, select, count, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-584">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-584">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-585">テーブル型を含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-585">The name of the database containing the table types.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="5d4a6-586">テーブル型を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-586">The name of the schema containing the table types.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="5d4a6-587">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-587">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="5d4a6-588">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-588">OData Select statement.</span></span> <span data-ttu-id="5d4a6-589">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-589">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span>
            <span data-ttu-id="5d4a6-590">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-590">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="5d4a6-591">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-591">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="5d4a6-592">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-592">Optional.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-593">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-593">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-594">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-594">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-595">Data Lake Analytics カタログからテーブルの種類の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-595">Retrieves the list of table types from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-596">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-596">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-597">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-597">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-598">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-598">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListTableValuedFunctionsByDatabaseNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;&gt; ListTableValuedFunctionsByDatabaseNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;&gt; ListTableValuedFunctionsByDatabaseNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListTableValuedFunctionsByDatabaseNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTableValuedFunctionsByDatabaseNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;&gt;" Usage="iCatalogOperations.ListTableValuedFunctionsByDatabaseNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="5d4a6-599">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-599">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-600">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-600">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-601">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-601">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-602">Data Lake Analytics カタログから、データベース内のすべてのテーブル値関数の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-602">Retrieves the list of all table valued functions in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-603">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-603">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-604">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-604">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-605">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-605">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListTableValuedFunctionsByDatabaseWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;&gt; ListTableValuedFunctionsByDatabaseWithHttpMessagesAsync (string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;&gt; ListTableValuedFunctionsByDatabaseWithHttpMessagesAsync(string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListTableValuedFunctionsByDatabaseWithHttpMessagesAsync(System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction},System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTableValuedFunctionsByDatabaseWithHttpMessagesAsync : string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;&gt;" Usage="iCatalogOperations.ListTableValuedFunctionsByDatabaseWithHttpMessagesAsync (accountName, databaseName, odataQuery, select, count, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-606">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-606">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-607">テーブル値関数を含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-607">The name of the database containing the table valued functions.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="5d4a6-608">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-608">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="5d4a6-609">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-609">OData Select statement.</span></span> <span data-ttu-id="5d4a6-610">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-610">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span>
            <span data-ttu-id="5d4a6-611">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-611">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="5d4a6-612">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-612">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="5d4a6-613">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-613">Optional.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-614">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-614">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-615">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-615">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-616">Data Lake Analytics カタログから、データベース内のすべてのテーブル値関数の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-616">Retrieves the list of all table valued functions in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-617">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-617">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-618">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-618">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-619">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-619">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListTableValuedFunctionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;&gt; ListTableValuedFunctionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;&gt; ListTableValuedFunctionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListTableValuedFunctionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTableValuedFunctionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;&gt;" Usage="iCatalogOperations.ListTableValuedFunctionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="5d4a6-620">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-620">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-621">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-621">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-622">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-622">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-623">Data Lake Analytics カタログからテーブル値関数の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-623">Retrieves the list of table valued functions from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-624">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-624">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-625">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-625">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-626">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-626">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListTableValuedFunctionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;&gt; ListTableValuedFunctionsWithHttpMessagesAsync (string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;&gt; ListTableValuedFunctionsWithHttpMessagesAsync(string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListTableValuedFunctionsWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction},System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTableValuedFunctionsWithHttpMessagesAsync : string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;&gt;" Usage="iCatalogOperations.ListTableValuedFunctionsWithHttpMessagesAsync (accountName, databaseName, schemaName, odataQuery, select, count, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-627">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-627">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-628">テーブル値関数を含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-628">The name of the database containing the table valued functions.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="5d4a6-629">テーブル値関数を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-629">The name of the schema containing the table valued functions.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="5d4a6-630">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-630">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="5d4a6-631">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-631">OData Select statement.</span></span> <span data-ttu-id="5d4a6-632">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-632">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span>
            <span data-ttu-id="5d4a6-633">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-633">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="5d4a6-634">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-634">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="5d4a6-635">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-635">Optional.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-636">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-636">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-637">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-637">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-638">Data Lake Analytics カタログからテーブル値関数の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-638">Retrieves the list of table valued functions from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-639">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-639">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-640">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-640">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-641">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-641">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListTypesNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;&gt;&gt; ListTypesNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;&gt;&gt; ListTypesNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListTypesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTypesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;&gt;&gt;" Usage="iCatalogOperations.ListTypesNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="5d4a6-642">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-642">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-643">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-643">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-644">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-644">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-645">Data Lake Analytics カタログから、指定されたデータベースとスキーマ内の型の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-645">Retrieves the list of types within the specified database and schema from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-646">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-646">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-647">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-647">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-648">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-648">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListTypesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;&gt;&gt; ListTypesWithHttpMessagesAsync (string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;&gt;&gt; ListTypesWithHttpMessagesAsync(string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListTypesWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType},System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTypesWithHttpMessagesAsync : string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt; * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;&gt;&gt;" Usage="iCatalogOperations.ListTypesWithHttpMessagesAsync (accountName, databaseName, schemaName, odataQuery, select, count, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-649">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-649">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-650">型を含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-650">The name of the database containing the types.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="5d4a6-651">種類を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-651">The name of the schema containing the types.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="5d4a6-652">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-652">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="5d4a6-653">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-653">OData Select statement.</span></span> <span data-ttu-id="5d4a6-654">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-654">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span>
            <span data-ttu-id="5d4a6-655">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-655">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="5d4a6-656">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-656">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="5d4a6-657">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-657">Optional.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-658">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-658">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-659">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-659">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-660">Data Lake Analytics カタログから、指定されたデータベースとスキーマ内の型の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-660">Retrieves the list of types within the specified database and schema from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-661">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-661">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-662">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-662">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-663">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-663">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListViewsByDatabaseNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;&gt; ListViewsByDatabaseNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;&gt; ListViewsByDatabaseNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListViewsByDatabaseNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListViewsByDatabaseNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;&gt;" Usage="iCatalogOperations.ListViewsByDatabaseNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="5d4a6-664">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-664">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-665">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-665">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-666">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-666">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-667">Data Lake Analytics カタログから、データベース内のすべてのビューの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-667">Retrieves the list of all views in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-668">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-668">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-669">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-669">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-670">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-670">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListViewsByDatabaseWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;&gt; ListViewsByDatabaseWithHttpMessagesAsync (string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;&gt; ListViewsByDatabaseWithHttpMessagesAsync(string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListViewsByDatabaseWithHttpMessagesAsync(System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView},System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListViewsByDatabaseWithHttpMessagesAsync : string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;&gt;" Usage="iCatalogOperations.ListViewsByDatabaseWithHttpMessagesAsync (accountName, databaseName, odataQuery, select, count, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-671">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-671">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-672">ビューを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-672">The name of the database containing the views.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="5d4a6-673">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-673">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="5d4a6-674">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-674">OData Select statement.</span></span> <span data-ttu-id="5d4a6-675">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-675">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span>
            <span data-ttu-id="5d4a6-676">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-676">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="5d4a6-677">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-677">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="5d4a6-678">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-678">Optional.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-679">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-679">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-680">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-680">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-681">Data Lake Analytics カタログから、データベース内のすべてのビューの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-681">Retrieves the list of all views in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-682">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-682">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-683">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-683">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-684">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-684">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListViewsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;&gt; ListViewsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;&gt; ListViewsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListViewsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListViewsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;&gt;" Usage="iCatalogOperations.ListViewsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="5d4a6-685">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-685">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-686">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-686">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-687">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-687">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-688">Data Lake Analytics カタログからビューの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-688">Retrieves the list of views from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-689">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-689">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-690">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-690">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-691">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-691">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListViewsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;&gt; ListViewsWithHttpMessagesAsync (string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;&gt; ListViewsWithHttpMessagesAsync(string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.ListViewsWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView},System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListViewsWithHttpMessagesAsync : string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;&gt;" Usage="iCatalogOperations.ListViewsWithHttpMessagesAsync (accountName, databaseName, schemaName, odataQuery, select, count, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-692">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-692">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-693">ビューを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-693">The name of the database containing the views.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="5d4a6-694">ビューを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-694">The name of the schema containing the views.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="5d4a6-695">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-695">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="5d4a6-696">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-696">OData Select statement.</span></span> <span data-ttu-id="5d4a6-697">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-697">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span>
            <span data-ttu-id="5d4a6-698">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-698">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="5d4a6-699">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-699">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="5d4a6-700">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-700">Optional.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-701">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-701">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-702">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-702">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-703">Data Lake Analytics カタログからビューの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-703">Retrieves the list of views from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-704">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-704">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="5d4a6-705">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-705">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-706">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-706">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateCredentialWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; UpdateCredentialWithHttpMessagesAsync (string accountName, string databaseName, string credentialName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; UpdateCredentialWithHttpMessagesAsync(string accountName, string databaseName, string credentialName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.UpdateCredentialWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCredentialWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iCatalogOperations.UpdateCredentialWithHttpMessagesAsync (accountName, databaseName, credentialName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-707">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-707">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-708">資格情報を含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-708">The name of the database containing the credential.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="5d4a6-709">資格情報の名前です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-709">The name of the credential.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5d4a6-710">資格情報 (名前とパスワード) を変更するために必要なパラメーター</span><span class="sxs-lookup"><span data-stu-id="5d4a6-710">The parameters required to modify the credential (name and password)</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-711">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-711">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-712">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-712">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-713">指定されたデータベースで外部データ ソースで使用する指定された資格情報を変更します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-713">Modifies the specified credential for use with external data sources in the specified database</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-714">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-714">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-715">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-715">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; UpdateSecretWithHttpMessagesAsync (string accountName, string databaseName, string secretName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; UpdateSecretWithHttpMessagesAsync(string accountName, string databaseName, string secretName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations.UpdateSecretWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateSecretWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iCatalogOperations.UpdateSecretWithHttpMessagesAsync (accountName, databaseName, secretName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="accountName">
            <span data-ttu-id="5d4a6-716">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-716">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="5d4a6-717">シークレットを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-717">The name of the database containing the secret.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="5d4a6-718">シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-718">The name of the secret.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5d4a6-719">シークレット (名前とパスワード) を変更するために必要なパラメーター</span><span class="sxs-lookup"><span data-stu-id="5d4a6-719">The parameters required to modify the secret (name and password)</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="5d4a6-720">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-720">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d4a6-721">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-721">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d4a6-722">指定されたデータベースで外部データ ソースで使用するため、指定されたシークレットを変更します。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-722">Modifies the specified secret for use with external data sources in the specified database.</span></span> <span data-ttu-id="5d4a6-723">これは廃止されており、次のリリースで削除される予定です。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-723">This is deprecated and will be removed in the next release.</span></span> <span data-ttu-id="5d4a6-724">UpdateCredential を使用してください。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-724">Please use UpdateCredential instead.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="5d4a6-725">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-725">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5d4a6-726">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="5d4a6-726">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>