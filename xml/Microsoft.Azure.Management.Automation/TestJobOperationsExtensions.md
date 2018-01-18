<Type Name="TestJobOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.TestJobOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TestJobOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TestJobOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.TestJobOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TestJobOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TestJobOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse Create (this Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse Create(class Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.Create(Microsoft.Azure.Management.Automation.ITestJobOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As ITestJobOperations, resourceGroupName As String, automationAccount As String, parameters As TestJobCreateParameters) As TestJobCreateResponse" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Automation.ITestJobOperations * string * string * Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters -&gt; Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse" Usage="Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.Create (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ITestJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="edd46-101">Microsoft.Azure.Management.Automation.ITestJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="edd46-101">Reference to the Microsoft.Azure.Management.Automation.ITestJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="edd46-102">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-102">Required.</span></span> <span data-ttu-id="edd46-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="edd46-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="edd46-104">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-104">Required.</span></span> <span data-ttu-id="edd46-105">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="edd46-105">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="edd46-106">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-106">Required.</span></span> <span data-ttu-id="edd46-107">作成のテスト ジョブの操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="edd46-107">The parameters supplied to the create test job operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="edd46-108">Runbook のテスト ジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="edd46-108">Create a test job of the runbook.</span></span>  <span data-ttu-id="edd46-109">(詳細については http://aka.ms/azureautomationsdk/testjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="edd46-109">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="edd46-110">作成の応答モデルでは、ジョブ操作をテストします。</span><span class="sxs-lookup"><span data-stu-id="edd46-110">The response model for the create test job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse&gt; CreateAsync (this Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse&gt; CreateAsync(class Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Automation.ITestJobOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateAsync (operations As ITestJobOperations, resourceGroupName As String, automationAccount As String, parameters As TestJobCreateParameters) As Task(Of TestJobCreateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Automation.ITestJobOperations * string * string * Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse&gt;" Usage="Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.CreateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ITestJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="edd46-111">Microsoft.Azure.Management.Automation.ITestJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="edd46-111">Reference to the Microsoft.Azure.Management.Automation.ITestJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="edd46-112">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-112">Required.</span></span> <span data-ttu-id="edd46-113">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="edd46-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="edd46-114">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-114">Required.</span></span> <span data-ttu-id="edd46-115">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="edd46-115">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="edd46-116">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-116">Required.</span></span> <span data-ttu-id="edd46-117">作成のテスト ジョブの操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="edd46-117">The parameters supplied to the create test job operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="edd46-118">Runbook のテスト ジョブを作成します。</span><span class="sxs-lookup"><span data-stu-id="edd46-118">Create a test job of the runbook.</span></span>  <span data-ttu-id="edd46-119">(詳細については http://aka.ms/azureautomationsdk/testjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="edd46-119">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="edd46-120">作成の応答モデルでは、ジョブ操作をテストします。</span><span class="sxs-lookup"><span data-stu-id="edd46-120">The response model for the create test job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.TestJobGetResponse Get (this Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.TestJobGetResponse Get(class Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.Get(Microsoft.Azure.Management.Automation.ITestJobOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ITestJobOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As TestJobGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.ITestJobOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.TestJobGetResponse" Usage="Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.Get (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.TestJobGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ITestJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="edd46-121">Microsoft.Azure.Management.Automation.ITestJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="edd46-121">Reference to the Microsoft.Azure.Management.Automation.ITestJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="edd46-122">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-122">Required.</span></span> <span data-ttu-id="edd46-123">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="edd46-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="edd46-124">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-124">Required.</span></span> <span data-ttu-id="edd46-125">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="edd46-125">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="edd46-126">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-126">Required.</span></span> <span data-ttu-id="edd46-127">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="edd46-127">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="edd46-128">指定された runbook のテスト ジョブを取得します。</span><span class="sxs-lookup"><span data-stu-id="edd46-128">Retrieve the test job for the specified runbook.</span></span>  <span data-ttu-id="edd46-129">(詳細については http://aka.ms/azureautomationsdk/testjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="edd46-129">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="edd46-130">Get 応答モデルでは、ジョブ操作をテストします。</span><span class="sxs-lookup"><span data-stu-id="edd46-130">The response model for the get test job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.TestJobGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.ITestJobOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As ITestJobOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As Task(Of TestJobGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.ITestJobOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ITestJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="edd46-131">Microsoft.Azure.Management.Automation.ITestJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="edd46-131">Reference to the Microsoft.Azure.Management.Automation.ITestJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="edd46-132">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-132">Required.</span></span> <span data-ttu-id="edd46-133">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="edd46-133">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="edd46-134">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-134">Required.</span></span> <span data-ttu-id="edd46-135">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="edd46-135">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="edd46-136">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-136">Required.</span></span> <span data-ttu-id="edd46-137">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="edd46-137">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="edd46-138">指定された runbook のテスト ジョブを取得します。</span><span class="sxs-lookup"><span data-stu-id="edd46-138">Retrieve the test job for the specified runbook.</span></span>  <span data-ttu-id="edd46-139">(詳細については http://aka.ms/azureautomationsdk/testjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="edd46-139">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="edd46-140">Get 応答モデルでは、ジョブ操作をテストします。</span><span class="sxs-lookup"><span data-stu-id="edd46-140">The response model for the get test job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resume">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Resume (this Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Resume(class Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.Resume(Microsoft.Azure.Management.Automation.ITestJobOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Resume (operations As ITestJobOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Resume : Microsoft.Azure.Management.Automation.ITestJobOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.Resume (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ITestJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="edd46-141">Microsoft.Azure.Management.Automation.ITestJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="edd46-141">Reference to the Microsoft.Azure.Management.Automation.ITestJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="edd46-142">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-142">Required.</span></span> <span data-ttu-id="edd46-143">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="edd46-143">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="edd46-144">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-144">Required.</span></span> <span data-ttu-id="edd46-145">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="edd46-145">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="edd46-146">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-146">Required.</span></span> <span data-ttu-id="edd46-147">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="edd46-147">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="edd46-148">テスト ジョブを再開します。</span><span class="sxs-lookup"><span data-stu-id="edd46-148">Resume the test job.</span></span>  <span data-ttu-id="edd46-149">(詳細については http://aka.ms/azureautomationsdk/testjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="edd46-149">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="edd46-150">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="edd46-150">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync (this Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync(class Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.ResumeAsync(Microsoft.Azure.Management.Automation.ITestJobOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ResumeAsync (operations As ITestJobOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member ResumeAsync : Microsoft.Azure.Management.Automation.ITestJobOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.ResumeAsync (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ITestJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="edd46-151">Microsoft.Azure.Management.Automation.ITestJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="edd46-151">Reference to the Microsoft.Azure.Management.Automation.ITestJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="edd46-152">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-152">Required.</span></span> <span data-ttu-id="edd46-153">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="edd46-153">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="edd46-154">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-154">Required.</span></span> <span data-ttu-id="edd46-155">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="edd46-155">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="edd46-156">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-156">Required.</span></span> <span data-ttu-id="edd46-157">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="edd46-157">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="edd46-158">テスト ジョブを再開します。</span><span class="sxs-lookup"><span data-stu-id="edd46-158">Resume the test job.</span></span>  <span data-ttu-id="edd46-159">(詳細については http://aka.ms/azureautomationsdk/testjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="edd46-159">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="edd46-160">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="edd46-160">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stop">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Stop (this Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Stop(class Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.Stop(Microsoft.Azure.Management.Automation.ITestJobOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Stop (operations As ITestJobOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Stop : Microsoft.Azure.Management.Automation.ITestJobOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.Stop (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ITestJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="edd46-161">Microsoft.Azure.Management.Automation.ITestJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="edd46-161">Reference to the Microsoft.Azure.Management.Automation.ITestJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="edd46-162">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-162">Required.</span></span> <span data-ttu-id="edd46-163">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="edd46-163">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="edd46-164">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-164">Required.</span></span> <span data-ttu-id="edd46-165">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="edd46-165">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="edd46-166">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-166">Required.</span></span> <span data-ttu-id="edd46-167">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="edd46-167">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="edd46-168">テスト ジョブを停止します。</span><span class="sxs-lookup"><span data-stu-id="edd46-168">Stop the test job.</span></span>  <span data-ttu-id="edd46-169">(詳細については http://aka.ms/azureautomationsdk/testjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="edd46-169">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="edd46-170">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="edd46-170">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; StopAsync (this Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; StopAsync(class Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.StopAsync(Microsoft.Azure.Management.Automation.ITestJobOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function StopAsync (operations As ITestJobOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member StopAsync : Microsoft.Azure.Management.Automation.ITestJobOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.StopAsync (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ITestJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="edd46-171">Microsoft.Azure.Management.Automation.ITestJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="edd46-171">Reference to the Microsoft.Azure.Management.Automation.ITestJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="edd46-172">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-172">Required.</span></span> <span data-ttu-id="edd46-173">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="edd46-173">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="edd46-174">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-174">Required.</span></span> <span data-ttu-id="edd46-175">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="edd46-175">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="edd46-176">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-176">Required.</span></span> <span data-ttu-id="edd46-177">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="edd46-177">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="edd46-178">テスト ジョブを停止します。</span><span class="sxs-lookup"><span data-stu-id="edd46-178">Stop the test job.</span></span>  <span data-ttu-id="edd46-179">(詳細については http://aka.ms/azureautomationsdk/testjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="edd46-179">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="edd46-180">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="edd46-180">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Suspend">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Suspend (this Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Suspend(class Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.Suspend(Microsoft.Azure.Management.Automation.ITestJobOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Suspend (operations As ITestJobOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Suspend : Microsoft.Azure.Management.Automation.ITestJobOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.Suspend (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ITestJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="edd46-181">Microsoft.Azure.Management.Automation.ITestJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="edd46-181">Reference to the Microsoft.Azure.Management.Automation.ITestJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="edd46-182">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-182">Required.</span></span> <span data-ttu-id="edd46-183">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="edd46-183">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="edd46-184">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-184">Required.</span></span> <span data-ttu-id="edd46-185">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="edd46-185">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="edd46-186">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-186">Required.</span></span> <span data-ttu-id="edd46-187">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="edd46-187">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="edd46-188">テスト ジョブを中断します。</span><span class="sxs-lookup"><span data-stu-id="edd46-188">Suspend the test job.</span></span>  <span data-ttu-id="edd46-189">(詳細については http://aka.ms/azureautomationsdk/testjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="edd46-189">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="edd46-190">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="edd46-190">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync (this Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync(class Microsoft.Azure.Management.Automation.ITestJobOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.SuspendAsync(Microsoft.Azure.Management.Automation.ITestJobOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SuspendAsync (operations As ITestJobOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member SuspendAsync : Microsoft.Azure.Management.Automation.ITestJobOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.TestJobOperationsExtensions.SuspendAsync (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ITestJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="edd46-191">Microsoft.Azure.Management.Automation.ITestJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="edd46-191">Reference to the Microsoft.Azure.Management.Automation.ITestJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="edd46-192">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-192">Required.</span></span> <span data-ttu-id="edd46-193">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="edd46-193">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="edd46-194">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-194">Required.</span></span> <span data-ttu-id="edd46-195">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="edd46-195">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="edd46-196">必須。</span><span class="sxs-lookup"><span data-stu-id="edd46-196">Required.</span></span> <span data-ttu-id="edd46-197">Runbook の名前です。</span><span class="sxs-lookup"><span data-stu-id="edd46-197">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="edd46-198">テスト ジョブを中断します。</span><span class="sxs-lookup"><span data-stu-id="edd46-198">Suspend the test job.</span></span>  <span data-ttu-id="edd46-199">(詳細については http://aka.ms/azureautomationsdk/testjoboperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="edd46-199">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="edd46-200">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="edd46-200">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>