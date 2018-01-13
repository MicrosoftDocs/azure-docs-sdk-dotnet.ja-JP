<Type Name="CatalogOperationsExtensions" FullName="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class CatalogOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CatalogOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CatalogOperationsExtensions" />
  <TypeSignature Language="F#" Value="type CatalogOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="71c31-101">CatalogOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="71c31-101">Extension methods for CatalogOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateCredential">
      <MemberSignature Language="C#" Value="public static void CreateCredential (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void CreateCredential(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.CreateCredential(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub CreateCredential (operations As ICatalogOperations, accountName As String, databaseName As String, credentialName As String, parameters As DataLakeAnalyticsCatalogCredentialCreateParameters)" />
      <MemberSignature Language="F#" Value="static member CreateCredential : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.CreateCredential (operations, accountName, databaseName, credentialName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-102">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-103">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-103">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-104">資格情報を作成するためのデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-104">The name of the database in which to create the credential.</span></span> <span data-ttu-id="71c31-105">注: これは、外部データベース名はなく、新しい資格情報オブジェクトを含む既存の U SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-105">Note: This is NOT an external database name, but the name of an existing U-SQL database that should contain the new credential object.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="71c31-106">資格情報の名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-106">The name of the credential.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="71c31-107">資格情報 (名前とパスワード) を作成するために必要なパラメーター</span><span class="sxs-lookup"><span data-stu-id="71c31-107">The parameters required to create the credential (name and password)</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-108">指定されたデータベースで外部データ ソースを使用する指定された資格情報を作成します。</span><span class="sxs-lookup"><span data-stu-id="71c31-108">Creates the specified credential for use with external data sources in the specified database.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCredentialAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CreateCredentialAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CreateCredentialAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.CreateCredentialAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateCredentialAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.CreateCredentialAsync (operations, accountName, databaseName, credentialName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;CreateCredentialAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-109">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-110">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-110">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-111">資格情報を作成するためのデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-111">The name of the database in which to create the credential.</span></span> <span data-ttu-id="71c31-112">注: これは、外部データベース名はなく、新しい資格情報オブジェクトを含む既存の U SQL データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-112">Note: This is NOT an external database name, but the name of an existing U-SQL database that should contain the new credential object.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="71c31-113">資格情報の名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-113">The name of the credential.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="71c31-114">資格情報 (名前とパスワード) を作成するために必要なパラメーター</span><span class="sxs-lookup"><span data-stu-id="71c31-114">The parameters required to create the credential (name and password)</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-116">指定されたデータベースで外部データ ソースを使用する指定された資格情報を作成します。</span><span class="sxs-lookup"><span data-stu-id="71c31-116">Creates the specified credential for use with external data sources in the specified database.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSecret">
      <MemberSignature Language="C#" Value="public static void CreateSecret (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void CreateSecret(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.CreateSecret(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub CreateSecret (operations As ICatalogOperations, accountName As String, databaseName As String, secretName As String, parameters As DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters)" />
      <MemberSignature Language="F#" Value="static member CreateSecret : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.CreateSecret (operations, accountName, databaseName, secretName, parameters)" />
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
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-117">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-118">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-118">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-119">シークレットを作成するデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-119">The name of the database in which to create the secret.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="71c31-120">シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-120">The name of the secret.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="71c31-121">(名前とパスワード) のシークレットの作成に必要なパラメーター</span><span class="sxs-lookup"><span data-stu-id="71c31-121">The parameters required to create the secret (name and password)</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-122">指定されたデータベースで外部データ ソースを使用する指定されたシークレットを作成します。</span><span class="sxs-lookup"><span data-stu-id="71c31-122">Creates the specified secret for use with external data sources in the specified database.</span></span> <span data-ttu-id="71c31-123">これは廃止されており、次のリリースで削除される予定です。</span><span class="sxs-lookup"><span data-stu-id="71c31-123">This is deprecated and will be removed in the next release.</span></span> <span data-ttu-id="71c31-124">CreateCredential を使用してください。</span><span class="sxs-lookup"><span data-stu-id="71c31-124">Please use CreateCredential instead.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CreateSecretAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CreateSecretAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.CreateSecretAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateSecretAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.CreateSecretAsync (operations, accountName, databaseName, secretName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;CreateSecretAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-125">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-125">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-126">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-126">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-127">シークレットを作成するデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-127">The name of the database in which to create the secret.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="71c31-128">シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-128">The name of the secret.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="71c31-129">(名前とパスワード) のシークレットの作成に必要なパラメーター</span><span class="sxs-lookup"><span data-stu-id="71c31-129">The parameters required to create the secret (name and password)</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-131">指定されたデータベースで外部データ ソースを使用する指定されたシークレットを作成します。</span><span class="sxs-lookup"><span data-stu-id="71c31-131">Creates the specified secret for use with external data sources in the specified database.</span></span> <span data-ttu-id="71c31-132">これは廃止されており、次のリリースで削除される予定です。</span><span class="sxs-lookup"><span data-stu-id="71c31-132">This is deprecated and will be removed in the next release.</span></span> <span data-ttu-id="71c31-133">CreateCredential を使用してください。</span><span class="sxs-lookup"><span data-stu-id="71c31-133">Please use CreateCredential instead.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAllSecrets">
      <MemberSignature Language="C#" Value="public static void DeleteAllSecrets (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteAllSecrets(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.DeleteAllSecrets(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteAllSecrets (operations As ICatalogOperations, accountName As String, databaseName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteAllSecrets : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.DeleteAllSecrets (operations, accountName, databaseName)" />
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
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-134">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-134">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-135">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-135">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-136">シークレットを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-136">The name of the database containing the secret.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-137">指定されたデータベース内のすべてのシークレットを削除します。</span><span class="sxs-lookup"><span data-stu-id="71c31-137">Deletes all secrets in the specified database.</span></span> <span data-ttu-id="71c31-138">これは廃止されており、次のリリースで削除される予定です。</span><span class="sxs-lookup"><span data-stu-id="71c31-138">This is deprecated and will be removed in the next release.</span></span> <span data-ttu-id="71c31-139">今後、のみを削除してください DeleteCredential を使用して個別の資格情報</span><span class="sxs-lookup"><span data-stu-id="71c31-139">In the future, please only drop individual credentials using DeleteCredential</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAllSecretsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAllSecretsAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAllSecretsAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.DeleteAllSecretsAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAllSecretsAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.DeleteAllSecretsAsync (operations, accountName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;DeleteAllSecretsAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-140">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-140">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-141">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-141">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-142">シークレットを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-142">The name of the database containing the secret.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-143">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-144">指定されたデータベース内のすべてのシークレットを削除します。</span><span class="sxs-lookup"><span data-stu-id="71c31-144">Deletes all secrets in the specified database.</span></span> <span data-ttu-id="71c31-145">これは廃止されており、次のリリースで削除される予定です。</span><span class="sxs-lookup"><span data-stu-id="71c31-145">This is deprecated and will be removed in the next release.</span></span> <span data-ttu-id="71c31-146">今後、のみを削除してください DeleteCredential を使用して個別の資格情報</span><span class="sxs-lookup"><span data-stu-id="71c31-146">In the future, please only drop individual credentials using DeleteCredential</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCredential">
      <MemberSignature Language="C#" Value="public static void DeleteCredential (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters parameters = null, Nullable&lt;bool&gt; cascade = false);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteCredential(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters parameters, valuetype System.Nullable`1&lt;bool&gt; cascade) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.DeleteCredential(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteCredential (operations As ICatalogOperations, accountName As String, databaseName As String, credentialName As String, Optional parameters As DataLakeAnalyticsCatalogCredentialDeleteParameters = null, Optional cascade As Nullable(Of Boolean) = false)" />
      <MemberSignature Language="F#" Value="static member DeleteCredential : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters * Nullable&lt;bool&gt; -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.DeleteCredential (operations, accountName, databaseName, credentialName, parameters, cascade)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters" />
        <Parameter Name="cascade" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-147">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-147">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-148">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-148">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-149">資格情報を含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-149">The name of the database containing the credential.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="71c31-150">削除する資格情報の名前</span><span class="sxs-lookup"><span data-stu-id="71c31-150">The name of the credential to delete</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="71c31-151">現在のユーザーがアカウント所有者ではない場合、資格情報を削除するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="71c31-151">The parameters to delete a credential if the current user is not the account owner.</span></span>
            </param>
        <param name="cascade">
            <span data-ttu-id="71c31-152">かどうか、削除があります (資格情報だけでなく、資格情報に依存するすべてのリソースを削除) する連鎖削除を示すか。</span><span class="sxs-lookup"><span data-stu-id="71c31-152">Indicates if the delete should be a cascading delete (which deletes all resources dependent on the credential as well as the credential) or not.</span></span> <span data-ttu-id="71c31-153">場合は、資格情報に依存するすべてのリソースがある場合、false は失敗します。</span><span class="sxs-lookup"><span data-stu-id="71c31-153">If false will fail if there are any resources relying on the credential.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-154">指定されたデータベースで指定された資格情報を削除します。</span><span class="sxs-lookup"><span data-stu-id="71c31-154">Deletes the specified credential in the specified database</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCredentialAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteCredentialAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters parameters = null, Nullable&lt;bool&gt; cascade = false, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteCredentialAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters parameters, valuetype System.Nullable`1&lt;bool&gt; cascade, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.DeleteCredentialAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteCredentialAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.DeleteCredentialAsync (operations, accountName, databaseName, credentialName, parameters, cascade, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;DeleteCredentialAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialDeleteParameters" />
        <Parameter Name="cascade" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-155">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-155">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-156">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-156">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-157">資格情報を含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-157">The name of the database containing the credential.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="71c31-158">削除する資格情報の名前</span><span class="sxs-lookup"><span data-stu-id="71c31-158">The name of the credential to delete</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="71c31-159">現在のユーザーがアカウント所有者ではない場合、資格情報を削除するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="71c31-159">The parameters to delete a credential if the current user is not the account owner.</span></span>
            </param>
        <param name="cascade">
            <span data-ttu-id="71c31-160">かどうか、削除があります (資格情報だけでなく、資格情報に依存するすべてのリソースを削除) する連鎖削除を示すか。</span><span class="sxs-lookup"><span data-stu-id="71c31-160">Indicates if the delete should be a cascading delete (which deletes all resources dependent on the credential as well as the credential) or not.</span></span> <span data-ttu-id="71c31-161">場合は、資格情報に依存するすべてのリソースがある場合、false は失敗します。</span><span class="sxs-lookup"><span data-stu-id="71c31-161">If false will fail if there are any resources relying on the credential.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-163">指定されたデータベースで指定された資格情報を削除します。</span><span class="sxs-lookup"><span data-stu-id="71c31-163">Deletes the specified credential in the specified database</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteSecret">
      <MemberSignature Language="C#" Value="public static void DeleteSecret (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteSecret(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.DeleteSecret(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteSecret (operations As ICatalogOperations, accountName As String, databaseName As String, secretName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteSecret : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.DeleteSecret (operations, accountName, databaseName, secretName)" />
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
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-164">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-164">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-165">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-165">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-166">シークレットを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-166">The name of the database containing the secret.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="71c31-167">削除するシークレットの名前</span><span class="sxs-lookup"><span data-stu-id="71c31-167">The name of the secret to delete</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-168">指定されたデータベースで指定されたシークレットを削除します。</span><span class="sxs-lookup"><span data-stu-id="71c31-168">Deletes the specified secret in the specified database.</span></span> <span data-ttu-id="71c31-169">これは廃止されており、次のリリースで削除される予定です。</span><span class="sxs-lookup"><span data-stu-id="71c31-169">This is deprecated and will be removed in the next release.</span></span> <span data-ttu-id="71c31-170">DeleteCredential を使用してください。</span><span class="sxs-lookup"><span data-stu-id="71c31-170">Please use DeleteCredential instead.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteSecretAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteSecretAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.DeleteSecretAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteSecretAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.DeleteSecretAsync (operations, accountName, databaseName, secretName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;DeleteSecretAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-171">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-171">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-172">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-172">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-173">シークレットを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-173">The name of the database containing the secret.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="71c31-174">削除するシークレットの名前</span><span class="sxs-lookup"><span data-stu-id="71c31-174">The name of the secret to delete</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-175">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-175">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-176">指定されたデータベースで指定されたシークレットを削除します。</span><span class="sxs-lookup"><span data-stu-id="71c31-176">Deletes the specified secret in the specified database.</span></span> <span data-ttu-id="71c31-177">これは廃止されており、次のリリースで削除される予定です。</span><span class="sxs-lookup"><span data-stu-id="71c31-177">This is deprecated and will be removed in the next release.</span></span> <span data-ttu-id="71c31-178">DeleteCredential を使用してください。</span><span class="sxs-lookup"><span data-stu-id="71c31-178">Please use DeleteCredential instead.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAssembly">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly GetAssembly (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string assemblyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly GetAssembly(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string assemblyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetAssembly(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAssembly (operations As ICatalogOperations, accountName As String, databaseName As String, assemblyName As String) As USqlAssembly" />
      <MemberSignature Language="F#" Value="static member GetAssembly : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetAssembly (operations, accountName, databaseName, assemblyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="assemblyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-179">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-179">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-180">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-180">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-181">アセンブリを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-181">The name of the database containing the assembly.</span></span>
            </param>
        <param name="assemblyName">
            <span data-ttu-id="71c31-182">アセンブリの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-182">The name of the assembly.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-183">Data Lake Analytics カタログから指定したアセンブリを取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-183">Retrieves the specified assembly from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAssemblyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt; GetAssemblyAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string assemblyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt; GetAssemblyAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string assemblyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetAssemblyAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAssemblyAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetAssemblyAsync (operations, accountName, databaseName, assemblyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetAssemblyAsync&gt;d__61))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="assemblyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-184">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-184">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-185">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-185">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-186">アセンブリを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-186">The name of the database containing the assembly.</span></span>
            </param>
        <param name="assemblyName">
            <span data-ttu-id="71c31-187">アセンブリの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-187">The name of the assembly.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-188">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-189">Data Lake Analytics カタログから指定したアセンブリを取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-189">Retrieves the specified assembly from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCredential">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential GetCredential (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential GetCredential(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetCredential(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCredential (operations As ICatalogOperations, accountName As String, databaseName As String, credentialName As String) As USqlCredential" />
      <MemberSignature Language="F#" Value="static member GetCredential : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetCredential (operations, accountName, databaseName, credentialName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-190">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-190">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-191">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-191">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-192">スキーマを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-192">The name of the database containing the schema.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="71c31-193">資格情報の名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-193">The name of the credential.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-194">Data Lake Analytics カタログから指定された資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-194">Retrieves the specified credential from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCredentialAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; GetCredentialAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; GetCredentialAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetCredentialAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCredentialAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetCredentialAsync (operations, accountName, databaseName, credentialName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetCredentialAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-195">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-195">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-196">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-196">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-197">スキーマを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-197">The name of the database containing the schema.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="71c31-198">資格情報の名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-198">The name of the credential.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-199">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-200">Data Lake Analytics カタログから指定された資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-200">Retrieves the specified credential from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatabase">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase GetDatabase (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase GetDatabase(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetDatabase(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDatabase (operations As ICatalogOperations, accountName As String, databaseName As String) As USqlDatabase" />
      <MemberSignature Language="F#" Value="static member GetDatabase : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetDatabase (operations, accountName, databaseName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-201">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-201">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-202">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-202">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-203">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-203">The name of the database.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-204">Data Lake Analytics カタログから、指定されたデータベースを取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-204">Retrieves the specified database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDatabaseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; GetDatabaseAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; GetDatabaseAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetDatabaseAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDatabaseAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetDatabaseAsync (operations, accountName, databaseName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetDatabaseAsync&gt;d__77))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-205">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-205">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-206">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-206">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-207">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-207">The name of the database.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-208">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-208">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-209">Data Lake Analytics カタログから、指定されたデータベースを取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-209">Retrieves the specified database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetExternalDataSource">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource GetExternalDataSource (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string externalDataSourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource GetExternalDataSource(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string externalDataSourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetExternalDataSource(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetExternalDataSource (operations As ICatalogOperations, accountName As String, databaseName As String, externalDataSourceName As String) As USqlExternalDataSource" />
      <MemberSignature Language="F#" Value="static member GetExternalDataSource : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetExternalDataSource (operations, accountName, databaseName, externalDataSourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="externalDataSourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-210">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-210">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-211">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-211">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-212">外部データ ソースを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-212">The name of the database containing the external data source.</span></span>
            </param>
        <param name="externalDataSourceName">
            <span data-ttu-id="71c31-213">外部データ ソースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-213">The name of the external data source.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-214">Data Lake Analytics カタログから、指定された外部データ ソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-214">Retrieves the specified external data source from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetExternalDataSourceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; GetExternalDataSourceAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string externalDataSourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; GetExternalDataSourceAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string externalDataSourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetExternalDataSourceAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetExternalDataSourceAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetExternalDataSourceAsync (operations, accountName, databaseName, externalDataSourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetExternalDataSourceAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="externalDataSourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-215">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-215">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-216">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-216">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-217">外部データ ソースを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-217">The name of the database containing the external data source.</span></span>
            </param>
        <param name="externalDataSourceName">
            <span data-ttu-id="71c31-218">外部データ ソースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-218">The name of the external data source.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-219">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-219">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-220">Data Lake Analytics カタログから、指定された外部データ ソースを取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-220">Retrieves the specified external data source from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPackage">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage GetPackage (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string packageName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage GetPackage(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string packageName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetPackage(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetPackage (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, packageName As String) As USqlPackage" />
      <MemberSignature Language="F#" Value="static member GetPackage : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetPackage (operations, accountName, databaseName, schemaName, packageName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="packageName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-221">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-221">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-222">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-222">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-223">パッケージを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-223">The name of the database containing the package.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-224">パッケージを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-224">The name of the schema containing the package.</span></span>
            </param>
        <param name="packageName">
            <span data-ttu-id="71c31-225">パッケージの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-225">The name of the package.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-226">Data Lake Analytics カタログから指定したパッケージを取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-226">Retrieves the specified package from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPackageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; GetPackageAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string packageName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; GetPackageAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string packageName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetPackageAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetPackageAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetPackageAsync (operations, accountName, databaseName, schemaName, packageName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetPackageAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="packageName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-227">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-227">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-228">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-228">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-229">パッケージを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-229">The name of the database containing the package.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-230">パッケージを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-230">The name of the schema containing the package.</span></span>
            </param>
        <param name="packageName">
            <span data-ttu-id="71c31-231">パッケージの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-231">The name of the package.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-232">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-232">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-233">Data Lake Analytics カタログから指定したパッケージを取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-233">Retrieves the specified package from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProcedure">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure GetProcedure (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string procedureName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure GetProcedure(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string procedureName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetProcedure(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetProcedure (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, procedureName As String) As USqlProcedure" />
      <MemberSignature Language="F#" Value="static member GetProcedure : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetProcedure (operations, accountName, databaseName, schemaName, procedureName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="procedureName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-234">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-234">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-235">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-235">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-236">プロシージャを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-236">The name of the database containing the procedure.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-237">プロシージャを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-237">The name of the schema containing the procedure.</span></span>
            </param>
        <param name="procedureName">
            <span data-ttu-id="71c31-238">プロシージャの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-238">The name of the procedure.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-239">Data Lake Analytics カタログから、指定したプロシージャを取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-239">Retrieves the specified procedure from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetProcedureAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; GetProcedureAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string procedureName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; GetProcedureAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string procedureName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetProcedureAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetProcedureAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetProcedureAsync (operations, accountName, databaseName, schemaName, procedureName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetProcedureAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="procedureName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-240">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-240">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-241">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-241">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-242">プロシージャを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-242">The name of the database containing the procedure.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-243">プロシージャを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-243">The name of the schema containing the procedure.</span></span>
            </param>
        <param name="procedureName">
            <span data-ttu-id="71c31-244">プロシージャの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-244">The name of the procedure.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-245">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-245">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-246">Data Lake Analytics カタログから、指定したプロシージャを取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-246">Retrieves the specified procedure from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSchema">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema GetSchema (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema GetSchema(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetSchema(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetSchema (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String) As USqlSchema" />
      <MemberSignature Language="F#" Value="static member GetSchema : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetSchema (operations, accountName, databaseName, schemaName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-247">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-247">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-248">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-248">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-249">スキーマを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-249">The name of the database containing the schema.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-250">スキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-250">The name of the schema.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-251">Data Lake Analytics カタログから、指定したスキーマを取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-251">Retrieves the specified schema from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSchemaAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; GetSchemaAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; GetSchemaAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetSchemaAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSchemaAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetSchemaAsync (operations, accountName, databaseName, schemaName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetSchemaAsync&gt;d__65))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-252">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-252">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-253">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-253">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-254">スキーマを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-254">The name of the database containing the schema.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-255">スキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-255">The name of the schema.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-256">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-256">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-257">Data Lake Analytics カタログから、指定したスキーマを取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-257">Retrieves the specified schema from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecret">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret GetSecret (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret GetSecret(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetSecret(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetSecret (operations As ICatalogOperations, accountName As String, databaseName As String, secretName As String) As USqlSecret" />
      <MemberSignature Language="F#" Value="static member GetSecret : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetSecret (operations, accountName, databaseName, secretName)" />
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
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-258">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-258">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-259">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-259">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-260">シークレットを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-260">The name of the database containing the secret.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="71c31-261">取得するシークレットの名前</span><span class="sxs-lookup"><span data-stu-id="71c31-261">The name of the secret to get</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-262">指定されたデータベースで、指定されたシークレットを取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-262">Gets the specified secret in the specified database.</span></span> <span data-ttu-id="71c31-263">これは廃止されており、次のリリースで削除される予定です。</span><span class="sxs-lookup"><span data-stu-id="71c31-263">This is deprecated and will be removed in the next release.</span></span> <span data-ttu-id="71c31-264">GetCredential を使用してください。</span><span class="sxs-lookup"><span data-stu-id="71c31-264">Please use GetCredential instead.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret&gt; GetSecretAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret&gt; GetSecretAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetSecretAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSecretAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetSecretAsync (operations, accountName, databaseName, secretName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetSecretAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSecret&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-265">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-265">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-266">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-266">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-267">シークレットを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-267">The name of the database containing the secret.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="71c31-268">取得するシークレットの名前</span><span class="sxs-lookup"><span data-stu-id="71c31-268">The name of the secret to get</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-269">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-269">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-270">指定されたデータベースで、指定されたシークレットを取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-270">Gets the specified secret in the specified database.</span></span> <span data-ttu-id="71c31-271">これは廃止されており、次のリリースで削除される予定です。</span><span class="sxs-lookup"><span data-stu-id="71c31-271">This is deprecated and will be removed in the next release.</span></span> <span data-ttu-id="71c31-272">GetCredential を使用してください。</span><span class="sxs-lookup"><span data-stu-id="71c31-272">Please use GetCredential instead.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTable">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable GetTable (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable GetTable(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTable(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTable (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, tableName As String) As USqlTable" />
      <MemberSignature Language="F#" Value="static member GetTable : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTable (operations, accountName, databaseName, schemaName, tableName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-273">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-273">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-274">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-274">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-275">テーブルを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-275">The name of the database containing the table.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-276">テーブルを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-276">The name of the schema containing the table.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="71c31-277">テーブルの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-277">The name of the table.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-278">Data Lake Analytics カタログから、指定したテーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-278">Retrieves the specified table from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; GetTableAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; GetTableAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTableAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableAsync (operations, accountName, databaseName, schemaName, tableName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetTableAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-279">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-279">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-280">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-280">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-281">テーブルを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-281">The name of the database containing the table.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-282">テーブルを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-282">The name of the schema containing the table.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="71c31-283">テーブルの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-283">The name of the table.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-284">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-284">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-285">Data Lake Analytics カタログから、指定したテーブルを取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-285">Retrieves the specified table from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTablePartition">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition GetTablePartition (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, string partitionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition GetTablePartition(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, string partitionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTablePartition(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTablePartition (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, tableName As String, partitionName As String) As USqlTablePartition" />
      <MemberSignature Language="F#" Value="static member GetTablePartition : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTablePartition (operations, accountName, databaseName, schemaName, tableName, partitionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="partitionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-286">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-286">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-287">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-287">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-288">パーティションを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-288">The name of the database containing the partition.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-289">パーティションを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-289">The name of the schema containing the partition.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="71c31-290">パーティションを含むテーブルの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-290">The name of the table containing the partition.</span></span>
            </param>
        <param name="partitionName">
            <span data-ttu-id="71c31-291">テーブルのパーティションの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-291">The name of the table partition.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-292">Data Lake Analytics カタログから指定したテーブルのパーティションを取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-292">Retrieves the specified table partition from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTablePartitionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; GetTablePartitionAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, string partitionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; GetTablePartitionAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, string partitionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTablePartitionAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTablePartitionAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTablePartitionAsync (operations, accountName, databaseName, schemaName, tableName, partitionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetTablePartitionAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="partitionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-293">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-293">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-294">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-294">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-295">パーティションを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-295">The name of the database containing the partition.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-296">パーティションを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-296">The name of the schema containing the partition.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="71c31-297">パーティションを含むテーブルの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-297">The name of the table containing the partition.</span></span>
            </param>
        <param name="partitionName">
            <span data-ttu-id="71c31-298">テーブルのパーティションの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-298">The name of the table partition.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-299">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-299">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-300">Data Lake Analytics カタログから指定したテーブルのパーティションを取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-300">Retrieves the specified table partition from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTableStatistic">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics GetTableStatistic (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, string statisticsName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics GetTableStatistic(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, string statisticsName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableStatistic(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTableStatistic (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, tableName As String, statisticsName As String) As USqlTableStatistics" />
      <MemberSignature Language="F#" Value="static member GetTableStatistic : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableStatistic (operations, accountName, databaseName, schemaName, tableName, statisticsName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="statisticsName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-301">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-301">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-302">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-302">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-303">統計情報を含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-303">The name of the database containing the statistics.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-304">統計情報を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-304">The name of the schema containing the statistics.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="71c31-305">統計情報を含むテーブルの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-305">The name of the table containing the statistics.</span></span>
            </param>
        <param name="statisticsName">
            <span data-ttu-id="71c31-306">テーブルの統計情報の名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-306">The name of the table statistics.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-307">Data Lake Analytics カタログから指定したテーブルの統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-307">Retrieves the specified table statistics from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTableStatisticAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; GetTableStatisticAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, string statisticsName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; GetTableStatisticAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, string statisticsName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableStatisticAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTableStatisticAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableStatisticAsync (operations, accountName, databaseName, schemaName, tableName, statisticsName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetTableStatisticAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="statisticsName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-308">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-308">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-309">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-309">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-310">統計情報を含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-310">The name of the database containing the statistics.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-311">統計情報を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-311">The name of the schema containing the statistics.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="71c31-312">統計情報を含むテーブルの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-312">The name of the table containing the statistics.</span></span>
            </param>
        <param name="statisticsName">
            <span data-ttu-id="71c31-313">テーブルの統計情報の名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-313">The name of the table statistics.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-314">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-314">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-315">Data Lake Analytics カタログから指定したテーブルの統計情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-315">Retrieves the specified table statistics from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTableType">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType GetTableType (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType GetTableType(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableType(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTableType (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, tableTypeName As String) As USqlTableType" />
      <MemberSignature Language="F#" Value="static member GetTableType : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableType (operations, accountName, databaseName, schemaName, tableTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-316">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-316">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-317">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-317">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-318">テーブル型を含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-318">The name of the database containing the table type.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-319">テーブル型を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-319">The name of the schema containing the table type.</span></span>
            </param>
        <param name="tableTypeName">
            <span data-ttu-id="71c31-320">取得するテーブルの型の名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-320">The name of the table type to retrieve.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-321">Data Lake Analytics カタログから、指定されたテーブル型を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-321">Retrieves the specified table type from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTableTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; GetTableTypeAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableTypeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; GetTableTypeAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableTypeAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTableTypeAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableTypeAsync (operations, accountName, databaseName, schemaName, tableTypeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetTableTypeAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-322">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-322">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-323">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-323">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-324">テーブル型を含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-324">The name of the database containing the table type.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-325">テーブル型を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-325">The name of the schema containing the table type.</span></span>
            </param>
        <param name="tableTypeName">
            <span data-ttu-id="71c31-326">取得するテーブルの型の名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-326">The name of the table type to retrieve.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-327">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-327">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-328">Data Lake Analytics カタログから、指定されたテーブル型を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-328">Retrieves the specified table type from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTableValuedFunction">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction GetTableValuedFunction (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableValuedFunctionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction GetTableValuedFunction(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableValuedFunctionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableValuedFunction(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTableValuedFunction (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, tableValuedFunctionName As String) As USqlTableValuedFunction" />
      <MemberSignature Language="F#" Value="static member GetTableValuedFunction : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableValuedFunction (operations, accountName, databaseName, schemaName, tableValuedFunctionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableValuedFunctionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-329">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-329">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-330">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-330">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-331">テーブル値関数を含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-331">The name of the database containing the table valued function.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-332">テーブル値関数を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-332">The name of the schema containing the table valued function.</span></span>
            </param>
        <param name="tableValuedFunctionName">
            <span data-ttu-id="71c31-333">TableValuedFunction の名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-333">The name of the tableValuedFunction.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-334">Data Lake Analytics カタログから、指定したテーブル値関数を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-334">Retrieves the specified table valued function from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTableValuedFunctionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; GetTableValuedFunctionAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableValuedFunctionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; GetTableValuedFunctionAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableValuedFunctionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableValuedFunctionAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetTableValuedFunctionAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetTableValuedFunctionAsync (operations, accountName, databaseName, schemaName, tableValuedFunctionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetTableValuedFunctionAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableValuedFunctionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-335">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-335">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-336">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-336">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-337">テーブル値関数を含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-337">The name of the database containing the table valued function.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-338">テーブル値関数を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-338">The name of the schema containing the table valued function.</span></span>
            </param>
        <param name="tableValuedFunctionName">
            <span data-ttu-id="71c31-339">TableValuedFunction の名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-339">The name of the tableValuedFunction.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-340">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-340">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-341">Data Lake Analytics カタログから、指定したテーブル値関数を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-341">Retrieves the specified table valued function from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetView">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView GetView (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string viewName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView GetView(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string viewName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetView(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetView (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, viewName As String) As USqlView" />
      <MemberSignature Language="F#" Value="static member GetView : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetView (operations, accountName, databaseName, schemaName, viewName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="viewName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-342">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-342">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-343">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-343">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-344">ビューを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-344">The name of the database containing the view.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-345">ビューを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-345">The name of the schema containing the view.</span></span>
            </param>
        <param name="viewName">
            <span data-ttu-id="71c31-346">ビューの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-346">The name of the view.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-347">Data Lake Analytics カタログから、指定されたビューを取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-347">Retrieves the specified view from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetViewAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; GetViewAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string viewName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; GetViewAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string viewName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetViewAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetViewAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.GetViewAsync (operations, accountName, databaseName, schemaName, viewName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;GetViewAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="viewName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-348">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-348">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-349">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-349">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-350">ビューを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-350">The name of the database containing the view.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-351">ビューを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-351">The name of the schema containing the view.</span></span>
            </param>
        <param name="viewName">
            <span data-ttu-id="71c31-352">ビューの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-352">The name of the view.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-353">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-353">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-354">Data Lake Analytics カタログから、指定されたビューを取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-354">Retrieves the specified view from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAssemblies">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt; ListAssemblies (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt; ListAssemblies(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListAssemblies(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAssemblies (operations As ICatalogOperations, accountName As String, databaseName As String, Optional odataQuery As ODataQuery(Of USqlAssembly) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlAssemblyClr)" />
      <MemberSignature Language="F#" Value="static member ListAssemblies : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListAssemblies (operations, accountName, databaseName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-355">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-355">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-356">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-356">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-357">アセンブリを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-357">The name of the database containing the assembly.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-358">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-358">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-359">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-359">OData Select statement.</span></span> <span data-ttu-id="71c31-360">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-360">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-361">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-361">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-362">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-362">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-363">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-363">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-364">Data Lake Analytics カタログからのアセンブリの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-364">Retrieves the list of assemblies from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAssembliesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;&gt; ListAssembliesAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;&gt; ListAssembliesAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListAssembliesAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAssembliesAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListAssembliesAsync (operations, accountName, databaseName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListAssembliesAsync&gt;d__63))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssembly&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-365">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-365">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-366">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-366">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-367">アセンブリを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-367">The name of the database containing the assembly.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-368">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-368">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-369">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-369">OData Select statement.</span></span> <span data-ttu-id="71c31-370">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-370">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-371">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-371">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-372">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-372">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-373">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-373">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-374">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-374">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-375">Data Lake Analytics カタログからのアセンブリの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-375">Retrieves the list of assemblies from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAssembliesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt; ListAssembliesNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt; ListAssembliesNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListAssembliesNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAssembliesNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlAssemblyClr)" />
      <MemberSignature Language="F#" Value="static member ListAssembliesNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListAssembliesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-376">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-376">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-377">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-377">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-378">Data Lake Analytics カタログからのアセンブリの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-378">Retrieves the list of assemblies from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAssembliesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;&gt; ListAssembliesNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;&gt; ListAssembliesNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListAssembliesNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAssembliesNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListAssembliesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListAssembliesNextAsync&gt;d__105))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlAssemblyClr&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-379">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-379">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-380">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-380">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-381">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-381">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-382">Data Lake Analytics カタログからのアセンブリの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-382">Retrieves the list of assemblies from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCredentials">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; ListCredentials (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; ListCredentials(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListCredentials(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListCredentials (operations As ICatalogOperations, accountName As String, databaseName As String, Optional odataQuery As ODataQuery(Of USqlCredential) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlCredential)" />
      <MemberSignature Language="F#" Value="static member ListCredentials : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListCredentials (operations, accountName, databaseName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-383">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-383">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-384">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-384">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-385">スキーマを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-385">The name of the database containing the schema.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-386">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-386">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-387">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-387">OData Select statement.</span></span> <span data-ttu-id="71c31-388">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-388">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-389">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-389">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-390">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-390">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-391">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-391">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-392">Data Lake Analytics カタログの資格情報の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-392">Retrieves the list of credentials from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCredentialsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt; ListCredentialsAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt; ListCredentialsAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListCredentialsAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListCredentialsAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListCredentialsAsync (operations, accountName, databaseName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListCredentialsAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-393">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-393">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-394">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-394">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-395">スキーマを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-395">The name of the database containing the schema.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-396">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-396">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-397">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-397">OData Select statement.</span></span> <span data-ttu-id="71c31-398">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-398">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-399">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-399">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-400">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-400">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-401">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-401">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-402">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-402">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-403">Data Lake Analytics カタログの資格情報の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-403">Retrieves the list of credentials from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCredentialsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; ListCredentialsNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt; ListCredentialsNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListCredentialsNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListCredentialsNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlCredential)" />
      <MemberSignature Language="F#" Value="static member ListCredentialsNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListCredentialsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-404">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-404">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-405">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-405">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-406">Data Lake Analytics カタログの資格情報の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-406">Retrieves the list of credentials from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCredentialsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt; ListCredentialsNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt; ListCredentialsNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListCredentialsNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListCredentialsNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListCredentialsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListCredentialsNextAsync&gt;d__81))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlCredential&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-407">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-407">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-408">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-408">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-409">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-409">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-410">Data Lake Analytics カタログの資格情報の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-410">Retrieves the list of credentials from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDatabases">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; ListDatabases (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; ListDatabases(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListDatabases(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListDatabases (operations As ICatalogOperations, accountName As String, Optional odataQuery As ODataQuery(Of USqlDatabase) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlDatabase)" />
      <MemberSignature Language="F#" Value="static member ListDatabases : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListDatabases (operations, accountName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-411">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-411">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-412">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-412">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-413">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-413">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-414">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-414">OData Select statement.</span></span> <span data-ttu-id="71c31-415">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-415">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-416">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-416">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-417">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-417">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-418">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-418">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-419">Data Lake Analytics カタログからのデータベースの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-419">Retrieves the list of databases from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDatabasesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt; ListDatabasesAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt; ListDatabasesAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListDatabasesAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListDatabasesAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListDatabasesAsync (operations, accountName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListDatabasesAsync&gt;d__79))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-420">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-420">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-421">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-421">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-422">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-422">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-423">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-423">OData Select statement.</span></span> <span data-ttu-id="71c31-424">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-424">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-425">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-425">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-426">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-426">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-427">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-427">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-428">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-428">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-429">Data Lake Analytics カタログからのデータベースの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-429">Retrieves the list of databases from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDatabasesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; ListDatabasesNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt; ListDatabasesNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListDatabasesNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListDatabasesNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlDatabase)" />
      <MemberSignature Language="F#" Value="static member ListDatabasesNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListDatabasesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-430">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-430">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-431">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-431">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-432">Data Lake Analytics カタログからのデータベースの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-432">Retrieves the list of databases from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDatabasesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt; ListDatabasesNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt; ListDatabasesNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListDatabasesNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListDatabasesNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListDatabasesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListDatabasesNextAsync&gt;d__117))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDatabase&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-433">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-433">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-434">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-434">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-435">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-435">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-436">Data Lake Analytics カタログからのデータベースの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-436">Retrieves the list of databases from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListExternalDataSources">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; ListExternalDataSources (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; ListExternalDataSources(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListExternalDataSources(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListExternalDataSources (operations As ICatalogOperations, accountName As String, databaseName As String, Optional odataQuery As ODataQuery(Of USqlExternalDataSource) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlExternalDataSource)" />
      <MemberSignature Language="F#" Value="static member ListExternalDataSources : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListExternalDataSources (operations, accountName, databaseName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-437">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-437">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-438">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-438">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-439">外部データ ソースを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-439">The name of the database containing the external data sources.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-440">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-440">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-441">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-441">OData Select statement.</span></span> <span data-ttu-id="71c31-442">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-442">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-443">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-443">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-444">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-444">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-445">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-445">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-446">Data Lake Analytics カタログから外部データ ソースの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-446">Retrieves the list of external data sources from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListExternalDataSourcesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt; ListExternalDataSourcesAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt; ListExternalDataSourcesAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListExternalDataSourcesAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListExternalDataSourcesAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListExternalDataSourcesAsync (operations, accountName, databaseName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListExternalDataSourcesAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-447">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-447">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-448">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-448">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-449">外部データ ソースを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-449">The name of the database containing the external data sources.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-450">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-450">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-451">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-451">OData Select statement.</span></span> <span data-ttu-id="71c31-452">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-452">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-453">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-453">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-454">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-454">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-455">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-455">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-456">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-456">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-457">Data Lake Analytics カタログから外部データ ソースの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-457">Retrieves the list of external data sources from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListExternalDataSourcesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; ListExternalDataSourcesNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt; ListExternalDataSourcesNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListExternalDataSourcesNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListExternalDataSourcesNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlExternalDataSource)" />
      <MemberSignature Language="F#" Value="static member ListExternalDataSourcesNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListExternalDataSourcesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-458">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-458">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-459">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-459">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-460">Data Lake Analytics カタログから外部データ ソースの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-460">Retrieves the list of external data sources from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListExternalDataSourcesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt; ListExternalDataSourcesNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt; ListExternalDataSourcesNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListExternalDataSourcesNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListExternalDataSourcesNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListExternalDataSourcesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListExternalDataSourcesNextAsync&gt;d__83))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlExternalDataSource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-461">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-461">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-462">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-462">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-463">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-463">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-464">Data Lake Analytics カタログから外部データ ソースの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-464">Retrieves the list of external data sources from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPackages">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; ListPackages (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; ListPackages(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListPackages(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListPackages (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, Optional odataQuery As ODataQuery(Of USqlPackage) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlPackage)" />
      <MemberSignature Language="F#" Value="static member ListPackages : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListPackages (operations, accountName, databaseName, schemaName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-465">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-465">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-466">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-466">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-467">パッケージを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-467">The name of the database containing the packages.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-468">パッケージを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-468">The name of the schema containing the packages.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-469">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-469">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-470">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-470">OData Select statement.</span></span> <span data-ttu-id="71c31-471">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-471">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-472">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-472">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-473">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-473">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-474">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-474">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-475">Data Lake Analytics カタログからのパッケージの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-475">Retrieves the list of packages from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPackagesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt; ListPackagesAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt; ListPackagesAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListPackagesAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListPackagesAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListPackagesAsync (operations, accountName, databaseName, schemaName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListPackagesAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-476">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-476">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-477">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-477">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-478">パッケージを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-478">The name of the database containing the packages.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-479">パッケージを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-479">The name of the schema containing the packages.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-480">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-480">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-481">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-481">OData Select statement.</span></span> <span data-ttu-id="71c31-482">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-482">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-483">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-483">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-484">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-484">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-485">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-485">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-486">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-486">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-487">Data Lake Analytics カタログからのパッケージの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-487">Retrieves the list of packages from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPackagesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; ListPackagesNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt; ListPackagesNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListPackagesNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListPackagesNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlPackage)" />
      <MemberSignature Language="F#" Value="static member ListPackagesNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListPackagesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-488">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-488">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-489">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-489">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-490">Data Lake Analytics カタログからのパッケージの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-490">Retrieves the list of packages from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPackagesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt; ListPackagesNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt; ListPackagesNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListPackagesNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListPackagesNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListPackagesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListPackagesNextAsync&gt;d__93))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-491">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-491">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-492">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-492">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-493">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-493">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-494">Data Lake Analytics カタログからのパッケージの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-494">Retrieves the list of packages from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListProcedures">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; ListProcedures (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; ListProcedures(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListProcedures(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListProcedures (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, Optional odataQuery As ODataQuery(Of USqlProcedure) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlProcedure)" />
      <MemberSignature Language="F#" Value="static member ListProcedures : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListProcedures (operations, accountName, databaseName, schemaName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-495">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-495">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-496">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-496">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-497">手順を含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-497">The name of the database containing the procedures.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-498">手順を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-498">The name of the schema containing the procedures.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-499">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-499">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-500">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-500">OData Select statement.</span></span> <span data-ttu-id="71c31-501">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-501">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-502">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-502">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-503">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-503">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-504">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-504">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-505">Data Lake Analytics カタログからプロシージャの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-505">Retrieves the list of procedures from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListProceduresAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt; ListProceduresAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt; ListProceduresAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListProceduresAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListProceduresAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListProceduresAsync (operations, accountName, databaseName, schemaName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListProceduresAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-506">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-506">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-507">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-507">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-508">手順を含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-508">The name of the database containing the procedures.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-509">手順を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-509">The name of the schema containing the procedures.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-510">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-510">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-511">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-511">OData Select statement.</span></span> <span data-ttu-id="71c31-512">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-512">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-513">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-513">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-514">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-514">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-515">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-515">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-516">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-516">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-517">Data Lake Analytics カタログからプロシージャの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-517">Retrieves the list of procedures from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListProceduresNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; ListProceduresNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt; ListProceduresNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListProceduresNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListProceduresNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlProcedure)" />
      <MemberSignature Language="F#" Value="static member ListProceduresNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListProceduresNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-518">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-518">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-519">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-519">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-520">Data Lake Analytics カタログからプロシージャの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-520">Retrieves the list of procedures from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListProceduresNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt; ListProceduresNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt; ListProceduresNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListProceduresNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListProceduresNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListProceduresNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListProceduresNextAsync&gt;d__85))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlProcedure&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-521">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-521">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-522">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-522">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-523">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-523">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-524">Data Lake Analytics カタログからプロシージャの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-524">Retrieves the list of procedures from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSchemas">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; ListSchemas (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; ListSchemas(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListSchemas(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListSchemas (operations As ICatalogOperations, accountName As String, databaseName As String, Optional odataQuery As ODataQuery(Of USqlSchema) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlSchema)" />
      <MemberSignature Language="F#" Value="static member ListSchemas : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListSchemas (operations, accountName, databaseName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-525">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-525">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-526">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-526">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-527">スキーマを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-527">The name of the database containing the schema.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-528">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-528">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-529">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-529">OData Select statement.</span></span> <span data-ttu-id="71c31-530">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-530">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-531">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-531">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-532">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-532">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-533">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-533">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-534">Data Lake Analytics カタログからスキーマの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-534">Retrieves the list of schemas from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSchemasAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt; ListSchemasAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt; ListSchemasAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListSchemasAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSchemasAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListSchemasAsync (operations, accountName, databaseName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListSchemasAsync&gt;d__67))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-535">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-535">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-536">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-536">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-537">スキーマを含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-537">The name of the database containing the schema.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-538">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-538">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-539">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-539">OData Select statement.</span></span> <span data-ttu-id="71c31-540">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-540">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-541">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-541">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-542">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-542">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-543">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-543">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-544">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-544">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-545">Data Lake Analytics カタログからスキーマの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-545">Retrieves the list of schemas from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSchemasNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; ListSchemasNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt; ListSchemasNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListSchemasNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListSchemasNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlSchema)" />
      <MemberSignature Language="F#" Value="static member ListSchemasNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListSchemasNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-546">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-546">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-547">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-547">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-548">Data Lake Analytics カタログからスキーマの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-548">Retrieves the list of schemas from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSchemasNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt; ListSchemasNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt; ListSchemasNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListSchemasNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSchemasNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListSchemasNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListSchemasNextAsync&gt;d__107))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlSchema&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-549">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-549">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-550">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-550">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-551">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-551">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-552">Data Lake Analytics カタログからスキーマの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-552">Retrieves the list of schemas from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablePartitions">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; ListTablePartitions (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; ListTablePartitions(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablePartitions(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTablePartitions (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, tableName As String, Optional odataQuery As ODataQuery(Of USqlTablePartition) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlTablePartition)" />
      <MemberSignature Language="F#" Value="static member ListTablePartitions : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablePartitions (operations, accountName, databaseName, schemaName, tableName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-553">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-553">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-554">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-554">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-555">パーティションを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-555">The name of the database containing the partitions.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-556">パーティションを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-556">The name of the schema containing the partitions.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="71c31-557">パーティションを含むテーブルの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-557">The name of the table containing the partitions.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-558">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-558">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-559">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-559">OData Select statement.</span></span> <span data-ttu-id="71c31-560">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-560">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-561">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-561">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-562">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-562">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-563">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-563">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-564">Data Lake Analytics カタログからテーブルのパーティションの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-564">Retrieves the list of table partitions from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablePartitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt; ListTablePartitionsAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt; ListTablePartitionsAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablePartitionsAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTablePartitionsAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablePartitionsAsync (operations, accountName, databaseName, schemaName, tableName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTablePartitionsAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-565">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-565">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-566">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-566">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-567">パーティションを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-567">The name of the database containing the partitions.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-568">パーティションを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-568">The name of the schema containing the partitions.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="71c31-569">パーティションを含むテーブルの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-569">The name of the table containing the partitions.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-570">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-570">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-571">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-571">OData Select statement.</span></span> <span data-ttu-id="71c31-572">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-572">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-573">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-573">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-574">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-574">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-575">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-575">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-576">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-576">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-577">Data Lake Analytics カタログからテーブルのパーティションの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-577">Retrieves the list of table partitions from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablePartitionsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; ListTablePartitionsNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt; ListTablePartitionsNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablePartitionsNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTablePartitionsNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlTablePartition)" />
      <MemberSignature Language="F#" Value="static member ListTablePartitionsNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablePartitionsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-578">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-578">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-579">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-579">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-580">Data Lake Analytics カタログからテーブルのパーティションの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-580">Retrieves the list of table partitions from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablePartitionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt; ListTablePartitionsNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt; ListTablePartitionsNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablePartitionsNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTablePartitionsNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablePartitionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTablePartitionsNextAsync&gt;d__99))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-581">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-581">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-582">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-582">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-583">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-583">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-584">Data Lake Analytics カタログからテーブルのパーティションの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-584">Retrieves the list of table partitions from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTables">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; ListTables (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, Nullable&lt;bool&gt; basic = false);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; ListTables(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Nullable`1&lt;bool&gt; basic) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTables(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable},System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTables (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, Optional odataQuery As ODataQuery(Of USqlTable) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null, Optional basic As Nullable(Of Boolean) = false) As IPage(Of USqlTable)" />
      <MemberSignature Language="F#" Value="static member ListTables : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTables (operations, accountName, databaseName, schemaName, odataQuery, select, count, basic)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="basic" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-585">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-585">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-586">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-586">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-587">テーブルを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-587">The name of the database containing the tables.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-588">テーブルを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-588">The name of the schema containing the tables.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-589">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-589">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-590">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-590">OData Select statement.</span></span> <span data-ttu-id="71c31-591">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-591">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-592">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-592">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-593">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-593">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-594">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-594">Optional.</span></span>
            </param>
        <param name="basic">
            <span data-ttu-id="71c31-595">基本的なスイッチでは、テーブルを一覧表示するときに返される情報のレベルを示します。</span><span class="sxs-lookup"><span data-stu-id="71c31-595">The basic switch indicates what level of information to return when listing tables.</span></span> <span data-ttu-id="71c31-596">基本的な場合は true、のみ database_name、schema_name、table_name と各、それ以外の場合のテーブルのすべてのメタデータが返されるテーブルのバージョンが返されます。</span><span class="sxs-lookup"><span data-stu-id="71c31-596">When basic is true, only database_name, schema_name, table_name and version are returned for each table, otherwise all table metadata is returned.</span></span> <span data-ttu-id="71c31-597">既定では false です。</span><span class="sxs-lookup"><span data-stu-id="71c31-597">By default, it is false.</span></span> <span data-ttu-id="71c31-598">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-598">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-599">Data Lake Analytics カタログからテーブルの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-599">Retrieves the list of tables from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt; ListTablesAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, Nullable&lt;bool&gt; basic = false, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt; ListTablesAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Nullable`1&lt;bool&gt; basic, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable},System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTablesAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesAsync (operations, accountName, databaseName, schemaName, odataQuery, select, count, basic, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTablesAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="basic" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-600">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-600">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-601">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-601">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-602">テーブルを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-602">The name of the database containing the tables.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-603">テーブルを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-603">The name of the schema containing the tables.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-604">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-604">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-605">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-605">OData Select statement.</span></span> <span data-ttu-id="71c31-606">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-606">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-607">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-607">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-608">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-608">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-609">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-609">Optional.</span></span>
            </param>
        <param name="basic">
            <span data-ttu-id="71c31-610">基本的なスイッチでは、テーブルを一覧表示するときに返される情報のレベルを示します。</span><span class="sxs-lookup"><span data-stu-id="71c31-610">The basic switch indicates what level of information to return when listing tables.</span></span> <span data-ttu-id="71c31-611">基本的な場合は true、のみ database_name、schema_name、table_name と各、それ以外の場合のテーブルのすべてのメタデータが返されるテーブルのバージョンが返されます。</span><span class="sxs-lookup"><span data-stu-id="71c31-611">When basic is true, only database_name, schema_name, table_name and version are returned for each table, otherwise all table metadata is returned.</span></span> <span data-ttu-id="71c31-612">既定では false です。</span><span class="sxs-lookup"><span data-stu-id="71c31-612">By default, it is false.</span></span> <span data-ttu-id="71c31-613">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-613">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-614">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-614">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-615">Data Lake Analytics カタログからテーブルの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-615">Retrieves the list of tables from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesByDatabase">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; ListTablesByDatabase (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, Nullable&lt;bool&gt; basic = false);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; ListTablesByDatabase(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Nullable`1&lt;bool&gt; basic) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesByDatabase(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable},System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTablesByDatabase (operations As ICatalogOperations, accountName As String, databaseName As String, Optional odataQuery As ODataQuery(Of USqlTable) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null, Optional basic As Nullable(Of Boolean) = false) As IPage(Of USqlTable)" />
      <MemberSignature Language="F#" Value="static member ListTablesByDatabase : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesByDatabase (operations, accountName, databaseName, odataQuery, select, count, basic)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="basic" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-616">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-616">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-617">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-617">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-618">テーブルを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-618">The name of the database containing the tables.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-619">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-619">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-620">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-620">OData Select statement.</span></span> <span data-ttu-id="71c31-621">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-621">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-622">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-622">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-623">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-623">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-624">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-624">Optional.</span></span>
            </param>
        <param name="basic">
            <span data-ttu-id="71c31-625">基本的なスイッチでは、テーブルを一覧表示するときに返される情報のレベルを示します。</span><span class="sxs-lookup"><span data-stu-id="71c31-625">The basic switch indicates what level of information to return when listing tables.</span></span> <span data-ttu-id="71c31-626">基本的な場合は true、のみ database_name、schema_name、table_name と各、それ以外の場合のテーブルのすべてのメタデータが返されるテーブルのバージョンが返されます。</span><span class="sxs-lookup"><span data-stu-id="71c31-626">When basic is true, only database_name, schema_name, table_name and version are returned for each table, otherwise all table metadata is returned.</span></span> <span data-ttu-id="71c31-627">既定では false</span><span class="sxs-lookup"><span data-stu-id="71c31-627">By default, it is false</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-628">Data Lake Analytics カタログから、データベース内のすべてのテーブルの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-628">Retrieves the list of all tables in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesByDatabaseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt; ListTablesByDatabaseAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, Nullable&lt;bool&gt; basic = false, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt; ListTablesByDatabaseAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Nullable`1&lt;bool&gt; basic, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesByDatabaseAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable},System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTablesByDatabaseAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesByDatabaseAsync (operations, accountName, databaseName, odataQuery, select, count, basic, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTablesByDatabaseAsync&gt;d__71))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="basic" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-629">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-629">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-630">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-630">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-631">テーブルを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-631">The name of the database containing the tables.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-632">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-632">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-633">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-633">OData Select statement.</span></span> <span data-ttu-id="71c31-634">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-634">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-635">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-635">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-636">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-636">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-637">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-637">Optional.</span></span>
            </param>
        <param name="basic">
            <span data-ttu-id="71c31-638">基本的なスイッチでは、テーブルを一覧表示するときに返される情報のレベルを示します。</span><span class="sxs-lookup"><span data-stu-id="71c31-638">The basic switch indicates what level of information to return when listing tables.</span></span> <span data-ttu-id="71c31-639">基本的な場合は true、のみ database_name、schema_name、table_name と各、それ以外の場合のテーブルのすべてのメタデータが返されるテーブルのバージョンが返されます。</span><span class="sxs-lookup"><span data-stu-id="71c31-639">When basic is true, only database_name, schema_name, table_name and version are returned for each table, otherwise all table metadata is returned.</span></span> <span data-ttu-id="71c31-640">既定では false</span><span class="sxs-lookup"><span data-stu-id="71c31-640">By default, it is false</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-641">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-641">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-642">Data Lake Analytics カタログから、データベース内のすべてのテーブルの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-642">Retrieves the list of all tables in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesByDatabaseNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; ListTablesByDatabaseNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; ListTablesByDatabaseNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesByDatabaseNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTablesByDatabaseNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlTable)" />
      <MemberSignature Language="F#" Value="static member ListTablesByDatabaseNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesByDatabaseNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-643">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-643">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-644">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-644">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-645">Data Lake Analytics カタログから、データベース内のすべてのテーブルの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-645">Retrieves the list of all tables in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesByDatabaseNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt; ListTablesByDatabaseNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt; ListTablesByDatabaseNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesByDatabaseNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTablesByDatabaseNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesByDatabaseNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTablesByDatabaseNextAsync&gt;d__111))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-646">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-646">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-647">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-647">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-648">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-648">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-649">Data Lake Analytics カタログから、データベース内のすべてのテーブルの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-649">Retrieves the list of all tables in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; ListTablesNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt; ListTablesNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTablesNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlTable)" />
      <MemberSignature Language="F#" Value="static member ListTablesNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-650">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-650">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-651">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-651">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-652">Data Lake Analytics カタログからテーブルの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-652">Retrieves the list of tables from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt; ListTablesNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt; ListTablesNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTablesNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTablesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTablesNextAsync&gt;d__87))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-653">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-653">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-654">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-654">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-655">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-655">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-656">Data Lake Analytics カタログからテーブルの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-656">Retrieves the list of tables from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatistics">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; ListTableStatistics (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; ListTableStatistics(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatistics(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTableStatistics (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, tableName As String, Optional odataQuery As ODataQuery(Of USqlTableStatistics) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlTableStatistics)" />
      <MemberSignature Language="F#" Value="static member ListTableStatistics : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatistics (operations, accountName, databaseName, schemaName, tableName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-657">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-657">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-658">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-658">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-659">統計情報を含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-659">The name of the database containing the statistics.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-660">統計情報を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-660">The name of the schema containing the statistics.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="71c31-661">統計情報を含むテーブルの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-661">The name of the table containing the statistics.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-662">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-662">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-663">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-663">OData Select statement.</span></span> <span data-ttu-id="71c31-664">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-664">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-665">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-665">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-666">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-666">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-667">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-667">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-668">Data Lake Analytics カタログからテーブルの統計情報の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-668">Retrieves the list of table statistics from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt; ListTableStatisticsAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt; ListTableStatisticsAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, string tableName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTableStatisticsAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsAsync (operations, accountName, databaseName, schemaName, tableName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTableStatisticsAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-669">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-669">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-670">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-670">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-671">統計情報を含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-671">The name of the database containing the statistics.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-672">統計情報を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-672">The name of the schema containing the statistics.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="71c31-673">統計情報を含むテーブルの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-673">The name of the table containing the statistics.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-674">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-674">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-675">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-675">OData Select statement.</span></span> <span data-ttu-id="71c31-676">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-676">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-677">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-677">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-678">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-678">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-679">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-679">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-680">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-680">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-681">Data Lake Analytics カタログからテーブルの統計情報の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-681">Retrieves the list of table statistics from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsByDatabase">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; ListTableStatisticsByDatabase (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; ListTableStatisticsByDatabase(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabase(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTableStatisticsByDatabase (operations As ICatalogOperations, accountName As String, databaseName As String, Optional odataQuery As ODataQuery(Of USqlTableStatistics) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlTableStatistics)" />
      <MemberSignature Language="F#" Value="static member ListTableStatisticsByDatabase : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabase (operations, accountName, databaseName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-682">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-682">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-683">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-683">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-684">テーブルの統計情報を含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-684">The name of the database containing the table statistics.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-685">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-685">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-686">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-686">OData Select statement.</span></span> <span data-ttu-id="71c31-687">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-687">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-688">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-688">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-689">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-689">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-690">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-690">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-691">Data Lake Analytics カタログから、データベース内のすべての統計情報の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-691">Retrieves the list of all statistics in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsByDatabaseAndSchema">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; ListTableStatisticsByDatabaseAndSchema (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; ListTableStatisticsByDatabaseAndSchema(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseAndSchema(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTableStatisticsByDatabaseAndSchema (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, Optional odataQuery As ODataQuery(Of USqlTableStatistics) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlTableStatistics)" />
      <MemberSignature Language="F#" Value="static member ListTableStatisticsByDatabaseAndSchema : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseAndSchema (operations, accountName, databaseName, schemaName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-692">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-692">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-693">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-693">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-694">統計情報を含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-694">The name of the database containing the statistics.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-695">統計情報を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-695">The name of the schema containing the statistics.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-696">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-696">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-697">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-697">OData Select statement.</span></span> <span data-ttu-id="71c31-698">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-698">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-699">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-699">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-700">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-700">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-701">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-701">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-702">Data Lake Analytics カタログから、指定したスキーマ内のすべてのテーブル統計の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-702">Retrieves the list of all table statistics within the specified schema from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsByDatabaseAndSchemaAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt; ListTableStatisticsByDatabaseAndSchemaAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt; ListTableStatisticsByDatabaseAndSchemaAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseAndSchemaAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTableStatisticsByDatabaseAndSchemaAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseAndSchemaAsync (operations, accountName, databaseName, schemaName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTableStatisticsByDatabaseAndSchemaAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-703">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-703">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-704">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-704">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-705">統計情報を含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-705">The name of the database containing the statistics.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-706">統計情報を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-706">The name of the schema containing the statistics.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-707">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-707">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-708">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-708">OData Select statement.</span></span> <span data-ttu-id="71c31-709">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-709">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-710">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-710">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-711">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-711">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-712">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-712">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-713">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-713">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-714">Data Lake Analytics カタログから、指定したスキーマ内のすべてのテーブル統計の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-714">Retrieves the list of all table statistics within the specified schema from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsByDatabaseAndSchemaNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; ListTableStatisticsByDatabaseAndSchemaNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; ListTableStatisticsByDatabaseAndSchemaNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseAndSchemaNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTableStatisticsByDatabaseAndSchemaNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlTableStatistics)" />
      <MemberSignature Language="F#" Value="static member ListTableStatisticsByDatabaseAndSchemaNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseAndSchemaNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-715">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-715">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-716">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-716">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-717">Data Lake Analytics カタログから、指定したスキーマ内のすべてのテーブル統計の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-717">Retrieves the list of all table statistics within the specified schema from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsByDatabaseAndSchemaNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt; ListTableStatisticsByDatabaseAndSchemaNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt; ListTableStatisticsByDatabaseAndSchemaNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseAndSchemaNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTableStatisticsByDatabaseAndSchemaNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseAndSchemaNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTableStatisticsByDatabaseAndSchemaNextAsync&gt;d__89))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-718">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-718">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-719">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-719">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-720">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-720">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-721">Data Lake Analytics カタログから、指定したスキーマ内のすべてのテーブル統計の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-721">Retrieves the list of all table statistics within the specified schema from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsByDatabaseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt; ListTableStatisticsByDatabaseAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt; ListTableStatisticsByDatabaseAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTableStatisticsByDatabaseAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseAsync (operations, accountName, databaseName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTableStatisticsByDatabaseAsync&gt;d__69))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-722">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-722">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-723">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-723">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-724">テーブルの統計情報を含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-724">The name of the database containing the table statistics.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-725">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-725">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-726">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-726">OData Select statement.</span></span> <span data-ttu-id="71c31-727">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-727">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-728">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-728">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-729">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-729">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-730">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-730">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-731">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-731">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-732">Data Lake Analytics カタログから、データベース内のすべての統計情報の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-732">Retrieves the list of all statistics in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsByDatabaseNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; ListTableStatisticsByDatabaseNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; ListTableStatisticsByDatabaseNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTableStatisticsByDatabaseNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlTableStatistics)" />
      <MemberSignature Language="F#" Value="static member ListTableStatisticsByDatabaseNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-733">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-733">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-734">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-734">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-735">Data Lake Analytics カタログから、データベース内のすべての統計情報の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-735">Retrieves the list of all statistics in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsByDatabaseNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt; ListTableStatisticsByDatabaseNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt; ListTableStatisticsByDatabaseNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTableStatisticsByDatabaseNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsByDatabaseNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTableStatisticsByDatabaseNextAsync&gt;d__109))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-736">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-736">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-737">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-737">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-738">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-738">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-739">Data Lake Analytics カタログから、データベース内のすべての統計情報の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-739">Retrieves the list of all statistics in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; ListTableStatisticsNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt; ListTableStatisticsNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTableStatisticsNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlTableStatistics)" />
      <MemberSignature Language="F#" Value="static member ListTableStatisticsNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-740">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-740">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-741">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-741">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-742">Data Lake Analytics カタログからテーブルの統計情報の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-742">Retrieves the list of table statistics from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableStatisticsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt; ListTableStatisticsNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt; ListTableStatisticsNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTableStatisticsNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableStatisticsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTableStatisticsNextAsync&gt;d__97))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-743">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-743">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-744">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-744">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-745">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-745">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-746">Data Lake Analytics カタログからテーブルの統計情報の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-746">Retrieves the list of table statistics from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableTypes">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; ListTableTypes (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; ListTableTypes(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableTypes(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTableTypes (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, Optional odataQuery As ODataQuery(Of USqlTableType) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlTableType)" />
      <MemberSignature Language="F#" Value="static member ListTableTypes : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableTypes (operations, accountName, databaseName, schemaName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-747">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-747">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-748">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-748">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-749">テーブル型を含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-749">The name of the database containing the table types.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-750">テーブル型を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-750">The name of the schema containing the table types.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-751">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-751">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-752">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-752">OData Select statement.</span></span> <span data-ttu-id="71c31-753">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-753">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-754">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-754">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-755">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-755">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-756">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-756">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-757">Data Lake Analytics カタログからテーブルの種類の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-757">Retrieves the list of table types from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableTypesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt; ListTableTypesAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt; ListTableTypesAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableTypesAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTableTypesAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableTypesAsync (operations, accountName, databaseName, schemaName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTableTypesAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-758">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-758">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-759">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-759">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-760">テーブル型を含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-760">The name of the database containing the table types.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-761">テーブル型を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-761">The name of the schema containing the table types.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-762">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-762">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-763">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-763">OData Select statement.</span></span> <span data-ttu-id="71c31-764">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-764">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-765">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-765">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-766">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-766">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-767">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-767">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-768">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-768">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-769">Data Lake Analytics カタログからテーブルの種類の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-769">Retrieves the list of table types from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableTypesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; ListTableTypesNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt; ListTableTypesNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableTypesNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTableTypesNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlTableType)" />
      <MemberSignature Language="F#" Value="static member ListTableTypesNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableTypesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-770">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-770">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-771">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-771">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-772">Data Lake Analytics カタログからテーブルの種類の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-772">Retrieves the list of table types from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableTypesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt; ListTableTypesNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt; ListTableTypesNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableTypesNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTableTypesNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableTypesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTableTypesNextAsync&gt;d__91))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableType&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-773">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-773">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-774">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-774">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-775">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-775">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-776">Data Lake Analytics カタログからテーブルの種類の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-776">Retrieves the list of table types from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableValuedFunctions">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; ListTableValuedFunctions (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; ListTableValuedFunctions(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctions(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTableValuedFunctions (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, Optional odataQuery As ODataQuery(Of USqlTableValuedFunction) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlTableValuedFunction)" />
      <MemberSignature Language="F#" Value="static member ListTableValuedFunctions : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctions (operations, accountName, databaseName, schemaName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-777">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-777">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-778">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-778">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-779">テーブル値関数を含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-779">The name of the database containing the table valued functions.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-780">テーブル値関数を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-780">The name of the schema containing the table valued functions.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-781">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-781">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-782">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-782">OData Select statement.</span></span> <span data-ttu-id="71c31-783">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-783">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-784">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-784">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-785">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-785">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-786">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-786">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-787">Data Lake Analytics カタログからテーブル値関数の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-787">Retrieves the list of table valued functions from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableValuedFunctionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt; ListTableValuedFunctionsAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt; ListTableValuedFunctionsAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTableValuedFunctionsAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsAsync (operations, accountName, databaseName, schemaName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTableValuedFunctionsAsync&gt;d__59))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-788">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-788">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-789">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-789">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-790">テーブル値関数を含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-790">The name of the database containing the table valued functions.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-791">テーブル値関数を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-791">The name of the schema containing the table valued functions.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-792">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-792">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-793">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-793">OData Select statement.</span></span> <span data-ttu-id="71c31-794">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-794">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-795">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-795">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-796">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-796">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-797">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-797">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-798">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-798">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-799">Data Lake Analytics カタログからテーブル値関数の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-799">Retrieves the list of table valued functions from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableValuedFunctionsByDatabase">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; ListTableValuedFunctionsByDatabase (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; ListTableValuedFunctionsByDatabase(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsByDatabase(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTableValuedFunctionsByDatabase (operations As ICatalogOperations, accountName As String, databaseName As String, Optional odataQuery As ODataQuery(Of USqlTableValuedFunction) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlTableValuedFunction)" />
      <MemberSignature Language="F#" Value="static member ListTableValuedFunctionsByDatabase : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsByDatabase (operations, accountName, databaseName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-800">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-800">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-801">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-801">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-802">テーブル値関数を含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-802">The name of the database containing the table valued functions.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-803">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-803">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-804">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-804">OData Select statement.</span></span> <span data-ttu-id="71c31-805">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-805">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-806">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-806">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-807">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-807">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-808">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-808">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-809">Data Lake Analytics カタログから、データベース内のすべてのテーブル値関数の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-809">Retrieves the list of all table valued functions in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableValuedFunctionsByDatabaseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt; ListTableValuedFunctionsByDatabaseAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt; ListTableValuedFunctionsByDatabaseAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsByDatabaseAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTableValuedFunctionsByDatabaseAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsByDatabaseAsync (operations, accountName, databaseName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTableValuedFunctionsByDatabaseAsync&gt;d__73))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-810">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-810">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-811">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-811">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-812">テーブル値関数を含むデータベースの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-812">The name of the database containing the table valued functions.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-813">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-813">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-814">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-814">OData Select statement.</span></span> <span data-ttu-id="71c31-815">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-815">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-816">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-816">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-817">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-817">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-818">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-818">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-819">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-819">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-820">Data Lake Analytics カタログから、データベース内のすべてのテーブル値関数の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-820">Retrieves the list of all table valued functions in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableValuedFunctionsByDatabaseNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; ListTableValuedFunctionsByDatabaseNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; ListTableValuedFunctionsByDatabaseNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsByDatabaseNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTableValuedFunctionsByDatabaseNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlTableValuedFunction)" />
      <MemberSignature Language="F#" Value="static member ListTableValuedFunctionsByDatabaseNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsByDatabaseNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-821">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-821">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-822">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-822">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-823">Data Lake Analytics カタログから、データベース内のすべてのテーブル値関数の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-823">Retrieves the list of all table valued functions in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableValuedFunctionsByDatabaseNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt; ListTableValuedFunctionsByDatabaseNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt; ListTableValuedFunctionsByDatabaseNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsByDatabaseNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTableValuedFunctionsByDatabaseNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsByDatabaseNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTableValuedFunctionsByDatabaseNextAsync&gt;d__113))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-824">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-824">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-825">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-825">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-826">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-826">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-827">Data Lake Analytics カタログから、データベース内のすべてのテーブル値関数の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-827">Retrieves the list of all table valued functions in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableValuedFunctionsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; ListTableValuedFunctionsNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt; ListTableValuedFunctionsNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTableValuedFunctionsNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlTableValuedFunction)" />
      <MemberSignature Language="F#" Value="static member ListTableValuedFunctionsNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-828">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-828">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-829">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-829">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-830">Data Lake Analytics カタログからテーブル値関数の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-830">Retrieves the list of table valued functions from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTableValuedFunctionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt; ListTableValuedFunctionsNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt; ListTableValuedFunctionsNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTableValuedFunctionsNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTableValuedFunctionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTableValuedFunctionsNextAsync&gt;d__103))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-831">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-831">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-832">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-832">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-833">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-833">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-834">Data Lake Analytics カタログからテーブル値関数の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-834">Retrieves the list of table valued functions from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTypes">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt; ListTypes (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt; ListTypes(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTypes(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTypes (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, Optional odataQuery As ODataQuery(Of USqlType) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlType)" />
      <MemberSignature Language="F#" Value="static member ListTypes : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTypes (operations, accountName, databaseName, schemaName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-835">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-835">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-836">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-836">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-837">型を含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-837">The name of the database containing the types.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-838">種類を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-838">The name of the schema containing the types.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-839">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-839">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-840">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-840">OData Select statement.</span></span> <span data-ttu-id="71c31-841">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-841">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-842">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-842">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-843">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-843">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-844">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-844">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-845">Data Lake Analytics カタログから、指定されたデータベースとスキーマ内の型の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-845">Retrieves the list of types within the specified database and schema from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTypesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;&gt; ListTypesAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;&gt; ListTypesAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTypesAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTypesAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTypesAsync (operations, accountName, databaseName, schemaName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTypesAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-846">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-846">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-847">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-847">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-848">型を含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-848">The name of the database containing the types.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-849">種類を含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-849">The name of the schema containing the types.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-850">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-850">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-851">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-851">OData Select statement.</span></span> <span data-ttu-id="71c31-852">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-852">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-853">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-853">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-854">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-854">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-855">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-855">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-856">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-856">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-857">Data Lake Analytics カタログから、指定されたデータベースとスキーマ内の型の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-857">Retrieves the list of types within the specified database and schema from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTypesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt; ListTypesNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt; ListTypesNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTypesNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTypesNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlType)" />
      <MemberSignature Language="F#" Value="static member ListTypesNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTypesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-858">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-858">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-859">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-859">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-860">Data Lake Analytics カタログから、指定されたデータベースとスキーマ内の型の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-860">Retrieves the list of types within the specified database and schema from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTypesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;&gt; ListTypesNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;&gt; ListTypesNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTypesNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListTypesNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListTypesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListTypesNextAsync&gt;d__101))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlType&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-861">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-861">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-862">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-862">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-863">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-863">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-864">Data Lake Analytics カタログから、指定されたデータベースとスキーマ内の型の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-864">Retrieves the list of types within the specified database and schema from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListViews">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; ListViews (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; ListViews(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViews(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListViews (operations As ICatalogOperations, accountName As String, databaseName As String, schemaName As String, Optional odataQuery As ODataQuery(Of USqlView) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlView)" />
      <MemberSignature Language="F#" Value="static member ListViews : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViews (operations, accountName, databaseName, schemaName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-865">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-865">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-866">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-866">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-867">ビューを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-867">The name of the database containing the views.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-868">ビューを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-868">The name of the schema containing the views.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-869">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-869">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-870">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-870">OData Select statement.</span></span> <span data-ttu-id="71c31-871">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-871">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-872">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-872">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-873">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-873">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-874">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-874">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-875">Data Lake Analytics カタログからビューの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-875">Retrieves the list of views from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListViewsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt; ListViewsAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt; ListViewsAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string schemaName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListViewsAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsAsync (operations, accountName, databaseName, schemaName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListViewsAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-876">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-876">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-877">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-877">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-878">ビューを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-878">The name of the database containing the views.</span></span>
            </param>
        <param name="schemaName">
            <span data-ttu-id="71c31-879">ビューを含むスキーマの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-879">The name of the schema containing the views.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-880">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-880">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-881">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-881">OData Select statement.</span></span> <span data-ttu-id="71c31-882">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-882">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-883">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-883">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-884">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-884">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-885">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-885">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-886">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-886">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-887">Data Lake Analytics カタログからビューの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-887">Retrieves the list of views from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListViewsByDatabase">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; ListViewsByDatabase (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; ListViewsByDatabase(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsByDatabase(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListViewsByDatabase (operations As ICatalogOperations, accountName As String, databaseName As String, Optional odataQuery As ODataQuery(Of USqlView) = null, Optional select As String = null, Optional count As Nullable(Of Boolean) = null) As IPage(Of USqlView)" />
      <MemberSignature Language="F#" Value="static member ListViewsByDatabase : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsByDatabase (operations, accountName, databaseName, odataQuery, select, count)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-888">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-888">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-889">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-889">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-890">ビューを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-890">The name of the database containing the views.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-891">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-891">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-892">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-892">OData Select statement.</span></span> <span data-ttu-id="71c31-893">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-893">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-894">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-894">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-895">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-895">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-896">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-896">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-897">Data Lake Analytics カタログから、データベース内のすべてのビューの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-897">Retrieves the list of all views in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListViewsByDatabaseAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt; ListViewsByDatabaseAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; odataQuery = null, string select = null, Nullable&lt;bool&gt; count = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt; ListViewsByDatabaseAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; odataQuery, string select, valuetype System.Nullable`1&lt;bool&gt; count, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsByDatabaseAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView},System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListViewsByDatabaseAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsByDatabaseAsync (operations, accountName, databaseName, odataQuery, select, count, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListViewsByDatabaseAsync&gt;d__75))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-898">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-898">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-899">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-899">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-900">ビューを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-900">The name of the database containing the views.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="71c31-901">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="71c31-901">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="71c31-902">OData の Select ステートメント。</span><span class="sxs-lookup"><span data-stu-id="71c31-902">OData Select statement.</span></span> <span data-ttu-id="71c31-903">各エントリのためだけに要求されると、カテゴリなどのプロパティを制限しますか? $select = CategoryName、説明します。</span><span class="sxs-lookup"><span data-stu-id="71c31-903">Limits the properties on each entry to just those requested, e.g. Categories?$select=CategoryName,Description.</span></span> <span data-ttu-id="71c31-904">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-904">Optional.</span></span>
            </param>
        <param name="count">
            <span data-ttu-id="71c31-905">応答、カテゴリなどのリソースに含まれている一致するリソースの数を要求を true または false のブール値。 $count = true です。</span><span class="sxs-lookup"><span data-stu-id="71c31-905">The Boolean value of true or false to request a count of the matching resources included with the resources in the response, e.g. Categories?$count=true.</span></span> <span data-ttu-id="71c31-906">省略可能。</span><span class="sxs-lookup"><span data-stu-id="71c31-906">Optional.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-907">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-907">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-908">Data Lake Analytics カタログから、データベース内のすべてのビューの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-908">Retrieves the list of all views in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListViewsByDatabaseNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; ListViewsByDatabaseNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; ListViewsByDatabaseNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsByDatabaseNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListViewsByDatabaseNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlView)" />
      <MemberSignature Language="F#" Value="static member ListViewsByDatabaseNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsByDatabaseNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-909">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-909">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-910">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-910">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-911">Data Lake Analytics カタログから、データベース内のすべてのビューの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-911">Retrieves the list of all views in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListViewsByDatabaseNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt; ListViewsByDatabaseNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt; ListViewsByDatabaseNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsByDatabaseNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListViewsByDatabaseNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsByDatabaseNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListViewsByDatabaseNextAsync&gt;d__115))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-912">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-912">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-913">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-913">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-914">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-914">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-915">Data Lake Analytics カタログから、データベース内のすべてのビューの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-915">Retrieves the list of all views in a database from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListViewsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; ListViewsNext (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt; ListViewsNext(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsNext(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListViewsNext (operations As ICatalogOperations, nextPageLink As String) As IPage(Of USqlView)" />
      <MemberSignature Language="F#" Value="static member ListViewsNext : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-916">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-916">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-917">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-917">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-918">Data Lake Analytics カタログからビューの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-918">Retrieves the list of views from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListViewsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt; ListViewsNextAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt; ListViewsNextAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsNextAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListViewsNextAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.ListViewsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;ListViewsNextAsync&gt;d__95))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlView&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-919">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-919">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="71c31-920">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="71c31-920">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-921">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-921">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-922">Data Lake Analytics カタログからビューの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="71c31-922">Retrieves the list of views from the Data Lake Analytics catalog.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCredential">
      <MemberSignature Language="C#" Value="public static void UpdateCredential (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void UpdateCredential(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.UpdateCredential(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub UpdateCredential (operations As ICatalogOperations, accountName As String, databaseName As String, credentialName As String, parameters As DataLakeAnalyticsCatalogCredentialUpdateParameters)" />
      <MemberSignature Language="F#" Value="static member UpdateCredential : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.UpdateCredential (operations, accountName, databaseName, credentialName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-923">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-923">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-924">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-924">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-925">資格情報を含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-925">The name of the database containing the credential.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="71c31-926">資格情報の名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-926">The name of the credential.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="71c31-927">資格情報 (名前とパスワード) を変更するために必要なパラメーター</span><span class="sxs-lookup"><span data-stu-id="71c31-927">The parameters required to modify the credential (name and password)</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-928">指定されたデータベースで外部データ ソースで使用する指定された資格情報を変更します。</span><span class="sxs-lookup"><span data-stu-id="71c31-928">Modifies the specified credential for use with external data sources in the specified database</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCredentialAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpdateCredentialAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpdateCredentialAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string credentialName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.UpdateCredentialAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateCredentialAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.UpdateCredentialAsync (operations, accountName, databaseName, credentialName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;UpdateCredentialAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogCredentialUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-929">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-929">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-930">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-930">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-931">資格情報を含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-931">The name of the database containing the credential.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="71c31-932">資格情報の名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-932">The name of the credential.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="71c31-933">資格情報 (名前とパスワード) を変更するために必要なパラメーター</span><span class="sxs-lookup"><span data-stu-id="71c31-933">The parameters required to modify the credential (name and password)</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-934">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-934">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-935">指定されたデータベースで外部データ ソースで使用する指定された資格情報を変更します。</span><span class="sxs-lookup"><span data-stu-id="71c31-935">Modifies the specified credential for use with external data sources in the specified database</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSecret">
      <MemberSignature Language="C#" Value="public static void UpdateSecret (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void UpdateSecret(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.UpdateSecret(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub UpdateSecret (operations As ICatalogOperations, accountName As String, databaseName As String, secretName As String, parameters As DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters)" />
      <MemberSignature Language="F#" Value="static member UpdateSecret : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters -&gt; unit" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.UpdateSecret (operations, accountName, databaseName, secretName, parameters)" />
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
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-936">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-936">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-937">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-937">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-938">シークレットを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-938">The name of the database containing the secret.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="71c31-939">シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-939">The name of the secret.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="71c31-940">シークレット (名前とパスワード) を変更するために必要なパラメーター</span><span class="sxs-lookup"><span data-stu-id="71c31-940">The parameters required to modify the secret (name and password)</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-941">指定されたデータベースで外部データ ソースで使用するため、指定されたシークレットを変更します。</span><span class="sxs-lookup"><span data-stu-id="71c31-941">Modifies the specified secret for use with external data sources in the specified database.</span></span> <span data-ttu-id="71c31-942">これは廃止されており、次のリリースで削除される予定です。</span><span class="sxs-lookup"><span data-stu-id="71c31-942">This is deprecated and will be removed in the next release.</span></span> <span data-ttu-id="71c31-943">UpdateCredential を使用してください。</span><span class="sxs-lookup"><span data-stu-id="71c31-943">Please use UpdateCredential instead.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpdateSecretAsync (this Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName, Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpdateSecretAsync(class Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations operations, string accountName, string databaseName, string secretName, class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.UpdateSecretAsync(Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateSecretAsync : Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions.UpdateSecretAsync (operations, accountName, databaseName, secretName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataLake.Analytics.CatalogOperationsExtensions/&lt;UpdateSecretAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataLake.Analytics.ICatalogOperations" RefType="this" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsCatalogSecretCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="71c31-944">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="71c31-944">The operations group for this extension method.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="71c31-945">基になるカタログ操作を実行する Azure Data Lake Analytics アカウントです。</span><span class="sxs-lookup"><span data-stu-id="71c31-945">The Azure Data Lake Analytics account upon which to execute catalog operations.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="71c31-946">シークレットを含むデータベースの名前です。</span><span class="sxs-lookup"><span data-stu-id="71c31-946">The name of the database containing the secret.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="71c31-947">シークレットの名前。</span><span class="sxs-lookup"><span data-stu-id="71c31-947">The name of the secret.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="71c31-948">シークレット (名前とパスワード) を変更するために必要なパラメーター</span><span class="sxs-lookup"><span data-stu-id="71c31-948">The parameters required to modify the secret (name and password)</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="71c31-949">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="71c31-949">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="71c31-950">指定されたデータベースで外部データ ソースで使用するため、指定されたシークレットを変更します。</span><span class="sxs-lookup"><span data-stu-id="71c31-950">Modifies the specified secret for use with external data sources in the specified database.</span></span> <span data-ttu-id="71c31-951">これは廃止されており、次のリリースで削除される予定です。</span><span class="sxs-lookup"><span data-stu-id="71c31-951">This is deprecated and will be removed in the next release.</span></span> <span data-ttu-id="71c31-952">UpdateCredential を使用してください。</span><span class="sxs-lookup"><span data-stu-id="71c31-952">Please use UpdateCredential instead.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>