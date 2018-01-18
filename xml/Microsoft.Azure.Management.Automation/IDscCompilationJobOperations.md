<Type Name="IDscCompilationJobOperations" FullName="Microsoft.Azure.Management.Automation.IDscCompilationJobOperations">
  <TypeSignature Language="C#" Value="public interface IDscCompilationJobOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDscCompilationJobOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IDscCompilationJobOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDscCompilationJobOperations" />
  <TypeSignature Language="F#" Value="type IDscCompilationJobOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="62c37-101">Automation dsc 構成のサービスの操作は、ジョブをコンパイルします。</span><span class="sxs-lookup"><span data-stu-id="62c37-101">Service operation for automation dsc configuration compile jobs.</span></span>  <span data-ttu-id="62c37-102">(詳細については http://aka.ms/azureautomationsdk/dscccompilationjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="62c37-102">(see http://aka.ms/azureautomationsdk/dscccompilationjoboperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateResponse&gt; CreateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateResponse&gt; CreateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscCompilationJobOperations.CreateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : string * string * Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateResponse&gt;" Usage="iDscCompilationJobOperations.CreateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="62c37-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="62c37-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="62c37-104">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="62c37-104">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="62c37-105">コンパイル ジョブの作成処理に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="62c37-105">The parameters supplied to the create compilation job operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="62c37-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="62c37-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62c37-107">構成の Dsc コンパイル ジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="62c37-107">Creates the Dsc compilation job of the configuration.</span></span>  <span data-ttu-id="62c37-108">(詳細については http://aka.ms/azureautomationsdk/dscconfigurationcompilejoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="62c37-108">(see http://aka.ms/azureautomationsdk/dscconfigurationcompilejoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="62c37-109">Dsc コンパイル ジョブ操作の作成の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="62c37-109">The response model for the create Dsc Compilation job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, Guid jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscCompilationJobGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, valuetype System.Guid jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscCompilationJobOperations.GetAsync(System.String,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobGetResponse&gt;" Usage="iDscCompilationJobOperations.GetAsync (resourceGroupName, automationAccount, jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="62c37-110">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="62c37-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="62c37-111">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="62c37-111">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="62c37-112">Dsc 構成コンパイル ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="62c37-112">The Dsc configuration compilation job id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="62c37-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="62c37-113">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62c37-114">ジョブ id によって識別される、Dsc 構成コンパイル ジョブを取得します。 (詳細については http://aka.ms/azureautomationsdk/dsccompilationjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="62c37-114">Retrieve the Dsc configuration compilation job identified by job id.  (see http://aka.ms/azureautomationsdk/dsccompilationjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="62c37-115">Get Dsc コンパイル ジョブ操作の応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="62c37-115">The response model for the get Dsc compilation job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOutputAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt; GetOutputAsync (string resourceGroupName, string automationAccount, Guid jobId, string jobStreamId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt; GetOutputAsync(string resourceGroupName, string automationAccount, valuetype System.Guid jobId, string jobStreamId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscCompilationJobOperations.GetOutputAsync(System.String,System.String,System.Guid,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetOutputAsync : string * string * Guid * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt;" Usage="iDscCompilationJobOperations.GetOutputAsync (resourceGroupName, automationAccount, jobId, jobStreamId, cancellationToken)" />
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
            <span data-ttu-id="62c37-116">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="62c37-116">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="62c37-117">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="62c37-117">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="62c37-118">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="62c37-118">The job id.</span></span>
            </param>
        <param name="jobStreamId">
            <span data-ttu-id="62c37-119">ジョブ ストリーム id です。</span><span class="sxs-lookup"><span data-stu-id="62c37-119">The job stream id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="62c37-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="62c37-120">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62c37-121">ジョブ ストリーム id によって識別されるジョブ ストリームを取得します。 (詳細については http://aka.ms/azureautomationsdk/jobstreamoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="62c37-121">Retrieve the job stream identified by job stream id.  (see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="62c37-122">ジョブ ストリームの取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="62c37-122">The response model for the get job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscCompilationJobListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscCompilationJobListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscCompilationJobOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscCompilationJobListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * Microsoft.Azure.Management.Automation.Models.DscCompilationJobListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse&gt;" Usage="iDscCompilationJobOperations.ListAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscCompilationJobListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="62c37-123">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="62c37-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="62c37-124">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="62c37-124">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="62c37-125">一覧表示操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="62c37-125">The parameters supplied to the list operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="62c37-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="62c37-126">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62c37-127">Dsc コンパイル ジョブの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="62c37-127">Retrieve a list of dsc compilation jobs.</span></span>  <span data-ttu-id="62c37-128">(詳細については http://aka.ms/azureautomationsdk/compilationjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="62c37-128">(see http://aka.ms/azureautomationsdk/compilationjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="62c37-129">一覧のジョブ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="62c37-129">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscCompilationJobOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse&gt;" Usage="iDscCompilationJobOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="62c37-130">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="62c37-130">The link to retrieve next set of items.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="62c37-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="62c37-131">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62c37-132">Dsc コンパイル ジョブの [次へ] の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="62c37-132">Retrieve next list of dsc compilation jobs.</span></span>  <span data-ttu-id="62c37-133">(詳細については http://aka.ms/azureautomationsdk/compilationjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="62c37-133">(see http://aka.ms/azureautomationsdk/compilationjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="62c37-134">一覧のジョブ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="62c37-134">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>