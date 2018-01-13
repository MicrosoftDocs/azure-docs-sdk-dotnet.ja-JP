<Type Name="IRunbookDraftOperations" FullName="Microsoft.Azure.Management.Automation.IRunbookDraftOperations">
  <TypeSignature Language="C#" Value="public interface IRunbookDraftOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRunbookDraftOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IRunbookDraftOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRunbookDraftOperations" />
  <TypeSignature Language="F#" Value="type IRunbookDraftOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ee2b8-101">Automation runbook の下書きのサービス操作。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-101">Service operation for automation runbook draft.</span></span>  <span data-ttu-id="ee2b8-102">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ee2b8-102">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginPublishAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginPublishAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginPublishAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.BeginPublishAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginPublishAsync : string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="iRunbookDraftOperations.BeginPublishAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ee2b8-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="ee2b8-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ee2b8-104">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-104">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ee2b8-105">Runbook の発行操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-105">The parameters supplied to the publish runbook operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ee2b8-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ee2b8-107">Runbook 名によって識別される runbook を取得します。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-107">Retrieve the runbook identified by runbook name.</span></span>  <span data-ttu-id="ee2b8-108">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ee2b8-108">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ee2b8-109">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-109">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginUpdateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginUpdateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.BeginUpdateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateAsync : string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="iRunbookDraftOperations.BeginUpdateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ee2b8-110">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="ee2b8-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ee2b8-111">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-111">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ee2b8-112">Runbook ドラフト パラメーターを変更しています。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-112">The runbook draft update parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ee2b8-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-113">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ee2b8-114">その内容として runbookStream で runbook のドラフトを更新します。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-114">Updates the runbook draft with runbookStream as its content.</span></span>  <span data-ttu-id="ee2b8-115">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ee2b8-115">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ee2b8-116">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-116">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateGraphAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginUpdateGraphAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginUpdateGraphAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.BeginUpdateGraphAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateGraphAsync : string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="iRunbookDraftOperations.BeginUpdateGraphAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ee2b8-117">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="ee2b8-117">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ee2b8-118">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-118">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ee2b8-119">Runbook ドラフト パラメーターを変更しています。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-119">The runbook draft update parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ee2b8-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-120">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ee2b8-121">その内容として runbookStream で runbook のドラフトを更新します。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-121">Updates the runbook draft with runbookStream as its content.</span></span>  <span data-ttu-id="ee2b8-122">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ee2b8-122">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ee2b8-123">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-123">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt; ContentAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt; ContentAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.ContentAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContentAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt;" Usage="iRunbookDraftOperations.ContentAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
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
            <span data-ttu-id="ee2b8-124">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="ee2b8-124">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ee2b8-125">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-125">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="ee2b8-126">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-126">The runbook name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ee2b8-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-127">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ee2b8-128">Runbook 名によって識別される runbook の下書きのコンテンツを取得します。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-128">Retrieve the content of runbook draft identified by runbook name.</span></span>
            <span data-ttu-id="ee2b8-129">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ee2b8-129">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ee2b8-130">Runbook のコンテンツ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-130">The response model for the runbook content operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse&gt;" Usage="iRunbookDraftOperations.GetAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ee2b8-131">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="ee2b8-131">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ee2b8-132">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-132">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="ee2b8-133">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-133">The runbook name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ee2b8-134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-134">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ee2b8-135">Runbook 名によって識別される runbook の下書きを取得します。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-135">Retrieve the runbook draft identified by runbook name.</span></span>  <span data-ttu-id="ee2b8-136">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ee2b8-136">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ee2b8-137">Runbook の下書きの取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-137">The response model for the get runbook draft operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublishAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; PublishAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; PublishAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.PublishAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PublishAsync : string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="iRunbookDraftOperations.PublishAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ee2b8-138">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="ee2b8-138">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ee2b8-139">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-139">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ee2b8-140">Runbook の発行操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-140">The parameters supplied to the publish runbook operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ee2b8-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-141">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ee2b8-142">Runbook 名によって識別される runbook を取得します。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-142">Retrieve the runbook identified by runbook name.</span></span>  <span data-ttu-id="ee2b8-143">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ee2b8-143">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ee2b8-144">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-144">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UndoEditAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse&gt; UndoEditAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse&gt; UndoEditAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.UndoEditAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UndoEditAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse&gt;" Usage="iRunbookDraftOperations.UndoEditAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ee2b8-145">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="ee2b8-145">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ee2b8-146">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-146">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="ee2b8-147">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-147">The runbook name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ee2b8-148">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-148">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ee2b8-149">Runbook 名によって識別される runbook を取得します。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-149">Retrieve the runbook identified by runbook name.</span></span>  <span data-ttu-id="ee2b8-150">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ee2b8-150">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ee2b8-151">Undoedit runbook の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-151">The response model for the undoedit runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; UpdateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; UpdateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.UpdateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="iRunbookDraftOperations.UpdateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ee2b8-152">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="ee2b8-152">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ee2b8-153">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-153">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ee2b8-154">Runbook ドラフト パラメーターを変更しています。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-154">The runbook draft update parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ee2b8-155">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-155">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ee2b8-156">その内容として runbookStream で runbook のドラフトを更新します。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-156">Updates the runbook draft with runbookStream as its content.</span></span>  <span data-ttu-id="ee2b8-157">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ee2b8-157">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ee2b8-158">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-158">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateGraphAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; UpdateGraphAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; UpdateGraphAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.UpdateGraphAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateGraphAsync : string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="iRunbookDraftOperations.UpdateGraphAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="ee2b8-159">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="ee2b8-159">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ee2b8-160">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-160">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ee2b8-161">Runbook ドラフト パラメーターを変更しています。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-161">The runbook draft update parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ee2b8-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-162">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ee2b8-163">その内容として runbookStream で runbook のドラフトを更新します。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-163">Updates the runbook draft with runbookStream as its content.</span></span>  <span data-ttu-id="ee2b8-164">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="ee2b8-164">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ee2b8-165">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="ee2b8-165">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>