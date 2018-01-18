<Type Name="RunbookDraftOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RunbookDraftOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RunbookDraftOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RunbookDraftOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RunbookDraftOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginPublish">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse BeginPublish (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse BeginPublish(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.BeginPublish(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginPublish (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookDraftPublishParameters) As LongRunningOperationResultResponse" />
      <MemberSignature Language="F#" Value="static member BeginPublish : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters -&gt; Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.BeginPublish (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b87bc-101">Microsoft.Azure.Management.Automation.IRunbookDraftOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b87bc-101">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b87bc-102">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-102">Required.</span></span> <span data-ttu-id="b87bc-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="b87bc-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b87bc-104">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-104">Required.</span></span> <span data-ttu-id="b87bc-105">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b87bc-105">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b87bc-106">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-106">Required.</span></span> <span data-ttu-id="b87bc-107">Runbook の発行操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="b87bc-107">The parameters supplied to the publish runbook operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b87bc-108">Runbook 名によって識別される runbook を取得します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-108">Retrieve the runbook identified by runbook name.</span></span>  <span data-ttu-id="b87bc-109">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="b87bc-109">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b87bc-110">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-110">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPublishAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginPublishAsync (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginPublishAsync(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.BeginPublishAsync(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginPublishAsync (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookDraftPublishParameters) As Task(Of LongRunningOperationResultResponse)" />
      <MemberSignature Language="F#" Value="static member BeginPublishAsync : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.BeginPublishAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b87bc-111">Microsoft.Azure.Management.Automation.IRunbookDraftOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b87bc-111">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b87bc-112">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-112">Required.</span></span> <span data-ttu-id="b87bc-113">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="b87bc-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b87bc-114">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-114">Required.</span></span> <span data-ttu-id="b87bc-115">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b87bc-115">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b87bc-116">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-116">Required.</span></span> <span data-ttu-id="b87bc-117">Runbook の発行操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="b87bc-117">The parameters supplied to the publish runbook operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b87bc-118">Runbook 名によって識別される runbook を取得します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-118">Retrieve the runbook identified by runbook name.</span></span>  <span data-ttu-id="b87bc-119">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="b87bc-119">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b87bc-120">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-120">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse BeginUpdate (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse BeginUpdate(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdate (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookDraftUpdateParameters) As LongRunningOperationResultResponse" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.BeginUpdate (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b87bc-121">Microsoft.Azure.Management.Automation.IRunbookDraftOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b87bc-121">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b87bc-122">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-122">Required.</span></span> <span data-ttu-id="b87bc-123">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="b87bc-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b87bc-124">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-124">Required.</span></span> <span data-ttu-id="b87bc-125">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b87bc-125">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b87bc-126">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-126">Required.</span></span> <span data-ttu-id="b87bc-127">Runbook ドラフト パラメーターを変更しています。</span><span class="sxs-lookup"><span data-stu-id="b87bc-127">The runbook draft update parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b87bc-128">その内容として runbookStream で runbook のドラフトを更新します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-128">Updates the runbook draft with runbookStream as its content.</span></span>  <span data-ttu-id="b87bc-129">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="b87bc-129">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b87bc-130">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-130">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdateAsync (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookDraftUpdateParameters) As Task(Of LongRunningOperationResultResponse)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b87bc-131">Microsoft.Azure.Management.Automation.IRunbookDraftOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b87bc-131">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b87bc-132">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-132">Required.</span></span> <span data-ttu-id="b87bc-133">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="b87bc-133">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b87bc-134">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-134">Required.</span></span> <span data-ttu-id="b87bc-135">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b87bc-135">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b87bc-136">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-136">Required.</span></span> <span data-ttu-id="b87bc-137">Runbook ドラフト パラメーターを変更しています。</span><span class="sxs-lookup"><span data-stu-id="b87bc-137">The runbook draft update parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b87bc-138">その内容として runbookStream で runbook のドラフトを更新します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-138">Updates the runbook draft with runbookStream as its content.</span></span>  <span data-ttu-id="b87bc-139">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="b87bc-139">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b87bc-140">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-140">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateGraph">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse BeginUpdateGraph (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse BeginUpdateGraph(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.BeginUpdateGraph(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdateGraph (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookDraftUpdateParameters) As LongRunningOperationResultResponse" />
      <MemberSignature Language="F#" Value="static member BeginUpdateGraph : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.BeginUpdateGraph (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b87bc-141">Microsoft.Azure.Management.Automation.IRunbookDraftOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b87bc-141">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b87bc-142">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-142">Required.</span></span> <span data-ttu-id="b87bc-143">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="b87bc-143">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b87bc-144">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-144">Required.</span></span> <span data-ttu-id="b87bc-145">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b87bc-145">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b87bc-146">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-146">Required.</span></span> <span data-ttu-id="b87bc-147">Runbook ドラフト パラメーターを変更しています。</span><span class="sxs-lookup"><span data-stu-id="b87bc-147">The runbook draft update parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b87bc-148">その内容として runbookStream で runbook のドラフトを更新します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-148">Updates the runbook draft with runbookStream as its content.</span></span>  <span data-ttu-id="b87bc-149">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="b87bc-149">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b87bc-150">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-150">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateGraphAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginUpdateGraphAsync (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginUpdateGraphAsync(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.BeginUpdateGraphAsync(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdateGraphAsync (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookDraftUpdateParameters) As Task(Of LongRunningOperationResultResponse)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateGraphAsync : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.BeginUpdateGraphAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b87bc-151">Microsoft.Azure.Management.Automation.IRunbookDraftOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b87bc-151">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b87bc-152">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-152">Required.</span></span> <span data-ttu-id="b87bc-153">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="b87bc-153">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b87bc-154">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-154">Required.</span></span> <span data-ttu-id="b87bc-155">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b87bc-155">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b87bc-156">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-156">Required.</span></span> <span data-ttu-id="b87bc-157">Runbook ドラフト パラメーターを変更しています。</span><span class="sxs-lookup"><span data-stu-id="b87bc-157">The runbook draft update parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b87bc-158">その内容として runbookStream で runbook のドラフトを更新します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-158">Updates the runbook draft with runbookStream as its content.</span></span>  <span data-ttu-id="b87bc-159">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="b87bc-159">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b87bc-160">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-160">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Content">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.RunbookContentResponse Content (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.RunbookContentResponse Content(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.Content(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Content (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As RunbookContentResponse" />
      <MemberSignature Language="F#" Value="static member Content : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.RunbookContentResponse" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.Content (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.RunbookContentResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b87bc-161">Microsoft.Azure.Management.Automation.IRunbookDraftOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b87bc-161">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b87bc-162">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-162">Required.</span></span> <span data-ttu-id="b87bc-163">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="b87bc-163">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b87bc-164">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-164">Required.</span></span> <span data-ttu-id="b87bc-165">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b87bc-165">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="b87bc-166">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-166">Required.</span></span> <span data-ttu-id="b87bc-167">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="b87bc-167">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b87bc-168">Runbook 名によって識別される runbook の下書きのコンテンツを取得します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-168">Retrieve the content of runbook draft identified by runbook name.</span></span>
            <span data-ttu-id="b87bc-169">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="b87bc-169">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b87bc-170">Runbook のコンテンツ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="b87bc-170">The response model for the runbook content operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt; ContentAsync (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt; ContentAsync(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.ContentAsync(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ContentAsync (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As Task(Of RunbookContentResponse)" />
      <MemberSignature Language="F#" Value="static member ContentAsync : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.ContentAsync (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b87bc-171">Microsoft.Azure.Management.Automation.IRunbookDraftOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b87bc-171">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b87bc-172">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-172">Required.</span></span> <span data-ttu-id="b87bc-173">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="b87bc-173">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b87bc-174">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-174">Required.</span></span> <span data-ttu-id="b87bc-175">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b87bc-175">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="b87bc-176">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-176">Required.</span></span> <span data-ttu-id="b87bc-177">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="b87bc-177">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b87bc-178">Runbook 名によって識別される runbook の下書きのコンテンツを取得します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-178">Retrieve the content of runbook draft identified by runbook name.</span></span>
            <span data-ttu-id="b87bc-179">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="b87bc-179">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b87bc-180">Runbook のコンテンツ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="b87bc-180">The response model for the runbook content operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse Get (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse Get(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As RunbookDraftGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.Get (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b87bc-181">Microsoft.Azure.Management.Automation.IRunbookDraftOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b87bc-181">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b87bc-182">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-182">Required.</span></span> <span data-ttu-id="b87bc-183">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="b87bc-183">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b87bc-184">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-184">Required.</span></span> <span data-ttu-id="b87bc-185">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b87bc-185">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="b87bc-186">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-186">Required.</span></span> <span data-ttu-id="b87bc-187">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="b87bc-187">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b87bc-188">Runbook 名によって識別される runbook の下書きを取得します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-188">Retrieve the runbook draft identified by runbook name.</span></span>  <span data-ttu-id="b87bc-189">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="b87bc-189">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b87bc-190">Runbook の下書きの取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="b87bc-190">The response model for the get runbook draft operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As Task(Of RunbookDraftGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b87bc-191">Microsoft.Azure.Management.Automation.IRunbookDraftOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b87bc-191">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b87bc-192">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-192">Required.</span></span> <span data-ttu-id="b87bc-193">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="b87bc-193">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b87bc-194">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-194">Required.</span></span> <span data-ttu-id="b87bc-195">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b87bc-195">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="b87bc-196">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-196">Required.</span></span> <span data-ttu-id="b87bc-197">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="b87bc-197">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b87bc-198">Runbook 名によって識別される runbook の下書きを取得します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-198">Retrieve the runbook draft identified by runbook name.</span></span>  <span data-ttu-id="b87bc-199">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="b87bc-199">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b87bc-200">Runbook の下書きの取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="b87bc-200">The response model for the get runbook draft operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Publish">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse Publish (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse Publish(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.Publish(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Publish (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookDraftPublishParameters) As LongRunningOperationResultResponse" />
      <MemberSignature Language="F#" Value="static member Publish : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters -&gt; Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.Publish (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b87bc-201">Microsoft.Azure.Management.Automation.IRunbookDraftOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b87bc-201">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b87bc-202">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-202">Required.</span></span> <span data-ttu-id="b87bc-203">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="b87bc-203">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b87bc-204">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-204">Required.</span></span> <span data-ttu-id="b87bc-205">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b87bc-205">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b87bc-206">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-206">Required.</span></span> <span data-ttu-id="b87bc-207">Runbook の発行操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="b87bc-207">The parameters supplied to the publish runbook operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b87bc-208">Runbook 名によって識別される runbook を取得します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-208">Retrieve the runbook identified by runbook name.</span></span>  <span data-ttu-id="b87bc-209">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="b87bc-209">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b87bc-210">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-210">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublishAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; PublishAsync (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; PublishAsync(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.PublishAsync(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PublishAsync (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookDraftPublishParameters) As Task(Of LongRunningOperationResultResponse)" />
      <MemberSignature Language="F#" Value="static member PublishAsync : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.PublishAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b87bc-211">Microsoft.Azure.Management.Automation.IRunbookDraftOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b87bc-211">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b87bc-212">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-212">Required.</span></span> <span data-ttu-id="b87bc-213">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="b87bc-213">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b87bc-214">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-214">Required.</span></span> <span data-ttu-id="b87bc-215">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b87bc-215">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b87bc-216">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-216">Required.</span></span> <span data-ttu-id="b87bc-217">Runbook の発行操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="b87bc-217">The parameters supplied to the publish runbook operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b87bc-218">Runbook 名によって識別される runbook を取得します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-218">Retrieve the runbook identified by runbook name.</span></span>  <span data-ttu-id="b87bc-219">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="b87bc-219">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b87bc-220">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-220">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UndoEdit">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse UndoEdit (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse UndoEdit(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.UndoEdit(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UndoEdit (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As RunbookDraftUndoEditResponse" />
      <MemberSignature Language="F#" Value="static member UndoEdit : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.UndoEdit (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b87bc-221">Microsoft.Azure.Management.Automation.IRunbookDraftOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b87bc-221">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b87bc-222">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-222">Required.</span></span> <span data-ttu-id="b87bc-223">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="b87bc-223">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b87bc-224">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-224">Required.</span></span> <span data-ttu-id="b87bc-225">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b87bc-225">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="b87bc-226">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-226">Required.</span></span> <span data-ttu-id="b87bc-227">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="b87bc-227">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b87bc-228">Runbook 名によって識別される runbook を取得します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-228">Retrieve the runbook identified by runbook name.</span></span>  <span data-ttu-id="b87bc-229">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="b87bc-229">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b87bc-230">Undoedit runbook の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="b87bc-230">The response model for the undoedit runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UndoEditAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse&gt; UndoEditAsync (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse&gt; UndoEditAsync(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.UndoEditAsync(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UndoEditAsync (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As Task(Of RunbookDraftUndoEditResponse)" />
      <MemberSignature Language="F#" Value="static member UndoEditAsync : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.UndoEditAsync (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b87bc-231">Microsoft.Azure.Management.Automation.IRunbookDraftOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b87bc-231">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b87bc-232">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-232">Required.</span></span> <span data-ttu-id="b87bc-233">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="b87bc-233">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b87bc-234">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-234">Required.</span></span> <span data-ttu-id="b87bc-235">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b87bc-235">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="b87bc-236">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-236">Required.</span></span> <span data-ttu-id="b87bc-237">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="b87bc-237">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b87bc-238">Runbook 名によって識別される runbook を取得します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-238">Retrieve the runbook identified by runbook name.</span></span>  <span data-ttu-id="b87bc-239">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="b87bc-239">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b87bc-240">Undoedit runbook の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="b87bc-240">The response model for the undoedit runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse Update (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse Update(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.Update(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookDraftUpdateParameters) As LongRunningOperationResultResponse" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.Update (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b87bc-241">Microsoft.Azure.Management.Automation.IRunbookDraftOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b87bc-241">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b87bc-242">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-242">Required.</span></span> <span data-ttu-id="b87bc-243">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="b87bc-243">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b87bc-244">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-244">Required.</span></span> <span data-ttu-id="b87bc-245">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b87bc-245">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b87bc-246">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-246">Required.</span></span> <span data-ttu-id="b87bc-247">Runbook ドラフト パラメーターを変更しています。</span><span class="sxs-lookup"><span data-stu-id="b87bc-247">The runbook draft update parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b87bc-248">その内容として runbookStream で runbook のドラフトを更新します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-248">Updates the runbook draft with runbookStream as its content.</span></span>  <span data-ttu-id="b87bc-249">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="b87bc-249">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b87bc-250">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-250">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; UpdateAsync (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; UpdateAsync(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateAsync (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookDraftUpdateParameters) As Task(Of LongRunningOperationResultResponse)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.UpdateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b87bc-251">Microsoft.Azure.Management.Automation.IRunbookDraftOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b87bc-251">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b87bc-252">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-252">Required.</span></span> <span data-ttu-id="b87bc-253">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="b87bc-253">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b87bc-254">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-254">Required.</span></span> <span data-ttu-id="b87bc-255">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b87bc-255">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b87bc-256">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-256">Required.</span></span> <span data-ttu-id="b87bc-257">Runbook ドラフト パラメーターを変更しています。</span><span class="sxs-lookup"><span data-stu-id="b87bc-257">The runbook draft update parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b87bc-258">その内容として runbookStream で runbook のドラフトを更新します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-258">Updates the runbook draft with runbookStream as its content.</span></span>  <span data-ttu-id="b87bc-259">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="b87bc-259">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b87bc-260">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-260">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateGraph">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse UpdateGraph (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse UpdateGraph(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.UpdateGraph(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateGraph (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookDraftUpdateParameters) As LongRunningOperationResultResponse" />
      <MemberSignature Language="F#" Value="static member UpdateGraph : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.UpdateGraph (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b87bc-261">Microsoft.Azure.Management.Automation.IRunbookDraftOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b87bc-261">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b87bc-262">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-262">Required.</span></span> <span data-ttu-id="b87bc-263">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="b87bc-263">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b87bc-264">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-264">Required.</span></span> <span data-ttu-id="b87bc-265">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b87bc-265">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b87bc-266">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-266">Required.</span></span> <span data-ttu-id="b87bc-267">Runbook ドラフト パラメーターを変更しています。</span><span class="sxs-lookup"><span data-stu-id="b87bc-267">The runbook draft update parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b87bc-268">その内容として runbookStream で runbook のドラフトを更新します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-268">Updates the runbook draft with runbookStream as its content.</span></span>  <span data-ttu-id="b87bc-269">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="b87bc-269">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b87bc-270">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-270">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateGraphAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; UpdateGraphAsync (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; UpdateGraphAsync(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.UpdateGraphAsync(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateGraphAsync (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookDraftUpdateParameters) As Task(Of LongRunningOperationResultResponse)" />
      <MemberSignature Language="F#" Value="static member UpdateGraphAsync : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.UpdateGraphAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b87bc-271">Microsoft.Azure.Management.Automation.IRunbookDraftOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b87bc-271">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b87bc-272">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-272">Required.</span></span> <span data-ttu-id="b87bc-273">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="b87bc-273">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b87bc-274">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-274">Required.</span></span> <span data-ttu-id="b87bc-275">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="b87bc-275">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b87bc-276">必須。</span><span class="sxs-lookup"><span data-stu-id="b87bc-276">Required.</span></span> <span data-ttu-id="b87bc-277">Runbook ドラフト パラメーターを変更しています。</span><span class="sxs-lookup"><span data-stu-id="b87bc-277">The runbook draft update parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b87bc-278">その内容として runbookStream で runbook のドラフトを更新します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-278">Updates the runbook draft with runbookStream as its content.</span></span>  <span data-ttu-id="b87bc-279">(詳細については http://aka.ms/azureautomationsdk/runbookdraftoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="b87bc-279">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b87bc-280">時間の長いの応答を標準のサービス操作を実行します。</span><span class="sxs-lookup"><span data-stu-id="b87bc-280">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>