<Type Name="JobOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.JobOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class JobOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit JobOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.JobOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module JobOperationsExtensions" />
  <TypeSignature Language="F#" Value="type JobOperationsExtensions = class" />
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
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobCreateResponse Create (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.JobCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobCreateResponse Create(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.JobCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.Create(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.JobCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IJobOperations, resourceGroupName As String, automationAccount As String, parameters As JobCreateParameters) As JobCreateResponse" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Microsoft.Azure.Management.Automation.Models.JobCreateParameters -&gt; Microsoft.Azure.Management.Automation.Models.JobCreateResponse" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.Create (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobCreateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.JobCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d7e-101">Microsoft.Azure.Management.Automation.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="62d7e-101">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d7e-102">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-102">Required.</span></span> <span data-ttu-id="62d7e-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="62d7e-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="62d7e-104">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-104">Required.</span></span> <span data-ttu-id="62d7e-105">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="62d7e-105">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="62d7e-106">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-106">Required.</span></span> <span data-ttu-id="62d7e-107">ジョブの作成処理に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="62d7e-107">The parameters supplied to the create job operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d7e-108">Runbook のジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="62d7e-108">Create a job of the runbook.</span></span>  <span data-ttu-id="62d7e-109">(詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="62d7e-109">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="62d7e-110">作成するジョブ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="62d7e-110">The response model for the create job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobCreateResponse&gt; CreateAsync (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.JobCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobCreateResponse&gt; CreateAsync(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.JobCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.JobCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateAsync (operations As IJobOperations, resourceGroupName As String, automationAccount As String, parameters As JobCreateParameters) As Task(Of JobCreateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Microsoft.Azure.Management.Automation.Models.JobCreateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobCreateResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.CreateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobCreateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.JobCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d7e-111">Microsoft.Azure.Management.Automation.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="62d7e-111">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d7e-112">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-112">Required.</span></span> <span data-ttu-id="62d7e-113">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="62d7e-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="62d7e-114">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-114">Required.</span></span> <span data-ttu-id="62d7e-115">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="62d7e-115">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="62d7e-116">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-116">Required.</span></span> <span data-ttu-id="62d7e-117">ジョブの作成処理に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="62d7e-117">The parameters supplied to the create job operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d7e-118">Runbook のジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="62d7e-118">Create a job of the runbook.</span></span>  <span data-ttu-id="62d7e-119">(詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="62d7e-119">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="62d7e-120">作成するジョブ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="62d7e-120">The response model for the create job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobGetResponse Get (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobGetResponse Get(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid) As JobGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Guid -&gt; Microsoft.Azure.Management.Automation.Models.JobGetResponse" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.Get (operations, resourceGroupName, automationAccount, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d7e-121">Microsoft.Azure.Management.Automation.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="62d7e-121">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d7e-122">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-122">Required.</span></span> <span data-ttu-id="62d7e-123">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="62d7e-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="62d7e-124">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-124">Required.</span></span> <span data-ttu-id="62d7e-125">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="62d7e-125">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="62d7e-126">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-126">Required.</span></span> <span data-ttu-id="62d7e-127">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="62d7e-127">The job id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d7e-128">ジョブ id によって識別されるジョブを取得します。 (詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="62d7e-128">Retrieve the job identified by job id.  (see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="62d7e-129">Get job 操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="62d7e-129">The response model for the get job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid) As Task(Of JobGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d7e-130">Microsoft.Azure.Management.Automation.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="62d7e-130">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d7e-131">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-131">Required.</span></span> <span data-ttu-id="62d7e-132">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="62d7e-132">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="62d7e-133">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-133">Required.</span></span> <span data-ttu-id="62d7e-134">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="62d7e-134">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="62d7e-135">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-135">Required.</span></span> <span data-ttu-id="62d7e-136">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="62d7e-136">The job id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d7e-137">ジョブ id によって識別されるジョブを取得します。 (詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="62d7e-137">Retrieve the job identified by job id.  (see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="62d7e-138">Get job 操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="62d7e-138">The response model for the get job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOutput">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobGetOutputResponse GetOutput (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobGetOutputResponse GetOutput(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.GetOutput(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetOutput (operations As IJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid) As JobGetOutputResponse" />
      <MemberSignature Language="F#" Value="static member GetOutput : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Guid -&gt; Microsoft.Azure.Management.Automation.Models.JobGetOutputResponse" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.GetOutput (operations, resourceGroupName, automationAccount, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobGetOutputResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d7e-139">Microsoft.Azure.Management.Automation.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="62d7e-139">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d7e-140">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-140">Required.</span></span> <span data-ttu-id="62d7e-141">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="62d7e-141">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="62d7e-142">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-142">Required.</span></span> <span data-ttu-id="62d7e-143">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="62d7e-143">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="62d7e-144">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-144">Required.</span></span> <span data-ttu-id="62d7e-145">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="62d7e-145">The job id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d7e-146">ジョブ id によって識別されるジョブの出力を取得します。 (詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="62d7e-146">Retrieve the job output identified by job id.  (see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="62d7e-147">Get ジョブの応答モデルでは、操作を出力します。</span><span class="sxs-lookup"><span data-stu-id="62d7e-147">The response model for the get job output operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOutputAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetOutputResponse&gt; GetOutputAsync (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobGetOutputResponse&gt; GetOutputAsync(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.GetOutputAsync(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetOutputAsync (operations As IJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid) As Task(Of JobGetOutputResponse)" />
      <MemberSignature Language="F#" Value="static member GetOutputAsync : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetOutputResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.GetOutputAsync (operations, resourceGroupName, automationAccount, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetOutputResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d7e-148">Microsoft.Azure.Management.Automation.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="62d7e-148">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d7e-149">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-149">Required.</span></span> <span data-ttu-id="62d7e-150">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="62d7e-150">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="62d7e-151">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-151">Required.</span></span> <span data-ttu-id="62d7e-152">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="62d7e-152">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="62d7e-153">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-153">Required.</span></span> <span data-ttu-id="62d7e-154">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="62d7e-154">The job id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d7e-155">ジョブ id によって識別されるジョブの出力を取得します。 (詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="62d7e-155">Retrieve the job output identified by job id.  (see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="62d7e-156">Get ジョブの応答モデルでは、操作を出力します。</span><span class="sxs-lookup"><span data-stu-id="62d7e-156">The response model for the get job output operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRunbookContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobGetRunbookContentResponse GetRunbookContent (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobGetRunbookContentResponse GetRunbookContent(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.GetRunbookContent(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetRunbookContent (operations As IJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid) As JobGetRunbookContentResponse" />
      <MemberSignature Language="F#" Value="static member GetRunbookContent : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Guid -&gt; Microsoft.Azure.Management.Automation.Models.JobGetRunbookContentResponse" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.GetRunbookContent (operations, resourceGroupName, automationAccount, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobGetRunbookContentResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d7e-157">Microsoft.Azure.Management.Automation.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="62d7e-157">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d7e-158">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-158">Required.</span></span> <span data-ttu-id="62d7e-159">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="62d7e-159">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="62d7e-160">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-160">Required.</span></span> <span data-ttu-id="62d7e-161">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="62d7e-161">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="62d7e-162">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-162">Required.</span></span> <span data-ttu-id="62d7e-163">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="62d7e-163">The job id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d7e-164">ジョブ id によって識別されるジョブの runbook のコンテンツを取得します。 (詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="62d7e-164">Retrieve the runbook content of the job identified by job id.  (see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="62d7e-165">Get の runbook のジョブ操作の内容の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="62d7e-165">The response model for the get runbook content of the job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRunbookContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetRunbookContentResponse&gt; GetRunbookContentAsync (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobGetRunbookContentResponse&gt; GetRunbookContentAsync(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.GetRunbookContentAsync(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetRunbookContentAsync (operations As IJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid) As Task(Of JobGetRunbookContentResponse)" />
      <MemberSignature Language="F#" Value="static member GetRunbookContentAsync : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetRunbookContentResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.GetRunbookContentAsync (operations, resourceGroupName, automationAccount, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetRunbookContentResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d7e-166">Microsoft.Azure.Management.Automation.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="62d7e-166">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d7e-167">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-167">Required.</span></span> <span data-ttu-id="62d7e-168">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="62d7e-168">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="62d7e-169">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-169">Required.</span></span> <span data-ttu-id="62d7e-170">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="62d7e-170">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="62d7e-171">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-171">Required.</span></span> <span data-ttu-id="62d7e-172">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="62d7e-172">The job id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d7e-173">ジョブ id によって識別されるジョブの runbook のコンテンツを取得します。 (詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="62d7e-173">Retrieve the runbook content of the job identified by job id.  (see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="62d7e-174">Get の runbook のジョブ操作の内容の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="62d7e-174">The response model for the get runbook content of the job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobListResponse List (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.JobListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobListResponse List(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.JobListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.List(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.JobListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IJobOperations, resourceGroupName As String, automationAccount As String, parameters As JobListParameters) As JobListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Microsoft.Azure.Management.Automation.Models.JobListParameters -&gt; Microsoft.Azure.Management.Automation.Models.JobListResponse" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.List (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.JobListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d7e-175">Microsoft.Azure.Management.Automation.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="62d7e-175">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d7e-176">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-176">Required.</span></span> <span data-ttu-id="62d7e-177">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="62d7e-177">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="62d7e-178">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-178">Required.</span></span> <span data-ttu-id="62d7e-179">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="62d7e-179">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="62d7e-180">省略可能。</span><span class="sxs-lookup"><span data-stu-id="62d7e-180">Optional.</span></span> <span data-ttu-id="62d7e-181">一覧表示操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="62d7e-181">The parameters supplied to the list operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d7e-182">ジョブの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="62d7e-182">Retrieve a list of jobs.</span></span>  <span data-ttu-id="62d7e-183">(詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="62d7e-183">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="62d7e-184">一覧のジョブ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="62d7e-184">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.JobListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.JobListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.JobListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IJobOperations, resourceGroupName As String, automationAccount As String, parameters As JobListParameters) As Task(Of JobListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Microsoft.Azure.Management.Automation.Models.JobListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.JobListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d7e-185">Microsoft.Azure.Management.Automation.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="62d7e-185">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d7e-186">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-186">Required.</span></span> <span data-ttu-id="62d7e-187">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="62d7e-187">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="62d7e-188">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-188">Required.</span></span> <span data-ttu-id="62d7e-189">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="62d7e-189">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="62d7e-190">省略可能。</span><span class="sxs-lookup"><span data-stu-id="62d7e-190">Optional.</span></span> <span data-ttu-id="62d7e-191">一覧表示操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="62d7e-191">The parameters supplied to the list operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d7e-192">ジョブの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="62d7e-192">Retrieve a list of jobs.</span></span>  <span data-ttu-id="62d7e-193">(詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="62d7e-193">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="62d7e-194">一覧のジョブ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="62d7e-194">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobListResponse ListNext (this Microsoft.Azure.Management.Automation.IJobOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobListResponse ListNext(class Microsoft.Azure.Management.Automation.IJobOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IJobOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IJobOperations, nextLink As String) As JobListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IJobOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.JobListResponse" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d7e-195">Microsoft.Azure.Management.Automation.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="62d7e-195">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="62d7e-196">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-196">Required.</span></span> <span data-ttu-id="62d7e-197">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="62d7e-197">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d7e-198">ジョブの [次へ] の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="62d7e-198">Retrieve next list of jobs.</span></span>  <span data-ttu-id="62d7e-199">(詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="62d7e-199">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="62d7e-200">一覧のジョブ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="62d7e-200">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IJobOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IJobOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IJobOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IJobOperations, nextLink As String) As Task(Of JobListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IJobOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d7e-201">Microsoft.Azure.Management.Automation.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="62d7e-201">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="62d7e-202">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-202">Required.</span></span> <span data-ttu-id="62d7e-203">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="62d7e-203">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d7e-204">ジョブの [次へ] の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="62d7e-204">Retrieve next list of jobs.</span></span>  <span data-ttu-id="62d7e-205">(詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="62d7e-205">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="62d7e-206">一覧のジョブ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="62d7e-206">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resume">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Resume (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Resume(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.Resume(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Resume (operations As IJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Resume : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Guid -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.Resume (operations, resourceGroupName, automationAccount, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d7e-207">Microsoft.Azure.Management.Automation.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="62d7e-207">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d7e-208">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-208">Required.</span></span> <span data-ttu-id="62d7e-209">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="62d7e-209">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="62d7e-210">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-210">Required.</span></span> <span data-ttu-id="62d7e-211">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="62d7e-211">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="62d7e-212">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-212">Required.</span></span> <span data-ttu-id="62d7e-213">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="62d7e-213">The job id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d7e-214">ジョブ Id によって識別されるジョブを再開します。</span><span class="sxs-lookup"><span data-stu-id="62d7e-214">Resume the job identified by jobId.</span></span>  <span data-ttu-id="62d7e-215">(詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="62d7e-215">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="62d7e-216">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="62d7e-216">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.ResumeAsync(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ResumeAsync (operations As IJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member ResumeAsync : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.ResumeAsync (operations, resourceGroupName, automationAccount, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d7e-217">Microsoft.Azure.Management.Automation.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="62d7e-217">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d7e-218">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-218">Required.</span></span> <span data-ttu-id="62d7e-219">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="62d7e-219">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="62d7e-220">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-220">Required.</span></span> <span data-ttu-id="62d7e-221">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="62d7e-221">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="62d7e-222">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-222">Required.</span></span> <span data-ttu-id="62d7e-223">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="62d7e-223">The job id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d7e-224">ジョブ Id によって識別されるジョブを再開します。</span><span class="sxs-lookup"><span data-stu-id="62d7e-224">Resume the job identified by jobId.</span></span>  <span data-ttu-id="62d7e-225">(詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="62d7e-225">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="62d7e-226">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="62d7e-226">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stop">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Stop (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Stop(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.Stop(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Stop (operations As IJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Stop : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Guid -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.Stop (operations, resourceGroupName, automationAccount, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d7e-227">Microsoft.Azure.Management.Automation.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="62d7e-227">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d7e-228">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-228">Required.</span></span> <span data-ttu-id="62d7e-229">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="62d7e-229">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="62d7e-230">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-230">Required.</span></span> <span data-ttu-id="62d7e-231">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="62d7e-231">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="62d7e-232">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-232">Required.</span></span> <span data-ttu-id="62d7e-233">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="62d7e-233">The job id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d7e-234">ジョブ Id によって識別されるジョブを停止します。</span><span class="sxs-lookup"><span data-stu-id="62d7e-234">Stop the job identified by jobId.</span></span>  <span data-ttu-id="62d7e-235">(詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="62d7e-235">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="62d7e-236">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="62d7e-236">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; StopAsync (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; StopAsync(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.StopAsync(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function StopAsync (operations As IJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member StopAsync : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.StopAsync (operations, resourceGroupName, automationAccount, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d7e-237">Microsoft.Azure.Management.Automation.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="62d7e-237">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d7e-238">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-238">Required.</span></span> <span data-ttu-id="62d7e-239">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="62d7e-239">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="62d7e-240">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-240">Required.</span></span> <span data-ttu-id="62d7e-241">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="62d7e-241">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="62d7e-242">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-242">Required.</span></span> <span data-ttu-id="62d7e-243">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="62d7e-243">The job id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d7e-244">ジョブ Id によって識別されるジョブを停止します。</span><span class="sxs-lookup"><span data-stu-id="62d7e-244">Stop the job identified by jobId.</span></span>  <span data-ttu-id="62d7e-245">(詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="62d7e-245">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="62d7e-246">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="62d7e-246">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Suspend">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Suspend (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Suspend(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.Suspend(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Suspend (operations As IJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Suspend : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Guid -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.Suspend (operations, resourceGroupName, automationAccount, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d7e-247">Microsoft.Azure.Management.Automation.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="62d7e-247">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d7e-248">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-248">Required.</span></span> <span data-ttu-id="62d7e-249">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="62d7e-249">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="62d7e-250">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-250">Required.</span></span> <span data-ttu-id="62d7e-251">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="62d7e-251">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="62d7e-252">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-252">Required.</span></span> <span data-ttu-id="62d7e-253">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="62d7e-253">The job id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d7e-254">ジョブ Id によって識別されるジョブを中断します。</span><span class="sxs-lookup"><span data-stu-id="62d7e-254">Suspend the job identified by jobId.</span></span>  <span data-ttu-id="62d7e-255">(詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="62d7e-255">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="62d7e-256">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="62d7e-256">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.SuspendAsync(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SuspendAsync (operations As IJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member SuspendAsync : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.SuspendAsync (operations, resourceGroupName, automationAccount, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d7e-257">Microsoft.Azure.Management.Automation.IJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="62d7e-257">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d7e-258">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-258">Required.</span></span> <span data-ttu-id="62d7e-259">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="62d7e-259">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="62d7e-260">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-260">Required.</span></span> <span data-ttu-id="62d7e-261">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="62d7e-261">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="62d7e-262">必須。</span><span class="sxs-lookup"><span data-stu-id="62d7e-262">Required.</span></span> <span data-ttu-id="62d7e-263">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="62d7e-263">The job id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d7e-264">ジョブ Id によって識別されるジョブを中断します。</span><span class="sxs-lookup"><span data-stu-id="62d7e-264">Suspend the job identified by jobId.</span></span>  <span data-ttu-id="62d7e-265">(詳細については http://aka.ms/azureautomationsdk/joboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="62d7e-265">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="62d7e-266">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="62d7e-266">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>