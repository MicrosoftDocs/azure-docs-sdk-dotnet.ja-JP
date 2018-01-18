<Type Name="ConnectionOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.ConnectionOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ConnectionOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ConnectionOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.ConnectionOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ConnectionOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ConnectionOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.Automation.IConnectionOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.Automation.IConnectionOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Automation.IConnectionOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IConnectionOperations, resourceGroupName As String, automationAccount As String, parameters As ConnectionCreateOrUpdateParameters) As ConnectionCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Automation.IConnectionOperations * string * string * Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.Automation.ConnectionOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa89e-101">Microsoft.Azure.Management.Automation.IConnectionOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa89e-101">Reference to the Microsoft.Azure.Management.Automation.IConnectionOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fa89e-102">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-102">Required.</span></span> <span data-ttu-id="fa89e-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="fa89e-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="fa89e-104">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-104">Required.</span></span> <span data-ttu-id="fa89e-105">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fa89e-105">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fa89e-106">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-106">Required.</span></span> <span data-ttu-id="fa89e-107">作成または更新の接続操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fa89e-107">The parameters supplied to the create or update connection operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa89e-108">接続を作成します。</span><span class="sxs-lookup"><span data-stu-id="fa89e-108">Create a connection.</span></span>  <span data-ttu-id="fa89e-109">(詳細については http://aka.ms/azureautomationsdk/connectionoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="fa89e-109">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa89e-110">作成または更新の接続操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="fa89e-110">The response model for the create or update connection operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Automation.IConnectionOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Automation.IConnectionOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Automation.IConnectionOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IConnectionOperations, resourceGroupName As String, automationAccount As String, parameters As ConnectionCreateOrUpdateParameters) As Task(Of ConnectionCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Automation.IConnectionOperations * string * string * Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ConnectionOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.ConnectionCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa89e-111">Microsoft.Azure.Management.Automation.IConnectionOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa89e-111">Reference to the Microsoft.Azure.Management.Automation.IConnectionOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fa89e-112">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-112">Required.</span></span> <span data-ttu-id="fa89e-113">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="fa89e-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="fa89e-114">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-114">Required.</span></span> <span data-ttu-id="fa89e-115">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fa89e-115">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fa89e-116">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-116">Required.</span></span> <span data-ttu-id="fa89e-117">作成または更新の接続操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="fa89e-117">The parameters supplied to the create or update connection operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa89e-118">接続を作成します。</span><span class="sxs-lookup"><span data-stu-id="fa89e-118">Create a connection.</span></span>  <span data-ttu-id="fa89e-119">(詳細については http://aka.ms/azureautomationsdk/connectionoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="fa89e-119">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa89e-120">作成または更新の接続操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="fa89e-120">The response model for the create or update connection operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.Automation.IConnectionOperations operations, string resourceGroupName, string automationAccount, string connectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.Automation.IConnectionOperations operations, string resourceGroupName, string automationAccount, string connectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionOperationsExtensions.Delete(Microsoft.Azure.Management.Automation.IConnectionOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IConnectionOperations, resourceGroupName As String, automationAccount As String, connectionName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Automation.IConnectionOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.ConnectionOperationsExtensions.Delete (operations, resourceGroupName, automationAccount, connectionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="connectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa89e-121">Microsoft.Azure.Management.Automation.IConnectionOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa89e-121">Reference to the Microsoft.Azure.Management.Automation.IConnectionOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fa89e-122">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-122">Required.</span></span> <span data-ttu-id="fa89e-123">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="fa89e-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="fa89e-124">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-124">Required.</span></span> <span data-ttu-id="fa89e-125">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fa89e-125">The automation account name.</span></span>
            </param>
        <param name="connectionName">
            <span data-ttu-id="fa89e-126">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-126">Required.</span></span> <span data-ttu-id="fa89e-127">接続の名前。</span><span class="sxs-lookup"><span data-stu-id="fa89e-127">The name of connection.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa89e-128">接続を削除します。</span><span class="sxs-lookup"><span data-stu-id="fa89e-128">Delete the connection.</span></span>  <span data-ttu-id="fa89e-129">(詳細については http://aka.ms/azureautomationsdk/connectionoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="fa89e-129">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa89e-130">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="fa89e-130">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Automation.IConnectionOperations operations, string resourceGroupName, string automationAccount, string connectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Automation.IConnectionOperations operations, string resourceGroupName, string automationAccount, string connectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Automation.IConnectionOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IConnectionOperations, resourceGroupName As String, automationAccount As String, connectionName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Automation.IConnectionOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ConnectionOperationsExtensions.DeleteAsync (operations, resourceGroupName, automationAccount, connectionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="connectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa89e-131">Microsoft.Azure.Management.Automation.IConnectionOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa89e-131">Reference to the Microsoft.Azure.Management.Automation.IConnectionOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fa89e-132">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-132">Required.</span></span> <span data-ttu-id="fa89e-133">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="fa89e-133">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="fa89e-134">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-134">Required.</span></span> <span data-ttu-id="fa89e-135">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fa89e-135">The automation account name.</span></span>
            </param>
        <param name="connectionName">
            <span data-ttu-id="fa89e-136">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-136">Required.</span></span> <span data-ttu-id="fa89e-137">接続の名前。</span><span class="sxs-lookup"><span data-stu-id="fa89e-137">The name of connection.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa89e-138">接続を削除します。</span><span class="sxs-lookup"><span data-stu-id="fa89e-138">Delete the connection.</span></span>  <span data-ttu-id="fa89e-139">(詳細については http://aka.ms/azureautomationsdk/connectionoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="fa89e-139">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa89e-140">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="fa89e-140">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.ConnectionGetResponse Get (this Microsoft.Azure.Management.Automation.IConnectionOperations operations, string resourceGroupName, string automationAccount, string connectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.ConnectionGetResponse Get(class Microsoft.Azure.Management.Automation.IConnectionOperations operations, string resourceGroupName, string automationAccount, string connectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IConnectionOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IConnectionOperations, resourceGroupName As String, automationAccount As String, connectionName As String) As ConnectionGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IConnectionOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.ConnectionGetResponse" Usage="Microsoft.Azure.Management.Automation.ConnectionOperationsExtensions.Get (operations, resourceGroupName, automationAccount, connectionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ConnectionGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="connectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa89e-141">Microsoft.Azure.Management.Automation.IConnectionOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa89e-141">Reference to the Microsoft.Azure.Management.Automation.IConnectionOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fa89e-142">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-142">Required.</span></span> <span data-ttu-id="fa89e-143">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="fa89e-143">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="fa89e-144">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-144">Required.</span></span> <span data-ttu-id="fa89e-145">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fa89e-145">The automation account name.</span></span>
            </param>
        <param name="connectionName">
            <span data-ttu-id="fa89e-146">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-146">Required.</span></span> <span data-ttu-id="fa89e-147">接続の名前。</span><span class="sxs-lookup"><span data-stu-id="fa89e-147">The name of connection.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa89e-148">接続の名前によって識別される接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="fa89e-148">Retrieve the connection identified by connection name.</span></span>  <span data-ttu-id="fa89e-149">(詳細については http://aka.ms/azureautomationsdk/connectionoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="fa89e-149">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa89e-150">接続の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="fa89e-150">The response model for the get connection operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IConnectionOperations operations, string resourceGroupName, string automationAccount, string connectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IConnectionOperations operations, string resourceGroupName, string automationAccount, string connectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IConnectionOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IConnectionOperations, resourceGroupName As String, automationAccount As String, connectionName As String) As Task(Of ConnectionGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IConnectionOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ConnectionOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, connectionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="connectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa89e-151">Microsoft.Azure.Management.Automation.IConnectionOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa89e-151">Reference to the Microsoft.Azure.Management.Automation.IConnectionOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fa89e-152">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-152">Required.</span></span> <span data-ttu-id="fa89e-153">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="fa89e-153">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="fa89e-154">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-154">Required.</span></span> <span data-ttu-id="fa89e-155">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fa89e-155">The automation account name.</span></span>
            </param>
        <param name="connectionName">
            <span data-ttu-id="fa89e-156">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-156">Required.</span></span> <span data-ttu-id="fa89e-157">接続の名前。</span><span class="sxs-lookup"><span data-stu-id="fa89e-157">The name of connection.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa89e-158">接続の名前によって識別される接続を取得します。</span><span class="sxs-lookup"><span data-stu-id="fa89e-158">Retrieve the connection identified by connection name.</span></span>  <span data-ttu-id="fa89e-159">(詳細については http://aka.ms/azureautomationsdk/connectionoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="fa89e-159">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa89e-160">接続の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="fa89e-160">The response model for the get connection operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.ConnectionListResponse List (this Microsoft.Azure.Management.Automation.IConnectionOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.ConnectionListResponse List(class Microsoft.Azure.Management.Automation.IConnectionOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionOperationsExtensions.List(Microsoft.Azure.Management.Automation.IConnectionOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IConnectionOperations, resourceGroupName As String, automationAccount As String) As ConnectionListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IConnectionOperations * string * string -&gt; Microsoft.Azure.Management.Automation.Models.ConnectionListResponse" Usage="Microsoft.Azure.Management.Automation.ConnectionOperationsExtensions.List (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ConnectionListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa89e-161">Microsoft.Azure.Management.Automation.IConnectionOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa89e-161">Reference to the Microsoft.Azure.Management.Automation.IConnectionOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fa89e-162">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-162">Required.</span></span> <span data-ttu-id="fa89e-163">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="fa89e-163">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="fa89e-164">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-164">Required.</span></span> <span data-ttu-id="fa89e-165">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fa89e-165">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa89e-166">接続の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="fa89e-166">Retrieve a list of connections.</span></span>  <span data-ttu-id="fa89e-167">(詳細については http://aka.ms/azureautomationsdk/connectionoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="fa89e-167">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa89e-168">リストの接続操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="fa89e-168">The response model for the list connection operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IConnectionOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IConnectionOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IConnectionOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IConnectionOperations, resourceGroupName As String, automationAccount As String) As Task(Of ConnectionListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IConnectionOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ConnectionOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa89e-169">Microsoft.Azure.Management.Automation.IConnectionOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa89e-169">Reference to the Microsoft.Azure.Management.Automation.IConnectionOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fa89e-170">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-170">Required.</span></span> <span data-ttu-id="fa89e-171">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="fa89e-171">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="fa89e-172">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-172">Required.</span></span> <span data-ttu-id="fa89e-173">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fa89e-173">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa89e-174">接続の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="fa89e-174">Retrieve a list of connections.</span></span>  <span data-ttu-id="fa89e-175">(詳細については http://aka.ms/azureautomationsdk/connectionoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="fa89e-175">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa89e-176">リストの接続操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="fa89e-176">The response model for the list connection operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.ConnectionListResponse ListNext (this Microsoft.Azure.Management.Automation.IConnectionOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.ConnectionListResponse ListNext(class Microsoft.Azure.Management.Automation.IConnectionOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IConnectionOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IConnectionOperations, nextLink As String) As ConnectionListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IConnectionOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.ConnectionListResponse" Usage="Microsoft.Azure.Management.Automation.ConnectionOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ConnectionListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa89e-177">Microsoft.Azure.Management.Automation.IConnectionOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa89e-177">Reference to the Microsoft.Azure.Management.Automation.IConnectionOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="fa89e-178">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-178">Required.</span></span> <span data-ttu-id="fa89e-179">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="fa89e-179">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa89e-180">接続の [次へ] の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="fa89e-180">Retrieve next list of connections.</span></span>  <span data-ttu-id="fa89e-181">(詳細については http://aka.ms/azureautomationsdk/connectionoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="fa89e-181">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa89e-182">リストの接続操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="fa89e-182">The response model for the list connection operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IConnectionOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IConnectionOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IConnectionOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IConnectionOperations, nextLink As String) As Task(Of ConnectionListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IConnectionOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ConnectionOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa89e-183">Microsoft.Azure.Management.Automation.IConnectionOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa89e-183">Reference to the Microsoft.Azure.Management.Automation.IConnectionOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="fa89e-184">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-184">Required.</span></span> <span data-ttu-id="fa89e-185">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="fa89e-185">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa89e-186">接続の [次へ] の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="fa89e-186">Retrieve next list of connections.</span></span>  <span data-ttu-id="fa89e-187">(詳細については http://aka.ms/azureautomationsdk/connectionoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="fa89e-187">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa89e-188">リストの接続操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="fa89e-188">The response model for the list connection operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Patch (this Microsoft.Azure.Management.Automation.IConnectionOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.ConnectionPatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Patch(class Microsoft.Azure.Management.Automation.IConnectionOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.ConnectionPatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionOperationsExtensions.Patch(Microsoft.Azure.Management.Automation.IConnectionOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.ConnectionPatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Patch (operations As IConnectionOperations, resourceGroupName As String, automationAccount As String, parameters As ConnectionPatchParameters) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Management.Automation.IConnectionOperations * string * string * Microsoft.Azure.Management.Automation.Models.ConnectionPatchParameters -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.ConnectionOperationsExtensions.Patch (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.ConnectionPatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa89e-189">Microsoft.Azure.Management.Automation.IConnectionOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa89e-189">Reference to the Microsoft.Azure.Management.Automation.IConnectionOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fa89e-190">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-190">Required.</span></span> <span data-ttu-id="fa89e-191">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="fa89e-191">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="fa89e-192">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-192">Required.</span></span> <span data-ttu-id="fa89e-193">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fa89e-193">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fa89e-194">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-194">Required.</span></span> <span data-ttu-id="fa89e-195">パラメーターは、修正プログラムへ接続操作を指定します。</span><span class="sxs-lookup"><span data-stu-id="fa89e-195">The parameters supplied to the patch a connection operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa89e-196">接続を更新します。</span><span class="sxs-lookup"><span data-stu-id="fa89e-196">Update a connection.</span></span>  <span data-ttu-id="fa89e-197">(詳細については http://aka.ms/azureautomationsdk/connectionoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="fa89e-197">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa89e-198">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="fa89e-198">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; PatchAsync (this Microsoft.Azure.Management.Automation.IConnectionOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.ConnectionPatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; PatchAsync(class Microsoft.Azure.Management.Automation.IConnectionOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.ConnectionPatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionOperationsExtensions.PatchAsync(Microsoft.Azure.Management.Automation.IConnectionOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.ConnectionPatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PatchAsync (operations As IConnectionOperations, resourceGroupName As String, automationAccount As String, parameters As ConnectionPatchParameters) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Management.Automation.IConnectionOperations * string * string * Microsoft.Azure.Management.Automation.Models.ConnectionPatchParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ConnectionOperationsExtensions.PatchAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.ConnectionPatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fa89e-199">Microsoft.Azure.Management.Automation.IConnectionOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="fa89e-199">Reference to the Microsoft.Azure.Management.Automation.IConnectionOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fa89e-200">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-200">Required.</span></span> <span data-ttu-id="fa89e-201">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="fa89e-201">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="fa89e-202">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-202">Required.</span></span> <span data-ttu-id="fa89e-203">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="fa89e-203">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fa89e-204">必須。</span><span class="sxs-lookup"><span data-stu-id="fa89e-204">Required.</span></span> <span data-ttu-id="fa89e-205">パラメーターは、修正プログラムへ接続操作を指定します。</span><span class="sxs-lookup"><span data-stu-id="fa89e-205">The parameters supplied to the patch a connection operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fa89e-206">接続を更新します。</span><span class="sxs-lookup"><span data-stu-id="fa89e-206">Update a connection.</span></span>  <span data-ttu-id="fa89e-207">(詳細については http://aka.ms/azureautomationsdk/connectionoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="fa89e-207">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="fa89e-208">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="fa89e-208">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>