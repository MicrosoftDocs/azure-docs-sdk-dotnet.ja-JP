<Type Name="IAutomationAccountOperations" FullName="Microsoft.Azure.Management.Automation.IAutomationAccountOperations">
  <TypeSignature Language="C#" Value="public interface IAutomationAccountOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAutomationAccountOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IAutomationAccountOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAutomationAccountOperations" />
  <TypeSignature Language="F#" Value="type IAutomationAccountOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d61e4-101">オートメーション アカウントのサービス操作。</span><span class="sxs-lookup"><span data-stu-id="d61e4-101">Service operation for automation accounts.</span></span>  <span data-ttu-id="d61e4-102">(詳細については http://aka.ms/azureautomationsdk/automationaccountoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="d61e4-102">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, class Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IAutomationAccountOperations.CreateOrUpdateAsync(System.String,Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateResponse&gt;" Usage="iAutomationAccountOperations.CreateOrUpdateAsync (resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d61e4-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="d61e4-103">The name of the resource group</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d61e4-104">作成または更新のオートメーション アカウントに指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="d61e4-104">Parameters supplied to the create or update automation account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d61e4-105">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d61e4-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d61e4-106">Automation アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="d61e4-106">Create an automation account.</span></span>  <span data-ttu-id="d61e4-107">(詳細については http://aka.ms/azureautomationsdk/automationaccountoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="d61e4-107">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d61e4-108">アカウントの作成または更新の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="d61e4-108">The response model for the create or update account operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string automationAccountName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string automationAccountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IAutomationAccountOperations.DeleteAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iAutomationAccountOperations.DeleteAsync (resourceGroupName, automationAccountName, cancellationToken)" />
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
        <Parameter Name="automationAccountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d61e4-109">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="d61e4-109">The name of the resource group</span></span>
            </param>
        <param name="automationAccountName">
            <span data-ttu-id="d61e4-110">オートメーション アカウントの名前です。</span><span class="sxs-lookup"><span data-stu-id="d61e4-110">Automation account name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d61e4-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d61e4-111">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d61e4-112">Automation アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="d61e4-112">Create an automation account.</span></span>  <span data-ttu-id="d61e4-113">(詳細については http://aka.ms/azureautomationsdk/automationaccountoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="d61e4-113">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d61e4-114">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="d61e4-114">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.AutomationAccountGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IAutomationAccountOperations.GetAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountGetResponse&gt;" Usage="iAutomationAccountOperations.GetAsync (resourceGroupName, automationAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d61e4-115">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="d61e4-115">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="d61e4-116">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d61e4-116">The automation account name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d61e4-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d61e4-117">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d61e4-118">アカウントのアカウント名を取得します。</span><span class="sxs-lookup"><span data-stu-id="d61e4-118">Retrieve the account by account name.</span></span>  <span data-ttu-id="d61e4-119">(詳細については http://aka.ms/azureautomationsdk/automationaccountoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="d61e4-119">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d61e4-120">アカウントの取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="d61e4-120">The response model for the get account operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt; ListAsync (string resourceGroupName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt; ListAsync(string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IAutomationAccountOperations.ListAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt;" Usage="iAutomationAccountOperations.ListAsync (resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d61e4-121">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="d61e4-121">The name of the resource group</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d61e4-122">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d61e4-122">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d61e4-123">アカウントの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="d61e4-123">Retrieve a list of accounts.</span></span>  <span data-ttu-id="d61e4-124">(詳細については http://aka.ms/azureautomationsdk/automationaccountoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="d61e4-124">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d61e4-125">アカウントの一覧の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="d61e4-125">The response model for the list account operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IAutomationAccountOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt;" Usage="iAutomationAccountOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="d61e4-126">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="d61e4-126">The link to retrieve next set of items.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d61e4-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d61e4-127">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d61e4-128">アカウントの [次へ] の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="d61e4-128">Retrieve next list of accounts.</span></span>  <span data-ttu-id="d61e4-129">(詳細については http://aka.ms/azureautomationsdk/automationaccountoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="d61e4-129">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d61e4-130">アカウントの一覧の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="d61e4-130">The response model for the list account operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchResponse&gt; PatchAsync (string resourceGroupName, Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchResponse&gt; PatchAsync(string resourceGroupName, class Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IAutomationAccountOperations.PatchAsync(System.String,Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchAsync : string * Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchResponse&gt;" Usage="iAutomationAccountOperations.PatchAsync (resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d61e4-131">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="d61e4-131">The name of the resource group</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d61e4-132">修正プログラムのオートメーション アカウントに指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="d61e4-132">Parameters supplied to the patch automation account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d61e4-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d61e4-133">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d61e4-134">Automation アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="d61e4-134">Create an automation account.</span></span>  <span data-ttu-id="d61e4-135">(詳細については http://aka.ms/azureautomationsdk/automationaccountoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="d61e4-135">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d61e4-136">アカウントの作成操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="d61e4-136">The response model for the create account operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>