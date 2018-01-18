<Type Name="IBackupLongTermRetentionVaultsOperations" FullName="Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations">
  <TypeSignature Language="C#" Value="public interface IBackupLongTermRetentionVaultsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IBackupLongTermRetentionVaultsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IBackupLongTermRetentionVaultsOperations" />
  <TypeSignature Language="F#" Value="type IBackupLongTermRetentionVaultsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="bef12-101">BackupLongTermRetentionVaultsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="bef12-101">BackupLongTermRetentionVaultsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault&gt;&gt;" Usage="iBackupLongTermRetentionVaultsOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, serverName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="bef12-102">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="bef12-102">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="bef12-103">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="bef12-103">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="bef12-104">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="bef12-104">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bef12-105">バックアップの長期的な保存の資格情報コンテナーを更新する必須パラメーター</span><span class="sxs-lookup"><span data-stu-id="bef12-105">The required parameters to update a backup long term retention vault</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bef12-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bef12-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bef12-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bef12-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bef12-108">サーバー バックアップの長期的な保有期間資格情報コンテナーを更新します。</span><span class="sxs-lookup"><span data-stu-id="bef12-108">Updates a server backup long term retention vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="bef12-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bef12-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bef12-110">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bef12-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bef12-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bef12-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault&gt;&gt;" Usage="iBackupLongTermRetentionVaultsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, serverName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="bef12-112">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="bef12-112">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="bef12-113">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="bef12-113">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="bef12-114">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="bef12-114">The name of the server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bef12-115">バックアップの長期的な保存の資格情報コンテナーを更新する必須パラメーター</span><span class="sxs-lookup"><span data-stu-id="bef12-115">The required parameters to update a backup long term retention vault</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bef12-116">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bef12-116">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bef12-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bef12-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bef12-118">サーバー バックアップの長期的な保有期間資格情報コンテナーを更新します。</span><span class="sxs-lookup"><span data-stu-id="bef12-118">Updates a server backup long term retention vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="bef12-119">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bef12-119">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bef12-120">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bef12-120">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bef12-121">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bef12-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string serverName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string serverName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.IBackupLongTermRetentionVaultsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault&gt;&gt;" Usage="iBackupLongTermRetentionVaultsOperations.GetWithHttpMessagesAsync (resourceGroupName, serverName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Sql.Models.BackupLongTermRetentionVault&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="bef12-122">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="bef12-122">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="bef12-123">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="bef12-123">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="bef12-124">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="bef12-124">The name of the server.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="bef12-125">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="bef12-125">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bef12-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bef12-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bef12-127">サーバー バックアップの長期的な保有期間資格情報コンテナーを取得します。</span><span class="sxs-lookup"><span data-stu-id="bef12-127">Gets a server backup long term retention vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="bef12-128">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bef12-128">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="bef12-129">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bef12-129">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bef12-130">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="bef12-130">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>