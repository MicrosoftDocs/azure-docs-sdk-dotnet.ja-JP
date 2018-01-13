<Type Name="AutomationAccountOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AutomationAccountOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AutomationAccountOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AutomationAccountOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AutomationAccountOperationsExtensions = class" />
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
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, class Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Automation.IAutomationAccountOperations,System.String,Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IAutomationAccountOperations, resourceGroupName As String, parameters As AutomationAccountCreateOrUpdateParameters) As AutomationAccountCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Automation.IAutomationAccountOperations * string * Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76f74-101">Microsoft.Azure.Management.Automation.IAutomationAccountOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="76f74-101">Reference to the Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76f74-102">必須。</span><span class="sxs-lookup"><span data-stu-id="76f74-102">Required.</span></span> <span data-ttu-id="76f74-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="76f74-103">The name of the resource group</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="76f74-104">必須。</span><span class="sxs-lookup"><span data-stu-id="76f74-104">Required.</span></span> <span data-ttu-id="76f74-105">作成または更新のオートメーション アカウントに指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="76f74-105">Parameters supplied to the create or update automation account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76f74-106">Automation アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="76f74-106">Create an automation account.</span></span>  <span data-ttu-id="76f74-107">(詳細については http://aka.ms/azureautomationsdk/automationaccountoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="76f74-107">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76f74-108">アカウントの作成または更新の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="76f74-108">The response model for the create or update account operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, class Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Automation.IAutomationAccountOperations,System.String,Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IAutomationAccountOperations, resourceGroupName As String, parameters As AutomationAccountCreateOrUpdateParameters) As Task(Of AutomationAccountCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Automation.IAutomationAccountOperations * string * Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76f74-109">Microsoft.Azure.Management.Automation.IAutomationAccountOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="76f74-109">Reference to the Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76f74-110">必須。</span><span class="sxs-lookup"><span data-stu-id="76f74-110">Required.</span></span> <span data-ttu-id="76f74-111">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="76f74-111">The name of the resource group</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="76f74-112">必須。</span><span class="sxs-lookup"><span data-stu-id="76f74-112">Required.</span></span> <span data-ttu-id="76f74-113">作成または更新のオートメーション アカウントに指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="76f74-113">Parameters supplied to the create or update automation account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76f74-114">Automation アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="76f74-114">Create an automation account.</span></span>  <span data-ttu-id="76f74-115">(詳細については http://aka.ms/azureautomationsdk/automationaccountoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="76f74-115">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76f74-116">アカウントの作成または更新の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="76f74-116">The response model for the create or update account operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, string automationAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, string automationAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.Delete(Microsoft.Azure.Management.Automation.IAutomationAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IAutomationAccountOperations, resourceGroupName As String, automationAccountName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Automation.IAutomationAccountOperations * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.Delete (operations, resourceGroupName, automationAccountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76f74-117">Microsoft.Azure.Management.Automation.IAutomationAccountOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="76f74-117">Reference to the Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76f74-118">必須。</span><span class="sxs-lookup"><span data-stu-id="76f74-118">Required.</span></span> <span data-ttu-id="76f74-119">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="76f74-119">The name of the resource group</span></span>
            </param>
        <param name="automationAccountName">
            <span data-ttu-id="76f74-120">必須。</span><span class="sxs-lookup"><span data-stu-id="76f74-120">Required.</span></span> <span data-ttu-id="76f74-121">オートメーション アカウントの名前です。</span><span class="sxs-lookup"><span data-stu-id="76f74-121">Automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76f74-122">Automation アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="76f74-122">Create an automation account.</span></span>  <span data-ttu-id="76f74-123">(詳細については http://aka.ms/azureautomationsdk/automationaccountoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="76f74-123">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76f74-124">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="76f74-124">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, string automationAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, string automationAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Automation.IAutomationAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IAutomationAccountOperations, resourceGroupName As String, automationAccountName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Automation.IAutomationAccountOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.DeleteAsync (operations, resourceGroupName, automationAccountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76f74-125">Microsoft.Azure.Management.Automation.IAutomationAccountOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="76f74-125">Reference to the Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76f74-126">必須。</span><span class="sxs-lookup"><span data-stu-id="76f74-126">Required.</span></span> <span data-ttu-id="76f74-127">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="76f74-127">The name of the resource group</span></span>
            </param>
        <param name="automationAccountName">
            <span data-ttu-id="76f74-128">必須。</span><span class="sxs-lookup"><span data-stu-id="76f74-128">Required.</span></span> <span data-ttu-id="76f74-129">オートメーション アカウントの名前です。</span><span class="sxs-lookup"><span data-stu-id="76f74-129">Automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76f74-130">Automation アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="76f74-130">Create an automation account.</span></span>  <span data-ttu-id="76f74-131">(詳細については http://aka.ms/azureautomationsdk/automationaccountoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="76f74-131">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76f74-132">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="76f74-132">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.AutomationAccountGetResponse Get (this Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.AutomationAccountGetResponse Get(class Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IAutomationAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IAutomationAccountOperations, resourceGroupName As String, automationAccount As String) As AutomationAccountGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IAutomationAccountOperations * string * string -&gt; Microsoft.Azure.Management.Automation.Models.AutomationAccountGetResponse" Usage="Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.Get (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.AutomationAccountGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76f74-133">Microsoft.Azure.Management.Automation.IAutomationAccountOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="76f74-133">Reference to the Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76f74-134">必須。</span><span class="sxs-lookup"><span data-stu-id="76f74-134">Required.</span></span> <span data-ttu-id="76f74-135">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="76f74-135">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="76f74-136">必須。</span><span class="sxs-lookup"><span data-stu-id="76f74-136">Required.</span></span> <span data-ttu-id="76f74-137">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="76f74-137">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76f74-138">アカウントのアカウント名を取得します。</span><span class="sxs-lookup"><span data-stu-id="76f74-138">Retrieve the account by account name.</span></span>  <span data-ttu-id="76f74-139">(詳細については http://aka.ms/azureautomationsdk/automationaccountoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="76f74-139">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76f74-140">アカウントの取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="76f74-140">The response model for the get account operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.AutomationAccountGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IAutomationAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IAutomationAccountOperations, resourceGroupName As String, automationAccount As String) As Task(Of AutomationAccountGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IAutomationAccountOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76f74-141">Microsoft.Azure.Management.Automation.IAutomationAccountOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="76f74-141">Reference to the Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76f74-142">必須。</span><span class="sxs-lookup"><span data-stu-id="76f74-142">Required.</span></span> <span data-ttu-id="76f74-143">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="76f74-143">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="76f74-144">必須。</span><span class="sxs-lookup"><span data-stu-id="76f74-144">Required.</span></span> <span data-ttu-id="76f74-145">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="76f74-145">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76f74-146">アカウントのアカウント名を取得します。</span><span class="sxs-lookup"><span data-stu-id="76f74-146">Retrieve the account by account name.</span></span>  <span data-ttu-id="76f74-147">(詳細については http://aka.ms/azureautomationsdk/automationaccountoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="76f74-147">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76f74-148">アカウントの取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="76f74-148">The response model for the get account operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse List (this Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse List(class Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.List(Microsoft.Azure.Management.Automation.IAutomationAccountOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IAutomationAccountOperations, resourceGroupName As String) As AutomationAccountListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IAutomationAccountOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse" Usage="Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76f74-149">Microsoft.Azure.Management.Automation.IAutomationAccountOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="76f74-149">Reference to the Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76f74-150">省略可能。</span><span class="sxs-lookup"><span data-stu-id="76f74-150">Optional.</span></span> <span data-ttu-id="76f74-151">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="76f74-151">The name of the resource group</span></span>
            </param>
        <summary>
            <span data-ttu-id="76f74-152">アカウントの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="76f74-152">Retrieve a list of accounts.</span></span>  <span data-ttu-id="76f74-153">(詳細については http://aka.ms/azureautomationsdk/automationaccountoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="76f74-153">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76f74-154">アカウントの一覧の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="76f74-154">The response model for the list account operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IAutomationAccountOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IAutomationAccountOperations, resourceGroupName As String) As Task(Of AutomationAccountListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IAutomationAccountOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.ListAsync (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76f74-155">Microsoft.Azure.Management.Automation.IAutomationAccountOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="76f74-155">Reference to the Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76f74-156">省略可能。</span><span class="sxs-lookup"><span data-stu-id="76f74-156">Optional.</span></span> <span data-ttu-id="76f74-157">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="76f74-157">The name of the resource group</span></span>
            </param>
        <summary>
            <span data-ttu-id="76f74-158">アカウントの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="76f74-158">Retrieve a list of accounts.</span></span>  <span data-ttu-id="76f74-159">(詳細については http://aka.ms/azureautomationsdk/automationaccountoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="76f74-159">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76f74-160">アカウントの一覧の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="76f74-160">The response model for the list account operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse ListNext (this Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse ListNext(class Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IAutomationAccountOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IAutomationAccountOperations, nextLink As String) As AutomationAccountListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IAutomationAccountOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse" Usage="Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationAccountOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76f74-161">Microsoft.Azure.Management.Automation.IAutomationAccountOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="76f74-161">Reference to the Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="76f74-162">必須。</span><span class="sxs-lookup"><span data-stu-id="76f74-162">Required.</span></span> <span data-ttu-id="76f74-163">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="76f74-163">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76f74-164">アカウントの [次へ] の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="76f74-164">Retrieve next list of accounts.</span></span>  <span data-ttu-id="76f74-165">(詳細については http://aka.ms/azureautomationsdk/automationaccountoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="76f74-165">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76f74-166">アカウントの一覧の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="76f74-166">The response model for the list account operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IAutomationAccountOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IAutomationAccountOperations, nextLink As String) As Task(Of AutomationAccountListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IAutomationAccountOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationAccountOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76f74-167">Microsoft.Azure.Management.Automation.IAutomationAccountOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="76f74-167">Reference to the Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="76f74-168">必須。</span><span class="sxs-lookup"><span data-stu-id="76f74-168">Required.</span></span> <span data-ttu-id="76f74-169">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="76f74-169">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76f74-170">アカウントの [次へ] の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="76f74-170">Retrieve next list of accounts.</span></span>  <span data-ttu-id="76f74-171">(詳細については http://aka.ms/azureautomationsdk/automationaccountoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="76f74-171">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76f74-172">アカウントの一覧の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="76f74-172">The response model for the list account operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchResponse Patch (this Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchResponse Patch(class Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, class Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.Patch(Microsoft.Azure.Management.Automation.IAutomationAccountOperations,System.String,Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Patch (operations As IAutomationAccountOperations, resourceGroupName As String, parameters As AutomationAccountPatchParameters) As AutomationAccountPatchResponse" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Management.Automation.IAutomationAccountOperations * string * Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters -&gt; Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchResponse" Usage="Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.Patch (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76f74-173">Microsoft.Azure.Management.Automation.IAutomationAccountOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="76f74-173">Reference to the Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76f74-174">必須。</span><span class="sxs-lookup"><span data-stu-id="76f74-174">Required.</span></span> <span data-ttu-id="76f74-175">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="76f74-175">The name of the resource group</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="76f74-176">必須。</span><span class="sxs-lookup"><span data-stu-id="76f74-176">Required.</span></span> <span data-ttu-id="76f74-177">修正プログラムのオートメーション アカウントに指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="76f74-177">Parameters supplied to the patch automation account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76f74-178">Automation アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="76f74-178">Create an automation account.</span></span>  <span data-ttu-id="76f74-179">(詳細については http://aka.ms/azureautomationsdk/automationaccountoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="76f74-179">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76f74-180">アカウントの作成操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="76f74-180">The response model for the create account operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchResponse&gt; PatchAsync (this Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchResponse&gt; PatchAsync(class Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, class Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.PatchAsync(Microsoft.Azure.Management.Automation.IAutomationAccountOperations,System.String,Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PatchAsync (operations As IAutomationAccountOperations, resourceGroupName As String, parameters As AutomationAccountPatchParameters) As Task(Of AutomationAccountPatchResponse)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Management.Automation.IAutomationAccountOperations * string * Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchResponse&gt;" Usage="Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.PatchAsync (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76f74-181">Microsoft.Azure.Management.Automation.IAutomationAccountOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="76f74-181">Reference to the Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76f74-182">必須。</span><span class="sxs-lookup"><span data-stu-id="76f74-182">Required.</span></span> <span data-ttu-id="76f74-183">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="76f74-183">The name of the resource group</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="76f74-184">必須。</span><span class="sxs-lookup"><span data-stu-id="76f74-184">Required.</span></span> <span data-ttu-id="76f74-185">修正プログラムのオートメーション アカウントに指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="76f74-185">Parameters supplied to the patch automation account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76f74-186">Automation アカウントを作成します。</span><span class="sxs-lookup"><span data-stu-id="76f74-186">Create an automation account.</span></span>  <span data-ttu-id="76f74-187">(詳細については http://aka.ms/azureautomationsdk/automationaccountoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="76f74-187">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76f74-188">アカウントの作成操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="76f74-188">The response model for the create account operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>