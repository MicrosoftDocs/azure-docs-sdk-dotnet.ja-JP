<Type Name="IBackupLongTermRetentionPoliciesOperations" FullName="Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations">
  <TypeSignature Language="C#" Value="public interface IBackupLongTermRetentionPoliciesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IBackupLongTermRetentionPoliciesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IBackupLongTermRetentionPoliciesOperations" />
  <TypeSignature Language="F#" Value="type IBackupLongTermRetentionPoliciesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c3a52-101">BackupLongTermRetentionPoliciesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="c3a52-101">BackupLongTermRetentionPoliciesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt;&gt;" Usage="iBackupLongTermRetentionPoliciesOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a52-102">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a52-102">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="c3a52-103">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="c3a52-103">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="c3a52-104">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a52-104">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="c3a52-105">データベースの名前</span><span class="sxs-lookup"><span data-stu-id="c3a52-105">The name of the database</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c3a52-106">バックアップの長期的な保有期間ポリシーの更新に必要なパラメーター</span><span class="sxs-lookup"><span data-stu-id="c3a52-106">The required parameters to update a backup long term retention policy</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a52-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a52-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a52-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a52-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a52-109">作成するか、データベース バックアップの長期的な保有期間ポリシーを更新</span><span class="sxs-lookup"><span data-stu-id="c3a52-109">Creates or updates a database backup long term retention policy</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a52-110">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a52-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a52-111">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a52-111">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a52-112">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a52-112">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt;&gt;" Usage="iBackupLongTermRetentionPoliciesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a52-113">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a52-113">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="c3a52-114">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="c3a52-114">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="c3a52-115">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a52-115">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="c3a52-116">データベースの名前</span><span class="sxs-lookup"><span data-stu-id="c3a52-116">The name of the database</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c3a52-117">バックアップの長期的な保有期間ポリシーの更新に必要なパラメーター</span><span class="sxs-lookup"><span data-stu-id="c3a52-117">The required parameters to update a backup long term retention policy</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a52-118">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a52-118">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a52-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a52-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a52-120">作成するか、データベース バックアップの長期的な保有期間ポリシーを更新</span><span class="sxs-lookup"><span data-stu-id="c3a52-120">Creates or updates a database backup long term retention policy</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a52-121">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a52-121">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a52-122">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a52-122">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a52-123">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a52-123">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IBackupLongTermRetentionPoliciesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt;&gt;" Usage="iBackupLongTermRetentionPoliciesOperations.GetWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionPolicy&gt;&gt;</ReturnType>
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
            <span data-ttu-id="c3a52-124">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a52-124">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="c3a52-125">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="c3a52-125">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="c3a52-126">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a52-126">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="c3a52-127">データベースの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a52-127">The name of the database.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a52-128">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a52-128">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a52-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a52-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a52-130">データベース バックアップの長期的な保有期間ポリシーを返します</span><span class="sxs-lookup"><span data-stu-id="c3a52-130">Returns a database backup long term retention policy</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a52-131">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a52-131">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a52-132">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a52-132">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a52-133">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a52-133">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>