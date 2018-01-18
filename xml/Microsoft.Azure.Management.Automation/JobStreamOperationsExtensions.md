<Type Name="JobStreamOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class JobStreamOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit JobStreamOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module JobStreamOperationsExtensions" />
  <TypeSignature Language="F#" Value="type JobStreamOperationsExtensions = class" />
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
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse Get (this Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, Guid jobId, string jobStreamId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse Get(class Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId, string jobStreamId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IJobStreamOperations,System.String,System.String,System.Guid,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IJobStreamOperations, resourceGroupName As String, automationAccount As String, jobId As Guid, jobStreamId As String) As JobStreamGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IJobStreamOperations * string * string * Guid * string -&gt; Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse" Usage="Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.Get (operations, resourceGroupName, automationAccount, jobId, jobStreamId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobStreamOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="jobStreamId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="247f2-101">Microsoft.Azure.Management.Automation.IJobStreamOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="247f2-101">Reference to the Microsoft.Azure.Management.Automation.IJobStreamOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="247f2-102">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-102">Required.</span></span> <span data-ttu-id="247f2-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="247f2-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="247f2-104">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-104">Required.</span></span> <span data-ttu-id="247f2-105">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="247f2-105">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="247f2-106">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-106">Required.</span></span> <span data-ttu-id="247f2-107">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="247f2-107">The job id.</span></span>
            </param>
        <param name="jobStreamId">
            <span data-ttu-id="247f2-108">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-108">Required.</span></span> <span data-ttu-id="247f2-109">ジョブ ストリーム id です。</span><span class="sxs-lookup"><span data-stu-id="247f2-109">The job stream id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="247f2-110">ジョブ ストリーム id によって識別されるジョブ ストリームを取得します。 (詳細については http://aka.ms/azureautomationsdk/jobstreamoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="247f2-110">Retrieve the job stream identified by job stream id.  (see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="247f2-111">ジョブ ストリームの取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="247f2-111">The response model for the get job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, Guid jobId, string jobStreamId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId, string jobStreamId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IJobStreamOperations,System.String,System.String,System.Guid,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IJobStreamOperations, resourceGroupName As String, automationAccount As String, jobId As Guid, jobStreamId As String) As Task(Of JobStreamGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IJobStreamOperations * string * string * Guid * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, jobId, jobStreamId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobStreamOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="jobStreamId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="247f2-112">Microsoft.Azure.Management.Automation.IJobStreamOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="247f2-112">Reference to the Microsoft.Azure.Management.Automation.IJobStreamOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="247f2-113">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-113">Required.</span></span> <span data-ttu-id="247f2-114">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="247f2-114">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="247f2-115">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-115">Required.</span></span> <span data-ttu-id="247f2-116">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="247f2-116">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="247f2-117">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-117">Required.</span></span> <span data-ttu-id="247f2-118">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="247f2-118">The job id.</span></span>
            </param>
        <param name="jobStreamId">
            <span data-ttu-id="247f2-119">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-119">Required.</span></span> <span data-ttu-id="247f2-120">ジョブ ストリーム id です。</span><span class="sxs-lookup"><span data-stu-id="247f2-120">The job stream id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="247f2-121">ジョブ ストリーム id によって識別されるジョブ ストリームを取得します。 (詳細については http://aka.ms/azureautomationsdk/jobstreamoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="247f2-121">Retrieve the job stream identified by job stream id.  (see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="247f2-122">ジョブ ストリームの取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="247f2-122">The response model for the get job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestJobStream">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse GetTestJobStream (this Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, string runbookName, string jobStreamId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse GetTestJobStream(class Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, string runbookName, string jobStreamId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.GetTestJobStream(Microsoft.Azure.Management.Automation.IJobStreamOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTestJobStream (operations As IJobStreamOperations, resourceGroupName As String, automationAccount As String, runbookName As String, jobStreamId As String) As JobStreamGetResponse" />
      <MemberSignature Language="F#" Value="static member GetTestJobStream : Microsoft.Azure.Management.Automation.IJobStreamOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse" Usage="Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.GetTestJobStream (operations, resourceGroupName, automationAccount, runbookName, jobStreamId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobStreamOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="jobStreamId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="247f2-123">Microsoft.Azure.Management.Automation.IJobStreamOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="247f2-123">Reference to the Microsoft.Azure.Management.Automation.IJobStreamOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="247f2-124">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-124">Required.</span></span> <span data-ttu-id="247f2-125">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="247f2-125">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="247f2-126">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-126">Required.</span></span> <span data-ttu-id="247f2-127">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="247f2-127">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="247f2-128">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-128">Required.</span></span> <span data-ttu-id="247f2-129">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="247f2-129">The runbook name.</span></span>
            </param>
        <param name="jobStreamId">
            <span data-ttu-id="247f2-130">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-130">Required.</span></span> <span data-ttu-id="247f2-131">ジョブ ストリーム id です。</span><span class="sxs-lookup"><span data-stu-id="247f2-131">The job stream id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="247f2-132">テスト ジョブの runbook 名とストリーム id によって識別されるストリームを取得します。 (詳細については http://aka.ms/azureautomationsdk/jobstreamoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="247f2-132">Retrieve a test job streams identified by runbook name and stream id.  (see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="247f2-133">ジョブ ストリームの取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="247f2-133">The response model for the get job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestJobStreamAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt; GetTestJobStreamAsync (this Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, string runbookName, string jobStreamId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt; GetTestJobStreamAsync(class Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, string runbookName, string jobStreamId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.GetTestJobStreamAsync(Microsoft.Azure.Management.Automation.IJobStreamOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTestJobStreamAsync (operations As IJobStreamOperations, resourceGroupName As String, automationAccount As String, runbookName As String, jobStreamId As String) As Task(Of JobStreamGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetTestJobStreamAsync : Microsoft.Azure.Management.Automation.IJobStreamOperations * string * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.GetTestJobStreamAsync (operations, resourceGroupName, automationAccount, runbookName, jobStreamId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobStreamOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="jobStreamId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="247f2-134">Microsoft.Azure.Management.Automation.IJobStreamOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="247f2-134">Reference to the Microsoft.Azure.Management.Automation.IJobStreamOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="247f2-135">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-135">Required.</span></span> <span data-ttu-id="247f2-136">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="247f2-136">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="247f2-137">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-137">Required.</span></span> <span data-ttu-id="247f2-138">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="247f2-138">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="247f2-139">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-139">Required.</span></span> <span data-ttu-id="247f2-140">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="247f2-140">The runbook name.</span></span>
            </param>
        <param name="jobStreamId">
            <span data-ttu-id="247f2-141">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-141">Required.</span></span> <span data-ttu-id="247f2-142">ジョブ ストリーム id です。</span><span class="sxs-lookup"><span data-stu-id="247f2-142">The job stream id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="247f2-143">テスト ジョブの runbook 名とストリーム id によって識別されるストリームを取得します。 (詳細については http://aka.ms/azureautomationsdk/jobstreamoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="247f2-143">Retrieve a test job streams identified by runbook name and stream id.  (see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="247f2-144">ジョブ ストリームの取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="247f2-144">The response model for the get job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobStreamListResponse List (this Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, Guid jobId, Microsoft.Azure.Management.Automation.Models.JobStreamListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobStreamListResponse List(class Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId, class Microsoft.Azure.Management.Automation.Models.JobStreamListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.List(Microsoft.Azure.Management.Automation.IJobStreamOperations,System.String,System.String,System.Guid,Microsoft.Azure.Management.Automation.Models.JobStreamListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IJobStreamOperations, resourceGroupName As String, automationAccount As String, jobId As Guid, parameters As JobStreamListParameters) As JobStreamListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IJobStreamOperations * string * string * Guid * Microsoft.Azure.Management.Automation.Models.JobStreamListParameters -&gt; Microsoft.Azure.Management.Automation.Models.JobStreamListResponse" Usage="Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.List (operations, resourceGroupName, automationAccount, jobId, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobStreamListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobStreamOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.JobStreamListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="247f2-145">Microsoft.Azure.Management.Automation.IJobStreamOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="247f2-145">Reference to the Microsoft.Azure.Management.Automation.IJobStreamOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="247f2-146">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-146">Required.</span></span> <span data-ttu-id="247f2-147">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="247f2-147">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="247f2-148">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-148">Required.</span></span> <span data-ttu-id="247f2-149">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="247f2-149">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="247f2-150">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-150">Required.</span></span> <span data-ttu-id="247f2-151">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="247f2-151">The job Id.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="247f2-152">省略可能。</span><span class="sxs-lookup"><span data-stu-id="247f2-152">Optional.</span></span> <span data-ttu-id="247f2-153">リスト ジョブ ストリームのストリームの項目の操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="247f2-153">The parameters supplied to the list job stream's stream items operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="247f2-154">ジョブ id によって識別されるジョブ ストリームの一覧を取得します。 (詳細については http://aka.ms/azureautomationsdk/jobstreamoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="247f2-154">Retrieve a list of jobs streams identified by job id.  (see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="247f2-155">一覧のジョブ ストリーム操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="247f2-155">The response model for the list job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, Guid jobId, Microsoft.Azure.Management.Automation.Models.JobStreamListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId, class Microsoft.Azure.Management.Automation.Models.JobStreamListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IJobStreamOperations,System.String,System.String,System.Guid,Microsoft.Azure.Management.Automation.Models.JobStreamListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IJobStreamOperations, resourceGroupName As String, automationAccount As String, jobId As Guid, parameters As JobStreamListParameters) As Task(Of JobStreamListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IJobStreamOperations * string * string * Guid * Microsoft.Azure.Management.Automation.Models.JobStreamListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount, jobId, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobStreamOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.JobStreamListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="247f2-156">Microsoft.Azure.Management.Automation.IJobStreamOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="247f2-156">Reference to the Microsoft.Azure.Management.Automation.IJobStreamOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="247f2-157">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-157">Required.</span></span> <span data-ttu-id="247f2-158">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="247f2-158">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="247f2-159">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-159">Required.</span></span> <span data-ttu-id="247f2-160">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="247f2-160">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="247f2-161">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-161">Required.</span></span> <span data-ttu-id="247f2-162">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="247f2-162">The job Id.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="247f2-163">省略可能。</span><span class="sxs-lookup"><span data-stu-id="247f2-163">Optional.</span></span> <span data-ttu-id="247f2-164">リスト ジョブ ストリームのストリームの項目の操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="247f2-164">The parameters supplied to the list job stream's stream items operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="247f2-165">ジョブ id によって識別されるジョブ ストリームの一覧を取得します。 (詳細については http://aka.ms/azureautomationsdk/jobstreamoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="247f2-165">Retrieve a list of jobs streams identified by job id.  (see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="247f2-166">一覧のジョブ ストリーム操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="247f2-166">The response model for the list job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobStreamListResponse ListNext (this Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobStreamListResponse ListNext(class Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IJobStreamOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IJobStreamOperations, nextLink As String) As JobStreamListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IJobStreamOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.JobStreamListResponse" Usage="Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobStreamListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobStreamOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="247f2-167">Microsoft.Azure.Management.Automation.IJobStreamOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="247f2-167">Reference to the Microsoft.Azure.Management.Automation.IJobStreamOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="247f2-168">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-168">Required.</span></span> <span data-ttu-id="247f2-169">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="247f2-169">NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="247f2-170">次のリンクを使用してジョブ ストリームの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="247f2-170">Gets the next page of job streams using next link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="247f2-171">一覧のジョブ ストリーム操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="247f2-171">The response model for the list job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IJobStreamOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IJobStreamOperations, nextLink As String) As Task(Of JobStreamListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IJobStreamOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobStreamOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="247f2-172">Microsoft.Azure.Management.Automation.IJobStreamOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="247f2-172">Reference to the Microsoft.Azure.Management.Automation.IJobStreamOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="247f2-173">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-173">Required.</span></span> <span data-ttu-id="247f2-174">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="247f2-174">NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="247f2-175">次のリンクを使用してジョブ ストリームの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="247f2-175">Gets the next page of job streams using next link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="247f2-176">一覧のジョブ ストリーム操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="247f2-176">The response model for the list job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTestJobStreams">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobStreamListResponse ListTestJobStreams (this Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, string runbookName, Microsoft.Azure.Management.Automation.Models.JobStreamListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobStreamListResponse ListTestJobStreams(class Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, string runbookName, class Microsoft.Azure.Management.Automation.Models.JobStreamListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.ListTestJobStreams(Microsoft.Azure.Management.Automation.IJobStreamOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Automation.Models.JobStreamListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTestJobStreams (operations As IJobStreamOperations, resourceGroupName As String, automationAccount As String, runbookName As String, parameters As JobStreamListParameters) As JobStreamListResponse" />
      <MemberSignature Language="F#" Value="static member ListTestJobStreams : Microsoft.Azure.Management.Automation.IJobStreamOperations * string * string * string * Microsoft.Azure.Management.Automation.Models.JobStreamListParameters -&gt; Microsoft.Azure.Management.Automation.Models.JobStreamListResponse" Usage="Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.ListTestJobStreams (operations, resourceGroupName, automationAccount, runbookName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobStreamListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobStreamOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.JobStreamListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="247f2-177">Microsoft.Azure.Management.Automation.IJobStreamOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="247f2-177">Reference to the Microsoft.Azure.Management.Automation.IJobStreamOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="247f2-178">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-178">Required.</span></span> <span data-ttu-id="247f2-179">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="247f2-179">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="247f2-180">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-180">Required.</span></span> <span data-ttu-id="247f2-181">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="247f2-181">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="247f2-182">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-182">Required.</span></span> <span data-ttu-id="247f2-183">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="247f2-183">The runbook name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="247f2-184">省略可能。</span><span class="sxs-lookup"><span data-stu-id="247f2-184">Optional.</span></span> <span data-ttu-id="247f2-185">リスト ジョブ ストリームのストリームの項目の操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="247f2-185">The parameters supplied to the list job stream's stream items operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="247f2-186">Runbook 名によって識別されるテスト ジョブのストリームの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="247f2-186">Retrieve a list of test job streams identified by runbook name.</span></span>
            <span data-ttu-id="247f2-187">(詳細については http://aka.ms/azureautomationsdk/jobstreamoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="247f2-187">(see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="247f2-188">一覧のジョブ ストリーム操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="247f2-188">The response model for the list job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTestJobStreamsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt; ListTestJobStreamsAsync (this Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, string runbookName, Microsoft.Azure.Management.Automation.Models.JobStreamListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt; ListTestJobStreamsAsync(class Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, string runbookName, class Microsoft.Azure.Management.Automation.Models.JobStreamListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.ListTestJobStreamsAsync(Microsoft.Azure.Management.Automation.IJobStreamOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Automation.Models.JobStreamListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTestJobStreamsAsync (operations As IJobStreamOperations, resourceGroupName As String, automationAccount As String, runbookName As String, parameters As JobStreamListParameters) As Task(Of JobStreamListResponse)" />
      <MemberSignature Language="F#" Value="static member ListTestJobStreamsAsync : Microsoft.Azure.Management.Automation.IJobStreamOperations * string * string * string * Microsoft.Azure.Management.Automation.Models.JobStreamListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.ListTestJobStreamsAsync (operations, resourceGroupName, automationAccount, runbookName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobStreamOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.JobStreamListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="247f2-189">Microsoft.Azure.Management.Automation.IJobStreamOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="247f2-189">Reference to the Microsoft.Azure.Management.Automation.IJobStreamOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="247f2-190">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-190">Required.</span></span> <span data-ttu-id="247f2-191">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="247f2-191">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="247f2-192">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-192">Required.</span></span> <span data-ttu-id="247f2-193">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="247f2-193">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="247f2-194">必須。</span><span class="sxs-lookup"><span data-stu-id="247f2-194">Required.</span></span> <span data-ttu-id="247f2-195">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="247f2-195">The runbook name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="247f2-196">省略可能。</span><span class="sxs-lookup"><span data-stu-id="247f2-196">Optional.</span></span> <span data-ttu-id="247f2-197">リスト ジョブ ストリームのストリームの項目の操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="247f2-197">The parameters supplied to the list job stream's stream items operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="247f2-198">Runbook 名によって識別されるテスト ジョブのストリームの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="247f2-198">Retrieve a list of test job streams identified by runbook name.</span></span>
            <span data-ttu-id="247f2-199">(詳細については http://aka.ms/azureautomationsdk/jobstreamoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="247f2-199">(see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="247f2-200">一覧のジョブ ストリーム操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="247f2-200">The response model for the list job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>