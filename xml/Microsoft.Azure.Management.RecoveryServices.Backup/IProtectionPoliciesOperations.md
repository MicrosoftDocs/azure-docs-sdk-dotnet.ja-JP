<Type Name="IProtectionPoliciesOperations" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations">
  <TypeSignature Language="C#" Value="public interface IProtectionPoliciesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IProtectionPoliciesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IProtectionPoliciesOperations" />
  <TypeSignature Language="F#" Value="type IProtectionPoliciesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0d228-101">ProtectionPoliciesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="0d228-101">ProtectionPoliciesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string vaultName, string resourceGroupName, string policyName, Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string vaultName, string resourceGroupName, string policyName, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;&gt;" Usage="iProtectionPoliciesOperations.CreateOrUpdateWithHttpMessagesAsync (vaultName, resourceGroupName, policyName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultName">
            <span data-ttu-id="0d228-102">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="0d228-102">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0d228-103">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="0d228-103">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="policyName">
            <span data-ttu-id="0d228-104">バックアップのポリシーを作成します。</span><span class="sxs-lookup"><span data-stu-id="0d228-104">Backup policy to be created.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="0d228-105">バックアップ ポリシーのリソース</span><span class="sxs-lookup"><span data-stu-id="0d228-105">resource backup policy</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="0d228-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="0d228-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0d228-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0d228-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0d228-108">作成するか、バックアップ ポリシーを変更します。</span><span class="sxs-lookup"><span data-stu-id="0d228-108">Creates or modifies a backup policy.</span></span> <span data-ttu-id="0d228-109">これは非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="0d228-109">This is an asynchronous operation.</span></span> <span data-ttu-id="0d228-110">GetPolicyOperationResult API を使用して、操作の状態を取得できます。</span><span class="sxs-lookup"><span data-stu-id="0d228-110">Status of the operation can be fetched using GetPolicyOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="0d228-111">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0d228-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="0d228-112">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0d228-112">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0d228-113">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0d228-113">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string vaultName, string resourceGroupName, string policyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string vaultName, string resourceGroupName, string policyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iProtectionPoliciesOperations.DeleteWithHttpMessagesAsync (vaultName, resourceGroupName, policyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultName">
            <span data-ttu-id="0d228-114">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="0d228-114">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0d228-115">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="0d228-115">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="policyName">
            <span data-ttu-id="0d228-116">削除するバックアップ ポリシー。</span><span class="sxs-lookup"><span data-stu-id="0d228-116">Backup policy to be deleted.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="0d228-117">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="0d228-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0d228-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0d228-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0d228-119">指定された、Recovery Services コンテナーからのバックアップ ポリシーを削除します。</span><span class="sxs-lookup"><span data-stu-id="0d228-119">Deletes specified backup policy from your Recovery Services Vault.</span></span>
            <span data-ttu-id="0d228-120">これは非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="0d228-120">This is an asynchronous operation.</span></span> <span data-ttu-id="0d228-121">GetPolicyOperationResult API を使用して、操作の状態を取得できます。</span><span class="sxs-lookup"><span data-stu-id="0d228-121">Status of the operation can be fetched using GetPolicyOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="0d228-122">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0d228-122">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0d228-123">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0d228-123">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;&gt; GetWithHttpMessagesAsync (string vaultName, string resourceGroupName, string policyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;&gt; GetWithHttpMessagesAsync(string vaultName, string resourceGroupName, string policyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionPoliciesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;&gt;" Usage="iProtectionPoliciesOperations.GetWithHttpMessagesAsync (vaultName, resourceGroupName, policyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultName">
            <span data-ttu-id="0d228-124">Recovery services コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="0d228-124">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="0d228-125">リソース グループが、recovery services コンテナーの名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="0d228-125">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="policyName">
            <span data-ttu-id="0d228-126">フェッチするバックアップ ポリシーの情報です。</span><span class="sxs-lookup"><span data-stu-id="0d228-126">Backup policy information to be fetched.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="0d228-127">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="0d228-127">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="0d228-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="0d228-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="0d228-129">Recovery Services コンテナーに関連付けられているバックアップ ポリシーの詳細を提供します。</span><span class="sxs-lookup"><span data-stu-id="0d228-129">Provides the details of the backup policies associated to Recovery Services Vault.</span></span> <span data-ttu-id="0d228-130">これは非同期操作です。</span><span class="sxs-lookup"><span data-stu-id="0d228-130">This is an asynchronous operation.</span></span> <span data-ttu-id="0d228-131">GetPolicyOperationResult API を使用して、操作の状態を取得できます。</span><span class="sxs-lookup"><span data-stu-id="0d228-131">Status of the operation can be fetched using GetPolicyOperationResult API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="0d228-132">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0d228-132">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="0d228-133">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0d228-133">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0d228-134">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="0d228-134">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>