<Type Name="IRunbookOperations" FullName="Microsoft.Azure.Management.Automation.IRunbookOperations">
  <TypeSignature Language="C#" Value="public interface IRunbookOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRunbookOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IRunbookOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRunbookOperations" />
  <TypeSignature Language="F#" Value="type IRunbookOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4d4c5-101">Automation の runbook のサービス操作。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-101">Service operation for automation runbooks.</span></span>  <span data-ttu-id="4d4c5-102">(詳細については http://aka.ms/azureautomationsdk/runbookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="4d4c5-102">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt; ContentAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt; ContentAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookOperations.ContentAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContentAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt;" Usage="iRunbookOperations.ContentAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4d4c5-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="4d4c5-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="4d4c5-104">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-104">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="4d4c5-105">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-105">The runbook name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d4c5-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d4c5-107">Runbook 名によって識別される runbook の内容を取得します。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-107">Retrieve the content of runbook identified by runbook name.</span></span>  <span data-ttu-id="4d4c5-108">(詳細については http://aka.ms/azureautomationsdk/runbookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="4d4c5-108">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4d4c5-109">Runbook のコンテンツ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-109">The response model for the runbook content operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt;" Usage="iRunbookOperations.CreateOrUpdateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4d4c5-110">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="4d4c5-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="4d4c5-111">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-111">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4d4c5-112">Runbook の作成または更新パラメーター。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-112">The create or update parameters for runbook.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d4c5-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-113">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d4c5-114">Runbook 名によって識別される runbook を作成します。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-114">Create the runbook identified by runbook name.</span></span>  <span data-ttu-id="4d4c5-115">(詳細については http://aka.ms/azureautomationsdk/runbookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="4d4c5-115">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4d4c5-116">Runbook の応答モデルでは、応答を作成します。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-116">The response model for the runbook create response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithDraftAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt; CreateOrUpdateWithDraftAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt; CreateOrUpdateWithDraftAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookOperations.CreateOrUpdateWithDraftAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithDraftAsync : string * string * Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt;" Usage="iRunbookOperations.CreateOrUpdateWithDraftAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4d4c5-117">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="4d4c5-117">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="4d4c5-118">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-118">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4d4c5-119">Runbook の作成または更新パラメーター。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-119">The create or update parameters for runbook.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d4c5-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-120">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d4c5-121">Runbook 名によって識別される runbook を作成します。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-121">Create the runbook identified by runbook name.</span></span>  <span data-ttu-id="4d4c5-122">(詳細については http://aka.ms/azureautomationsdk/runbookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="4d4c5-122">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4d4c5-123">Runbook の応答モデルでは、応答を作成します。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-123">The response model for the runbook create response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iRunbookOperations.DeleteAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
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
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4d4c5-124">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="4d4c5-124">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="4d4c5-125">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-125">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="4d4c5-126">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-126">The runbook name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d4c5-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-127">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d4c5-128">名前で、runbook を削除します。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-128">Delete the runbook by name.</span></span>  <span data-ttu-id="4d4c5-129">(詳細については http://aka.ms/azureautomationsdk/runbookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="4d4c5-129">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4d4c5-130">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="4d4c5-130">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt;" Usage="iRunbookOperations.GetAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4d4c5-131">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="4d4c5-131">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="4d4c5-132">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-132">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="4d4c5-133">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-133">The runbook name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d4c5-134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-134">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d4c5-135">Runbook 名によって識別される runbook を取得します。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-135">Retrieve the runbook identified by runbook name.</span></span>  <span data-ttu-id="4d4c5-136">(詳細については http://aka.ms/azureautomationsdk/runbookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="4d4c5-136">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4d4c5-137">Runbook の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-137">The response model for the get runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt;" Usage="iRunbookOperations.ListAsync (resourceGroupName, automationAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4d4c5-138">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="4d4c5-138">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="4d4c5-139">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-139">The automation account name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d4c5-140">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-140">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d4c5-141">Runbook の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-141">Retrieve a list of runbooks.</span></span>  <span data-ttu-id="4d4c5-142">(詳細については http://aka.ms/azureautomationsdk/runbookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="4d4c5-142">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4d4c5-143">一覧の runbook の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-143">The response model for the list runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt;" Usage="iRunbookOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="4d4c5-144">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-144">The link to retrieve next set of items.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d4c5-145">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-145">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d4c5-146">Runbook の次の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-146">Retrieve next list of runbooks.</span></span>  <span data-ttu-id="4d4c5-147">(詳細については http://aka.ms/azureautomationsdk/runbookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="4d4c5-147">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4d4c5-148">一覧の runbook の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-148">The response model for the list runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt; PatchAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt; PatchAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookOperations.PatchAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchAsync : string * string * Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt;" Usage="iRunbookOperations.PatchAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="4d4c5-149">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="4d4c5-149">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="4d4c5-150">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-150">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4d4c5-151">Runbook の更新プログラムのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-151">The patch parameters for runbook.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d4c5-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-152">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d4c5-153">Runbook 名によって識別される runbook を更新します。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-153">Update the runbook identified by runbook name.</span></span>  <span data-ttu-id="4d4c5-154">(詳細については http://aka.ms/azureautomationsdk/runbookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="4d4c5-154">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4d4c5-155">Runbook の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="4d4c5-155">The response model for the get runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>