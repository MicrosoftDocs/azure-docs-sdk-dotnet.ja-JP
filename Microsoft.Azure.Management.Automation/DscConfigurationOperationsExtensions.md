<Type Name="DscConfigurationOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DscConfigurationOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DscConfigurationOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DscConfigurationOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DscConfigurationOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Automation.IDscConfigurationOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IDscConfigurationOperations, resourceGroupName As String, automationAccount As String, parameters As DscConfigurationCreateOrUpdateParameters) As DscConfigurationCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Automation.IDscConfigurationOperations * string * string * Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e5f2a-101">Microsoft.Azure.Management.Automation.IDscConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-101">Reference to the Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e5f2a-102">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-102">Required.</span></span> <span data-ttu-id="e5f2a-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="e5f2a-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e5f2a-104">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-104">Required.</span></span> <span data-ttu-id="e5f2a-105">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-105">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e5f2a-106">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-106">Required.</span></span> <span data-ttu-id="e5f2a-107">構成の作成または更新パラメーター。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-107">The create or update parameters for configuration.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e5f2a-108">構成名で識別される構成を作成します。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-108">Create the configuration identified by configuration name.</span></span>  <span data-ttu-id="e5f2a-109">(詳細については http://aka.ms/azureautomationsdk/configurationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="e5f2a-109">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e5f2a-110">構成の応答モデルでは、応答を作成します。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-110">The response model for the configuration create response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Automation.IDscConfigurationOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IDscConfigurationOperations, resourceGroupName As String, automationAccount As String, parameters As DscConfigurationCreateOrUpdateParameters) As Task(Of DscConfigurationCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Automation.IDscConfigurationOperations * string * string * Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e5f2a-111">Microsoft.Azure.Management.Automation.IDscConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-111">Reference to the Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e5f2a-112">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-112">Required.</span></span> <span data-ttu-id="e5f2a-113">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="e5f2a-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e5f2a-114">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-114">Required.</span></span> <span data-ttu-id="e5f2a-115">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-115">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e5f2a-116">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-116">Required.</span></span> <span data-ttu-id="e5f2a-117">構成の作成または更新パラメーター。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-117">The create or update parameters for configuration.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e5f2a-118">構成名で識別される構成を作成します。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-118">Create the configuration identified by configuration name.</span></span>  <span data-ttu-id="e5f2a-119">(詳細については http://aka.ms/azureautomationsdk/configurationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="e5f2a-119">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e5f2a-120">構成の応答モデルでは、応答を作成します。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-120">The response model for the configuration create response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.Delete(Microsoft.Azure.Management.Automation.IDscConfigurationOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IDscConfigurationOperations, resourceGroupName As String, automationAccount As String, configurationName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Automation.IDscConfigurationOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.Delete (operations, resourceGroupName, automationAccount, configurationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e5f2a-121">Microsoft.Azure.Management.Automation.IDscConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-121">Reference to the Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e5f2a-122">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-122">Required.</span></span> <span data-ttu-id="e5f2a-123">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="e5f2a-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e5f2a-124">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-124">Required.</span></span> <span data-ttu-id="e5f2a-125">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-125">The automation account name.</span></span>
            </param>
        <param name="configurationName">
            <span data-ttu-id="e5f2a-126">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-126">Required.</span></span> <span data-ttu-id="e5f2a-127">構成の名前。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-127">The configuration name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e5f2a-128">構成名で識別される、dsc 構成を削除します。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-128">Delete the dsc configuration identified by configuration name.</span></span>
            <span data-ttu-id="e5f2a-129">(詳細については http://aka.ms/azureautomationsdk/configurationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="e5f2a-129">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e5f2a-130">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="e5f2a-130">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Automation.IDscConfigurationOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IDscConfigurationOperations, resourceGroupName As String, automationAccount As String, configurationName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Automation.IDscConfigurationOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.DeleteAsync (operations, resourceGroupName, automationAccount, configurationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e5f2a-131">Microsoft.Azure.Management.Automation.IDscConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-131">Reference to the Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e5f2a-132">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-132">Required.</span></span> <span data-ttu-id="e5f2a-133">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="e5f2a-133">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e5f2a-134">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-134">Required.</span></span> <span data-ttu-id="e5f2a-135">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-135">The automation account name.</span></span>
            </param>
        <param name="configurationName">
            <span data-ttu-id="e5f2a-136">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-136">Required.</span></span> <span data-ttu-id="e5f2a-137">構成の名前。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-137">The configuration name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e5f2a-138">構成名で識別される、dsc 構成を削除します。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-138">Delete the dsc configuration identified by configuration name.</span></span>
            <span data-ttu-id="e5f2a-139">(詳細については http://aka.ms/azureautomationsdk/configurationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="e5f2a-139">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e5f2a-140">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="e5f2a-140">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscConfigurationGetResponse Get (this Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscConfigurationGetResponse Get(class Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IDscConfigurationOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDscConfigurationOperations, resourceGroupName As String, automationAccount As String, configurationName As String) As DscConfigurationGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IDscConfigurationOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.DscConfigurationGetResponse" Usage="Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.Get (operations, resourceGroupName, automationAccount, configurationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscConfigurationGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e5f2a-141">Microsoft.Azure.Management.Automation.IDscConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-141">Reference to the Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e5f2a-142">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-142">Required.</span></span> <span data-ttu-id="e5f2a-143">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="e5f2a-143">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e5f2a-144">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-144">Required.</span></span> <span data-ttu-id="e5f2a-145">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-145">The automation account name.</span></span>
            </param>
        <param name="configurationName">
            <span data-ttu-id="e5f2a-146">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-146">Required.</span></span> <span data-ttu-id="e5f2a-147">構成の名前。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-147">The configuration name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e5f2a-148">構成名で識別される構成を取得します。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-148">Retrieve the configuration identified by configuration name.</span></span>  <span data-ttu-id="e5f2a-149">(詳細については http://aka.ms/azureautomationsdk/configurationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="e5f2a-149">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e5f2a-150">構成の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-150">The response model for the get configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscConfigurationGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IDscConfigurationOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IDscConfigurationOperations, resourceGroupName As String, automationAccount As String, configurationName As String) As Task(Of DscConfigurationGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IDscConfigurationOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, configurationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e5f2a-151">Microsoft.Azure.Management.Automation.IDscConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-151">Reference to the Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e5f2a-152">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-152">Required.</span></span> <span data-ttu-id="e5f2a-153">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="e5f2a-153">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e5f2a-154">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-154">Required.</span></span> <span data-ttu-id="e5f2a-155">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-155">The automation account name.</span></span>
            </param>
        <param name="configurationName">
            <span data-ttu-id="e5f2a-156">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-156">Required.</span></span> <span data-ttu-id="e5f2a-157">構成の名前。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-157">The configuration name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e5f2a-158">構成名で識別される構成を取得します。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-158">Retrieve the configuration identified by configuration name.</span></span>  <span data-ttu-id="e5f2a-159">(詳細については http://aka.ms/azureautomationsdk/configurationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="e5f2a-159">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e5f2a-160">構成の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-160">The response model for the get configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscConfigurationGetContentResponse GetContent (this Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscConfigurationGetContentResponse GetContent(class Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.GetContent(Microsoft.Azure.Management.Automation.IDscConfigurationOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetContent (operations As IDscConfigurationOperations, resourceGroupName As String, automationAccount As String, configurationName As String) As DscConfigurationGetContentResponse" />
      <MemberSignature Language="F#" Value="static member GetContent : Microsoft.Azure.Management.Automation.IDscConfigurationOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.DscConfigurationGetContentResponse" Usage="Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.GetContent (operations, resourceGroupName, automationAccount, configurationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscConfigurationGetContentResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e5f2a-161">Microsoft.Azure.Management.Automation.IDscConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-161">Reference to the Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e5f2a-162">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-162">Required.</span></span> <span data-ttu-id="e5f2a-163">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="e5f2a-163">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e5f2a-164">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-164">Required.</span></span> <span data-ttu-id="e5f2a-165">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-165">The automation account name.</span></span>
            </param>
        <param name="configurationName">
            <span data-ttu-id="e5f2a-166">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-166">Required.</span></span> <span data-ttu-id="e5f2a-167">構成の名前。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-167">The configuration name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e5f2a-168">構成名で識別される、構成スクリプトを取得します。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-168">Retrieve the configuration script identified by configuration name.</span></span>
            <span data-ttu-id="e5f2a-169">(詳細については http://aka.ms/azureautomationsdk/configurationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="e5f2a-169">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e5f2a-170">構成の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-170">The response model for the get configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationGetContentResponse&gt; GetContentAsync (this Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscConfigurationGetContentResponse&gt; GetContentAsync(class Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.GetContentAsync(Microsoft.Azure.Management.Automation.IDscConfigurationOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetContentAsync (operations As IDscConfigurationOperations, resourceGroupName As String, automationAccount As String, configurationName As String) As Task(Of DscConfigurationGetContentResponse)" />
      <MemberSignature Language="F#" Value="static member GetContentAsync : Microsoft.Azure.Management.Automation.IDscConfigurationOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationGetContentResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.GetContentAsync (operations, resourceGroupName, automationAccount, configurationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationGetContentResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e5f2a-171">Microsoft.Azure.Management.Automation.IDscConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-171">Reference to the Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e5f2a-172">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-172">Required.</span></span> <span data-ttu-id="e5f2a-173">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="e5f2a-173">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e5f2a-174">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-174">Required.</span></span> <span data-ttu-id="e5f2a-175">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-175">The automation account name.</span></span>
            </param>
        <param name="configurationName">
            <span data-ttu-id="e5f2a-176">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-176">Required.</span></span> <span data-ttu-id="e5f2a-177">構成の名前。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-177">The configuration name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e5f2a-178">構成名で識別される、構成スクリプトを取得します。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-178">Retrieve the configuration script identified by configuration name.</span></span>
            <span data-ttu-id="e5f2a-179">(詳細については http://aka.ms/azureautomationsdk/configurationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="e5f2a-179">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e5f2a-180">構成の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-180">The response model for the get configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse List (this Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse List(class Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.List(Microsoft.Azure.Management.Automation.IDscConfigurationOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDscConfigurationOperations, resourceGroupName As String, automationAccount As String) As DscConfigurationListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IDscConfigurationOperations * string * string -&gt; Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse" Usage="Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.List (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e5f2a-181">Microsoft.Azure.Management.Automation.IDscConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-181">Reference to the Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e5f2a-182">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-182">Required.</span></span> <span data-ttu-id="e5f2a-183">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="e5f2a-183">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e5f2a-184">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-184">Required.</span></span> <span data-ttu-id="e5f2a-185">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-185">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e5f2a-186">構成の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-186">Retrieve a list of configurations.</span></span>  <span data-ttu-id="e5f2a-187">(詳細については http://aka.ms/azureautomationsdk/configurationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="e5f2a-187">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e5f2a-188">一覧の構成操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-188">The response model for the list configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IDscConfigurationOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IDscConfigurationOperations, resourceGroupName As String, automationAccount As String) As Task(Of DscConfigurationListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IDscConfigurationOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e5f2a-189">Microsoft.Azure.Management.Automation.IDscConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-189">Reference to the Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e5f2a-190">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-190">Required.</span></span> <span data-ttu-id="e5f2a-191">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="e5f2a-191">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e5f2a-192">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-192">Required.</span></span> <span data-ttu-id="e5f2a-193">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-193">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e5f2a-194">構成の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-194">Retrieve a list of configurations.</span></span>  <span data-ttu-id="e5f2a-195">(詳細については http://aka.ms/azureautomationsdk/configurationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="e5f2a-195">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e5f2a-196">一覧の構成操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-196">The response model for the list configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse ListNext (this Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse ListNext(class Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IDscConfigurationOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IDscConfigurationOperations, nextLink As String) As DscConfigurationListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IDscConfigurationOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse" Usage="Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscConfigurationOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e5f2a-197">Microsoft.Azure.Management.Automation.IDscConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-197">Reference to the Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="e5f2a-198">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-198">Required.</span></span> <span data-ttu-id="e5f2a-199">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-199">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e5f2a-200">構成の [次へ] の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-200">Retrieve next list of configurations.</span></span>  <span data-ttu-id="e5f2a-201">(詳細については http://aka.ms/azureautomationsdk/configurationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="e5f2a-201">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e5f2a-202">一覧の構成操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-202">The response model for the list configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IDscConfigurationOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IDscConfigurationOperations, nextLink As String) As Task(Of DscConfigurationListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IDscConfigurationOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscConfigurationOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e5f2a-203">Microsoft.Azure.Management.Automation.IDscConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-203">Reference to the Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="e5f2a-204">必須。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-204">Required.</span></span> <span data-ttu-id="e5f2a-205">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-205">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e5f2a-206">構成の [次へ] の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-206">Retrieve next list of configurations.</span></span>  <span data-ttu-id="e5f2a-207">(詳細については http://aka.ms/azureautomationsdk/configurationoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="e5f2a-207">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e5f2a-208">一覧の構成操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="e5f2a-208">The response model for the list configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>