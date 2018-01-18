<Type Name="DscCompilationJobOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.DscCompilationJobOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DscCompilationJobOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DscCompilationJobOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.DscCompilationJobOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DscCompilationJobOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DscCompilationJobOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateResponse Create (this Microsoft.Azure.Management.Automation.IDscCompilationJobOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateResponse Create(class Microsoft.Azure.Management.Automation.IDscCompilationJobOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscCompilationJobOperationsExtensions.Create(Microsoft.Azure.Management.Automation.IDscCompilationJobOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IDscCompilationJobOperations, resourceGroupName As String, automationAccount As String, parameters As DscCompilationJobCreateParameters) As DscCompilationJobCreateResponse" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Automation.IDscCompilationJobOperations * string * string * Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateParameters -&gt; Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateResponse" Usage="Microsoft.Azure.Management.Automation.DscCompilationJobOperationsExtensions.Create (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscCompilationJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbb4d-101">Microsoft.Azure.Management.Automation.IDscCompilationJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-101">Reference to the Microsoft.Azure.Management.Automation.IDscCompilationJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbb4d-102">必須。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-102">Required.</span></span> <span data-ttu-id="cbb4d-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="cbb4d-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="cbb4d-104">必須。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-104">Required.</span></span> <span data-ttu-id="cbb4d-105">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-105">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cbb4d-106">必須。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-106">Required.</span></span> <span data-ttu-id="cbb4d-107">コンパイル ジョブの作成処理に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-107">The parameters supplied to the create compilation job operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbb4d-108">構成の Dsc コンパイル ジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-108">Creates the Dsc compilation job of the configuration.</span></span>  <span data-ttu-id="cbb4d-109">(詳細については http://aka.ms/azureautomationsdk/dscconfigurationcompilejoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="cbb4d-109">(see http://aka.ms/azureautomationsdk/dscconfigurationcompilejoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="cbb4d-110">Dsc コンパイル ジョブ操作の作成の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-110">The response model for the create Dsc Compilation job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateResponse&gt; CreateAsync (this Microsoft.Azure.Management.Automation.IDscCompilationJobOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateResponse&gt; CreateAsync(class Microsoft.Azure.Management.Automation.IDscCompilationJobOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscCompilationJobOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Automation.IDscCompilationJobOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateAsync (operations As IDscCompilationJobOperations, resourceGroupName As String, automationAccount As String, parameters As DscCompilationJobCreateParameters) As Task(Of DscCompilationJobCreateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Automation.IDscCompilationJobOperations * string * string * Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscCompilationJobOperationsExtensions.CreateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscCompilationJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbb4d-111">Microsoft.Azure.Management.Automation.IDscCompilationJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-111">Reference to the Microsoft.Azure.Management.Automation.IDscCompilationJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbb4d-112">必須。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-112">Required.</span></span> <span data-ttu-id="cbb4d-113">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="cbb4d-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="cbb4d-114">必須。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-114">Required.</span></span> <span data-ttu-id="cbb4d-115">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-115">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cbb4d-116">必須。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-116">Required.</span></span> <span data-ttu-id="cbb4d-117">コンパイル ジョブの作成処理に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-117">The parameters supplied to the create compilation job operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbb4d-118">構成の Dsc コンパイル ジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-118">Creates the Dsc compilation job of the configuration.</span></span>  <span data-ttu-id="cbb4d-119">(詳細については http://aka.ms/azureautomationsdk/dscconfigurationcompilejoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="cbb4d-119">(see http://aka.ms/azureautomationsdk/dscconfigurationcompilejoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="cbb4d-120">Dsc コンパイル ジョブ操作の作成の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-120">The response model for the create Dsc Compilation job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscCompilationJobGetResponse Get (this Microsoft.Azure.Management.Automation.IDscCompilationJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscCompilationJobGetResponse Get(class Microsoft.Azure.Management.Automation.IDscCompilationJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscCompilationJobOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IDscCompilationJobOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDscCompilationJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid) As DscCompilationJobGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IDscCompilationJobOperations * string * string * Guid -&gt; Microsoft.Azure.Management.Automation.Models.DscCompilationJobGetResponse" Usage="Microsoft.Azure.Management.Automation.DscCompilationJobOperationsExtensions.Get (operations, resourceGroupName, automationAccount, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscCompilationJobGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscCompilationJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbb4d-121">Microsoft.Azure.Management.Automation.IDscCompilationJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-121">Reference to the Microsoft.Azure.Management.Automation.IDscCompilationJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbb4d-122">必須。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-122">Required.</span></span> <span data-ttu-id="cbb4d-123">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="cbb4d-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="cbb4d-124">必須。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-124">Required.</span></span> <span data-ttu-id="cbb4d-125">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-125">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="cbb4d-126">必須。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-126">Required.</span></span> <span data-ttu-id="cbb4d-127">Dsc 構成コンパイル ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-127">The Dsc configuration compilation job id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbb4d-128">ジョブ id によって識別される、Dsc 構成コンパイル ジョブを取得します。 (詳細については http://aka.ms/azureautomationsdk/dsccompilationjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="cbb4d-128">Retrieve the Dsc configuration compilation job identified by job id.  (see http://aka.ms/azureautomationsdk/dsccompilationjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="cbb4d-129">Get Dsc コンパイル ジョブ操作の応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-129">The response model for the get Dsc compilation job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IDscCompilationJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscCompilationJobGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IDscCompilationJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscCompilationJobOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IDscCompilationJobOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IDscCompilationJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid) As Task(Of DscCompilationJobGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IDscCompilationJobOperations * string * string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscCompilationJobOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscCompilationJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbb4d-130">Microsoft.Azure.Management.Automation.IDscCompilationJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-130">Reference to the Microsoft.Azure.Management.Automation.IDscCompilationJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbb4d-131">必須。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-131">Required.</span></span> <span data-ttu-id="cbb4d-132">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="cbb4d-132">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="cbb4d-133">必須。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-133">Required.</span></span> <span data-ttu-id="cbb4d-134">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-134">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="cbb4d-135">必須。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-135">Required.</span></span> <span data-ttu-id="cbb4d-136">Dsc 構成コンパイル ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-136">The Dsc configuration compilation job id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbb4d-137">ジョブ id によって識別される、Dsc 構成コンパイル ジョブを取得します。 (詳細については http://aka.ms/azureautomationsdk/dsccompilationjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="cbb4d-137">Retrieve the Dsc configuration compilation job identified by job id.  (see http://aka.ms/azureautomationsdk/dsccompilationjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="cbb4d-138">Get Dsc コンパイル ジョブ操作の応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-138">The response model for the get Dsc compilation job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOutput">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse GetOutput (this Microsoft.Azure.Management.Automation.IDscCompilationJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId, string jobStreamId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse GetOutput(class Microsoft.Azure.Management.Automation.IDscCompilationJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId, string jobStreamId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscCompilationJobOperationsExtensions.GetOutput(Microsoft.Azure.Management.Automation.IDscCompilationJobOperations,System.String,System.String,System.Guid,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetOutput (operations As IDscCompilationJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid, jobStreamId As String) As JobStreamGetResponse" />
      <MemberSignature Language="F#" Value="static member GetOutput : Microsoft.Azure.Management.Automation.IDscCompilationJobOperations * string * string * Guid * string -&gt; Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse" Usage="Microsoft.Azure.Management.Automation.DscCompilationJobOperationsExtensions.GetOutput (operations, resourceGroupName, automationAccount, jobId, jobStreamId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscCompilationJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="jobStreamId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbb4d-139">Microsoft.Azure.Management.Automation.IDscCompilationJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-139">Reference to the Microsoft.Azure.Management.Automation.IDscCompilationJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbb4d-140">必須。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-140">Required.</span></span> <span data-ttu-id="cbb4d-141">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="cbb4d-141">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="cbb4d-142">必須。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-142">Required.</span></span> <span data-ttu-id="cbb4d-143">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-143">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="cbb4d-144">必須。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-144">Required.</span></span> <span data-ttu-id="cbb4d-145">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-145">The job id.</span></span>
            </param>
        <param name="jobStreamId">
            <span data-ttu-id="cbb4d-146">必須。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-146">Required.</span></span> <span data-ttu-id="cbb4d-147">ジョブ ストリーム id です。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-147">The job stream id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbb4d-148">ジョブ ストリーム id によって識別されるジョブ ストリームを取得します。 (詳細については http://aka.ms/azureautomationsdk/jobstreamoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="cbb4d-148">Retrieve the job stream identified by job stream id.  (see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="cbb4d-149">ジョブ ストリームの取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-149">The response model for the get job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOutputAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt; GetOutputAsync (this Microsoft.Azure.Management.Automation.IDscCompilationJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId, string jobStreamId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt; GetOutputAsync(class Microsoft.Azure.Management.Automation.IDscCompilationJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId, string jobStreamId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscCompilationJobOperationsExtensions.GetOutputAsync(Microsoft.Azure.Management.Automation.IDscCompilationJobOperations,System.String,System.String,System.Guid,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetOutputAsync (operations As IDscCompilationJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid, jobStreamId As String) As Task(Of JobStreamGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetOutputAsync : Microsoft.Azure.Management.Automation.IDscCompilationJobOperations * string * string * Guid * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscCompilationJobOperationsExtensions.GetOutputAsync (operations, resourceGroupName, automationAccount, jobId, jobStreamId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscCompilationJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="jobStreamId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbb4d-150">Microsoft.Azure.Management.Automation.IDscCompilationJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-150">Reference to the Microsoft.Azure.Management.Automation.IDscCompilationJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbb4d-151">必須。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-151">Required.</span></span> <span data-ttu-id="cbb4d-152">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="cbb4d-152">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="cbb4d-153">必須。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-153">Required.</span></span> <span data-ttu-id="cbb4d-154">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-154">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="cbb4d-155">必須。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-155">Required.</span></span> <span data-ttu-id="cbb4d-156">ジョブ id。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-156">The job id.</span></span>
            </param>
        <param name="jobStreamId">
            <span data-ttu-id="cbb4d-157">必須。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-157">Required.</span></span> <span data-ttu-id="cbb4d-158">ジョブ ストリーム id です。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-158">The job stream id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbb4d-159">ジョブ ストリーム id によって識別されるジョブ ストリームを取得します。 (詳細については http://aka.ms/azureautomationsdk/jobstreamoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="cbb4d-159">Retrieve the job stream identified by job stream id.  (see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="cbb4d-160">ジョブ ストリームの取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-160">The response model for the get job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse List (this Microsoft.Azure.Management.Automation.IDscCompilationJobOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscCompilationJobListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse List(class Microsoft.Azure.Management.Automation.IDscCompilationJobOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscCompilationJobListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscCompilationJobOperationsExtensions.List(Microsoft.Azure.Management.Automation.IDscCompilationJobOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscCompilationJobListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDscCompilationJobOperations, resourceGroupName As String, automationAccount As String, parameters As DscCompilationJobListParameters) As DscCompilationJobListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IDscCompilationJobOperations * string * string * Microsoft.Azure.Management.Automation.Models.DscCompilationJobListParameters -&gt; Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse" Usage="Microsoft.Azure.Management.Automation.DscCompilationJobOperationsExtensions.List (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscCompilationJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscCompilationJobListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbb4d-161">Microsoft.Azure.Management.Automation.IDscCompilationJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-161">Reference to the Microsoft.Azure.Management.Automation.IDscCompilationJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbb4d-162">必須。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-162">Required.</span></span> <span data-ttu-id="cbb4d-163">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="cbb4d-163">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="cbb4d-164">必須。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-164">Required.</span></span> <span data-ttu-id="cbb4d-165">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-165">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cbb4d-166">省略可能。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-166">Optional.</span></span> <span data-ttu-id="cbb4d-167">一覧表示操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-167">The parameters supplied to the list operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbb4d-168">Dsc コンパイル ジョブの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-168">Retrieve a list of dsc compilation jobs.</span></span>  <span data-ttu-id="cbb4d-169">(詳細については http://aka.ms/azureautomationsdk/compilationjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="cbb4d-169">(see http://aka.ms/azureautomationsdk/compilationjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="cbb4d-170">一覧のジョブ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-170">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IDscCompilationJobOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscCompilationJobListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IDscCompilationJobOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscCompilationJobListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscCompilationJobOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IDscCompilationJobOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscCompilationJobListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IDscCompilationJobOperations, resourceGroupName As String, automationAccount As String, parameters As DscCompilationJobListParameters) As Task(Of DscCompilationJobListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IDscCompilationJobOperations * string * string * Microsoft.Azure.Management.Automation.Models.DscCompilationJobListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscCompilationJobOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscCompilationJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscCompilationJobListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbb4d-171">Microsoft.Azure.Management.Automation.IDscCompilationJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-171">Reference to the Microsoft.Azure.Management.Automation.IDscCompilationJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cbb4d-172">必須。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-172">Required.</span></span> <span data-ttu-id="cbb4d-173">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="cbb4d-173">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="cbb4d-174">必須。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-174">Required.</span></span> <span data-ttu-id="cbb4d-175">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-175">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cbb4d-176">省略可能。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-176">Optional.</span></span> <span data-ttu-id="cbb4d-177">一覧表示操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-177">The parameters supplied to the list operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbb4d-178">Dsc コンパイル ジョブの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-178">Retrieve a list of dsc compilation jobs.</span></span>  <span data-ttu-id="cbb4d-179">(詳細については http://aka.ms/azureautomationsdk/compilationjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="cbb4d-179">(see http://aka.ms/azureautomationsdk/compilationjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="cbb4d-180">一覧のジョブ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-180">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse ListNext (this Microsoft.Azure.Management.Automation.IDscCompilationJobOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse ListNext(class Microsoft.Azure.Management.Automation.IDscCompilationJobOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscCompilationJobOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IDscCompilationJobOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IDscCompilationJobOperations, nextLink As String) As DscCompilationJobListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IDscCompilationJobOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse" Usage="Microsoft.Azure.Management.Automation.DscCompilationJobOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscCompilationJobOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbb4d-181">Microsoft.Azure.Management.Automation.IDscCompilationJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-181">Reference to the Microsoft.Azure.Management.Automation.IDscCompilationJobOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="cbb4d-182">必須。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-182">Required.</span></span> <span data-ttu-id="cbb4d-183">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-183">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbb4d-184">Dsc コンパイル ジョブの [次へ] の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-184">Retrieve next list of dsc compilation jobs.</span></span>  <span data-ttu-id="cbb4d-185">(詳細については http://aka.ms/azureautomationsdk/compilationjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="cbb4d-185">(see http://aka.ms/azureautomationsdk/compilationjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="cbb4d-186">一覧のジョブ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-186">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IDscCompilationJobOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IDscCompilationJobOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscCompilationJobOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IDscCompilationJobOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IDscCompilationJobOperations, nextLink As String) As Task(Of DscCompilationJobListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IDscCompilationJobOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscCompilationJobOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscCompilationJobOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cbb4d-187">Microsoft.Azure.Management.Automation.IDscCompilationJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-187">Reference to the Microsoft.Azure.Management.Automation.IDscCompilationJobOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="cbb4d-188">必須。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-188">Required.</span></span> <span data-ttu-id="cbb4d-189">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-189">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cbb4d-190">Dsc コンパイル ジョブの [次へ] の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-190">Retrieve next list of dsc compilation jobs.</span></span>  <span data-ttu-id="cbb4d-191">(詳細については http://aka.ms/azureautomationsdk/compilationjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="cbb4d-191">(see http://aka.ms/azureautomationsdk/compilationjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="cbb4d-192">一覧のジョブ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="cbb4d-192">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>