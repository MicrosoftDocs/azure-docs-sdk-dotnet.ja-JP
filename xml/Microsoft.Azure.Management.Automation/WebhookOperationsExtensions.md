<Type Name="WebhookOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class WebhookOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit WebhookOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module WebhookOperationsExtensions" />
  <TypeSignature Language="F#" Value="type WebhookOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, parameters As WebhookCreateOrUpdateParameters) As WebhookCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d8982-101">Microsoft.Azure.Management.Automation.IWebhookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="d8982-101">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d8982-102">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-102">Required.</span></span> <span data-ttu-id="d8982-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="d8982-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="d8982-104">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-104">Required.</span></span> <span data-ttu-id="d8982-105">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d8982-105">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d8982-106">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-106">Required.</span></span> <span data-ttu-id="d8982-107">Webhook の作成または更新プログラムのパラメーター。</span><span class="sxs-lookup"><span data-stu-id="d8982-107">The create or update parameters for webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d8982-108">Webhook の名前によって識別される webhook を作成します。</span><span class="sxs-lookup"><span data-stu-id="d8982-108">Create the webhook identified by webhook name.</span></span>  <span data-ttu-id="d8982-109">(詳細については http://aka.ms/azureautomationsdk/webhookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="d8982-109">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d8982-110">作成または更新の webhook 操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="d8982-110">The response model for the create or update webhook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, parameters As WebhookCreateOrUpdateParameters) As Task(Of WebhookCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d8982-111">Microsoft.Azure.Management.Automation.IWebhookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="d8982-111">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d8982-112">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-112">Required.</span></span> <span data-ttu-id="d8982-113">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="d8982-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="d8982-114">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-114">Required.</span></span> <span data-ttu-id="d8982-115">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d8982-115">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d8982-116">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-116">Required.</span></span> <span data-ttu-id="d8982-117">Webhook の作成または更新プログラムのパラメーター。</span><span class="sxs-lookup"><span data-stu-id="d8982-117">The create or update parameters for webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d8982-118">Webhook の名前によって識別される webhook を作成します。</span><span class="sxs-lookup"><span data-stu-id="d8982-118">Create the webhook identified by webhook name.</span></span>  <span data-ttu-id="d8982-119">(詳細については http://aka.ms/azureautomationsdk/webhookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="d8982-119">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d8982-120">作成または更新の webhook 操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="d8982-120">The response model for the create or update webhook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string webhookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string webhookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.Delete(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, webhookName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.Delete (operations, resourceGroupName, automationAccount, webhookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d8982-121">Microsoft.Azure.Management.Automation.IWebhookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="d8982-121">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d8982-122">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-122">Required.</span></span> <span data-ttu-id="d8982-123">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="d8982-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="d8982-124">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-124">Required.</span></span> <span data-ttu-id="d8982-125">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d8982-125">The automation account name.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="d8982-126">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-126">Required.</span></span> <span data-ttu-id="d8982-127">Webhook の名前です。</span><span class="sxs-lookup"><span data-stu-id="d8982-127">The webhook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d8982-128">名前で、webhook を削除します。</span><span class="sxs-lookup"><span data-stu-id="d8982-128">Delete the webhook by name.</span></span>  <span data-ttu-id="d8982-129">(詳細については http://aka.ms/azureautomationsdk/webhookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="d8982-129">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d8982-130">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="d8982-130">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string webhookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string webhookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, webhookName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.DeleteAsync (operations, resourceGroupName, automationAccount, webhookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d8982-131">Microsoft.Azure.Management.Automation.IWebhookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="d8982-131">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d8982-132">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-132">Required.</span></span> <span data-ttu-id="d8982-133">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="d8982-133">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="d8982-134">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-134">Required.</span></span> <span data-ttu-id="d8982-135">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d8982-135">The automation account name.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="d8982-136">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-136">Required.</span></span> <span data-ttu-id="d8982-137">Webhook の名前です。</span><span class="sxs-lookup"><span data-stu-id="d8982-137">The webhook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d8982-138">名前で、webhook を削除します。</span><span class="sxs-lookup"><span data-stu-id="d8982-138">Delete the webhook by name.</span></span>  <span data-ttu-id="d8982-139">(詳細については http://aka.ms/azureautomationsdk/webhookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="d8982-139">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d8982-140">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="d8982-140">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateUri">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse GenerateUri (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse GenerateUri(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.GenerateUri(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GenerateUri (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String) As WebhookGenerateUriResponse" />
      <MemberSignature Language="F#" Value="static member GenerateUri : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string -&gt; Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.GenerateUri (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d8982-141">Microsoft.Azure.Management.Automation.IWebhookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="d8982-141">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d8982-142">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-142">Required.</span></span> <span data-ttu-id="d8982-143">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d8982-143">The name of the resource group.</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="d8982-144">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-144">Required.</span></span> <span data-ttu-id="d8982-145">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d8982-145">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d8982-146">Webhook の作成に使用するための Uri を生成します。</span><span class="sxs-lookup"><span data-stu-id="d8982-146">Generates a Uri for use in creating a webhook.</span></span>  <span data-ttu-id="d8982-147">(詳細については http://aka.ms/azureautomationsdk/webhookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="d8982-147">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d8982-148">Webhook の応答モデルでは、uri の応答を取得します。</span><span class="sxs-lookup"><span data-stu-id="d8982-148">The response model for the webhook get uri response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateUriAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse&gt; GenerateUriAsync (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse&gt; GenerateUriAsync(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.GenerateUriAsync(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GenerateUriAsync (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String) As Task(Of WebhookGenerateUriResponse)" />
      <MemberSignature Language="F#" Value="static member GenerateUriAsync : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse&gt;" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.GenerateUriAsync (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d8982-149">Microsoft.Azure.Management.Automation.IWebhookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="d8982-149">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d8982-150">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-150">Required.</span></span> <span data-ttu-id="d8982-151">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d8982-151">The name of the resource group.</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="d8982-152">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-152">Required.</span></span> <span data-ttu-id="d8982-153">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d8982-153">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d8982-154">Webhook の作成に使用するための Uri を生成します。</span><span class="sxs-lookup"><span data-stu-id="d8982-154">Generates a Uri for use in creating a webhook.</span></span>  <span data-ttu-id="d8982-155">(詳細については http://aka.ms/azureautomationsdk/webhookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="d8982-155">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d8982-156">Webhook の応答モデルでは、uri の応答を取得します。</span><span class="sxs-lookup"><span data-stu-id="d8982-156">The response model for the webhook get uri response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.WebhookGetResponse Get (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string webhookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.WebhookGetResponse Get(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string webhookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, webhookName As String) As WebhookGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.WebhookGetResponse" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.Get (operations, resourceGroupName, automationAccount, webhookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.WebhookGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d8982-157">Microsoft.Azure.Management.Automation.IWebhookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="d8982-157">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d8982-158">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-158">Required.</span></span> <span data-ttu-id="d8982-159">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="d8982-159">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="d8982-160">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-160">Required.</span></span> <span data-ttu-id="d8982-161">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d8982-161">The automation account name.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="d8982-162">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-162">Required.</span></span> <span data-ttu-id="d8982-163">Webhook の名前です。</span><span class="sxs-lookup"><span data-stu-id="d8982-163">The webhook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d8982-164">Webhook の名前によって識別される webhook を取得します。</span><span class="sxs-lookup"><span data-stu-id="d8982-164">Retrieve the webhook identified by webhook name.</span></span>  <span data-ttu-id="d8982-165">(詳細については http://aka.ms/azureautomationsdk/webhookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="d8982-165">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d8982-166">Webhook の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="d8982-166">The response model for the get webhook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string webhookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string webhookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, webhookName As String) As Task(Of WebhookGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, webhookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d8982-167">Microsoft.Azure.Management.Automation.IWebhookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="d8982-167">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d8982-168">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-168">Required.</span></span> <span data-ttu-id="d8982-169">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="d8982-169">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="d8982-170">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-170">Required.</span></span> <span data-ttu-id="d8982-171">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d8982-171">The automation account name.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="d8982-172">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-172">Required.</span></span> <span data-ttu-id="d8982-173">Webhook の名前です。</span><span class="sxs-lookup"><span data-stu-id="d8982-173">The webhook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d8982-174">Webhook の名前によって識別される webhook を取得します。</span><span class="sxs-lookup"><span data-stu-id="d8982-174">Retrieve the webhook identified by webhook name.</span></span>  <span data-ttu-id="d8982-175">(詳細については http://aka.ms/azureautomationsdk/webhookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="d8982-175">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d8982-176">Webhook の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="d8982-176">The response model for the get webhook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.WebhookListResponse List (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.WebhookListResponse List(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.List(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As WebhookListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.WebhookListResponse" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.List (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.WebhookListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d8982-177">Microsoft.Azure.Management.Automation.IWebhookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="d8982-177">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d8982-178">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-178">Required.</span></span> <span data-ttu-id="d8982-179">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="d8982-179">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="d8982-180">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-180">Required.</span></span> <span data-ttu-id="d8982-181">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d8982-181">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="d8982-182">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d8982-182">Optional.</span></span> <span data-ttu-id="d8982-183">Automation runbook の名前。</span><span class="sxs-lookup"><span data-stu-id="d8982-183">The automation runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d8982-184">Webhook の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="d8982-184">Retrieve a list of webhooks.</span></span>  <span data-ttu-id="d8982-185">(詳細については http://aka.ms/azureautomationsdk/webhookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="d8982-185">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d8982-186">一覧の webhook 操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="d8982-186">The response model for the list webhook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As Task(Of WebhookListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d8982-187">Microsoft.Azure.Management.Automation.IWebhookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="d8982-187">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d8982-188">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-188">Required.</span></span> <span data-ttu-id="d8982-189">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="d8982-189">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="d8982-190">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-190">Required.</span></span> <span data-ttu-id="d8982-191">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d8982-191">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="d8982-192">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d8982-192">Optional.</span></span> <span data-ttu-id="d8982-193">Automation runbook の名前。</span><span class="sxs-lookup"><span data-stu-id="d8982-193">The automation runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d8982-194">Webhook の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="d8982-194">Retrieve a list of webhooks.</span></span>  <span data-ttu-id="d8982-195">(詳細については http://aka.ms/azureautomationsdk/webhookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="d8982-195">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d8982-196">一覧の webhook 操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="d8982-196">The response model for the list webhook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.WebhookListResponse ListNext (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.WebhookListResponse ListNext(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IWebhookOperations, nextLink As String) As WebhookListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IWebhookOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.WebhookListResponse" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.WebhookListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d8982-197">Microsoft.Azure.Management.Automation.IWebhookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="d8982-197">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="d8982-198">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-198">Required.</span></span> <span data-ttu-id="d8982-199">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="d8982-199">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d8982-200">Webhook の次の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="d8982-200">Retrieve next list of webhooks.</span></span>  <span data-ttu-id="d8982-201">(詳細については http://aka.ms/azureautomationsdk/webhookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="d8982-201">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d8982-202">一覧の webhook 操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="d8982-202">The response model for the list webhook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IWebhookOperations, nextLink As String) As Task(Of WebhookListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IWebhookOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d8982-203">Microsoft.Azure.Management.Automation.IWebhookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="d8982-203">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="d8982-204">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-204">Required.</span></span> <span data-ttu-id="d8982-205">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="d8982-205">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d8982-206">Webhook の次の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="d8982-206">Retrieve next list of webhooks.</span></span>  <span data-ttu-id="d8982-207">(詳細については http://aka.ms/azureautomationsdk/webhookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="d8982-207">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d8982-208">一覧の webhook 操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="d8982-208">The response model for the list webhook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.WebhookGetResponse Patch (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.WebhookGetResponse Patch(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.Patch(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Patch (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, parameters As WebhookPatchParameters) As WebhookGetResponse" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters -&gt; Microsoft.Azure.Management.Automation.Models.WebhookGetResponse" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.Patch (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.WebhookGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d8982-209">Microsoft.Azure.Management.Automation.IWebhookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="d8982-209">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d8982-210">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-210">Required.</span></span> <span data-ttu-id="d8982-211">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="d8982-211">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="d8982-212">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-212">Required.</span></span> <span data-ttu-id="d8982-213">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d8982-213">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d8982-214">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-214">Required.</span></span> <span data-ttu-id="d8982-215">Webhook の更新プログラムのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="d8982-215">The patch parameters for webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d8982-216">Webhook の webhook 名によって識別される修正プログラムを適用します。</span><span class="sxs-lookup"><span data-stu-id="d8982-216">Patch the webhook identified by webhook name.</span></span>  <span data-ttu-id="d8982-217">(詳細については http://aka.ms/azureautomationsdk/webhookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="d8982-217">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d8982-218">Webhook の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="d8982-218">The response model for the get webhook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt; PatchAsync (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt; PatchAsync(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.PatchAsync(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PatchAsync (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, parameters As WebhookPatchParameters) As Task(Of WebhookGetResponse)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.PatchAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d8982-219">Microsoft.Azure.Management.Automation.IWebhookOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="d8982-219">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d8982-220">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-220">Required.</span></span> <span data-ttu-id="d8982-221">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="d8982-221">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="d8982-222">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-222">Required.</span></span> <span data-ttu-id="d8982-223">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="d8982-223">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d8982-224">必須。</span><span class="sxs-lookup"><span data-stu-id="d8982-224">Required.</span></span> <span data-ttu-id="d8982-225">Webhook の更新プログラムのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="d8982-225">The patch parameters for webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d8982-226">Webhook の webhook 名によって識別される修正プログラムを適用します。</span><span class="sxs-lookup"><span data-stu-id="d8982-226">Patch the webhook identified by webhook name.</span></span>  <span data-ttu-id="d8982-227">(詳細については http://aka.ms/azureautomationsdk/webhookoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="d8982-227">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d8982-228">Webhook の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="d8982-228">The response model for the get webhook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>