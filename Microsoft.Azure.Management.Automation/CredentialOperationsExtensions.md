<Type Name="CredentialOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.CredentialOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class CredentialOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CredentialOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.CredentialOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CredentialOperationsExtensions" />
  <TypeSignature Language="F#" Value="type CredentialOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.Automation.ICredentialOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.Automation.ICredentialOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.CredentialOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Automation.ICredentialOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ICredentialOperations, resourceGroupName As String, automationAccount As String, parameters As CredentialCreateOrUpdateParameters) As CredentialCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Automation.ICredentialOperations * string * string * Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.Automation.CredentialOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ICredentialOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fb40c-101">Microsoft.Azure.Management.Automation.ICredentialOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fb40c-101">Reference to the Microsoft.Azure.Management.Automation.ICredentialOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fb40c-102">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-102">Required.</span></span> <span data-ttu-id="fb40c-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="fb40c-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="fb40c-104">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-104">Required.</span></span> <span data-ttu-id="fb40c-105">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fb40c-105">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fb40c-106">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-106">Required.</span></span> <span data-ttu-id="fb40c-107">作成または更新の資格情報の操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fb40c-107">The parameters supplied to the create or update credential operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fb40c-108">資格情報を作成します。</span><span class="sxs-lookup"><span data-stu-id="fb40c-108">Create a credential.</span></span>  <span data-ttu-id="fb40c-109">(詳細については http://aka.ms/azureautomationsdk/credentialoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="fb40c-109">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fb40c-110">作成または更新の資格情報の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="fb40c-110">The response model for the create or update credential operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Automation.ICredentialOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Automation.ICredentialOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.CredentialOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Automation.ICredentialOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As ICredentialOperations, resourceGroupName As String, automationAccount As String, parameters As CredentialCreateOrUpdateParameters) As Task(Of CredentialCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Automation.ICredentialOperations * string * string * Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.Automation.CredentialOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ICredentialOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.CredentialCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fb40c-111">Microsoft.Azure.Management.Automation.ICredentialOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fb40c-111">Reference to the Microsoft.Azure.Management.Automation.ICredentialOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fb40c-112">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-112">Required.</span></span> <span data-ttu-id="fb40c-113">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="fb40c-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="fb40c-114">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-114">Required.</span></span> <span data-ttu-id="fb40c-115">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fb40c-115">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fb40c-116">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-116">Required.</span></span> <span data-ttu-id="fb40c-117">作成または更新の資格情報の操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fb40c-117">The parameters supplied to the create or update credential operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fb40c-118">資格情報を作成します。</span><span class="sxs-lookup"><span data-stu-id="fb40c-118">Create a credential.</span></span>  <span data-ttu-id="fb40c-119">(詳細については http://aka.ms/azureautomationsdk/credentialoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="fb40c-119">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fb40c-120">作成または更新の資格情報の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="fb40c-120">The response model for the create or update credential operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.Automation.ICredentialOperations operations, string resourceGroupName, string automationAccount, string credentialName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.Automation.ICredentialOperations operations, string resourceGroupName, string automationAccount, string credentialName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.CredentialOperationsExtensions.Delete(Microsoft.Azure.Management.Automation.ICredentialOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As ICredentialOperations, resourceGroupName As String, automationAccount As String, credentialName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Automation.ICredentialOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.CredentialOperationsExtensions.Delete (operations, resourceGroupName, automationAccount, credentialName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ICredentialOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fb40c-121">Microsoft.Azure.Management.Automation.ICredentialOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fb40c-121">Reference to the Microsoft.Azure.Management.Automation.ICredentialOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fb40c-122">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-122">Required.</span></span> <span data-ttu-id="fb40c-123">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="fb40c-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="fb40c-124">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-124">Required.</span></span> <span data-ttu-id="fb40c-125">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fb40c-125">The automation account name.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="fb40c-126">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-126">Required.</span></span> <span data-ttu-id="fb40c-127">資格情報の名前。</span><span class="sxs-lookup"><span data-stu-id="fb40c-127">The name of credential.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fb40c-128">資格情報を削除します。</span><span class="sxs-lookup"><span data-stu-id="fb40c-128">Delete the credential.</span></span>  <span data-ttu-id="fb40c-129">(詳細については http://aka.ms/azureautomationsdk/credentialoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="fb40c-129">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fb40c-130">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="fb40c-130">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Automation.ICredentialOperations operations, string resourceGroupName, string automationAccount, string credentialName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Automation.ICredentialOperations operations, string resourceGroupName, string automationAccount, string credentialName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.CredentialOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Automation.ICredentialOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As ICredentialOperations, resourceGroupName As String, automationAccount As String, credentialName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Automation.ICredentialOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.CredentialOperationsExtensions.DeleteAsync (operations, resourceGroupName, automationAccount, credentialName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ICredentialOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fb40c-131">Microsoft.Azure.Management.Automation.ICredentialOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fb40c-131">Reference to the Microsoft.Azure.Management.Automation.ICredentialOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fb40c-132">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-132">Required.</span></span> <span data-ttu-id="fb40c-133">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="fb40c-133">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="fb40c-134">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-134">Required.</span></span> <span data-ttu-id="fb40c-135">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fb40c-135">The automation account name.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="fb40c-136">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-136">Required.</span></span> <span data-ttu-id="fb40c-137">資格情報の名前。</span><span class="sxs-lookup"><span data-stu-id="fb40c-137">The name of credential.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fb40c-138">資格情報を削除します。</span><span class="sxs-lookup"><span data-stu-id="fb40c-138">Delete the credential.</span></span>  <span data-ttu-id="fb40c-139">(詳細については http://aka.ms/azureautomationsdk/credentialoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="fb40c-139">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fb40c-140">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="fb40c-140">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.CredentialGetResponse Get (this Microsoft.Azure.Management.Automation.ICredentialOperations operations, string resourceGroupName, string automationAccount, string credentialName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.CredentialGetResponse Get(class Microsoft.Azure.Management.Automation.ICredentialOperations operations, string resourceGroupName, string automationAccount, string credentialName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.CredentialOperationsExtensions.Get(Microsoft.Azure.Management.Automation.ICredentialOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ICredentialOperations, resourceGroupName As String, automationAccount As String, credentialName As String) As CredentialGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.ICredentialOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.CredentialGetResponse" Usage="Microsoft.Azure.Management.Automation.CredentialOperationsExtensions.Get (operations, resourceGroupName, automationAccount, credentialName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.CredentialGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ICredentialOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fb40c-141">Microsoft.Azure.Management.Automation.ICredentialOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fb40c-141">Reference to the Microsoft.Azure.Management.Automation.ICredentialOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fb40c-142">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-142">Required.</span></span> <span data-ttu-id="fb40c-143">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="fb40c-143">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="fb40c-144">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-144">Required.</span></span> <span data-ttu-id="fb40c-145">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fb40c-145">The automation account name.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="fb40c-146">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-146">Required.</span></span> <span data-ttu-id="fb40c-147">資格情報の名前。</span><span class="sxs-lookup"><span data-stu-id="fb40c-147">The name of credential.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fb40c-148">資格情報の名前によって識別される資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="fb40c-148">Retrieve the credential identified by credential name.</span></span>  <span data-ttu-id="fb40c-149">(詳細については http://aka.ms/azureautomationsdk/credentialoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="fb40c-149">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fb40c-150">資格情報の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="fb40c-150">The response model for the get credential operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.ICredentialOperations operations, string resourceGroupName, string automationAccount, string credentialName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CredentialGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.ICredentialOperations operations, string resourceGroupName, string automationAccount, string credentialName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.CredentialOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.ICredentialOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As ICredentialOperations, resourceGroupName As String, automationAccount As String, credentialName As String) As Task(Of CredentialGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.ICredentialOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.CredentialOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, credentialName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ICredentialOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="credentialName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fb40c-151">Microsoft.Azure.Management.Automation.ICredentialOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fb40c-151">Reference to the Microsoft.Azure.Management.Automation.ICredentialOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fb40c-152">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-152">Required.</span></span> <span data-ttu-id="fb40c-153">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="fb40c-153">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="fb40c-154">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-154">Required.</span></span> <span data-ttu-id="fb40c-155">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fb40c-155">The automation account name.</span></span>
            </param>
        <param name="credentialName">
            <span data-ttu-id="fb40c-156">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-156">Required.</span></span> <span data-ttu-id="fb40c-157">資格情報の名前。</span><span class="sxs-lookup"><span data-stu-id="fb40c-157">The name of credential.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fb40c-158">資格情報の名前によって識別される資格情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="fb40c-158">Retrieve the credential identified by credential name.</span></span>  <span data-ttu-id="fb40c-159">(詳細については http://aka.ms/azureautomationsdk/credentialoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="fb40c-159">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fb40c-160">資格情報の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="fb40c-160">The response model for the get credential operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.CredentialListResponse List (this Microsoft.Azure.Management.Automation.ICredentialOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.CredentialListResponse List(class Microsoft.Azure.Management.Automation.ICredentialOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.CredentialOperationsExtensions.List(Microsoft.Azure.Management.Automation.ICredentialOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ICredentialOperations, resourceGroupName As String, automationAccount As String) As CredentialListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.ICredentialOperations * string * string -&gt; Microsoft.Azure.Management.Automation.Models.CredentialListResponse" Usage="Microsoft.Azure.Management.Automation.CredentialOperationsExtensions.List (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.CredentialListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ICredentialOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fb40c-161">Microsoft.Azure.Management.Automation.ICredentialOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fb40c-161">Reference to the Microsoft.Azure.Management.Automation.ICredentialOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fb40c-162">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-162">Required.</span></span> <span data-ttu-id="fb40c-163">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="fb40c-163">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="fb40c-164">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-164">Required.</span></span> <span data-ttu-id="fb40c-165">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fb40c-165">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fb40c-166">資格情報の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="fb40c-166">Retrieve a list of credentials.</span></span>  <span data-ttu-id="fb40c-167">(詳細については http://aka.ms/azureautomationsdk/credentialoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="fb40c-167">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fb40c-168">一覧の資格情報の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="fb40c-168">The response model for the list credential operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.ICredentialOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CredentialListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.ICredentialOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.CredentialOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.ICredentialOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As ICredentialOperations, resourceGroupName As String, automationAccount As String) As Task(Of CredentialListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.ICredentialOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.CredentialOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ICredentialOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fb40c-169">Microsoft.Azure.Management.Automation.ICredentialOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fb40c-169">Reference to the Microsoft.Azure.Management.Automation.ICredentialOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fb40c-170">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-170">Required.</span></span> <span data-ttu-id="fb40c-171">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="fb40c-171">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="fb40c-172">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-172">Required.</span></span> <span data-ttu-id="fb40c-173">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fb40c-173">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fb40c-174">資格情報の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="fb40c-174">Retrieve a list of credentials.</span></span>  <span data-ttu-id="fb40c-175">(詳細については http://aka.ms/azureautomationsdk/credentialoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="fb40c-175">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fb40c-176">一覧の資格情報の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="fb40c-176">The response model for the list credential operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.CredentialListResponse ListNext (this Microsoft.Azure.Management.Automation.ICredentialOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.CredentialListResponse ListNext(class Microsoft.Azure.Management.Automation.ICredentialOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.CredentialOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.ICredentialOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ICredentialOperations, nextLink As String) As CredentialListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.ICredentialOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.CredentialListResponse" Usage="Microsoft.Azure.Management.Automation.CredentialOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.CredentialListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ICredentialOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fb40c-177">Microsoft.Azure.Management.Automation.ICredentialOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fb40c-177">Reference to the Microsoft.Azure.Management.Automation.ICredentialOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="fb40c-178">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-178">Required.</span></span> <span data-ttu-id="fb40c-179">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="fb40c-179">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fb40c-180">資格情報の次の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="fb40c-180">Retrieve next list of credentials.</span></span>  <span data-ttu-id="fb40c-181">(詳細については http://aka.ms/azureautomationsdk/credentialoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="fb40c-181">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fb40c-182">一覧の資格情報の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="fb40c-182">The response model for the list credential operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.ICredentialOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.CredentialListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.ICredentialOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.CredentialOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.ICredentialOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As ICredentialOperations, nextLink As String) As Task(Of CredentialListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.ICredentialOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.CredentialOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.CredentialListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ICredentialOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fb40c-183">Microsoft.Azure.Management.Automation.ICredentialOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fb40c-183">Reference to the Microsoft.Azure.Management.Automation.ICredentialOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="fb40c-184">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-184">Required.</span></span> <span data-ttu-id="fb40c-185">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="fb40c-185">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fb40c-186">資格情報の次の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="fb40c-186">Retrieve next list of credentials.</span></span>  <span data-ttu-id="fb40c-187">(詳細については http://aka.ms/azureautomationsdk/credentialoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="fb40c-187">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fb40c-188">一覧の資格情報の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="fb40c-188">The response model for the list credential operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Patch (this Microsoft.Azure.Management.Automation.ICredentialOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.CredentialPatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Patch(class Microsoft.Azure.Management.Automation.ICredentialOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.CredentialPatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.CredentialOperationsExtensions.Patch(Microsoft.Azure.Management.Automation.ICredentialOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.CredentialPatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Patch (operations As ICredentialOperations, resourceGroupName As String, automationAccount As String, parameters As CredentialPatchParameters) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Management.Automation.ICredentialOperations * string * string * Microsoft.Azure.Management.Automation.Models.CredentialPatchParameters -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.CredentialOperationsExtensions.Patch (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ICredentialOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.CredentialPatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fb40c-189">Microsoft.Azure.Management.Automation.ICredentialOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fb40c-189">Reference to the Microsoft.Azure.Management.Automation.ICredentialOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fb40c-190">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-190">Required.</span></span> <span data-ttu-id="fb40c-191">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="fb40c-191">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="fb40c-192">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-192">Required.</span></span> <span data-ttu-id="fb40c-193">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fb40c-193">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fb40c-194">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-194">Required.</span></span> <span data-ttu-id="fb40c-195">Patch 資格情報の操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fb40c-195">The parameters supplied to the patch credential operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fb40c-196">資格情報を更新します。</span><span class="sxs-lookup"><span data-stu-id="fb40c-196">Update a credential.</span></span>  <span data-ttu-id="fb40c-197">(詳細については http://aka.ms/azureautomationsdk/credentialoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="fb40c-197">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fb40c-198">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="fb40c-198">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; PatchAsync (this Microsoft.Azure.Management.Automation.ICredentialOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.CredentialPatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; PatchAsync(class Microsoft.Azure.Management.Automation.ICredentialOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.CredentialPatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.CredentialOperationsExtensions.PatchAsync(Microsoft.Azure.Management.Automation.ICredentialOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.CredentialPatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PatchAsync (operations As ICredentialOperations, resourceGroupName As String, automationAccount As String, parameters As CredentialPatchParameters) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Management.Automation.ICredentialOperations * string * string * Microsoft.Azure.Management.Automation.Models.CredentialPatchParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.CredentialOperationsExtensions.PatchAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.ICredentialOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.CredentialPatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fb40c-199">Microsoft.Azure.Management.Automation.ICredentialOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fb40c-199">Reference to the Microsoft.Azure.Management.Automation.ICredentialOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fb40c-200">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-200">Required.</span></span> <span data-ttu-id="fb40c-201">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="fb40c-201">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="fb40c-202">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-202">Required.</span></span> <span data-ttu-id="fb40c-203">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fb40c-203">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fb40c-204">必須。</span><span class="sxs-lookup"><span data-stu-id="fb40c-204">Required.</span></span> <span data-ttu-id="fb40c-205">Patch 資格情報の操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fb40c-205">The parameters supplied to the patch credential operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fb40c-206">資格情報を更新します。</span><span class="sxs-lookup"><span data-stu-id="fb40c-206">Update a credential.</span></span>  <span data-ttu-id="fb40c-207">(詳細については http://aka.ms/azureautomationsdk/credentialoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="fb40c-207">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fb40c-208">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="fb40c-208">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>