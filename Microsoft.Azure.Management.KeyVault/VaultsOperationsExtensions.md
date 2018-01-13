<Type Name="VaultsOperationsExtensions" FullName="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VaultsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VaultsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VaultsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VaultsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4725d-101">VaultsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="4725d-101">Extension methods for VaultsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginPurgeDeleted">
      <MemberSignature Language="C#" Value="public static void BeginPurgeDeleted (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string vaultName, string location);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginPurgeDeleted(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string vaultName, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.BeginPurgeDeleted(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginPurgeDeleted (operations As IVaultsOperations, vaultName As String, location As String)" />
      <MemberSignature Language="F#" Value="static member BeginPurgeDeleted : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.BeginPurgeDeleted (operations, vaultName, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4725d-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4725d-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="4725d-103">論理削除された資格情報コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="4725d-103">The name of the soft-deleted vault.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="4725d-104">論理削除された資格情報コンテナーの場所です。</span><span class="sxs-lookup"><span data-stu-id="4725d-104">The location of the soft-deleted vault.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4725d-105">指定した資格情報コンテナーを完全に削除します。</span><span class="sxs-lookup"><span data-stu-id="4725d-105">Permanently deletes the specified vault.</span></span> <span data-ttu-id="4725d-106">別名が削除された Azure key vault を削除します。</span><span class="sxs-lookup"><span data-stu-id="4725d-106">aka Purges the deleted Azure key vault.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPurgeDeletedAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginPurgeDeletedAsync (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string vaultName, string location, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginPurgeDeletedAsync(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string vaultName, string location, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.BeginPurgeDeletedAsync(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginPurgeDeletedAsync : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.BeginPurgeDeletedAsync (operations, vaultName, location, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions/&lt;BeginPurgeDeletedAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4725d-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4725d-107">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="4725d-108">論理削除された資格情報コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="4725d-108">The name of the soft-deleted vault.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="4725d-109">論理削除された資格情報コンテナーの場所です。</span><span class="sxs-lookup"><span data-stu-id="4725d-109">The location of the soft-deleted vault.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4725d-110">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4725d-110">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4725d-111">指定した資格情報コンテナーを完全に削除します。</span><span class="sxs-lookup"><span data-stu-id="4725d-111">Permanently deletes the specified vault.</span></span> <span data-ttu-id="4725d-112">別名が削除された Azure key vault を削除します。</span><span class="sxs-lookup"><span data-stu-id="4725d-112">aka Purges the deleted Azure key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.KeyVault.Models.Vault CreateOrUpdate (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, string vaultName, Microsoft.Azure.Management.KeyVault.Models.VaultCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.KeyVault.Models.Vault CreateOrUpdate(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, string vaultName, class Microsoft.Azure.Management.KeyVault.Models.VaultCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.String,Microsoft.Azure.Management.KeyVault.Models.VaultCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IVaultsOperations, resourceGroupName As String, vaultName As String, parameters As VaultCreateOrUpdateParameters) As Vault" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * string * Microsoft.Azure.Management.KeyVault.Models.VaultCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.KeyVault.Models.Vault" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, vaultName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Models.Vault</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.KeyVault.Models.VaultCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4725d-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4725d-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4725d-114">サーバーが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4725d-114">The name of the Resource Group to which the server belongs.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="4725d-115">コンテナーの名前</span><span class="sxs-lookup"><span data-stu-id="4725d-115">Name of the vault</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4725d-116">パラメーターを作成または資格情報コンテナーの更新</span><span class="sxs-lookup"><span data-stu-id="4725d-116">Parameters to create or update the vault</span></span>
            </param>
        <summary>
            <span data-ttu-id="4725d-117">作成または指定したサブスクリプションでキー資格情報コンテナーを更新します。</span><span class="sxs-lookup"><span data-stu-id="4725d-117">Create or update a key vault in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, string vaultName, Microsoft.Azure.Management.KeyVault.Models.VaultCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.KeyVault.Models.Vault&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, string vaultName, class Microsoft.Azure.Management.KeyVault.Models.VaultCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.String,Microsoft.Azure.Management.KeyVault.Models.VaultCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * string * Microsoft.Azure.Management.KeyVault.Models.VaultCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, vaultName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.KeyVault.Models.VaultCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4725d-118">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4725d-118">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4725d-119">サーバーが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4725d-119">The name of the Resource Group to which the server belongs.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="4725d-120">コンテナーの名前</span><span class="sxs-lookup"><span data-stu-id="4725d-120">Name of the vault</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4725d-121">パラメーターを作成または資格情報コンテナーの更新</span><span class="sxs-lookup"><span data-stu-id="4725d-121">Parameters to create or update the vault</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4725d-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4725d-122">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4725d-123">作成または指定したサブスクリプションでキー資格情報コンテナーを更新します。</span><span class="sxs-lookup"><span data-stu-id="4725d-123">Create or update a key vault in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, string vaultName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, string vaultName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.Delete(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IVaultsOperations, resourceGroupName As String, vaultName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.Delete (operations, resourceGroupName, vaultName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4725d-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4725d-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4725d-125">資格情報コンテナーが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4725d-125">The name of the Resource Group to which the vault belongs.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="4725d-126">削除する資格情報コンテナーの名前</span><span class="sxs-lookup"><span data-stu-id="4725d-126">The name of the vault to delete</span></span>
            </param>
        <summary>
            <span data-ttu-id="4725d-127">指定した Azure key vault を削除します。</span><span class="sxs-lookup"><span data-stu-id="4725d-127">Deletes the specified Azure key vault.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, string vaultName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, string vaultName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.DeleteAsync (operations, resourceGroupName, vaultName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4725d-128">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4725d-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4725d-129">資格情報コンテナーが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4725d-129">The name of the Resource Group to which the vault belongs.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="4725d-130">削除する資格情報コンテナーの名前</span><span class="sxs-lookup"><span data-stu-id="4725d-130">The name of the vault to delete</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4725d-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4725d-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4725d-132">指定した Azure key vault を削除します。</span><span class="sxs-lookup"><span data-stu-id="4725d-132">Deletes the specified Azure key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.KeyVault.Models.Vault Get (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, string vaultName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.KeyVault.Models.Vault Get(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, string vaultName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.Get(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVaultsOperations, resourceGroupName As String, vaultName As String) As Vault" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * string -&gt; Microsoft.Azure.Management.KeyVault.Models.Vault" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.Get (operations, resourceGroupName, vaultName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Models.Vault</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4725d-133">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4725d-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4725d-134">資格情報コンテナーが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4725d-134">The name of the Resource Group to which the vault belongs.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="4725d-135">資格情報コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="4725d-135">The name of the vault.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4725d-136">指定した Azure key vault を取得します。</span><span class="sxs-lookup"><span data-stu-id="4725d-136">Gets the specified Azure key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt; GetAsync (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, string vaultName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.KeyVault.Models.Vault&gt; GetAsync(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, string vaultName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.GetAsync(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.GetAsync (operations, resourceGroupName, vaultName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4725d-137">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4725d-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4725d-138">資格情報コンテナーが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4725d-138">The name of the Resource Group to which the vault belongs.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="4725d-139">資格情報コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="4725d-139">The name of the vault.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4725d-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4725d-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4725d-141">指定した Azure key vault を取得します。</span><span class="sxs-lookup"><span data-stu-id="4725d-141">Gets the specified Azure key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeleted">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.KeyVault.Models.DeletedVault GetDeleted (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string vaultName, string location);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.KeyVault.Models.DeletedVault GetDeleted(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string vaultName, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.GetDeleted(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDeleted (operations As IVaultsOperations, vaultName As String, location As String) As DeletedVault" />
      <MemberSignature Language="F#" Value="static member GetDeleted : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * string -&gt; Microsoft.Azure.Management.KeyVault.Models.DeletedVault" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.GetDeleted (operations, vaultName, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Models.DeletedVault</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4725d-142">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4725d-142">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="4725d-143">資格情報コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="4725d-143">The name of the vault.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="4725d-144">削除済みの資格情報コンテナーの場所です。</span><span class="sxs-lookup"><span data-stu-id="4725d-144">The location of the deleted vault.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4725d-145">削除された Azure key vault を取得します。</span><span class="sxs-lookup"><span data-stu-id="4725d-145">Gets the deleted Azure key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt; GetDeletedAsync (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string vaultName, string location, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt; GetDeletedAsync(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string vaultName, string location, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.GetDeletedAsync(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedAsync : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.GetDeletedAsync (operations, vaultName, location, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions/&lt;GetDeletedAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4725d-146">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4725d-146">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="4725d-147">資格情報コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="4725d-147">The name of the vault.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="4725d-148">削除済みの資格情報コンテナーの場所です。</span><span class="sxs-lookup"><span data-stu-id="4725d-148">The location of the deleted vault.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4725d-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4725d-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4725d-150">削除された Azure key vault を取得します。</span><span class="sxs-lookup"><span data-stu-id="4725d-150">Gets the deleted Azure key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Resource&gt; List (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, Nullable&lt;int&gt; top = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Models.Resource&gt; List(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, valuetype System.Nullable`1&lt;int32&gt; top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.List(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IVaultsOperations, Optional top As Nullable(Of Integer) = null) As IPage(Of Resource)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.KeyVault.IVaultsOperations * Nullable&lt;int&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Resource&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.List (operations, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Resource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4725d-151">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4725d-151">The operations group for this extension method.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="4725d-152">返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="4725d-152">Maximum number of results to return.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4725d-153">一覧操作では、サブスクリプションに関連付けられている資格情報コンテナーに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="4725d-153">The List operation gets information about the vaults associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Resource&gt;&gt; ListAsync (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Models.Resource&gt;&gt; ListAsync(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListAsync(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.KeyVault.IVaultsOperations * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Resource&gt;&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListAsync (operations, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions/&lt;ListAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Resource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4725d-154">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4725d-154">The operations group for this extension method.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="4725d-155">返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="4725d-155">Maximum number of results to return.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4725d-156">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4725d-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4725d-157">一覧操作では、サブスクリプションに関連付けられている資格情報コンテナーに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="4725d-157">The List operation gets information about the vaults associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt; ListByResourceGroup (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, Nullable&lt;int&gt; top = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Models.Vault&gt; ListByResourceGroup(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, valuetype System.Nullable`1&lt;int32&gt; top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IVaultsOperations, resourceGroupName As String, Optional top As Nullable(Of Integer) = null) As IPage(Of Vault)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * Nullable&lt;int&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4725d-158">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4725d-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4725d-159">資格情報コンテナーが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4725d-159">The name of the Resource Group to which the vault belongs.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="4725d-160">返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="4725d-160">Maximum number of results to return.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4725d-161">一覧操作では、および指定されたリソース グループ内で、サブスクリプションに関連付けられている資格情報コンテナーに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="4725d-161">The List operation gets information about the vaults associated with the subscription and within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Models.Vault&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string resourceGroupName, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4725d-162">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4725d-162">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4725d-163">資格情報コンテナーが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="4725d-163">The name of the Resource Group to which the vault belongs.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="4725d-164">返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="4725d-164">Maximum number of results to return.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4725d-165">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4725d-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4725d-166">一覧操作では、および指定されたリソース グループ内で、サブスクリプションに関連付けられている資格情報コンテナーに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="4725d-166">The List operation gets information about the vaults associated with the subscription and within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Models.Vault&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IVaultsOperations, nextPageLink As String) As IPage(Of Vault)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4725d-167">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4725d-167">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4725d-168">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="4725d-168">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4725d-169">一覧操作では、および指定されたリソース グループ内で、サブスクリプションに関連付けられている資格情報コンテナーに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="4725d-169">The List operation gets information about the vaults associated with the subscription and within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Models.Vault&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Vault&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4725d-170">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4725d-170">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4725d-171">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="4725d-171">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4725d-172">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4725d-172">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4725d-173">一覧操作では、および指定されたリソース グループ内で、サブスクリプションに関連付けられている資格情報コンテナーに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="4725d-173">The List operation gets information about the vaults associated with the subscription and within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDeleted">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt; ListDeleted (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt; ListDeleted(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListDeleted(Microsoft.Azure.Management.KeyVault.IVaultsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListDeleted (operations As IVaultsOperations) As IPage(Of DeletedVault)" />
      <MemberSignature Language="F#" Value="static member ListDeleted : Microsoft.Azure.Management.KeyVault.IVaultsOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListDeleted operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4725d-174">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4725d-174">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4725d-175">サブスクリプションの削除済みの資格情報コンテナーに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="4725d-175">Gets information about the deleted vaults in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDeletedAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;&gt; ListDeletedAsync (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;&gt; ListDeletedAsync(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListDeletedAsync(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListDeletedAsync : Microsoft.Azure.Management.KeyVault.IVaultsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListDeletedAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions/&lt;ListDeletedAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4725d-176">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4725d-176">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4725d-177">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4725d-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4725d-178">サブスクリプションの削除済みの資格情報コンテナーに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="4725d-178">Gets information about the deleted vaults in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDeletedNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt; ListDeletedNext (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt; ListDeletedNext(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListDeletedNext(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListDeletedNext (operations As IVaultsOperations, nextPageLink As String) As IPage(Of DeletedVault)" />
      <MemberSignature Language="F#" Value="static member ListDeletedNext : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListDeletedNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4725d-179">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4725d-179">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4725d-180">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="4725d-180">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4725d-181">サブスクリプションの削除済みの資格情報コンテナーに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="4725d-181">Gets information about the deleted vaults in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDeletedNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;&gt; ListDeletedNextAsync (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;&gt; ListDeletedNextAsync(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListDeletedNextAsync(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListDeletedNextAsync : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListDeletedNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions/&lt;ListDeletedNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.DeletedVault&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4725d-182">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4725d-182">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4725d-183">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="4725d-183">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4725d-184">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4725d-184">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4725d-185">サブスクリプションの削除済みの資格情報コンテナーに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="4725d-185">Gets information about the deleted vaults in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Resource&gt; ListNext (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Models.Resource&gt; ListNext(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListNext(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IVaultsOperations, nextPageLink As String) As IPage(Of Resource)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Resource&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Resource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4725d-186">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4725d-186">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4725d-187">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="4725d-187">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4725d-188">一覧操作では、サブスクリプションに関連付けられている資格情報コンテナーに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="4725d-188">The List operation gets information about the vaults associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Resource&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.KeyVault.Models.Resource&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Resource&gt;&gt;" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions/&lt;ListNextAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.KeyVault.Models.Resource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4725d-189">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4725d-189">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4725d-190">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="4725d-190">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4725d-191">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4725d-191">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4725d-192">一覧操作では、サブスクリプションに関連付けられている資格情報コンテナーに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="4725d-192">The List operation gets information about the vaults associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeleted">
      <MemberSignature Language="C#" Value="public static void PurgeDeleted (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string vaultName, string location);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void PurgeDeleted(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string vaultName, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.PurgeDeleted(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub PurgeDeleted (operations As IVaultsOperations, vaultName As String, location As String)" />
      <MemberSignature Language="F#" Value="static member PurgeDeleted : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.PurgeDeleted (operations, vaultName, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4725d-193">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4725d-193">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="4725d-194">論理削除された資格情報コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="4725d-194">The name of the soft-deleted vault.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="4725d-195">論理削除された資格情報コンテナーの場所です。</span><span class="sxs-lookup"><span data-stu-id="4725d-195">The location of the soft-deleted vault.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4725d-196">指定した資格情報コンテナーを完全に削除します。</span><span class="sxs-lookup"><span data-stu-id="4725d-196">Permanently deletes the specified vault.</span></span> <span data-ttu-id="4725d-197">別名が削除された Azure key vault を削除します。</span><span class="sxs-lookup"><span data-stu-id="4725d-197">aka Purges the deleted Azure key vault.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeDeletedAsync (this Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string vaultName, string location, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeDeletedAsync(class Microsoft.Azure.Management.KeyVault.IVaultsOperations operations, string vaultName, string location, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.PurgeDeletedAsync(Microsoft.Azure.Management.KeyVault.IVaultsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PurgeDeletedAsync : Microsoft.Azure.Management.KeyVault.IVaultsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions.PurgeDeletedAsync (operations, vaultName, location, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.KeyVault.VaultsOperationsExtensions/&lt;PurgeDeletedAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.KeyVault.IVaultsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4725d-198">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="4725d-198">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="4725d-199">論理削除された資格情報コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="4725d-199">The name of the soft-deleted vault.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="4725d-200">論理削除された資格情報コンテナーの場所です。</span><span class="sxs-lookup"><span data-stu-id="4725d-200">The location of the soft-deleted vault.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4725d-201">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4725d-201">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4725d-202">指定した資格情報コンテナーを完全に削除します。</span><span class="sxs-lookup"><span data-stu-id="4725d-202">Permanently deletes the specified vault.</span></span> <span data-ttu-id="4725d-203">別名が削除された Azure key vault を削除します。</span><span class="sxs-lookup"><span data-stu-id="4725d-203">aka Purges the deleted Azure key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>