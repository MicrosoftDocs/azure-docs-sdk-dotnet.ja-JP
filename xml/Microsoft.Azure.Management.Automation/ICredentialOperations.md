<Type Name="ICredentialOperations" FullName="Microsoft.Azure.Management.Automation.ICredentialOperations">
  <TypeSignature Language="C#" Value="public interface ICredentialOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICredentialOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.ICredentialOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICredentialOperations" />
  <TypeSignature Language="F#" Value="type ICredentialOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f9518-101">Automation の資格情報をサービス操作。</span><span class="sxs-lookup"><span data-stu-id="f9518-101">Service operation for automation credentials.</span></span>  <span data-ttu-id="f9518-102">(詳細については http://aka.ms/azureautomationsdk/credentialoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="f9518-102">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICredentialOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateResponse&gt;" Usage="iCredentialOperations.CreateOrUpdateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f9518-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="f9518-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="f9518-104">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="f9518-104">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f9518-105">作成または更新の資格情報の操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="f9518-105">The parameters supplied to the create or update credential operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f9518-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f9518-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9518-107">資格情報を作成します。</span><span class="sxs-lookup"><span data-stu-id="f9518-107">Create a credential.</span></span>  <span data-ttu-id="f9518-108">(詳細については http://aka.ms/azureautomationsdk/credentialoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="f9518-108">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f9518-109">作成または更新の資格情報の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="f9518-109">The response model for the create or update credential operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string automationAccount, string credentialName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string automationAccount, string credentialName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICredentialOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iCredentialOperations.DeleteAsync (resourceGroupName, automationAccount, credentialName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f9518-110">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="f9518-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="f9518-111">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="f9518-111">The automation account name.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="f9518-112">資格情報の名前。</span><span class="sxs-lookup"><span data-stu-id="f9518-112">The name of credential.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f9518-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f9518-113">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9518-114">資格情報を削除します。</span><span class="sxs-lookup"><span data-stu-id="f9518-114">Delete the credential.</span></span>  <span data-ttu-id="f9518-115">(詳細については http://aka.ms/azureautomationsdk/credentialoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="f9518-115">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f9518-116">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="f9518-116">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string credentialName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CredentialGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string credentialName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICredentialOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialGetResponse&gt;" Usage="iCredentialOperations.GetAsync (resourceGroupName, automationAccount, credentialName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f9518-117">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="f9518-117">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="f9518-118">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="f9518-118">The automation account name.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="f9518-119">資格情報の名前。</span><span class="sxs-lookup"><span data-stu-id="f9518-119">The name of credential.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f9518-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f9518-120">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9518-121">資格情報の名前によって識別される資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="f9518-121">Retrieve the credential identified by credential name.</span></span>  <span data-ttu-id="f9518-122">(詳細については http://aka.ms/azureautomationsdk/credentialoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="f9518-122">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f9518-123">資格情報の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="f9518-123">The response model for the get credential operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CredentialListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICredentialOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialListResponse&gt;" Usage="iCredentialOperations.ListAsync (resourceGroupName, automationAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f9518-124">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="f9518-124">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="f9518-125">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="f9518-125">The automation account name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f9518-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f9518-126">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9518-127">資格情報の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="f9518-127">Retrieve a list of credentials.</span></span>  <span data-ttu-id="f9518-128">(詳細については http://aka.ms/azureautomationsdk/credentialoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="f9518-128">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f9518-129">一覧の資格情報の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="f9518-129">The response model for the list credential operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CredentialListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICredentialOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialListResponse&gt;" Usage="iCredentialOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="f9518-130">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="f9518-130">The link to retrieve next set of items.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f9518-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f9518-131">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9518-132">資格情報の次の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="f9518-132">Retrieve next list of credentials.</span></span>  <span data-ttu-id="f9518-133">(詳細については http://aka.ms/azureautomationsdk/credentialoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="f9518-133">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f9518-134">一覧の資格情報の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="f9518-134">The response model for the list credential operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; PatchAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.CredentialPatchParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; PatchAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.CredentialPatchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICredentialOperations.PatchAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.CredentialPatchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchAsync : string * string * Microsoft.Azure.Management.Automation.Models.CredentialPatchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iCredentialOperations.PatchAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.CredentialPatchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f9518-135">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="f9518-135">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="f9518-136">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="f9518-136">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f9518-137">Patch 資格情報の操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="f9518-137">The parameters supplied to the patch credential operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f9518-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f9518-138">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f9518-139">資格情報を更新します。</span><span class="sxs-lookup"><span data-stu-id="f9518-139">Update a credential.</span></span>  <span data-ttu-id="f9518-140">(詳細については http://aka.ms/azureautomationsdk/credentialoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="f9518-140">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f9518-141">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="f9518-141">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>