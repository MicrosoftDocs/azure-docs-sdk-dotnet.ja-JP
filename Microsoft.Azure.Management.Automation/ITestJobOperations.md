<Type Name="ITestJobOperations" FullName="Microsoft.Azure.Management.Automation.ITestJobOperations">
  <TypeSignature Language="C#" Value="public interface ITestJobOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITestJobOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.ITestJobOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITestJobOperations" />
  <TypeSignature Language="F#" Value="type ITestJobOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="38b9a-101">オートメーションのテスト ジョブのサービス操作。</span><span class="sxs-lookup"><span data-stu-id="38b9a-101">Service operation for automation test jobs.</span></span>  <span data-ttu-id="38b9a-102">(詳細については http://aka.ms/azureautomationsdk/testjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="38b9a-102">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse&gt; CreateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse&gt; CreateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ITestJobOperations.CreateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : string * string * Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse&gt;" Usage="iTestJobOperations.CreateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="38b9a-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="38b9a-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="38b9a-104">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="38b9a-104">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="38b9a-105">作成のテスト ジョブの操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="38b9a-105">The parameters supplied to the create test job operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="38b9a-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="38b9a-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="38b9a-107">Runbook のテスト ジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="38b9a-107">Create a test job of the runbook.</span></span>  <span data-ttu-id="38b9a-108">(詳細については http://aka.ms/azureautomationsdk/testjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="38b9a-108">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="38b9a-109">作成の応答モデルでは、ジョブ操作をテストします。</span><span class="sxs-lookup"><span data-stu-id="38b9a-109">The response model for the create test job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.TestJobGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ITestJobOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobGetResponse&gt;" Usage="iTestJobOperations.GetAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="38b9a-110">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="38b9a-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="38b9a-111">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="38b9a-111">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="38b9a-112">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="38b9a-112">The runbook name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="38b9a-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="38b9a-113">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="38b9a-114">指定された runbook のテスト ジョブを取得します。</span><span class="sxs-lookup"><span data-stu-id="38b9a-114">Retrieve the test job for the specified runbook.</span></span>  <span data-ttu-id="38b9a-115">(詳細については http://aka.ms/azureautomationsdk/testjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="38b9a-115">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="38b9a-116">Get 応答モデルでは、ジョブ操作をテストします。</span><span class="sxs-lookup"><span data-stu-id="38b9a-116">The response model for the get test job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ITestJobOperations.ResumeAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResumeAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iTestJobOperations.ResumeAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
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
            <span data-ttu-id="38b9a-117">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="38b9a-117">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="38b9a-118">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="38b9a-118">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="38b9a-119">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="38b9a-119">The runbook name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="38b9a-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="38b9a-120">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="38b9a-121">テスト ジョブを再開します。</span><span class="sxs-lookup"><span data-stu-id="38b9a-121">Resume the test job.</span></span>  <span data-ttu-id="38b9a-122">(詳細については http://aka.ms/azureautomationsdk/testjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="38b9a-122">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="38b9a-123">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="38b9a-123">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; StopAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; StopAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ITestJobOperations.StopAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StopAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iTestJobOperations.StopAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
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
            <span data-ttu-id="38b9a-124">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="38b9a-124">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="38b9a-125">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="38b9a-125">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="38b9a-126">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="38b9a-126">The runbook name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="38b9a-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="38b9a-127">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="38b9a-128">テスト ジョブを停止します。</span><span class="sxs-lookup"><span data-stu-id="38b9a-128">Stop the test job.</span></span>  <span data-ttu-id="38b9a-129">(詳細については http://aka.ms/azureautomationsdk/testjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="38b9a-129">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="38b9a-130">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="38b9a-130">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ITestJobOperations.SuspendAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SuspendAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iTestJobOperations.SuspendAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
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
            <span data-ttu-id="38b9a-131">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="38b9a-131">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="38b9a-132">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="38b9a-132">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="38b9a-133">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="38b9a-133">The runbook name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="38b9a-134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="38b9a-134">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="38b9a-135">テスト ジョブを中断します。</span><span class="sxs-lookup"><span data-stu-id="38b9a-135">Suspend the test job.</span></span>  <span data-ttu-id="38b9a-136">(詳細については http://aka.ms/azureautomationsdk/testjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="38b9a-136">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="38b9a-137">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="38b9a-137">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>