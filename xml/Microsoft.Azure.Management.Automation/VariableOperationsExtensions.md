<Type Name="VariableOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.VariableOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VariableOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VariableOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.VariableOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VariableOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VariableOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.VariableOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Automation.IVariableOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IVariableOperations, resourceGroupName As String, automationAccount As String, parameters As VariableCreateOrUpdateParameters) As VariableCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Automation.IVariableOperations * string * string * Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.Automation.VariableOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IVariableOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="792f4-101">Microsoft.Azure.Management.Automation.IVariableOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="792f4-101">Reference to the Microsoft.Azure.Management.Automation.IVariableOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="792f4-102">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-102">Required.</span></span> <span data-ttu-id="792f4-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="792f4-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="792f4-104">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-104">Required.</span></span> <span data-ttu-id="792f4-105">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="792f4-105">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="792f4-106">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-106">Required.</span></span> <span data-ttu-id="792f4-107">変数を作成または更新操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="792f4-107">The parameters supplied to the create or update variable operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="792f4-108">変数を作成します。</span><span class="sxs-lookup"><span data-stu-id="792f4-108">Create a variable.</span></span>  <span data-ttu-id="792f4-109">(詳細については http://aka.ms/azureautomationsdk/variableoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="792f4-109">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="792f4-110">変数を作成または更新操作の応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="792f4-110">The response model for the create or update variable operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.VariableOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Automation.IVariableOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IVariableOperations, resourceGroupName As String, automationAccount As String, parameters As VariableCreateOrUpdateParameters) As Task(Of VariableCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Automation.IVariableOperations * string * string * Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.Automation.VariableOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IVariableOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="792f4-111">Microsoft.Azure.Management.Automation.IVariableOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="792f4-111">Reference to the Microsoft.Azure.Management.Automation.IVariableOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="792f4-112">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-112">Required.</span></span> <span data-ttu-id="792f4-113">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="792f4-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="792f4-114">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-114">Required.</span></span> <span data-ttu-id="792f4-115">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="792f4-115">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="792f4-116">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-116">Required.</span></span> <span data-ttu-id="792f4-117">変数を作成または更新操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="792f4-117">The parameters supplied to the create or update variable operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="792f4-118">変数を作成します。</span><span class="sxs-lookup"><span data-stu-id="792f4-118">Create a variable.</span></span>  <span data-ttu-id="792f4-119">(詳細については http://aka.ms/azureautomationsdk/variableoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="792f4-119">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="792f4-120">変数を作成または更新操作の応答モデルです。</span><span class="sxs-lookup"><span data-stu-id="792f4-120">The response model for the create or update variable operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, string variableName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, string variableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.VariableOperationsExtensions.Delete(Microsoft.Azure.Management.Automation.IVariableOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IVariableOperations, resourceGroupName As String, automationAccount As String, variableName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Automation.IVariableOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.VariableOperationsExtensions.Delete (operations, resourceGroupName, automationAccount, variableName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IVariableOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="variableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="792f4-121">Microsoft.Azure.Management.Automation.IVariableOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="792f4-121">Reference to the Microsoft.Azure.Management.Automation.IVariableOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="792f4-122">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-122">Required.</span></span> <span data-ttu-id="792f4-123">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="792f4-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="792f4-124">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-124">Required.</span></span> <span data-ttu-id="792f4-125">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="792f4-125">The automation account name.</span></span>
            </param>
        <param name="variableName">
            <span data-ttu-id="792f4-126">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-126">Required.</span></span> <span data-ttu-id="792f4-127">変数の名前。</span><span class="sxs-lookup"><span data-stu-id="792f4-127">The name of variable.</span></span>
            </param>
        <summary>
            <span data-ttu-id="792f4-128">変数を削除します。</span><span class="sxs-lookup"><span data-stu-id="792f4-128">Delete the variable.</span></span>  <span data-ttu-id="792f4-129">(詳細については http://aka.ms/azureautomationsdk/variableoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="792f4-129">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="792f4-130">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="792f4-130">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, string variableName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, string variableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.VariableOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Automation.IVariableOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IVariableOperations, resourceGroupName As String, automationAccount As String, variableName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Automation.IVariableOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.VariableOperationsExtensions.DeleteAsync (operations, resourceGroupName, automationAccount, variableName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IVariableOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="variableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="792f4-131">Microsoft.Azure.Management.Automation.IVariableOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="792f4-131">Reference to the Microsoft.Azure.Management.Automation.IVariableOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="792f4-132">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-132">Required.</span></span> <span data-ttu-id="792f4-133">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="792f4-133">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="792f4-134">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-134">Required.</span></span> <span data-ttu-id="792f4-135">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="792f4-135">The automation account name.</span></span>
            </param>
        <param name="variableName">
            <span data-ttu-id="792f4-136">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-136">Required.</span></span> <span data-ttu-id="792f4-137">変数の名前。</span><span class="sxs-lookup"><span data-stu-id="792f4-137">The name of variable.</span></span>
            </param>
        <summary>
            <span data-ttu-id="792f4-138">変数を削除します。</span><span class="sxs-lookup"><span data-stu-id="792f4-138">Delete the variable.</span></span>  <span data-ttu-id="792f4-139">(詳細については http://aka.ms/azureautomationsdk/variableoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="792f4-139">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="792f4-140">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="792f4-140">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.VariableGetResponse Get (this Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, string variableName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.VariableGetResponse Get(class Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, string variableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.VariableOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IVariableOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVariableOperations, resourceGroupName As String, automationAccount As String, variableName As String) As VariableGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IVariableOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.VariableGetResponse" Usage="Microsoft.Azure.Management.Automation.VariableOperationsExtensions.Get (operations, resourceGroupName, automationAccount, variableName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.VariableGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IVariableOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="variableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="792f4-141">Microsoft.Azure.Management.Automation.IVariableOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="792f4-141">Reference to the Microsoft.Azure.Management.Automation.IVariableOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="792f4-142">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-142">Required.</span></span> <span data-ttu-id="792f4-143">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="792f4-143">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="792f4-144">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-144">Required.</span></span> <span data-ttu-id="792f4-145">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="792f4-145">The automation account name.</span></span>
            </param>
        <param name="variableName">
            <span data-ttu-id="792f4-146">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-146">Required.</span></span> <span data-ttu-id="792f4-147">変数の名前。</span><span class="sxs-lookup"><span data-stu-id="792f4-147">The name of variable.</span></span>
            </param>
        <summary>
            <span data-ttu-id="792f4-148">変数名で識別される変数を取得します。</span><span class="sxs-lookup"><span data-stu-id="792f4-148">Retrieve the variable identified by variable name.</span></span>  <span data-ttu-id="792f4-149">(詳細については http://aka.ms/azureautomationsdk/variableoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="792f4-149">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="792f4-150">変数の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="792f4-150">The response model for the get variable operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, string variableName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.VariableGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, string variableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.VariableOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IVariableOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IVariableOperations, resourceGroupName As String, automationAccount As String, variableName As String) As Task(Of VariableGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IVariableOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.VariableOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, variableName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IVariableOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="variableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="792f4-151">Microsoft.Azure.Management.Automation.IVariableOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="792f4-151">Reference to the Microsoft.Azure.Management.Automation.IVariableOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="792f4-152">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-152">Required.</span></span> <span data-ttu-id="792f4-153">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="792f4-153">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="792f4-154">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-154">Required.</span></span> <span data-ttu-id="792f4-155">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="792f4-155">The automation account name.</span></span>
            </param>
        <param name="variableName">
            <span data-ttu-id="792f4-156">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-156">Required.</span></span> <span data-ttu-id="792f4-157">変数の名前。</span><span class="sxs-lookup"><span data-stu-id="792f4-157">The name of variable.</span></span>
            </param>
        <summary>
            <span data-ttu-id="792f4-158">変数名で識別される変数を取得します。</span><span class="sxs-lookup"><span data-stu-id="792f4-158">Retrieve the variable identified by variable name.</span></span>  <span data-ttu-id="792f4-159">(詳細については http://aka.ms/azureautomationsdk/variableoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="792f4-159">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="792f4-160">変数の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="792f4-160">The response model for the get variable operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.VariableListResponse List (this Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.VariableListResponse List(class Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.VariableOperationsExtensions.List(Microsoft.Azure.Management.Automation.IVariableOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IVariableOperations, resourceGroupName As String, automationAccount As String) As VariableListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IVariableOperations * string * string -&gt; Microsoft.Azure.Management.Automation.Models.VariableListResponse" Usage="Microsoft.Azure.Management.Automation.VariableOperationsExtensions.List (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.VariableListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IVariableOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="792f4-161">Microsoft.Azure.Management.Automation.IVariableOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="792f4-161">Reference to the Microsoft.Azure.Management.Automation.IVariableOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="792f4-162">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-162">Required.</span></span> <span data-ttu-id="792f4-163">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="792f4-163">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="792f4-164">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-164">Required.</span></span> <span data-ttu-id="792f4-165">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="792f4-165">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="792f4-166">変数の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="792f4-166">Retrieve a list of variables.</span></span>  <span data-ttu-id="792f4-167">(詳細については http://aka.ms/azureautomationsdk/variableoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="792f4-167">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="792f4-168">一覧の変数の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="792f4-168">The response model for the list variables operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.VariableListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.VariableOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IVariableOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IVariableOperations, resourceGroupName As String, automationAccount As String) As Task(Of VariableListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IVariableOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.VariableOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IVariableOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="792f4-169">Microsoft.Azure.Management.Automation.IVariableOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="792f4-169">Reference to the Microsoft.Azure.Management.Automation.IVariableOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="792f4-170">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-170">Required.</span></span> <span data-ttu-id="792f4-171">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="792f4-171">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="792f4-172">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-172">Required.</span></span> <span data-ttu-id="792f4-173">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="792f4-173">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="792f4-174">変数の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="792f4-174">Retrieve a list of variables.</span></span>  <span data-ttu-id="792f4-175">(詳細については http://aka.ms/azureautomationsdk/variableoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="792f4-175">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="792f4-176">一覧の変数の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="792f4-176">The response model for the list variables operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.VariableListResponse ListNext (this Microsoft.Azure.Management.Automation.IVariableOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.VariableListResponse ListNext(class Microsoft.Azure.Management.Automation.IVariableOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.VariableOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IVariableOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IVariableOperations, nextLink As String) As VariableListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IVariableOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.VariableListResponse" Usage="Microsoft.Azure.Management.Automation.VariableOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.VariableListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IVariableOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="792f4-177">Microsoft.Azure.Management.Automation.IVariableOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="792f4-177">Reference to the Microsoft.Azure.Management.Automation.IVariableOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="792f4-178">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-178">Required.</span></span> <span data-ttu-id="792f4-179">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="792f4-179">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="792f4-180">次の変数の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="792f4-180">Retrieve next list of variables.</span></span>  <span data-ttu-id="792f4-181">(詳細については http://aka.ms/azureautomationsdk/variableoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="792f4-181">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="792f4-182">一覧の変数の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="792f4-182">The response model for the list variables operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IVariableOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.VariableListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IVariableOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.VariableOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IVariableOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IVariableOperations, nextLink As String) As Task(Of VariableListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IVariableOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.VariableOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IVariableOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="792f4-183">Microsoft.Azure.Management.Automation.IVariableOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="792f4-183">Reference to the Microsoft.Azure.Management.Automation.IVariableOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="792f4-184">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-184">Required.</span></span> <span data-ttu-id="792f4-185">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="792f4-185">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="792f4-186">次の変数の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="792f4-186">Retrieve next list of variables.</span></span>  <span data-ttu-id="792f4-187">(詳細については http://aka.ms/azureautomationsdk/variableoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="792f4-187">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="792f4-188">一覧の変数の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="792f4-188">The response model for the list variables operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Patch (this Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.VariablePatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Patch(class Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.VariablePatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.VariableOperationsExtensions.Patch(Microsoft.Azure.Management.Automation.IVariableOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.VariablePatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Patch (operations As IVariableOperations, resourceGroupName As String, automationAccount As String, parameters As VariablePatchParameters) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Management.Automation.IVariableOperations * string * string * Microsoft.Azure.Management.Automation.Models.VariablePatchParameters -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.VariableOperationsExtensions.Patch (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IVariableOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.VariablePatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="792f4-189">Microsoft.Azure.Management.Automation.IVariableOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="792f4-189">Reference to the Microsoft.Azure.Management.Automation.IVariableOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="792f4-190">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-190">Required.</span></span> <span data-ttu-id="792f4-191">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="792f4-191">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="792f4-192">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-192">Required.</span></span> <span data-ttu-id="792f4-193">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="792f4-193">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="792f4-194">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-194">Required.</span></span> <span data-ttu-id="792f4-195">Patch 変数操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="792f4-195">The parameters supplied to the patch variable operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="792f4-196">変数を更新します。</span><span class="sxs-lookup"><span data-stu-id="792f4-196">Update a variable.</span></span>  <span data-ttu-id="792f4-197">(詳細については http://aka.ms/azureautomationsdk/variableoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="792f4-197">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="792f4-198">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="792f4-198">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; PatchAsync (this Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.VariablePatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; PatchAsync(class Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.VariablePatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.VariableOperationsExtensions.PatchAsync(Microsoft.Azure.Management.Automation.IVariableOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.VariablePatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PatchAsync (operations As IVariableOperations, resourceGroupName As String, automationAccount As String, parameters As VariablePatchParameters) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Management.Automation.IVariableOperations * string * string * Microsoft.Azure.Management.Automation.Models.VariablePatchParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.VariableOperationsExtensions.PatchAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IVariableOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.VariablePatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="792f4-199">Microsoft.Azure.Management.Automation.IVariableOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="792f4-199">Reference to the Microsoft.Azure.Management.Automation.IVariableOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="792f4-200">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-200">Required.</span></span> <span data-ttu-id="792f4-201">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="792f4-201">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="792f4-202">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-202">Required.</span></span> <span data-ttu-id="792f4-203">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="792f4-203">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="792f4-204">必須。</span><span class="sxs-lookup"><span data-stu-id="792f4-204">Required.</span></span> <span data-ttu-id="792f4-205">Patch 変数操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="792f4-205">The parameters supplied to the patch variable operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="792f4-206">変数を更新します。</span><span class="sxs-lookup"><span data-stu-id="792f4-206">Update a variable.</span></span>  <span data-ttu-id="792f4-207">(詳細については http://aka.ms/azureautomationsdk/variableoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="792f4-207">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="792f4-208">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="792f4-208">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>