<Type Name="IJobOperations" FullName="Microsoft.Azure.Management.Automation.IJobOperations">
  <TypeSignature Language="C#" Value="public interface IJobOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IJobOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IJobOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IJobOperations" />
  <TypeSignature Language="F#" Value="type IJobOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="12c60-101">オートメーション ジョブのサービス操作。</span><span class="sxs-lookup"><span data-stu-id="12c60-101">Service operation for automation jobs.</span></span>  <span data-ttu-id="12c60-102">(詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="12c60-102">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobCreateResponse&gt; CreateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.JobCreateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobCreateResponse&gt; CreateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.JobCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobOperations.CreateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.JobCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : string * string * Microsoft.Azure.Management.Automation.Models.JobCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobCreateResponse&gt;" Usage="iJobOperations.CreateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobCreateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.JobCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="12c60-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="12c60-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="12c60-104">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="12c60-104">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="12c60-105">ジョブの作成処理に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="12c60-105">The parameters supplied to the create job operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12c60-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="12c60-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12c60-107">Runbook のジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="12c60-107">Create a job of the runbook.</span></span>  <span data-ttu-id="12c60-108">(詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="12c60-108">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="12c60-109">作成するジョブ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="12c60-109">The response model for the create job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, Guid jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, valuetype System.Guid jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobOperations.GetAsync(System.String,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetResponse&gt;" Usage="iJobOperations.GetAsync (resourceGroupName, automationAccount, jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="12c60-110">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="12c60-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="12c60-111">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="12c60-111">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="12c60-112">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="12c60-112">The job id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12c60-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="12c60-113">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12c60-114">ジョブ id によって識別されるジョブを取得します。 (詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="12c60-114">Retrieve the job identified by job id.  (see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="12c60-115">Get job 操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="12c60-115">The response model for the get job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOutputAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetOutputResponse&gt; GetOutputAsync (string resourceGroupName, string automationAccount, Guid jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobGetOutputResponse&gt; GetOutputAsync(string resourceGroupName, string automationAccount, valuetype System.Guid jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobOperations.GetOutputAsync(System.String,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetOutputAsync : string * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetOutputResponse&gt;" Usage="iJobOperations.GetOutputAsync (resourceGroupName, automationAccount, jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetOutputResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="12c60-116">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="12c60-116">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="12c60-117">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="12c60-117">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="12c60-118">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="12c60-118">The job id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12c60-119">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="12c60-119">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12c60-120">ジョブ id によって識別されるジョブの出力を取得します。 (詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="12c60-120">Retrieve the job output identified by job id.  (see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="12c60-121">Get ジョブの応答モデルでは、操作を出力します。</span><span class="sxs-lookup"><span data-stu-id="12c60-121">The response model for the get job output operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRunbookContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetRunbookContentResponse&gt; GetRunbookContentAsync (string resourceGroupName, string automationAccount, Guid jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobGetRunbookContentResponse&gt; GetRunbookContentAsync(string resourceGroupName, string automationAccount, valuetype System.Guid jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobOperations.GetRunbookContentAsync(System.String,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetRunbookContentAsync : string * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetRunbookContentResponse&gt;" Usage="iJobOperations.GetRunbookContentAsync (resourceGroupName, automationAccount, jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetRunbookContentResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="12c60-122">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="12c60-122">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="12c60-123">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="12c60-123">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="12c60-124">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="12c60-124">The job id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12c60-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="12c60-125">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12c60-126">ジョブ id によって識別されるジョブの runbook のコンテンツを取得します。 (詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="12c60-126">Retrieve the runbook content of the job identified by job id.  (see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="12c60-127">Get の runbook のジョブ操作の内容の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="12c60-127">The response model for the get runbook content of the job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.JobListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.JobListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.JobListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * Microsoft.Azure.Management.Automation.Models.JobListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobListResponse&gt;" Usage="iJobOperations.ListAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.JobListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="12c60-128">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="12c60-128">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="12c60-129">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="12c60-129">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="12c60-130">一覧表示操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="12c60-130">The parameters supplied to the list operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12c60-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="12c60-131">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12c60-132">ジョブの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="12c60-132">Retrieve a list of jobs.</span></span>  <span data-ttu-id="12c60-133">(詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="12c60-133">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="12c60-134">一覧のジョブ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="12c60-134">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobListResponse&gt;" Usage="iJobOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="12c60-135">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="12c60-135">The link to retrieve next set of items.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12c60-136">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="12c60-136">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12c60-137">ジョブの [次へ] の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="12c60-137">Retrieve next list of jobs.</span></span>  <span data-ttu-id="12c60-138">(詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="12c60-138">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="12c60-139">一覧のジョブ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="12c60-139">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync (string resourceGroupName, string automationAccount, Guid jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync(string resourceGroupName, string automationAccount, valuetype System.Guid jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobOperations.ResumeAsync(System.String,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResumeAsync : string * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iJobOperations.ResumeAsync (resourceGroupName, automationAccount, jobId, cancellationToken)" />
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
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="12c60-140">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="12c60-140">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="12c60-141">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="12c60-141">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="12c60-142">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="12c60-142">The job id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12c60-143">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="12c60-143">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12c60-144">ジョブ Id によって識別されるジョブを再開します。</span><span class="sxs-lookup"><span data-stu-id="12c60-144">Resume the job identified by jobId.</span></span>  <span data-ttu-id="12c60-145">(詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="12c60-145">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="12c60-146">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="12c60-146">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; StopAsync (string resourceGroupName, string automationAccount, Guid jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; StopAsync(string resourceGroupName, string automationAccount, valuetype System.Guid jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobOperations.StopAsync(System.String,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StopAsync : string * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iJobOperations.StopAsync (resourceGroupName, automationAccount, jobId, cancellationToken)" />
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
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="12c60-147">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="12c60-147">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="12c60-148">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="12c60-148">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="12c60-149">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="12c60-149">The job id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12c60-150">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="12c60-150">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12c60-151">ジョブ Id によって識別されるジョブを停止します。</span><span class="sxs-lookup"><span data-stu-id="12c60-151">Stop the job identified by jobId.</span></span>  <span data-ttu-id="12c60-152">(詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="12c60-152">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="12c60-153">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="12c60-153">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync (string resourceGroupName, string automationAccount, Guid jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync(string resourceGroupName, string automationAccount, valuetype System.Guid jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobOperations.SuspendAsync(System.String,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SuspendAsync : string * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iJobOperations.SuspendAsync (resourceGroupName, automationAccount, jobId, cancellationToken)" />
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
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="12c60-154">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="12c60-154">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="12c60-155">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="12c60-155">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="12c60-156">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="12c60-156">The job id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12c60-157">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="12c60-157">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12c60-158">ジョブ Id によって識別されるジョブを中断します。</span><span class="sxs-lookup"><span data-stu-id="12c60-158">Suspend the job identified by jobId.</span></span>  <span data-ttu-id="12c60-159">(詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="12c60-159">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="12c60-160">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="12c60-160">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>