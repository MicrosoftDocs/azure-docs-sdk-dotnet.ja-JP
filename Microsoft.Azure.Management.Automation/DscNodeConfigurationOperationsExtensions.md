<Type Name="DscNodeConfigurationOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DscNodeConfigurationOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DscNodeConfigurationOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DscNodeConfigurationOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DscNodeConfigurationOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse CreateOrUpdate (this Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse CreateOrUpdate(class Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IDscNodeConfigurationOperations, resourceGroupName As String, automationAccount As String, parameters As DscNodeConfigurationCreateOrUpdateParameters) As DscNodeConfigurationGetResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations * string * string * Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse" Usage="Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5185b-101">Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="5185b-101">Reference to the Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5185b-102">必須。</span><span class="sxs-lookup"><span data-stu-id="5185b-102">Required.</span></span> <span data-ttu-id="5185b-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="5185b-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5185b-104">必須。</span><span class="sxs-lookup"><span data-stu-id="5185b-104">Required.</span></span> <span data-ttu-id="5185b-105">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="5185b-105">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5185b-106">必須。</span><span class="sxs-lookup"><span data-stu-id="5185b-106">Required.</span></span> <span data-ttu-id="5185b-107">構成の作成または更新パラメーター。</span><span class="sxs-lookup"><span data-stu-id="5185b-107">The create or update parameters for configuration.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5185b-108">ノード構成名で識別されるノードの構成を作成します。</span><span class="sxs-lookup"><span data-stu-id="5185b-108">Create the node configuration identified by node configuration name.</span></span>  <span data-ttu-id="5185b-109">(詳細については http://aka.ms/azureautomationsdk/dscnodeconfigurations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="5185b-109">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5185b-110">Get Dsc ノード構成の操作の応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="5185b-110">The response model for the get Dsc node configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IDscNodeConfigurationOperations, resourceGroupName As String, automationAccount As String, parameters As DscNodeConfigurationCreateOrUpdateParameters) As Task(Of DscNodeConfigurationGetResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations * string * string * Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5185b-111">Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="5185b-111">Reference to the Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5185b-112">必須。</span><span class="sxs-lookup"><span data-stu-id="5185b-112">Required.</span></span> <span data-ttu-id="5185b-113">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="5185b-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5185b-114">必須。</span><span class="sxs-lookup"><span data-stu-id="5185b-114">Required.</span></span> <span data-ttu-id="5185b-115">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="5185b-115">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5185b-116">必須。</span><span class="sxs-lookup"><span data-stu-id="5185b-116">Required.</span></span> <span data-ttu-id="5185b-117">構成の作成または更新パラメーター。</span><span class="sxs-lookup"><span data-stu-id="5185b-117">The create or update parameters for configuration.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5185b-118">ノード構成名で識別されるノードの構成を作成します。</span><span class="sxs-lookup"><span data-stu-id="5185b-118">Create the node configuration identified by node configuration name.</span></span>  <span data-ttu-id="5185b-119">(詳細については http://aka.ms/azureautomationsdk/dscnodeconfigurations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="5185b-119">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5185b-120">Get Dsc ノード構成の操作の応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="5185b-120">The response model for the get Dsc node configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, string nodeConfigurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, string nodeConfigurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.Delete(Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IDscNodeConfigurationOperations, resourceGroupName As String, automationAccount As String, nodeConfigurationName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.Delete (operations, resourceGroupName, automationAccount, nodeConfigurationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeConfigurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5185b-121">Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="5185b-121">Reference to the Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5185b-122">必須。</span><span class="sxs-lookup"><span data-stu-id="5185b-122">Required.</span></span> <span data-ttu-id="5185b-123">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="5185b-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5185b-124">必須。</span><span class="sxs-lookup"><span data-stu-id="5185b-124">Required.</span></span> <span data-ttu-id="5185b-125">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="5185b-125">The automation account name.</span></span>
            </param>
        <param name="nodeConfigurationName">
            <span data-ttu-id="5185b-126">必須。</span><span class="sxs-lookup"><span data-stu-id="5185b-126">Required.</span></span> <span data-ttu-id="5185b-127">Dsc ノード構成名。</span><span class="sxs-lookup"><span data-stu-id="5185b-127">The Dsc node configuration name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5185b-128">ノードの構成での Dsc ノード構成を削除します。</span><span class="sxs-lookup"><span data-stu-id="5185b-128">Delete the Dsc node configurations by node configuration.</span></span>  <span data-ttu-id="5185b-129">(詳細については http://aka.ms/azureautomationsdk/dscnodeconfigurations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="5185b-129">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5185b-130">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="5185b-130">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, string nodeConfigurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, string nodeConfigurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IDscNodeConfigurationOperations, resourceGroupName As String, automationAccount As String, nodeConfigurationName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.DeleteAsync (operations, resourceGroupName, automationAccount, nodeConfigurationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeConfigurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5185b-131">Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="5185b-131">Reference to the Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5185b-132">必須。</span><span class="sxs-lookup"><span data-stu-id="5185b-132">Required.</span></span> <span data-ttu-id="5185b-133">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="5185b-133">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5185b-134">必須。</span><span class="sxs-lookup"><span data-stu-id="5185b-134">Required.</span></span> <span data-ttu-id="5185b-135">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="5185b-135">The automation account name.</span></span>
            </param>
        <param name="nodeConfigurationName">
            <span data-ttu-id="5185b-136">必須。</span><span class="sxs-lookup"><span data-stu-id="5185b-136">Required.</span></span> <span data-ttu-id="5185b-137">Dsc ノード構成名。</span><span class="sxs-lookup"><span data-stu-id="5185b-137">The Dsc node configuration name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5185b-138">ノードの構成での Dsc ノード構成を削除します。</span><span class="sxs-lookup"><span data-stu-id="5185b-138">Delete the Dsc node configurations by node configuration.</span></span>  <span data-ttu-id="5185b-139">(詳細については http://aka.ms/azureautomationsdk/dscnodeconfigurations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="5185b-139">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5185b-140">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="5185b-140">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse Get (this Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, string nodeConfigurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse Get(class Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, string nodeConfigurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDscNodeConfigurationOperations, resourceGroupName As String, automationAccount As String, nodeConfigurationName As String) As DscNodeConfigurationGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse" Usage="Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.Get (operations, resourceGroupName, automationAccount, nodeConfigurationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeConfigurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5185b-141">Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="5185b-141">Reference to the Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5185b-142">必須。</span><span class="sxs-lookup"><span data-stu-id="5185b-142">Required.</span></span> <span data-ttu-id="5185b-143">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="5185b-143">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5185b-144">必須。</span><span class="sxs-lookup"><span data-stu-id="5185b-144">Required.</span></span> <span data-ttu-id="5185b-145">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="5185b-145">The automation account name.</span></span>
            </param>
        <param name="nodeConfigurationName">
            <span data-ttu-id="5185b-146">必須。</span><span class="sxs-lookup"><span data-stu-id="5185b-146">Required.</span></span> <span data-ttu-id="5185b-147">Dsc ノード構成名。</span><span class="sxs-lookup"><span data-stu-id="5185b-147">The Dsc node configuration name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5185b-148">ノードの構成での Dsc ノード構成を取得します。</span><span class="sxs-lookup"><span data-stu-id="5185b-148">Retrieve the Dsc node configurations by node configuration.</span></span>  <span data-ttu-id="5185b-149">(詳細については http://aka.ms/azureautomationsdk/dscnodeconfigurations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="5185b-149">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5185b-150">Get Dsc ノード構成の操作の応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="5185b-150">The response model for the get Dsc node configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, string nodeConfigurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, string nodeConfigurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IDscNodeConfigurationOperations, resourceGroupName As String, automationAccount As String, nodeConfigurationName As String) As Task(Of DscNodeConfigurationGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, nodeConfigurationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeConfigurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5185b-151">Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="5185b-151">Reference to the Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5185b-152">必須。</span><span class="sxs-lookup"><span data-stu-id="5185b-152">Required.</span></span> <span data-ttu-id="5185b-153">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="5185b-153">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5185b-154">必須。</span><span class="sxs-lookup"><span data-stu-id="5185b-154">Required.</span></span> <span data-ttu-id="5185b-155">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="5185b-155">The automation account name.</span></span>
            </param>
        <param name="nodeConfigurationName">
            <span data-ttu-id="5185b-156">必須。</span><span class="sxs-lookup"><span data-stu-id="5185b-156">Required.</span></span> <span data-ttu-id="5185b-157">Dsc ノード構成名。</span><span class="sxs-lookup"><span data-stu-id="5185b-157">The Dsc node configuration name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5185b-158">ノードの構成での Dsc ノード構成を取得します。</span><span class="sxs-lookup"><span data-stu-id="5185b-158">Retrieve the Dsc node configurations by node configuration.</span></span>  <span data-ttu-id="5185b-159">(詳細については http://aka.ms/azureautomationsdk/dscnodeconfigurations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="5185b-159">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5185b-160">Get Dsc ノード構成の操作の応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="5185b-160">The response model for the get Dsc node configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse List (this Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse List(class Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.List(Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDscNodeConfigurationOperations, resourceGroupName As String, automationAccount As String, parameters As DscNodeConfigurationListParameters) As DscNodeConfigurationListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations * string * string * Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters -&gt; Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse" Usage="Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.List (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5185b-161">Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="5185b-161">Reference to the Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5185b-162">必須。</span><span class="sxs-lookup"><span data-stu-id="5185b-162">Required.</span></span> <span data-ttu-id="5185b-163">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="5185b-163">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5185b-164">必須。</span><span class="sxs-lookup"><span data-stu-id="5185b-164">Required.</span></span> <span data-ttu-id="5185b-165">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="5185b-165">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5185b-166">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5185b-166">Optional.</span></span> <span data-ttu-id="5185b-167">一覧表示操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="5185b-167">The parameters supplied to the list operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5185b-168">Dsc ノード構成の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5185b-168">Retrieve a list of dsc node configurations.</span></span>  <span data-ttu-id="5185b-169">(詳細については http://aka.ms/azureautomationsdk/dscnodeconfigurations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="5185b-169">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5185b-170">一覧のジョブ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="5185b-170">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IDscNodeConfigurationOperations, resourceGroupName As String, automationAccount As String, parameters As DscNodeConfigurationListParameters) As Task(Of DscNodeConfigurationListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations * string * string * Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5185b-171">Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="5185b-171">Reference to the Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5185b-172">必須。</span><span class="sxs-lookup"><span data-stu-id="5185b-172">Required.</span></span> <span data-ttu-id="5185b-173">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="5185b-173">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5185b-174">必須。</span><span class="sxs-lookup"><span data-stu-id="5185b-174">Required.</span></span> <span data-ttu-id="5185b-175">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="5185b-175">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5185b-176">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5185b-176">Optional.</span></span> <span data-ttu-id="5185b-177">一覧表示操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="5185b-177">The parameters supplied to the list operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5185b-178">Dsc ノード構成の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5185b-178">Retrieve a list of dsc node configurations.</span></span>  <span data-ttu-id="5185b-179">(詳細については http://aka.ms/azureautomationsdk/dscnodeconfigurations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="5185b-179">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5185b-180">一覧のジョブ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="5185b-180">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse ListNext (this Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse ListNext(class Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IDscNodeConfigurationOperations, nextLink As String) As DscNodeConfigurationListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse" Usage="Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5185b-181">Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="5185b-181">Reference to the Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="5185b-182">必須。</span><span class="sxs-lookup"><span data-stu-id="5185b-182">Required.</span></span> <span data-ttu-id="5185b-183">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="5185b-183">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5185b-184">Dsc ノード configrations の次の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5185b-184">Retrieve next list of dsc node configrations.</span></span>  <span data-ttu-id="5185b-185">(詳細については http://aka.ms/azureautomationsdk/dscnodeconfigurations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="5185b-185">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5185b-186">一覧のジョブ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="5185b-186">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IDscNodeConfigurationOperations, nextLink As String) As Task(Of DscNodeConfigurationListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscNodeConfigurationOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeConfigurationListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5185b-187">Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="5185b-187">Reference to the Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="5185b-188">必須。</span><span class="sxs-lookup"><span data-stu-id="5185b-188">Required.</span></span> <span data-ttu-id="5185b-189">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="5185b-189">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5185b-190">Dsc ノード configrations の次の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5185b-190">Retrieve next list of dsc node configrations.</span></span>  <span data-ttu-id="5185b-191">(詳細については http://aka.ms/azureautomationsdk/dscnodeconfigurations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="5185b-191">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5185b-192">一覧のジョブ操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="5185b-192">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>