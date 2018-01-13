<Type Name="RunbookOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RunbookOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RunbookOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RunbookOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RunbookOperationsExtensions = class" />
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
    <Member MemberName="Content">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.RunbookContentResponse Content (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.RunbookContentResponse Content(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.Content(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Content (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As RunbookContentResponse" />
      <MemberSignature Language="F#" Value="static member Content : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.RunbookContentResponse" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.Content (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.RunbookContentResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51fa9-101">Microsoft.Azure.Management.Automation.IRunbookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="51fa9-101">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51fa9-102">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-102">Required.</span></span> <span data-ttu-id="51fa9-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="51fa9-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="51fa9-104">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-104">Required.</span></span> <span data-ttu-id="51fa9-105">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51fa9-105">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="51fa9-106">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-106">Required.</span></span> <span data-ttu-id="51fa9-107">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="51fa9-107">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51fa9-108">Runbook 名によって識別される runbook の内容を取得します。</span><span class="sxs-lookup"><span data-stu-id="51fa9-108">Retrieve the content of runbook identified by runbook name.</span></span>  <span data-ttu-id="51fa9-109">(詳細については http://aka.ms/azureautomationsdk/runbookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="51fa9-109">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="51fa9-110">Runbook のコンテンツ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="51fa9-110">The response model for the runbook content operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt; ContentAsync (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt; ContentAsync(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.ContentAsync(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ContentAsync (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As Task(Of RunbookContentResponse)" />
      <MemberSignature Language="F#" Value="static member ContentAsync : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.ContentAsync (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51fa9-111">Microsoft.Azure.Management.Automation.IRunbookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="51fa9-111">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51fa9-112">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-112">Required.</span></span> <span data-ttu-id="51fa9-113">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="51fa9-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="51fa9-114">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-114">Required.</span></span> <span data-ttu-id="51fa9-115">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51fa9-115">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="51fa9-116">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-116">Required.</span></span> <span data-ttu-id="51fa9-117">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="51fa9-117">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51fa9-118">Runbook 名によって識別される runbook の内容を取得します。</span><span class="sxs-lookup"><span data-stu-id="51fa9-118">Retrieve the content of runbook identified by runbook name.</span></span>  <span data-ttu-id="51fa9-119">(詳細については http://aka.ms/azureautomationsdk/runbookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="51fa9-119">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="51fa9-120">Runbook のコンテンツ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="51fa9-120">The response model for the runbook content operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookCreateOrUpdateParameters) As RunbookCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51fa9-121">Microsoft.Azure.Management.Automation.IRunbookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="51fa9-121">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51fa9-122">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-122">Required.</span></span> <span data-ttu-id="51fa9-123">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="51fa9-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="51fa9-124">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-124">Required.</span></span> <span data-ttu-id="51fa9-125">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51fa9-125">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="51fa9-126">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-126">Required.</span></span> <span data-ttu-id="51fa9-127">Runbook の作成または更新パラメーター。</span><span class="sxs-lookup"><span data-stu-id="51fa9-127">The create or update parameters for runbook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51fa9-128">Runbook 名によって識別される runbook を作成します。</span><span class="sxs-lookup"><span data-stu-id="51fa9-128">Create the runbook identified by runbook name.</span></span>  <span data-ttu-id="51fa9-129">(詳細については http://aka.ms/azureautomationsdk/runbookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="51fa9-129">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="51fa9-130">Runbook の応答モデルでは、応答を作成します。</span><span class="sxs-lookup"><span data-stu-id="51fa9-130">The response model for the runbook create response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookCreateOrUpdateParameters) As Task(Of RunbookCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51fa9-131">Microsoft.Azure.Management.Automation.IRunbookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="51fa9-131">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51fa9-132">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-132">Required.</span></span> <span data-ttu-id="51fa9-133">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="51fa9-133">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="51fa9-134">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-134">Required.</span></span> <span data-ttu-id="51fa9-135">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51fa9-135">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="51fa9-136">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-136">Required.</span></span> <span data-ttu-id="51fa9-137">Runbook の作成または更新パラメーター。</span><span class="sxs-lookup"><span data-stu-id="51fa9-137">The create or update parameters for runbook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51fa9-138">Runbook 名によって識別される runbook を作成します。</span><span class="sxs-lookup"><span data-stu-id="51fa9-138">Create the runbook identified by runbook name.</span></span>  <span data-ttu-id="51fa9-139">(詳細については http://aka.ms/azureautomationsdk/runbookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="51fa9-139">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="51fa9-140">Runbook の応答モデルでは、応答を作成します。</span><span class="sxs-lookup"><span data-stu-id="51fa9-140">The response model for the runbook create response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithDraft">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse CreateOrUpdateWithDraft (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse CreateOrUpdateWithDraft(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.CreateOrUpdateWithDraft(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithDraft (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookCreateOrUpdateDraftParameters) As RunbookCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithDraft : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters -&gt; Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.CreateOrUpdateWithDraft (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51fa9-141">Microsoft.Azure.Management.Automation.IRunbookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="51fa9-141">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51fa9-142">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-142">Required.</span></span> <span data-ttu-id="51fa9-143">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="51fa9-143">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="51fa9-144">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-144">Required.</span></span> <span data-ttu-id="51fa9-145">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51fa9-145">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="51fa9-146">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-146">Required.</span></span> <span data-ttu-id="51fa9-147">Runbook の作成または更新パラメーター。</span><span class="sxs-lookup"><span data-stu-id="51fa9-147">The create or update parameters for runbook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51fa9-148">Runbook 名によって識別される runbook を作成します。</span><span class="sxs-lookup"><span data-stu-id="51fa9-148">Create the runbook identified by runbook name.</span></span>  <span data-ttu-id="51fa9-149">(詳細については http://aka.ms/azureautomationsdk/runbookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="51fa9-149">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="51fa9-150">Runbook の応答モデルでは、応答を作成します。</span><span class="sxs-lookup"><span data-stu-id="51fa9-150">The response model for the runbook create response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithDraftAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt; CreateOrUpdateWithDraftAsync (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt; CreateOrUpdateWithDraftAsync(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.CreateOrUpdateWithDraftAsync(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithDraftAsync (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookCreateOrUpdateDraftParameters) As Task(Of RunbookCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithDraftAsync : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.CreateOrUpdateWithDraftAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51fa9-151">Microsoft.Azure.Management.Automation.IRunbookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="51fa9-151">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51fa9-152">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-152">Required.</span></span> <span data-ttu-id="51fa9-153">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="51fa9-153">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="51fa9-154">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-154">Required.</span></span> <span data-ttu-id="51fa9-155">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51fa9-155">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="51fa9-156">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-156">Required.</span></span> <span data-ttu-id="51fa9-157">Runbook の作成または更新パラメーター。</span><span class="sxs-lookup"><span data-stu-id="51fa9-157">The create or update parameters for runbook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51fa9-158">Runbook 名によって識別される runbook を作成します。</span><span class="sxs-lookup"><span data-stu-id="51fa9-158">Create the runbook identified by runbook name.</span></span>  <span data-ttu-id="51fa9-159">(詳細については http://aka.ms/azureautomationsdk/runbookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="51fa9-159">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="51fa9-160">Runbook の応答モデルでは、応答を作成します。</span><span class="sxs-lookup"><span data-stu-id="51fa9-160">The response model for the runbook create response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.Delete(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.Delete (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51fa9-161">Microsoft.Azure.Management.Automation.IRunbookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="51fa9-161">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51fa9-162">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-162">Required.</span></span> <span data-ttu-id="51fa9-163">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="51fa9-163">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="51fa9-164">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-164">Required.</span></span> <span data-ttu-id="51fa9-165">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51fa9-165">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="51fa9-166">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-166">Required.</span></span> <span data-ttu-id="51fa9-167">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="51fa9-167">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51fa9-168">名前で、runbook を削除します。</span><span class="sxs-lookup"><span data-stu-id="51fa9-168">Delete the runbook by name.</span></span>  <span data-ttu-id="51fa9-169">(詳細については http://aka.ms/azureautomationsdk/runbookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="51fa9-169">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="51fa9-170">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="51fa9-170">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.DeleteAsync (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51fa9-171">Microsoft.Azure.Management.Automation.IRunbookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="51fa9-171">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51fa9-172">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-172">Required.</span></span> <span data-ttu-id="51fa9-173">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="51fa9-173">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="51fa9-174">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-174">Required.</span></span> <span data-ttu-id="51fa9-175">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51fa9-175">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="51fa9-176">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-176">Required.</span></span> <span data-ttu-id="51fa9-177">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="51fa9-177">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51fa9-178">名前で、runbook を削除します。</span><span class="sxs-lookup"><span data-stu-id="51fa9-178">Delete the runbook by name.</span></span>  <span data-ttu-id="51fa9-179">(詳細については http://aka.ms/azureautomationsdk/runbookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="51fa9-179">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="51fa9-180">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="51fa9-180">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.RunbookGetResponse Get (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.RunbookGetResponse Get(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As RunbookGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.RunbookGetResponse" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.Get (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.RunbookGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51fa9-181">Microsoft.Azure.Management.Automation.IRunbookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="51fa9-181">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51fa9-182">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-182">Required.</span></span> <span data-ttu-id="51fa9-183">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="51fa9-183">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="51fa9-184">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-184">Required.</span></span> <span data-ttu-id="51fa9-185">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51fa9-185">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="51fa9-186">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-186">Required.</span></span> <span data-ttu-id="51fa9-187">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="51fa9-187">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51fa9-188">Runbook 名によって識別される runbook を取得します。</span><span class="sxs-lookup"><span data-stu-id="51fa9-188">Retrieve the runbook identified by runbook name.</span></span>  <span data-ttu-id="51fa9-189">(詳細については http://aka.ms/azureautomationsdk/runbookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="51fa9-189">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="51fa9-190">Runbook の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="51fa9-190">The response model for the get runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As Task(Of RunbookGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51fa9-191">Microsoft.Azure.Management.Automation.IRunbookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="51fa9-191">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51fa9-192">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-192">Required.</span></span> <span data-ttu-id="51fa9-193">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="51fa9-193">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="51fa9-194">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-194">Required.</span></span> <span data-ttu-id="51fa9-195">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51fa9-195">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="51fa9-196">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-196">Required.</span></span> <span data-ttu-id="51fa9-197">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="51fa9-197">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51fa9-198">Runbook 名によって識別される runbook を取得します。</span><span class="sxs-lookup"><span data-stu-id="51fa9-198">Retrieve the runbook identified by runbook name.</span></span>  <span data-ttu-id="51fa9-199">(詳細については http://aka.ms/azureautomationsdk/runbookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="51fa9-199">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="51fa9-200">Runbook の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="51fa9-200">The response model for the get runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.RunbookListResponse List (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.RunbookListResponse List(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.List(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String) As RunbookListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string -&gt; Microsoft.Azure.Management.Automation.Models.RunbookListResponse" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.List (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.RunbookListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51fa9-201">Microsoft.Azure.Management.Automation.IRunbookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="51fa9-201">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51fa9-202">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-202">Required.</span></span> <span data-ttu-id="51fa9-203">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="51fa9-203">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="51fa9-204">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-204">Required.</span></span> <span data-ttu-id="51fa9-205">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51fa9-205">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51fa9-206">Runbook の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="51fa9-206">Retrieve a list of runbooks.</span></span>  <span data-ttu-id="51fa9-207">(詳細については http://aka.ms/azureautomationsdk/runbookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="51fa9-207">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="51fa9-208">一覧の runbook の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="51fa9-208">The response model for the list runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String) As Task(Of RunbookListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51fa9-209">Microsoft.Azure.Management.Automation.IRunbookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="51fa9-209">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51fa9-210">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-210">Required.</span></span> <span data-ttu-id="51fa9-211">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="51fa9-211">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="51fa9-212">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-212">Required.</span></span> <span data-ttu-id="51fa9-213">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51fa9-213">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51fa9-214">Runbook の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="51fa9-214">Retrieve a list of runbooks.</span></span>  <span data-ttu-id="51fa9-215">(詳細については http://aka.ms/azureautomationsdk/runbookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="51fa9-215">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="51fa9-216">一覧の runbook の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="51fa9-216">The response model for the list runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.RunbookListResponse ListNext (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.RunbookListResponse ListNext(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IRunbookOperations, nextLink As String) As RunbookListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IRunbookOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.RunbookListResponse" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.RunbookListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51fa9-217">Microsoft.Azure.Management.Automation.IRunbookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="51fa9-217">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="51fa9-218">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-218">Required.</span></span> <span data-ttu-id="51fa9-219">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="51fa9-219">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51fa9-220">Runbook の次の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="51fa9-220">Retrieve next list of runbooks.</span></span>  <span data-ttu-id="51fa9-221">(詳細については http://aka.ms/azureautomationsdk/runbookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="51fa9-221">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="51fa9-222">一覧の runbook の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="51fa9-222">The response model for the list runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IRunbookOperations, nextLink As String) As Task(Of RunbookListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IRunbookOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51fa9-223">Microsoft.Azure.Management.Automation.IRunbookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="51fa9-223">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="51fa9-224">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-224">Required.</span></span> <span data-ttu-id="51fa9-225">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="51fa9-225">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51fa9-226">Runbook の次の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="51fa9-226">Retrieve next list of runbooks.</span></span>  <span data-ttu-id="51fa9-227">(詳細については http://aka.ms/azureautomationsdk/runbookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="51fa9-227">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="51fa9-228">一覧の runbook の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="51fa9-228">The response model for the list runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.RunbookGetResponse Patch (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.RunbookGetResponse Patch(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.Patch(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Patch (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookPatchParameters) As RunbookGetResponse" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters -&gt; Microsoft.Azure.Management.Automation.Models.RunbookGetResponse" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.Patch (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.RunbookGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51fa9-229">Microsoft.Azure.Management.Automation.IRunbookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="51fa9-229">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51fa9-230">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-230">Required.</span></span> <span data-ttu-id="51fa9-231">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="51fa9-231">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="51fa9-232">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-232">Required.</span></span> <span data-ttu-id="51fa9-233">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51fa9-233">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="51fa9-234">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-234">Required.</span></span> <span data-ttu-id="51fa9-235">Runbook の更新プログラムのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="51fa9-235">The patch parameters for runbook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51fa9-236">Runbook 名によって識別される runbook を更新します。</span><span class="sxs-lookup"><span data-stu-id="51fa9-236">Update the runbook identified by runbook name.</span></span>  <span data-ttu-id="51fa9-237">(詳細については http://aka.ms/azureautomationsdk/runbookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="51fa9-237">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="51fa9-238">Runbook の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="51fa9-238">The response model for the get runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt; PatchAsync (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt; PatchAsync(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.PatchAsync(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PatchAsync (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookPatchParameters) As Task(Of RunbookGetResponse)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.PatchAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="51fa9-239">Microsoft.Azure.Management.Automation.IRunbookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="51fa9-239">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51fa9-240">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-240">Required.</span></span> <span data-ttu-id="51fa9-241">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="51fa9-241">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="51fa9-242">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-242">Required.</span></span> <span data-ttu-id="51fa9-243">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="51fa9-243">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="51fa9-244">必須。</span><span class="sxs-lookup"><span data-stu-id="51fa9-244">Required.</span></span> <span data-ttu-id="51fa9-245">Runbook の更新プログラムのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="51fa9-245">The patch parameters for runbook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51fa9-246">Runbook 名によって識別される runbook を更新します。</span><span class="sxs-lookup"><span data-stu-id="51fa9-246">Update the runbook identified by runbook name.</span></span>  <span data-ttu-id="51fa9-247">(詳細については http://aka.ms/azureautomationsdk/runbookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="51fa9-247">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="51fa9-248">Runbook の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="51fa9-248">The response model for the get runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>