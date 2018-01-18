<Type Name="ServerKeysOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ServerKeysOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServerKeysOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ServerKeysOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ServerKeysOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1bc00-101">ServerKeysOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="1bc00-101">Extension methods for ServerKeysOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ServerKey BeginCreateOrUpdate (this Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string resourceGroupName, string serverName, string keyName, Microsoft.Azure.Management.Sql.Models.ServerKey parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ServerKey BeginCreateOrUpdate(class Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string resourceGroupName, string serverName, string keyName, class Microsoft.Azure.Management.Sql.Models.ServerKey parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Sql.IServerKeysOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerKey)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IServerKeysOperations, resourceGroupName As String, serverName As String, keyName As String, parameters As ServerKey) As ServerKey" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Sql.IServerKeysOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ServerKey -&gt; Microsoft.Azure.Management.Sql.Models.ServerKey" Usage="Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, serverName, keyName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ServerKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerKey" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1bc00-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1bc00-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1bc00-103">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="1bc00-104">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="1bc00-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="1bc00-105">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-105">The name of the server.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1bc00-106">処理されるサーバー キーの名前 (更新または作成した)。</span><span class="sxs-lookup"><span data-stu-id="1bc00-106">The name of the server key to be operated on (updated or created).</span></span> <span data-ttu-id="1bc00-107">'Vault_key_version' の形式にするには、キー名が必要です。</span><span class="sxs-lookup"><span data-stu-id="1bc00-107">The key name is required to be in the format of 'vault_key_version'.</span></span> <span data-ttu-id="1bc00-108">たとえば、keyId が https://YourVaultName.vault.azure.net/keys/YourKeyName/01234567890123456789012345678901 の場合は、サーバーのキー名形式でなければなりません: YourVaultName_YourKeyName_01234567890123456789012345678901</span><span class="sxs-lookup"><span data-stu-id="1bc00-108">For example, if the keyId is https://YourVaultName.vault.azure.net/keys/YourKeyName/01234567890123456789012345678901, then the server key name should be formatted as: YourVaultName_YourKeyName_01234567890123456789012345678901</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1bc00-109">要求されたサーバー キーのリソースの状態。</span><span class="sxs-lookup"><span data-stu-id="1bc00-109">The requested server key resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1bc00-110">作成するか、サーバーのキーを更新します。</span><span class="sxs-lookup"><span data-stu-id="1bc00-110">Creates or updates a server key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerKey&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string resourceGroupName, string serverName, string keyName, Microsoft.Azure.Management.Sql.Models.ServerKey parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerKey&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string resourceGroupName, string serverName, string keyName, class Microsoft.Azure.Management.Sql.Models.ServerKey parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IServerKeysOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerKey,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IServerKeysOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ServerKey * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerKey&gt;" Usage="Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, keyName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerKey" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1bc00-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1bc00-111">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1bc00-112">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-112">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="1bc00-113">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="1bc00-113">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="1bc00-114">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-114">The name of the server.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1bc00-115">処理されるサーバー キーの名前 (更新または作成した)。</span><span class="sxs-lookup"><span data-stu-id="1bc00-115">The name of the server key to be operated on (updated or created).</span></span> <span data-ttu-id="1bc00-116">'Vault_key_version' の形式にするには、キー名が必要です。</span><span class="sxs-lookup"><span data-stu-id="1bc00-116">The key name is required to be in the format of 'vault_key_version'.</span></span> <span data-ttu-id="1bc00-117">たとえば、keyId が https://YourVaultName.vault.azure.net/keys/YourKeyName/01234567890123456789012345678901 の場合は、サーバーのキー名形式でなければなりません: YourVaultName_YourKeyName_01234567890123456789012345678901</span><span class="sxs-lookup"><span data-stu-id="1bc00-117">For example, if the keyId is https://YourVaultName.vault.azure.net/keys/YourKeyName/01234567890123456789012345678901, then the server key name should be formatted as: YourVaultName_YourKeyName_01234567890123456789012345678901</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1bc00-118">要求されたサーバー キーのリソースの状態。</span><span class="sxs-lookup"><span data-stu-id="1bc00-118">The requested server key resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1bc00-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1bc00-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1bc00-120">作成するか、サーバーのキーを更新します。</span><span class="sxs-lookup"><span data-stu-id="1bc00-120">Creates or updates a server key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string resourceGroupName, string serverName, string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string resourceGroupName, string serverName, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Sql.IServerKeysOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IServerKeysOperations, resourceGroupName As String, serverName As String, keyName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Sql.IServerKeysOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.BeginDelete (operations, resourceGroupName, serverName, keyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1bc00-121">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1bc00-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1bc00-122">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-122">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="1bc00-123">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="1bc00-123">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="1bc00-124">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-124">The name of the server.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1bc00-125">削除するサーバーのキーの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-125">The name of the server key to be deleted.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1bc00-126">指定した名前のサーバーのキーを削除します。</span><span class="sxs-lookup"><span data-stu-id="1bc00-126">Deletes the server key with the given name.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string resourceGroupName, string serverName, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string resourceGroupName, string serverName, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Sql.IServerKeysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Sql.IServerKeysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, serverName, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions/&lt;BeginDeleteAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1bc00-127">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1bc00-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1bc00-128">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-128">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="1bc00-129">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="1bc00-129">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="1bc00-130">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-130">The name of the server.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1bc00-131">削除するサーバーのキーの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-131">The name of the server key to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1bc00-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1bc00-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1bc00-133">指定した名前のサーバーのキーを削除します。</span><span class="sxs-lookup"><span data-stu-id="1bc00-133">Deletes the server key with the given name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ServerKey CreateOrUpdate (this Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string resourceGroupName, string serverName, string keyName, Microsoft.Azure.Management.Sql.Models.ServerKey parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ServerKey CreateOrUpdate(class Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string resourceGroupName, string serverName, string keyName, class Microsoft.Azure.Management.Sql.Models.ServerKey parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IServerKeysOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerKey)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IServerKeysOperations, resourceGroupName As String, serverName As String, keyName As String, parameters As ServerKey) As ServerKey" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IServerKeysOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ServerKey -&gt; Microsoft.Azure.Management.Sql.Models.ServerKey" Usage="Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, keyName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ServerKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerKey" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1bc00-134">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1bc00-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1bc00-135">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-135">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="1bc00-136">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="1bc00-136">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="1bc00-137">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-137">The name of the server.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1bc00-138">処理されるサーバー キーの名前 (更新または作成した)。</span><span class="sxs-lookup"><span data-stu-id="1bc00-138">The name of the server key to be operated on (updated or created).</span></span> <span data-ttu-id="1bc00-139">'Vault_key_version' の形式にするには、キー名が必要です。</span><span class="sxs-lookup"><span data-stu-id="1bc00-139">The key name is required to be in the format of 'vault_key_version'.</span></span> <span data-ttu-id="1bc00-140">たとえば、keyId が https://YourVaultName.vault.azure.net/keys/YourKeyName/01234567890123456789012345678901 の場合は、サーバーのキー名形式でなければなりません: YourVaultName_YourKeyName_01234567890123456789012345678901</span><span class="sxs-lookup"><span data-stu-id="1bc00-140">For example, if the keyId is https://YourVaultName.vault.azure.net/keys/YourKeyName/01234567890123456789012345678901, then the server key name should be formatted as: YourVaultName_YourKeyName_01234567890123456789012345678901</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1bc00-141">要求されたサーバー キーのリソースの状態。</span><span class="sxs-lookup"><span data-stu-id="1bc00-141">The requested server key resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1bc00-142">作成するか、サーバーのキーを更新します。</span><span class="sxs-lookup"><span data-stu-id="1bc00-142">Creates or updates a server key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerKey&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string resourceGroupName, string serverName, string keyName, Microsoft.Azure.Management.Sql.Models.ServerKey parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerKey&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string resourceGroupName, string serverName, string keyName, class Microsoft.Azure.Management.Sql.Models.ServerKey parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IServerKeysOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.ServerKey,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IServerKeysOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.ServerKey * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerKey&gt;" Usage="Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, keyName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.ServerKey" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1bc00-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1bc00-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1bc00-144">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-144">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="1bc00-145">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="1bc00-145">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="1bc00-146">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-146">The name of the server.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1bc00-147">処理されるサーバー キーの名前 (更新または作成した)。</span><span class="sxs-lookup"><span data-stu-id="1bc00-147">The name of the server key to be operated on (updated or created).</span></span> <span data-ttu-id="1bc00-148">'Vault_key_version' の形式にするには、キー名が必要です。</span><span class="sxs-lookup"><span data-stu-id="1bc00-148">The key name is required to be in the format of 'vault_key_version'.</span></span> <span data-ttu-id="1bc00-149">たとえば、keyId が https://YourVaultName.vault.azure.net/keys/YourKeyName/01234567890123456789012345678901 の場合は、サーバーのキー名形式でなければなりません: YourVaultName_YourKeyName_01234567890123456789012345678901</span><span class="sxs-lookup"><span data-stu-id="1bc00-149">For example, if the keyId is https://YourVaultName.vault.azure.net/keys/YourKeyName/01234567890123456789012345678901, then the server key name should be formatted as: YourVaultName_YourKeyName_01234567890123456789012345678901</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1bc00-150">要求されたサーバー キーのリソースの状態。</span><span class="sxs-lookup"><span data-stu-id="1bc00-150">The requested server key resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1bc00-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1bc00-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1bc00-152">作成するか、サーバーのキーを更新します。</span><span class="sxs-lookup"><span data-stu-id="1bc00-152">Creates or updates a server key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string resourceGroupName, string serverName, string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string resourceGroupName, string serverName, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.Delete(Microsoft.Azure.Management.Sql.IServerKeysOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IServerKeysOperations, resourceGroupName As String, serverName As String, keyName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Sql.IServerKeysOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.Delete (operations, resourceGroupName, serverName, keyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1bc00-153">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1bc00-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1bc00-154">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-154">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="1bc00-155">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="1bc00-155">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="1bc00-156">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-156">The name of the server.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1bc00-157">削除するサーバーのキーの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-157">The name of the server key to be deleted.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1bc00-158">指定した名前のサーバーのキーを削除します。</span><span class="sxs-lookup"><span data-stu-id="1bc00-158">Deletes the server key with the given name.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string resourceGroupName, string serverName, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string resourceGroupName, string serverName, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.IServerKeysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.IServerKeysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1bc00-159">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1bc00-159">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1bc00-160">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-160">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="1bc00-161">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="1bc00-161">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="1bc00-162">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-162">The name of the server.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1bc00-163">削除するサーバーのキーの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-163">The name of the server key to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1bc00-164">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1bc00-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1bc00-165">指定した名前のサーバーのキーを削除します。</span><span class="sxs-lookup"><span data-stu-id="1bc00-165">Deletes the server key with the given name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.ServerKey Get (this Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string resourceGroupName, string serverName, string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.ServerKey Get(class Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string resourceGroupName, string serverName, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IServerKeysOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IServerKeysOperations, resourceGroupName As String, serverName As String, keyName As String) As ServerKey" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IServerKeysOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.ServerKey" Usage="Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.Get (operations, resourceGroupName, serverName, keyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.ServerKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1bc00-166">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1bc00-166">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1bc00-167">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-167">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="1bc00-168">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="1bc00-168">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="1bc00-169">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-169">The name of the server.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1bc00-170">取得するサーバーのキーの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-170">The name of the server key to be retrieved.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1bc00-171">サーバーのキーを取得します。</span><span class="sxs-lookup"><span data-stu-id="1bc00-171">Gets a server key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerKey&gt; GetAsync (this Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string resourceGroupName, string serverName, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerKey&gt; GetAsync(class Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string resourceGroupName, string serverName, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IServerKeysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IServerKeysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerKey&gt;" Usage="Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.ServerKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1bc00-172">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1bc00-172">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1bc00-173">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-173">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="1bc00-174">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="1bc00-174">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="1bc00-175">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-175">The name of the server.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="1bc00-176">取得するサーバーのキーの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-176">The name of the server key to be retrieved.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1bc00-177">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1bc00-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1bc00-178">サーバーのキーを取得します。</span><span class="sxs-lookup"><span data-stu-id="1bc00-178">Gets a server key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServer">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerKey&gt; ListByServer (this Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerKey&gt; ListByServer(class Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.ListByServer(Microsoft.Azure.Management.Sql.IServerKeysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServer (operations As IServerKeysOperations, resourceGroupName As String, serverName As String) As IPage(Of ServerKey)" />
      <MemberSignature Language="F#" Value="static member ListByServer : Microsoft.Azure.Management.Sql.IServerKeysOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerKey&gt;" Usage="Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.ListByServer (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1bc00-179">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1bc00-179">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1bc00-180">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-180">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="1bc00-181">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="1bc00-181">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="1bc00-182">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-182">The name of the server.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1bc00-183">サーバー キーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1bc00-183">Gets a list of server keys.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerKey&gt;&gt; ListByServerAsync (this Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerKey&gt;&gt; ListByServerAsync(class Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.ListByServerAsync(Microsoft.Azure.Management.Sql.IServerKeysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerAsync : Microsoft.Azure.Management.Sql.IServerKeysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerKey&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.ListByServerAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions/&lt;ListByServerAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1bc00-184">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1bc00-184">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1bc00-185">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-185">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="1bc00-186">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="1bc00-186">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="1bc00-187">サーバーの名前。</span><span class="sxs-lookup"><span data-stu-id="1bc00-187">The name of the server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1bc00-188">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1bc00-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1bc00-189">サーバー キーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1bc00-189">Gets a list of server keys.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerKey&gt; ListByServerNext (this Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerKey&gt; ListByServerNext(class Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.ListByServerNext(Microsoft.Azure.Management.Sql.IServerKeysOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServerNext (operations As IServerKeysOperations, nextPageLink As String) As IPage(Of ServerKey)" />
      <MemberSignature Language="F#" Value="static member ListByServerNext : Microsoft.Azure.Management.Sql.IServerKeysOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerKey&gt;" Usage="Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.ListByServerNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerKeysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1bc00-190">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1bc00-190">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1bc00-191">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1bc00-191">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1bc00-192">サーバー キーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1bc00-192">Gets a list of server keys.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerKey&gt;&gt; ListByServerNextAsync (this Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.ServerKey&gt;&gt; ListByServerNextAsync(class Microsoft.Azure.Management.Sql.IServerKeysOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.ListByServerNextAsync(Microsoft.Azure.Management.Sql.IServerKeysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerNextAsync : Microsoft.Azure.Management.Sql.IServerKeysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerKey&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions.ListByServerNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.ServerKeysOperationsExtensions/&lt;ListByServerNextAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.ServerKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IServerKeysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1bc00-193">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="1bc00-193">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1bc00-194">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="1bc00-194">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1bc00-195">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="1bc00-195">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1bc00-196">サーバー キーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="1bc00-196">Gets a list of server keys.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>