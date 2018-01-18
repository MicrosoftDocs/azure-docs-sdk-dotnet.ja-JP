<Type Name="IJobStreamOperations" FullName="Microsoft.Azure.Management.Automation.IJobStreamOperations">
  <TypeSignature Language="C#" Value="public interface IJobStreamOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IJobStreamOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IJobStreamOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IJobStreamOperations" />
  <TypeSignature Language="F#" Value="type IJobStreamOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="77816-101">Automation ジョブ ストリームのサービス操作。</span><span class="sxs-lookup"><span data-stu-id="77816-101">Service operation for automation job streams.</span></span>  <span data-ttu-id="77816-102">(詳細については http://aka.ms/azureautomationsdk/jobstreamoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="77816-102">(see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, Guid jobId, string jobStreamId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, valuetype System.Guid jobId, string jobStreamId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobStreamOperations.GetAsync(System.String,System.String,System.Guid,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * Guid * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt;" Usage="iJobStreamOperations.GetAsync (resourceGroupName, automationAccount, jobId, jobStreamId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="jobStreamId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="77816-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="77816-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="77816-104">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="77816-104">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="77816-105">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="77816-105">The job id.</span></span>
            </param>
        <param name="jobStreamId">
            <span data-ttu-id="77816-106">ジョブ ストリーム id です。</span><span class="sxs-lookup"><span data-stu-id="77816-106">The job stream id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="77816-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="77816-107">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="77816-108">ジョブ ストリーム id によって識別されるジョブ ストリームを取得します。 (詳細については http://aka.ms/azureautomationsdk/jobstreamoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="77816-108">Retrieve the job stream identified by job stream id.  (see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="77816-109">ジョブ ストリームの取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="77816-109">The response model for the get job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestJobStreamAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt; GetTestJobStreamAsync (string resourceGroupName, string automationAccount, string runbookName, string jobStreamId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt; GetTestJobStreamAsync(string resourceGroupName, string automationAccount, string runbookName, string jobStreamId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobStreamOperations.GetTestJobStreamAsync(System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTestJobStreamAsync : string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt;" Usage="iJobStreamOperations.GetTestJobStreamAsync (resourceGroupName, automationAccount, runbookName, jobStreamId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="jobStreamId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="77816-110">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="77816-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="77816-111">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="77816-111">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="77816-112">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="77816-112">The runbook name.</span></span>
            </param>
        <param name="jobStreamId">
            <span data-ttu-id="77816-113">ジョブ ストリーム id です。</span><span class="sxs-lookup"><span data-stu-id="77816-113">The job stream id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="77816-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="77816-114">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="77816-115">テスト ジョブの runbook 名とストリーム id によって識別されるストリームを取得します。 (詳細については http://aka.ms/azureautomationsdk/jobstreamoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="77816-115">Retrieve a test job streams identified by runbook name and stream id.  (see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="77816-116">ジョブ ストリームの取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="77816-116">The response model for the get job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, Guid jobId, Microsoft.Azure.Management.Automation.Models.JobStreamListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, valuetype System.Guid jobId, class Microsoft.Azure.Management.Automation.Models.JobStreamListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobStreamOperations.ListAsync(System.String,System.String,System.Guid,Microsoft.Azure.Management.Automation.Models.JobStreamListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * Guid * Microsoft.Azure.Management.Automation.Models.JobStreamListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt;" Usage="iJobStreamOperations.ListAsync (resourceGroupName, automationAccount, jobId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.JobStreamListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="77816-117">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="77816-117">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="77816-118">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="77816-118">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="77816-119">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="77816-119">The job Id.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="77816-120">リスト ジョブ ストリームのストリームの項目の操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="77816-120">The parameters supplied to the list job stream's stream items operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="77816-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="77816-121">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="77816-122">ジョブ id によって識別されるジョブ ストリームの一覧を取得します。 (詳細については http://aka.ms/azureautomationsdk/jobstreamoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="77816-122">Retrieve a list of jobs streams identified by job id.  (see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="77816-123">一覧のジョブ ストリーム操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="77816-123">The response model for the list job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobStreamOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt;" Usage="iJobStreamOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="77816-124">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="77816-124">NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="77816-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="77816-125">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="77816-126">次のリンクを使用してジョブ ストリームの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="77816-126">Gets the next page of job streams using next link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="77816-127">一覧のジョブ ストリーム操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="77816-127">The response model for the list job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTestJobStreamsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt; ListTestJobStreamsAsync (string resourceGroupName, string automationAccount, string runbookName, Microsoft.Azure.Management.Automation.Models.JobStreamListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt; ListTestJobStreamsAsync(string resourceGroupName, string automationAccount, string runbookName, class Microsoft.Azure.Management.Automation.Models.JobStreamListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobStreamOperations.ListTestJobStreamsAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Automation.Models.JobStreamListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTestJobStreamsAsync : string * string * string * Microsoft.Azure.Management.Automation.Models.JobStreamListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt;" Usage="iJobStreamOperations.ListTestJobStreamsAsync (resourceGroupName, automationAccount, runbookName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.JobStreamListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="77816-128">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="77816-128">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="77816-129">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="77816-129">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="77816-130">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="77816-130">The runbook name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="77816-131">リスト ジョブ ストリームのストリームの項目の操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="77816-131">The parameters supplied to the list job stream's stream items operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="77816-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="77816-132">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="77816-133">Runbook 名によって識別されるテスト ジョブのストリームの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="77816-133">Retrieve a list of test job streams identified by runbook name.</span></span>
            <span data-ttu-id="77816-134">(詳細については http://aka.ms/azureautomationsdk/jobstreamoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="77816-134">(see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="77816-135">一覧のジョブ ストリーム操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="77816-135">The response model for the list job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>