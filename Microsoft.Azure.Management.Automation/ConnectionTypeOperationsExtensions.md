<Type Name="ConnectionTypeOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ConnectionTypeOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ConnectionTypeOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ConnectionTypeOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ConnectionTypeOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Automation.IConnectionTypeOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IConnectionTypeOperations, resourceGroupName As String, automationAccount As String, parameters As ConnectionTypeCreateOrUpdateParameters) As ConnectionTypeCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Automation.IConnectionTypeOperations * string * string * Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e1a8a-101">Microsoft.Azure.Management.Automation.IConnectionTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-101">Reference to the Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e1a8a-102">必須。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-102">Required.</span></span> <span data-ttu-id="e1a8a-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="e1a8a-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e1a8a-104">必須。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-104">Required.</span></span> <span data-ttu-id="e1a8a-105">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-105">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e1a8a-106">必須。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-106">Required.</span></span> <span data-ttu-id="e1a8a-107">作成または更新 connectiontype 操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-107">The parameters supplied to the create or update connectiontype operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e1a8a-108">Connectiontype は作成します。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-108">Create a connectiontype.</span></span>  <span data-ttu-id="e1a8a-109">(詳細については http://aka.ms/azureautomationsdk/connectiontypeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="e1a8a-109">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e1a8a-110">作成または更新の接続の種類の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-110">The response model for the create or update connection type operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Automation.IConnectionTypeOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IConnectionTypeOperations, resourceGroupName As String, automationAccount As String, parameters As ConnectionTypeCreateOrUpdateParameters) As Task(Of ConnectionTypeCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Automation.IConnectionTypeOperations * string * string * Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.ConnectionTypeCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e1a8a-111">Microsoft.Azure.Management.Automation.IConnectionTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-111">Reference to the Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e1a8a-112">必須。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-112">Required.</span></span> <span data-ttu-id="e1a8a-113">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="e1a8a-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e1a8a-114">必須。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-114">Required.</span></span> <span data-ttu-id="e1a8a-115">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-115">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e1a8a-116">必須。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-116">Required.</span></span> <span data-ttu-id="e1a8a-117">作成または更新 connectiontype 操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-117">The parameters supplied to the create or update connectiontype operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e1a8a-118">Connectiontype は作成します。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-118">Create a connectiontype.</span></span>  <span data-ttu-id="e1a8a-119">(詳細については http://aka.ms/azureautomationsdk/connectiontypeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="e1a8a-119">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e1a8a-120">作成または更新の接続の種類の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-120">The response model for the create or update connection type operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount, string connectionTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount, string connectionTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.Delete(Microsoft.Azure.Management.Automation.IConnectionTypeOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IConnectionTypeOperations, resourceGroupName As String, automationAccount As String, connectionTypeName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Automation.IConnectionTypeOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.Delete (operations, resourceGroupName, automationAccount, connectionTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="connectionTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e1a8a-121">Microsoft.Azure.Management.Automation.IConnectionTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-121">Reference to the Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e1a8a-122">必須。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-122">Required.</span></span> <span data-ttu-id="e1a8a-123">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="e1a8a-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e1a8a-124">必須。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-124">Required.</span></span> <span data-ttu-id="e1a8a-125">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-125">The automation account name.</span></span>
            </param>
        <param name="connectionTypeName">
            <span data-ttu-id="e1a8a-126">必須。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-126">Required.</span></span> <span data-ttu-id="e1a8a-127">クエリ文字列の名前。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-127">The name of connectiontype.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e1a8a-128">クエリ文字列を削除します。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-128">Delete the connectiontype.</span></span>  <span data-ttu-id="e1a8a-129">(詳細については http://aka.ms/azureautomationsdk/connectiontypeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="e1a8a-129">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e1a8a-130">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="e1a8a-130">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount, string connectionTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount, string connectionTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Automation.IConnectionTypeOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IConnectionTypeOperations, resourceGroupName As String, automationAccount As String, connectionTypeName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Automation.IConnectionTypeOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.DeleteAsync (operations, resourceGroupName, automationAccount, connectionTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="connectionTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e1a8a-131">Microsoft.Azure.Management.Automation.IConnectionTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-131">Reference to the Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e1a8a-132">必須。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-132">Required.</span></span> <span data-ttu-id="e1a8a-133">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="e1a8a-133">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e1a8a-134">必須。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-134">Required.</span></span> <span data-ttu-id="e1a8a-135">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-135">The automation account name.</span></span>
            </param>
        <param name="connectionTypeName">
            <span data-ttu-id="e1a8a-136">必須。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-136">Required.</span></span> <span data-ttu-id="e1a8a-137">クエリ文字列の名前。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-137">The name of connectiontype.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e1a8a-138">クエリ文字列を削除します。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-138">Delete the connectiontype.</span></span>  <span data-ttu-id="e1a8a-139">(詳細については http://aka.ms/azureautomationsdk/connectiontypeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="e1a8a-139">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e1a8a-140">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="e1a8a-140">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.ConnectionTypeGetResponse Get (this Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount, string connectionTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.ConnectionTypeGetResponse Get(class Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount, string connectionTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IConnectionTypeOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IConnectionTypeOperations, resourceGroupName As String, automationAccount As String, connectionTypeName As String) As ConnectionTypeGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IConnectionTypeOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.ConnectionTypeGetResponse" Usage="Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.Get (operations, resourceGroupName, automationAccount, connectionTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ConnectionTypeGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="connectionTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e1a8a-141">Microsoft.Azure.Management.Automation.IConnectionTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-141">Reference to the Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e1a8a-142">必須。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-142">Required.</span></span> <span data-ttu-id="e1a8a-143">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="e1a8a-143">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e1a8a-144">必須。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-144">Required.</span></span> <span data-ttu-id="e1a8a-145">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-145">The automation account name.</span></span>
            </param>
        <param name="connectionTypeName">
            <span data-ttu-id="e1a8a-146">必須。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-146">Required.</span></span> <span data-ttu-id="e1a8a-147">クエリ文字列の名前。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-147">The name of connectiontype.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e1a8a-148">Connectiontype 名前によって識別されるクエリ文字列を取得します。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-148">Retrieve the connectiontype identified by connectiontype name.</span></span>
            <span data-ttu-id="e1a8a-149">(詳細については http://aka.ms/azureautomationsdk/connectiontypeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="e1a8a-149">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e1a8a-150">接続の種類の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-150">The response model for the get connection type operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount, string connectionTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionTypeGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount, string connectionTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IConnectionTypeOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IConnectionTypeOperations, resourceGroupName As String, automationAccount As String, connectionTypeName As String) As Task(Of ConnectionTypeGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IConnectionTypeOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, connectionTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="connectionTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e1a8a-151">Microsoft.Azure.Management.Automation.IConnectionTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-151">Reference to the Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e1a8a-152">必須。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-152">Required.</span></span> <span data-ttu-id="e1a8a-153">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="e1a8a-153">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e1a8a-154">必須。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-154">Required.</span></span> <span data-ttu-id="e1a8a-155">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-155">The automation account name.</span></span>
            </param>
        <param name="connectionTypeName">
            <span data-ttu-id="e1a8a-156">必須。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-156">Required.</span></span> <span data-ttu-id="e1a8a-157">クエリ文字列の名前。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-157">The name of connectiontype.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e1a8a-158">Connectiontype 名前によって識別されるクエリ文字列を取得します。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-158">Retrieve the connectiontype identified by connectiontype name.</span></span>
            <span data-ttu-id="e1a8a-159">(詳細については http://aka.ms/azureautomationsdk/connectiontypeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="e1a8a-159">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e1a8a-160">接続の種類の取得操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-160">The response model for the get connection type operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse List (this Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse List(class Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.List(Microsoft.Azure.Management.Automation.IConnectionTypeOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IConnectionTypeOperations, resourceGroupName As String, automationAccount As String) As ConnectionTypeListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IConnectionTypeOperations * string * string -&gt; Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse" Usage="Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.List (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e1a8a-161">Microsoft.Azure.Management.Automation.IConnectionTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-161">Reference to the Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e1a8a-162">必須。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-162">Required.</span></span> <span data-ttu-id="e1a8a-163">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="e1a8a-163">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e1a8a-164">必須。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-164">Required.</span></span> <span data-ttu-id="e1a8a-165">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-165">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e1a8a-166">Connectiontypes の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-166">Retrieve a list of connectiontypes.</span></span>  <span data-ttu-id="e1a8a-167">(詳細については http://aka.ms/azureautomationsdk/connectiontypeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="e1a8a-167">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e1a8a-168">リスト接続の種類の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-168">The response model for the list connection type operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IConnectionTypeOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IConnectionTypeOperations, resourceGroupName As String, automationAccount As String) As Task(Of ConnectionTypeListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IConnectionTypeOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionTypeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e1a8a-169">Microsoft.Azure.Management.Automation.IConnectionTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-169">Reference to the Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e1a8a-170">必須。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-170">Required.</span></span> <span data-ttu-id="e1a8a-171">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="e1a8a-171">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="e1a8a-172">必須。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-172">Required.</span></span> <span data-ttu-id="e1a8a-173">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-173">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e1a8a-174">Connectiontypes の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-174">Retrieve a list of connectiontypes.</span></span>  <span data-ttu-id="e1a8a-175">(詳細については http://aka.ms/azureautomationsdk/connectiontypeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="e1a8a-175">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e1a8a-176">リスト接続の種類の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-176">The response model for the list connection type operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse ListNext (this Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse ListNext(class Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IConnectionTypeOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IConnectionTypeOperations, nextLink As String) As ConnectionTypeListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IConnectionTypeOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse" Usage="Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionTypeOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e1a8a-177">Microsoft.Azure.Management.Automation.IConnectionTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-177">Reference to the Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="e1a8a-178">必須。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-178">Required.</span></span> <span data-ttu-id="e1a8a-179">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-179">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e1a8a-180">Connectiontypes の次の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-180">Retrieve next list of connectiontypes.</span></span>  <span data-ttu-id="e1a8a-181">(詳細については http://aka.ms/azureautomationsdk/connectiontypeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="e1a8a-181">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e1a8a-182">リスト接続の種類の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-182">The response model for the list connection type operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IConnectionTypeOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IConnectionTypeOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IConnectionTypeOperations, nextLink As String) As Task(Of ConnectionTypeListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IConnectionTypeOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ConnectionTypeOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ConnectionTypeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IConnectionTypeOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e1a8a-183">Microsoft.Azure.Management.Automation.IConnectionTypeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-183">Reference to the Microsoft.Azure.Management.Automation.IConnectionTypeOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="e1a8a-184">必須。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-184">Required.</span></span> <span data-ttu-id="e1a8a-185">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-185">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e1a8a-186">Connectiontypes の次の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-186">Retrieve next list of connectiontypes.</span></span>  <span data-ttu-id="e1a8a-187">(詳細については http://aka.ms/azureautomationsdk/connectiontypeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="e1a8a-187">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="e1a8a-188">リスト接続の種類の操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="e1a8a-188">The response model for the list connection type operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>