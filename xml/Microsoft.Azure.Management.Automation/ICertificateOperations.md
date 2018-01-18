<Type Name="ICertificateOperations" FullName="Microsoft.Azure.Management.Automation.ICertificateOperations">
  <TypeSignature Language="C#" Value="public interface ICertificateOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICertificateOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.ICertificateOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICertificateOperations" />
  <TypeSignature Language="F#" Value="type ICertificateOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="04394-101">オートメーションの証明書をサービス操作。</span><span class="sxs-lookup"><span data-stu-id="04394-101">Service operation for automation certificates.</span></span>  <span data-ttu-id="04394-102">(詳細については http://aka.ms/azureautomationsdk/certificateoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="04394-102">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICertificateOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateResponse&gt;" Usage="iCertificateOperations.CreateOrUpdateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.CertificateCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="04394-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="04394-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="04394-104">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="04394-104">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="04394-105">証明書の作成または更新の操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="04394-105">The parameters supplied to the create or update certificate operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="04394-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="04394-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04394-107">証明書を作成します。</span><span class="sxs-lookup"><span data-stu-id="04394-107">Create a certificate.</span></span>  <span data-ttu-id="04394-108">(詳細については http://aka.ms/azureautomationsdk/certificateoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="04394-108">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="04394-109">証明書の作成または更新の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="04394-109">The response model for the create or update certificate operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string automationAccount, string certificateName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string automationAccount, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICertificateOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iCertificateOperations.DeleteAsync (resourceGroupName, automationAccount, certificateName, cancellationToken)" />
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
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="04394-110">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="04394-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="04394-111">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="04394-111">The automation account name.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="04394-112">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="04394-112">The name of certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="04394-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="04394-113">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04394-114">証明書を削除します。</span><span class="sxs-lookup"><span data-stu-id="04394-114">Delete the certificate.</span></span>  <span data-ttu-id="04394-115">(詳細については http://aka.ms/azureautomationsdk/certificateoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="04394-115">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="04394-116">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="04394-116">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string certificateName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CertificateGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICertificateOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateGetResponse&gt;" Usage="iCertificateOperations.GetAsync (resourceGroupName, automationAccount, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="04394-117">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="04394-117">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="04394-118">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="04394-118">The automation account name.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="04394-119">証明書の名前。</span><span class="sxs-lookup"><span data-stu-id="04394-119">The name of certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="04394-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="04394-120">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04394-121">証明書の名前によって識別される証明書を取得します。</span><span class="sxs-lookup"><span data-stu-id="04394-121">Retrieve the certificate identified by certificate name.</span></span>  <span data-ttu-id="04394-122">(詳細については http://aka.ms/azureautomationsdk/certificateoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="04394-122">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="04394-123">証明書の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="04394-123">The response model for the get certificate operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICertificateOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt;" Usage="iCertificateOperations.ListAsync (resourceGroupName, automationAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="04394-124">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="04394-124">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="04394-125">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="04394-125">The automation account name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="04394-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="04394-126">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04394-127">証明書の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="04394-127">Retrieve a list of certificates.</span></span>  <span data-ttu-id="04394-128">(詳細については http://aka.ms/azureautomationsdk/certificateoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="04394-128">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="04394-129">一覧の証明書の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="04394-129">The response model for the list certificate operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICertificateOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt;" Usage="iCertificateOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CertificateListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="04394-130">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="04394-130">The link to retrieve next set of items.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="04394-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="04394-131">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04394-132">証明書の [次へ] の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="04394-132">Retrieve next list of certificates.</span></span>  <span data-ttu-id="04394-133">(詳細については http://aka.ms/azureautomationsdk/certificateoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="04394-133">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="04394-134">一覧の証明書の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="04394-134">The response model for the list certificate operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; PatchAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.CertificatePatchParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; PatchAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.CertificatePatchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ICertificateOperations.PatchAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.CertificatePatchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchAsync : string * string * Microsoft.Azure.Management.Automation.Models.CertificatePatchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iCertificateOperations.PatchAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
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
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.CertificatePatchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="04394-135">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="04394-135">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="04394-136">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="04394-136">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="04394-137">証明書の更新プログラムの操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="04394-137">The parameters supplied to the patch certificate operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="04394-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="04394-138">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="04394-139">証明書を更新します。</span><span class="sxs-lookup"><span data-stu-id="04394-139">Update a certificate.</span></span>  <span data-ttu-id="04394-140">(詳細については http://aka.ms/azureautomationsdk/certificateoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="04394-140">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="04394-141">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="04394-141">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>