<Type Name="IVaultOperations" FullName="Microsoft.Azure.Management.BackupServices.IVaultOperations">
  <TypeSignature Language="C#" Value="public interface IVaultOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVaultOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.IVaultOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVaultOperations" />
  <TypeSignature Language="F#" Value="type IVaultOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="32c30-101">Azure Backup の拡張機能の資格情報コンテナーに関連する操作の定義。</span><span class="sxs-lookup"><span data-stu-id="32c30-101">Definition of Vault-related operations for the Azure Backup extension.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters parameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters parameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;" Usage="iVaultOperations.CreateOrUpdateAsync (resourceGroupName, resourceName, parameters, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="32c30-102">所属する資格情報コンテナーにリソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="32c30-102">The name of resource group to which vault belongs</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="32c30-103">資格情報コンテナーの名前</span><span class="sxs-lookup"><span data-stu-id="32c30-103">The name of the vault</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="32c30-104">パラメーターを作成または資格情報コンテナーの更新</span><span class="sxs-lookup"><span data-stu-id="32c30-104">Parameters to create or update the vault</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="32c30-105">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="32c30-105">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="32c30-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="32c30-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32c30-107">新しい Azure バックアップ コンテナーを作成します。</span><span class="sxs-lookup"><span data-stu-id="32c30-107">Creates a new Azure backup vault.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="32c30-108">資格情報コンテナー情報です。</span><span class="sxs-lookup"><span data-stu-id="32c30-108">Vault information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; DeleteAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; DeleteAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.DeleteAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;" Usage="iVaultOperations.DeleteAsync (resourceGroupName, resourceName, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="32c30-109">所属する資格情報コンテナーにリソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="32c30-109">The name of resource group to which vault belongs</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="32c30-110">資格情報コンテナーの名前</span><span class="sxs-lookup"><span data-stu-id="32c30-110">The name of the vault</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="32c30-111">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="32c30-111">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="32c30-112">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="32c30-112">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32c30-113">指定された Azure バックアップ コンテナーを削除します。</span><span class="sxs-lookup"><span data-stu-id="32c30-113">Deletes the specified Azure backup vault.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="32c30-114">資格情報コンテナー情報です。</span><span class="sxs-lookup"><span data-stu-id="32c30-114">Vault information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; GetAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; GetAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.GetAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;" Usage="iVaultOperations.GetAsync (resourceGroupName, resourceName, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="32c30-115">所属する資格情報コンテナーにリソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="32c30-115">The name of resource group to which vault belongs</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="32c30-116">資格情報コンテナーの名前</span><span class="sxs-lookup"><span data-stu-id="32c30-116">The name of the vault</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="32c30-117">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="32c30-117">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="32c30-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="32c30-118">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32c30-119">指定した Azure key vault を取得します。</span><span class="sxs-lookup"><span data-stu-id="32c30-119">Gets the specified Azure key vault.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="32c30-120">資格情報コンテナー情報です。</span><span class="sxs-lookup"><span data-stu-id="32c30-120">Vault information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetResourceStorageConfigAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt; GetResourceStorageConfigAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt; GetResourceStorageConfigAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.GetResourceStorageConfigAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetResourceStorageConfigAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt;" Usage="iVaultOperations.GetResourceStorageConfigAsync (resourceGroupName, resourceName, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="32c30-121">所属する資格情報コンテナーにリソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="32c30-121">The name of resource group to which vault belongs</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="32c30-122">資格情報コンテナーの名前</span><span class="sxs-lookup"><span data-stu-id="32c30-122">The name of the vault</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="32c30-123">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="32c30-123">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="32c30-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="32c30-124">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32c30-125">リソースの記憶域構成をフェッチします。</span><span class="sxs-lookup"><span data-stu-id="32c30-125">Fetches resource storage config.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="32c30-126">Get リソース記憶域構成の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="32c30-126">The definition of a get resource storage config response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListAsync (int top, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListAsync(int32 top, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.ListAsync(System.Int32,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : int * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;" Usage="iVaultOperations.ListAsync (top, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="top">
            <span data-ttu-id="32c30-127">返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="32c30-127">Maximum number of results to return.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="32c30-128">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="32c30-128">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="32c30-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="32c30-129">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32c30-130">サブスクリプションに関連付けられているバックアップ資格情報コンテナーの情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="32c30-130">Gets information of the backup vaults associated with subscription.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="32c30-131">資格情報コンテナーの一覧</span><span class="sxs-lookup"><span data-stu-id="32c30-131">List of vaults</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListByResourceGroupAsync (string resourceGroupName, int top, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListByResourceGroupAsync(string resourceGroupName, int32 top, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.ListByResourceGroupAsync(System.String,System.Int32,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupAsync : string * int * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;" Usage="iVaultOperations.ListByResourceGroupAsync (resourceGroupName, top, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="32c30-132">返される資格情報コンテナーのセットを制限するリソース グループの名前を指定する省略可能な引数。</span><span class="sxs-lookup"><span data-stu-id="32c30-132">An optional argument which specifies the name of the resource group that constrains the set of vaults that are returned.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="32c30-133">返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="32c30-133">Maximum number of results to return.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="32c30-134">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="32c30-134">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="32c30-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="32c30-135">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32c30-136">リソース グループに関連付けられているバックアップ資格情報コンテナーの情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="32c30-136">Gets information of the backup vaults associated with resource group.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="32c30-137">資格情報コンテナーの一覧</span><span class="sxs-lookup"><span data-stu-id="32c30-137">List of vaults</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateStorageTypeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UpdateStorageTypeAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest updateVaultStorageTypeRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UpdateStorageTypeAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest updateVaultStorageTypeRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.UpdateStorageTypeAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateStorageTypeAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iVaultOperations.UpdateStorageTypeAsync (resourceGroupName, resourceName, updateVaultStorageTypeRequest, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="updateVaultStorageTypeRequest" Type="Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="updateVaultStorageTypeRequest">
            <span data-ttu-id="32c30-138">資格情報コンテナーの記憶域の種類の更新の要求</span><span class="sxs-lookup"><span data-stu-id="32c30-138">Update Vault Storage Type Request</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="32c30-139">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="32c30-139">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="32c30-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="32c30-140">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32c30-141">更新プログラムには、ストレージ モデルの種類が資格情報コンテナーします。</span><span class="sxs-lookup"><span data-stu-id="32c30-141">Updates vault storage model type.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="32c30-142">操作の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="32c30-142">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadCertificateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt; UploadCertificateAsync (string resourceGroupName, string resourceName, string certificateName, Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest vaultCredUploadCertRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt; UploadCertificateAsync(string resourceGroupName, string resourceName, string certificateName, class Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest vaultCredUploadCertRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IVaultOperations.UploadCertificateAsync(System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UploadCertificateAsync : string * string * string * Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt;" Usage="iVaultOperations.UploadCertificateAsync (resourceGroupName, resourceName, certificateName, vaultCredUploadCertRequest, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="vaultCredUploadCertRequest" Type="Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="certificateName">
            <span data-ttu-id="32c30-143">証明書の名前です。</span><span class="sxs-lookup"><span data-stu-id="32c30-143">Name of the certificate.</span></span>
            </param>
        <param name="vaultCredUploadCertRequest">
            <span data-ttu-id="32c30-144">証明書のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="32c30-144">Certificate parameters.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="32c30-145">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="32c30-145">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="32c30-146">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="32c30-146">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32c30-147">アップロードには、資格情報証明書が資格情報コンテナーします。</span><span class="sxs-lookup"><span data-stu-id="32c30-147">Uploads vault credential certificate.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="32c30-148">証明書の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="32c30-148">The definition of a certificate response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>