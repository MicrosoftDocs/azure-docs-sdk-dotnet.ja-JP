<Type Name="ICSMProtectionPolicyOperations" FullName="Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations">
  <TypeSignature Language="C#" Value="public interface ICSMProtectionPolicyOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICSMProtectionPolicyOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICSMProtectionPolicyOperations" />
  <TypeSignature Language="F#" Value="type ICSMProtectionPolicyOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="bc7a4-101">Azure Backup の拡張機能の保護ポリシーの操作の定義。</span><span class="sxs-lookup"><span data-stu-id="bc7a4-101">Definition of Protection Policy operations for the Azure Backup extension.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; AddAsync (string resourceGroupName, string resourceName, string policyName, Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequest cSMAddProtectionPolicyRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; AddAsync(string resourceGroupName, string resourceName, string policyName, class Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequest cSMAddProtectionPolicyRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations.AddAsync(System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddAsync : string * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iCSMProtectionPolicyOperations.AddAsync (resourceGroupName, resourceName, policyName, cSMAddProtectionPolicyRequest, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="cSMAddProtectionPolicyRequest" Type="Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="policyName">
            <span data-ttu-id="bc7a4-102">保護ポリシーを更新する名前。</span><span class="sxs-lookup"><span data-stu-id="bc7a4-102">The protection policy Name to be updated.</span></span>
            </param>
        <param name="cSMAddProtectionPolicyRequest">
            <span data-ttu-id="bc7a4-103">保護ポリシーの作成要求。</span><span class="sxs-lookup"><span data-stu-id="bc7a4-103">The protection policy creation request.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="bc7a4-104">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="bc7a4-104">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bc7a4-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bc7a4-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bc7a4-106">新しい保護ポリシーを作成します。</span><span class="sxs-lookup"><span data-stu-id="bc7a4-106">Create new Protection Policy.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="bc7a4-107">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="bc7a4-107">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string resourceName, string policyName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string resourceName, string policyName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations.DeleteAsync(System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iCSMProtectionPolicyOperations.DeleteAsync (resourceGroupName, resourceName, policyName, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="policyName">
            <span data-ttu-id="bc7a4-108">保護ポリシーを削除する名前。</span><span class="sxs-lookup"><span data-stu-id="bc7a4-108">The protection policy Name to be deleted.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="bc7a4-109">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="bc7a4-109">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bc7a4-110">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bc7a4-110">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bc7a4-111">保護ポリシーを削除します。</span><span class="sxs-lookup"><span data-stu-id="bc7a4-111">Delete a Protection Policy.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="bc7a4-112">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="bc7a4-112">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyListOperationResponse&gt; ListAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyListOperationResponse&gt; ListAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyListOperationResponse&gt;" Usage="iCSMProtectionPolicyOperations.ListAsync (resourceGroupName, resourceName, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyListOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="customRequestHeaders">
            <span data-ttu-id="bc7a4-113">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="bc7a4-113">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bc7a4-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bc7a4-114">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bc7a4-115">すべての保護ポリシーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="bc7a4-115">Get the list of all Protection Policy.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="bc7a4-116">CSMProtectionPolicyListOperationResponse の定義。</span><span class="sxs-lookup"><span data-stu-id="bc7a4-116">The definition of a CSMProtectionPolicyListOperationResponse.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UpdateAsync (string resourceGroupName, string resourceName, string policyName, Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionPolicyRequest cSMUpdateProtectionPolicyRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UpdateAsync(string resourceGroupName, string resourceName, string policyName, class Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionPolicyRequest cSMUpdateProtectionPolicyRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations.UpdateAsync(System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionPolicyRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : string * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionPolicyRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iCSMProtectionPolicyOperations.UpdateAsync (resourceGroupName, resourceName, policyName, cSMUpdateProtectionPolicyRequest, customRequestHeaders, cancellationToken)" />
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
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="cSMUpdateProtectionPolicyRequest" Type="Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionPolicyRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="policyName">
            <span data-ttu-id="bc7a4-117">保護ポリシーを更新する名前。</span><span class="sxs-lookup"><span data-stu-id="bc7a4-117">The protection policy Name to be updated.</span></span>
            </param>
        <param name="cSMUpdateProtectionPolicyRequest">
            <span data-ttu-id="bc7a4-118">保護ポリシーの作成要求。</span><span class="sxs-lookup"><span data-stu-id="bc7a4-118">The protection policy creation request.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="bc7a4-119">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="bc7a4-119">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bc7a4-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="bc7a4-120">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bc7a4-121">保護ポリシーを更新します。</span><span class="sxs-lookup"><span data-stu-id="bc7a4-121">Update Protection Policy.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="bc7a4-122">操作の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="bc7a4-122">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>