<Type Name="IVaultExtendedInfoOperations" FullName="Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations">
  <TypeSignature Language="C#" Value="public interface IVaultExtendedInfoOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVaultExtendedInfoOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVaultExtendedInfoOperations" />
  <TypeSignature Language="F#" Value="type IVaultExtendedInfoOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c6a0e-101">VaultExtendedInfoOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="c6a0e-101">VaultExtendedInfoOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string vaultName, Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource resourceResourceExtendedInfoDetails, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string vaultName, class Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource resourceResourceExtendedInfoDetails, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource&gt;&gt;" Usage="iVaultExtendedInfoOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, vaultName, resourceResourceExtendedInfoDetails, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceResourceExtendedInfoDetails" Type="Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c6a0e-102">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="c6a0e-102">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="c6a0e-103">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="c6a0e-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceResourceExtendedInfoDetails">
            <span data-ttu-id="c6a0e-104">resourceResourceExtendedInfoDetails</span><span class="sxs-lookup"><span data-stu-id="c6a0e-104">resourceResourceExtendedInfoDetails</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c6a0e-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c6a0e-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c6a0e-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c6a0e-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a0e-107">拡張情報を資格情報コンテナーを作成します。</span><span class="sxs-lookup"><span data-stu-id="c6a0e-107">Create vault extended info.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c6a0e-108">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c6a0e-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c6a0e-109">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c6a0e-109">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c6a0e-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c6a0e-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string vaultName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string vaultName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource&gt;&gt;" Usage="iVaultExtendedInfoOperations.GetWithHttpMessagesAsync (resourceGroupName, vaultName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c6a0e-111">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="c6a0e-111">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="c6a0e-112">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="c6a0e-112">The name of the recovery services vault.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c6a0e-113">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c6a0e-113">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c6a0e-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c6a0e-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a0e-115">資格情報コンテナー情報の拡張を取得します。</span><span class="sxs-lookup"><span data-stu-id="c6a0e-115">Get the vault extended info.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c6a0e-116">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c6a0e-116">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c6a0e-117">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c6a0e-117">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c6a0e-118">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c6a0e-118">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string vaultName, Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource resourceResourceExtendedInfoDetails, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string vaultName, class Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource resourceResourceExtendedInfoDetails, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.IVaultExtendedInfoOperations.UpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource&gt;&gt;" Usage="iVaultExtendedInfoOperations.UpdateWithHttpMessagesAsync (resourceGroupName, vaultName, resourceResourceExtendedInfoDetails, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceResourceExtendedInfoDetails" Type="Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c6a0e-119">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="c6a0e-119">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="c6a0e-120">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="c6a0e-120">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceResourceExtendedInfoDetails">
            <span data-ttu-id="c6a0e-121">resourceResourceExtendedInfoDetails</span><span class="sxs-lookup"><span data-stu-id="c6a0e-121">resourceResourceExtendedInfoDetails</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c6a0e-122">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c6a0e-122">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c6a0e-123">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c6a0e-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c6a0e-124">資格情報コンテナーの拡張情報を更新します。</span><span class="sxs-lookup"><span data-stu-id="c6a0e-124">Update vault extended info.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c6a0e-125">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c6a0e-125">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c6a0e-126">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c6a0e-126">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c6a0e-127">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c6a0e-127">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>