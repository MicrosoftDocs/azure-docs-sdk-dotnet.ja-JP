<Type Name="VaultOperationsExtensions" FullName="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VaultOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VaultOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VaultOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VaultOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse CreateOrUpdate (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters parameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse CreateOrUpdate(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters parameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, resourceName, parameters, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c1f5b-101">Microsoft.Azure.Management.BackupServices.IVaultOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-101">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c1f5b-102">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-102">Required.</span></span> <span data-ttu-id="c1f5b-103">所属する資格情報コンテナーにリソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="c1f5b-103">The name of resource group to which vault belongs</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="c1f5b-104">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-104">Required.</span></span> <span data-ttu-id="c1f5b-105">資格情報コンテナーの名前</span><span class="sxs-lookup"><span data-stu-id="c1f5b-105">The name of the vault</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c1f5b-106">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-106">Required.</span></span> <span data-ttu-id="c1f5b-107">パラメーターを作成または資格情報コンテナーの更新</span><span class="sxs-lookup"><span data-stu-id="c1f5b-107">Parameters to create or update the vault</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="c1f5b-108">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-108">Optional.</span></span> <span data-ttu-id="c1f5b-109">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-109">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1f5b-110">新しい Azure バックアップ コンテナーを作成します。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-110">Creates a new Azure backup vault.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c1f5b-111">資格情報コンテナー情報です。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-111">Vault information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters parameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters parameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, resourceName, parameters, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultCreateOrUpdateParameters" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c1f5b-112">Microsoft.Azure.Management.BackupServices.IVaultOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-112">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c1f5b-113">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-113">Required.</span></span> <span data-ttu-id="c1f5b-114">所属する資格情報コンテナーにリソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="c1f5b-114">The name of resource group to which vault belongs</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="c1f5b-115">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-115">Required.</span></span> <span data-ttu-id="c1f5b-116">資格情報コンテナーの名前</span><span class="sxs-lookup"><span data-stu-id="c1f5b-116">The name of the vault</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c1f5b-117">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-117">Required.</span></span> <span data-ttu-id="c1f5b-118">パラメーターを作成または資格情報コンテナーの更新</span><span class="sxs-lookup"><span data-stu-id="c1f5b-118">Parameters to create or update the vault</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="c1f5b-119">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-119">Optional.</span></span> <span data-ttu-id="c1f5b-120">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-120">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1f5b-121">新しい Azure バックアップ コンテナーを作成します。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-121">Creates a new Azure backup vault.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c1f5b-122">資格情報コンテナー情報です。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-122">Vault information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse Delete (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse Delete(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.Delete(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.Delete (operations, resourceGroupName, resourceName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c1f5b-123">Microsoft.Azure.Management.BackupServices.IVaultOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-123">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c1f5b-124">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-124">Required.</span></span> <span data-ttu-id="c1f5b-125">所属する資格情報コンテナーにリソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="c1f5b-125">The name of resource group to which vault belongs</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="c1f5b-126">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-126">Required.</span></span> <span data-ttu-id="c1f5b-127">資格情報コンテナーの名前</span><span class="sxs-lookup"><span data-stu-id="c1f5b-127">The name of the vault</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="c1f5b-128">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-128">Optional.</span></span> <span data-ttu-id="c1f5b-129">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-129">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1f5b-130">指定された Azure バックアップ コンテナーを削除します。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-130">Deletes the specified Azure backup vault.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c1f5b-131">資格情報コンテナー情報です。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-131">Vault information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; DeleteAsync (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; DeleteAsync(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.DeleteAsync (operations, resourceGroupName, resourceName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c1f5b-132">Microsoft.Azure.Management.BackupServices.IVaultOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-132">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c1f5b-133">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-133">Required.</span></span> <span data-ttu-id="c1f5b-134">所属する資格情報コンテナーにリソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="c1f5b-134">The name of resource group to which vault belongs</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="c1f5b-135">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-135">Required.</span></span> <span data-ttu-id="c1f5b-136">資格情報コンテナーの名前</span><span class="sxs-lookup"><span data-stu-id="c1f5b-136">The name of the vault</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="c1f5b-137">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-137">Optional.</span></span> <span data-ttu-id="c1f5b-138">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-138">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1f5b-139">指定された Azure バックアップ コンテナーを削除します。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-139">Deletes the specified Azure backup vault.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c1f5b-140">資格情報コンテナー情報です。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-140">Vault information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse Get (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse Get(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.Get(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.Get (operations, resourceGroupName, resourceName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c1f5b-141">Microsoft.Azure.Management.BackupServices.IVaultOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-141">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c1f5b-142">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-142">Required.</span></span> <span data-ttu-id="c1f5b-143">所属する資格情報コンテナーにリソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="c1f5b-143">The name of resource group to which vault belongs</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="c1f5b-144">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-144">Required.</span></span> <span data-ttu-id="c1f5b-145">資格情報コンテナーの名前</span><span class="sxs-lookup"><span data-stu-id="c1f5b-145">The name of the vault</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="c1f5b-146">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-146">Optional.</span></span> <span data-ttu-id="c1f5b-147">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-147">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1f5b-148">指定した Azure key vault を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-148">Gets the specified Azure key vault.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c1f5b-149">資格情報コンテナー情報です。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-149">Vault information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; GetAsync (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt; GetAsync(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.GetAsync(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.GetAsync (operations, resourceGroupName, resourceName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c1f5b-150">Microsoft.Azure.Management.BackupServices.IVaultOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-150">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c1f5b-151">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-151">Required.</span></span> <span data-ttu-id="c1f5b-152">所属する資格情報コンテナーにリソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="c1f5b-152">The name of resource group to which vault belongs</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="c1f5b-153">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-153">Required.</span></span> <span data-ttu-id="c1f5b-154">資格情報コンテナーの名前</span><span class="sxs-lookup"><span data-stu-id="c1f5b-154">The name of the vault</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="c1f5b-155">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-155">Optional.</span></span> <span data-ttu-id="c1f5b-156">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-156">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1f5b-157">指定した Azure key vault を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-157">Gets the specified Azure key vault.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c1f5b-158">資格情報コンテナー情報です。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-158">Vault information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetResourceStorageConfig">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse GetResourceStorageConfig (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse GetResourceStorageConfig(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.GetResourceStorageConfig(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetResourceStorageConfig : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.GetResourceStorageConfig (operations, resourceGroupName, resourceName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c1f5b-159">Microsoft.Azure.Management.BackupServices.IVaultOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-159">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c1f5b-160">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-160">Required.</span></span> <span data-ttu-id="c1f5b-161">所属する資格情報コンテナーにリソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="c1f5b-161">The name of resource group to which vault belongs</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="c1f5b-162">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-162">Required.</span></span> <span data-ttu-id="c1f5b-163">資格情報コンテナーの名前</span><span class="sxs-lookup"><span data-stu-id="c1f5b-163">The name of the vault</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="c1f5b-164">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-164">Optional.</span></span> <span data-ttu-id="c1f5b-165">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-165">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1f5b-166">リソースの記憶域構成をフェッチします。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-166">Fetches resource storage config.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c1f5b-167">Get リソース記憶域構成の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-167">The definition of a get resource storage config response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetResourceStorageConfigAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt; GetResourceStorageConfigAsync (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt; GetResourceStorageConfigAsync(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.GetResourceStorageConfigAsync(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetResourceStorageConfigAsync : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.GetResourceStorageConfigAsync (operations, resourceGroupName, resourceName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.GetResourceStorageConfigResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c1f5b-168">Microsoft.Azure.Management.BackupServices.IVaultOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-168">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c1f5b-169">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-169">Required.</span></span> <span data-ttu-id="c1f5b-170">所属する資格情報コンテナーにリソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="c1f5b-170">The name of resource group to which vault belongs</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="c1f5b-171">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-171">Required.</span></span> <span data-ttu-id="c1f5b-172">資格情報コンテナーの名前</span><span class="sxs-lookup"><span data-stu-id="c1f5b-172">The name of the vault</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="c1f5b-173">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-173">Optional.</span></span> <span data-ttu-id="c1f5b-174">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-174">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1f5b-175">リソースの記憶域構成をフェッチします。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-175">Fetches resource storage config.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c1f5b-176">Get リソース記憶域構成の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-176">The definition of a get resource storage config response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse List (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, int top, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse List(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, int32 top, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.List(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.Int32,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.BackupServices.IVaultOperations * int * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.List (operations, top, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c1f5b-177">Microsoft.Azure.Management.BackupServices.IVaultOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-177">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="c1f5b-178">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-178">Required.</span></span> <span data-ttu-id="c1f5b-179">返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-179">Maximum number of results to return.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="c1f5b-180">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-180">Optional.</span></span> <span data-ttu-id="c1f5b-181">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-181">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1f5b-182">サブスクリプションに関連付けられているバックアップ資格情報コンテナーの情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-182">Gets information of the backup vaults associated with subscription.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c1f5b-183">資格情報コンテナーの一覧</span><span class="sxs-lookup"><span data-stu-id="c1f5b-183">List of vaults</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListAsync (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, int top, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListAsync(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, int32 top, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.ListAsync(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.Int32,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.BackupServices.IVaultOperations * int * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.ListAsync (operations, top, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c1f5b-184">Microsoft.Azure.Management.BackupServices.IVaultOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-184">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="c1f5b-185">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-185">Required.</span></span> <span data-ttu-id="c1f5b-186">返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-186">Maximum number of results to return.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="c1f5b-187">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-187">Optional.</span></span> <span data-ttu-id="c1f5b-188">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-188">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1f5b-189">サブスクリプションに関連付けられているバックアップ資格情報コンテナーの情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-189">Gets information of the backup vaults associated with subscription.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c1f5b-190">資格情報コンテナーの一覧</span><span class="sxs-lookup"><span data-stu-id="c1f5b-190">List of vaults</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse ListByResourceGroup (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, int top, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse ListByResourceGroup(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, int32 top, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.Int32,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * int * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, top, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c1f5b-191">Microsoft.Azure.Management.BackupServices.IVaultOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-191">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c1f5b-192">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-192">Optional.</span></span> <span data-ttu-id="c1f5b-193">返される資格情報コンテナーのセットを制限するリソース グループの名前を指定する省略可能な引数。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-193">An optional argument which specifies the name of the resource group that constrains the set of vaults that are returned.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="c1f5b-194">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-194">Required.</span></span> <span data-ttu-id="c1f5b-195">返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-195">Maximum number of results to return.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="c1f5b-196">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-196">Optional.</span></span> <span data-ttu-id="c1f5b-197">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-197">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1f5b-198">リソース グループに関連付けられているバックアップ資格情報コンテナーの情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-198">Gets information of the backup vaults associated with resource group.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c1f5b-199">資格情報コンテナーの一覧</span><span class="sxs-lookup"><span data-stu-id="c1f5b-199">List of vaults</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, int top, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, int32 top, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.Int32,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * int * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, top, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.AzureBackupVaultListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c1f5b-200">Microsoft.Azure.Management.BackupServices.IVaultOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-200">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c1f5b-201">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-201">Optional.</span></span> <span data-ttu-id="c1f5b-202">返される資格情報コンテナーのセットを制限するリソース グループの名前を指定する省略可能な引数。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-202">An optional argument which specifies the name of the resource group that constrains the set of vaults that are returned.</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="c1f5b-203">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-203">Required.</span></span> <span data-ttu-id="c1f5b-204">返される結果の最大数。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-204">Maximum number of results to return.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="c1f5b-205">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-205">Optional.</span></span> <span data-ttu-id="c1f5b-206">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-206">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1f5b-207">リソース グループに関連付けられているバックアップ資格情報コンテナーの情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-207">Gets information of the backup vaults associated with resource group.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c1f5b-208">資格情報コンテナーの一覧</span><span class="sxs-lookup"><span data-stu-id="c1f5b-208">List of vaults</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateStorageType">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.OperationResponse UpdateStorageType (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest updateVaultStorageTypeRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.OperationResponse UpdateStorageType(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest updateVaultStorageTypeRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.UpdateStorageType(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateStorageType : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.OperationResponse" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.UpdateStorageType (operations, resourceGroupName, resourceName, updateVaultStorageTypeRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.OperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="updateVaultStorageTypeRequest" Type="Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c1f5b-209">Microsoft.Azure.Management.BackupServices.IVaultOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-209">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c1f5b-210">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-210">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="c1f5b-211">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-211">Required.</span></span>
            </param>
        <param name="updateVaultStorageTypeRequest">
            <span data-ttu-id="c1f5b-212">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-212">Required.</span></span> <span data-ttu-id="c1f5b-213">資格情報コンテナーの記憶域の種類の更新の要求</span><span class="sxs-lookup"><span data-stu-id="c1f5b-213">Update Vault Storage Type Request</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="c1f5b-214">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-214">Optional.</span></span> <span data-ttu-id="c1f5b-215">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-215">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1f5b-216">更新プログラムには、ストレージ モデルの種類が資格情報コンテナーします。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-216">Updates vault storage model type.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c1f5b-217">操作の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-217">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateStorageTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UpdateStorageTypeAsync (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest updateVaultStorageTypeRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UpdateStorageTypeAsync(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest updateVaultStorageTypeRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.UpdateStorageTypeAsync(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateStorageTypeAsync : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.UpdateStorageTypeAsync (operations, resourceGroupName, resourceName, updateVaultStorageTypeRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="updateVaultStorageTypeRequest" Type="Microsoft.Azure.Management.BackupServices.Models.UpdateVaultStorageTypeRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c1f5b-218">Microsoft.Azure.Management.BackupServices.IVaultOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-218">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c1f5b-219">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-219">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="c1f5b-220">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-220">Required.</span></span>
            </param>
        <param name="updateVaultStorageTypeRequest">
            <span data-ttu-id="c1f5b-221">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-221">Required.</span></span> <span data-ttu-id="c1f5b-222">資格情報コンテナーの記憶域の種類の更新の要求</span><span class="sxs-lookup"><span data-stu-id="c1f5b-222">Update Vault Storage Type Request</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="c1f5b-223">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-223">Optional.</span></span> <span data-ttu-id="c1f5b-224">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-224">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1f5b-225">更新プログラムには、ストレージ モデルの種類が資格情報コンテナーします。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-225">Updates vault storage model type.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c1f5b-226">操作の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-226">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadCertificate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse UploadCertificate (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, string certificateName, Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest vaultCredUploadCertRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse UploadCertificate(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, string certificateName, class Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest vaultCredUploadCertRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.UploadCertificate(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UploadCertificate : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.UploadCertificate (operations, resourceGroupName, resourceName, certificateName, vaultCredUploadCertRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="vaultCredUploadCertRequest" Type="Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c1f5b-227">Microsoft.Azure.Management.BackupServices.IVaultOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-227">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c1f5b-228">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-228">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="c1f5b-229">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-229">Required.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c1f5b-230">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-230">Required.</span></span> <span data-ttu-id="c1f5b-231">証明書の名前です。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-231">Name of the certificate.</span></span>
            </param>
        <param name="vaultCredUploadCertRequest">
            <span data-ttu-id="c1f5b-232">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-232">Required.</span></span> <span data-ttu-id="c1f5b-233">証明書のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-233">Certificate parameters.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="c1f5b-234">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-234">Optional.</span></span> <span data-ttu-id="c1f5b-235">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-235">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1f5b-236">アップロードには、資格情報証明書が資格情報コンテナーします。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-236">Uploads vault credential certificate.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c1f5b-237">証明書の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-237">The definition of a certificate response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt; UploadCertificateAsync (this Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, string certificateName, Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest vaultCredUploadCertRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt; UploadCertificateAsync(class Microsoft.Azure.Management.BackupServices.IVaultOperations operations, string resourceGroupName, string resourceName, string certificateName, class Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest vaultCredUploadCertRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.UploadCertificateAsync(Microsoft.Azure.Management.BackupServices.IVaultOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UploadCertificateAsync : Microsoft.Azure.Management.BackupServices.IVaultOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.VaultOperationsExtensions.UploadCertificateAsync (operations, resourceGroupName, resourceName, certificateName, vaultCredUploadCertRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IVaultOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="vaultCredUploadCertRequest" Type="Microsoft.Azure.Management.BackupServices.Models.VaultCredUploadCertRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c1f5b-238">Microsoft.Azure.Management.BackupServices.IVaultOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-238">Reference to the Microsoft.Azure.Management.BackupServices.IVaultOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c1f5b-239">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-239">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="c1f5b-240">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-240">Required.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="c1f5b-241">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-241">Required.</span></span> <span data-ttu-id="c1f5b-242">証明書の名前です。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-242">Name of the certificate.</span></span>
            </param>
        <param name="vaultCredUploadCertRequest">
            <span data-ttu-id="c1f5b-243">必須。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-243">Required.</span></span> <span data-ttu-id="c1f5b-244">証明書のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-244">Certificate parameters.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="c1f5b-245">省略可能。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-245">Optional.</span></span> <span data-ttu-id="c1f5b-246">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-246">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c1f5b-247">アップロードには、資格情報証明書が資格情報コンテナーします。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-247">Uploads vault credential certificate.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c1f5b-248">証明書の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="c1f5b-248">The definition of a certificate response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>