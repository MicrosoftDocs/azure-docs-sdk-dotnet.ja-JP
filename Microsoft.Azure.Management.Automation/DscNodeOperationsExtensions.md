<Type Name="DscNodeOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DscNodeOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DscNodeOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DscNodeOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DscNodeOperationsExtensions = class" />
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
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, Guid nodeId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid nodeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.Delete(Microsoft.Azure.Management.Automation.IDscNodeOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IDscNodeOperations, resourceGroupName As String, automationAccount As String, nodeId As Guid) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Automation.IDscNodeOperations * string * string * Guid -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.Delete (operations, resourceGroupName, automationAccount, nodeId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="efe76-101">Microsoft.Azure.Management.Automation.IDscNodeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="efe76-101">Reference to the Microsoft.Azure.Management.Automation.IDscNodeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="efe76-102">必須。</span><span class="sxs-lookup"><span data-stu-id="efe76-102">Required.</span></span> <span data-ttu-id="efe76-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="efe76-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="efe76-104">必須。</span><span class="sxs-lookup"><span data-stu-id="efe76-104">Required.</span></span> <span data-ttu-id="efe76-105">オートメーション アカウントの名前です。</span><span class="sxs-lookup"><span data-stu-id="efe76-105">Automation account name.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="efe76-106">必須。</span><span class="sxs-lookup"><span data-stu-id="efe76-106">Required.</span></span> <span data-ttu-id="efe76-107">ノード id。</span><span class="sxs-lookup"><span data-stu-id="efe76-107">The node id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="efe76-108">ノード id で識別される dsc ノードを削除します。 (詳細については http://aka.ms/azureautomationsdk/dscnodeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="efe76-108">Delete the dsc node identified by node id.  (see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="efe76-109">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="efe76-109">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, Guid nodeId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid nodeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Automation.IDscNodeOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IDscNodeOperations, resourceGroupName As String, automationAccount As String, nodeId As Guid) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Automation.IDscNodeOperations * string * string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.DeleteAsync (operations, resourceGroupName, automationAccount, nodeId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="efe76-110">Microsoft.Azure.Management.Automation.IDscNodeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="efe76-110">Reference to the Microsoft.Azure.Management.Automation.IDscNodeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="efe76-111">必須。</span><span class="sxs-lookup"><span data-stu-id="efe76-111">Required.</span></span> <span data-ttu-id="efe76-112">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="efe76-112">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="efe76-113">必須。</span><span class="sxs-lookup"><span data-stu-id="efe76-113">Required.</span></span> <span data-ttu-id="efe76-114">オートメーション アカウントの名前です。</span><span class="sxs-lookup"><span data-stu-id="efe76-114">Automation account name.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="efe76-115">必須。</span><span class="sxs-lookup"><span data-stu-id="efe76-115">Required.</span></span> <span data-ttu-id="efe76-116">ノード id。</span><span class="sxs-lookup"><span data-stu-id="efe76-116">The node id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="efe76-117">ノード id で識別される dsc ノードを削除します。 (詳細については http://aka.ms/azureautomationsdk/dscnodeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="efe76-117">Delete the dsc node identified by node id.  (see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="efe76-118">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="efe76-118">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscNodeGetResponse Get (this Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, Guid nodeId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscNodeGetResponse Get(class Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid nodeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IDscNodeOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDscNodeOperations, resourceGroupName As String, automationAccount As String, nodeId As Guid) As DscNodeGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IDscNodeOperations * string * string * Guid -&gt; Microsoft.Azure.Management.Automation.Models.DscNodeGetResponse" Usage="Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.Get (operations, resourceGroupName, automationAccount, nodeId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscNodeGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="efe76-119">Microsoft.Azure.Management.Automation.IDscNodeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="efe76-119">Reference to the Microsoft.Azure.Management.Automation.IDscNodeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="efe76-120">必須。</span><span class="sxs-lookup"><span data-stu-id="efe76-120">Required.</span></span> <span data-ttu-id="efe76-121">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="efe76-121">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="efe76-122">必須。</span><span class="sxs-lookup"><span data-stu-id="efe76-122">Required.</span></span> <span data-ttu-id="efe76-123">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="efe76-123">The automation account name.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="efe76-124">必須。</span><span class="sxs-lookup"><span data-stu-id="efe76-124">Required.</span></span> <span data-ttu-id="efe76-125">ノード id。</span><span class="sxs-lookup"><span data-stu-id="efe76-125">The node id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="efe76-126">ノード id で識別される dsc ノードを取得します。 (詳細については http://aka.ms/azureautomationsdk/dscnodeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="efe76-126">Retrieve the dsc node identified by node id.  (see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="efe76-127">Get 応答モデル ノードの dsc 操作です。</span><span class="sxs-lookup"><span data-stu-id="efe76-127">The response model for the get dsc node operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, Guid nodeId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid nodeId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IDscNodeOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IDscNodeOperations, resourceGroupName As String, automationAccount As String, nodeId As Guid) As Task(Of DscNodeGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IDscNodeOperations * string * string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, nodeId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="efe76-128">Microsoft.Azure.Management.Automation.IDscNodeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="efe76-128">Reference to the Microsoft.Azure.Management.Automation.IDscNodeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="efe76-129">必須。</span><span class="sxs-lookup"><span data-stu-id="efe76-129">Required.</span></span> <span data-ttu-id="efe76-130">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="efe76-130">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="efe76-131">必須。</span><span class="sxs-lookup"><span data-stu-id="efe76-131">Required.</span></span> <span data-ttu-id="efe76-132">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="efe76-132">The automation account name.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="efe76-133">必須。</span><span class="sxs-lookup"><span data-stu-id="efe76-133">Required.</span></span> <span data-ttu-id="efe76-134">ノード id。</span><span class="sxs-lookup"><span data-stu-id="efe76-134">The node id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="efe76-135">ノード id で識別される dsc ノードを取得します。 (詳細については http://aka.ms/azureautomationsdk/dscnodeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="efe76-135">Retrieve the dsc node identified by node id.  (see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="efe76-136">Get 応答モデル ノードの dsc 操作です。</span><span class="sxs-lookup"><span data-stu-id="efe76-136">The response model for the get dsc node operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscNodeListResponse List (this Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodeListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscNodeListResponse List(class Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodeListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.List(Microsoft.Azure.Management.Automation.IDscNodeOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodeListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDscNodeOperations, resourceGroupName As String, automationAccount As String, parameters As DscNodeListParameters) As DscNodeListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IDscNodeOperations * string * string * Microsoft.Azure.Management.Automation.Models.DscNodeListParameters -&gt; Microsoft.Azure.Management.Automation.Models.DscNodeListResponse" Usage="Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.List (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscNodeListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodeListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="efe76-137">Microsoft.Azure.Management.Automation.IDscNodeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="efe76-137">Reference to the Microsoft.Azure.Management.Automation.IDscNodeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="efe76-138">必須。</span><span class="sxs-lookup"><span data-stu-id="efe76-138">Required.</span></span> <span data-ttu-id="efe76-139">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="efe76-139">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="efe76-140">必須。</span><span class="sxs-lookup"><span data-stu-id="efe76-140">Required.</span></span> <span data-ttu-id="efe76-141">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="efe76-141">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="efe76-142">省略可能。</span><span class="sxs-lookup"><span data-stu-id="efe76-142">Optional.</span></span> <span data-ttu-id="efe76-143">一覧表示操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="efe76-143">The parameters supplied to the list operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="efe76-144">Dsc ノードの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="efe76-144">Retrieve a list of dsc nodes.</span></span>  <span data-ttu-id="efe76-145">(詳細については http://aka.ms/azureautomationsdk/dscnodeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="efe76-145">(see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="efe76-146">一覧の dsc ノードの操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="efe76-146">The response model for the list dsc nodes operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodeListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodeListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IDscNodeOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodeListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IDscNodeOperations, resourceGroupName As String, automationAccount As String, parameters As DscNodeListParameters) As Task(Of DscNodeListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IDscNodeOperations * string * string * Microsoft.Azure.Management.Automation.Models.DscNodeListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodeListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="efe76-147">Microsoft.Azure.Management.Automation.IDscNodeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="efe76-147">Reference to the Microsoft.Azure.Management.Automation.IDscNodeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="efe76-148">必須。</span><span class="sxs-lookup"><span data-stu-id="efe76-148">Required.</span></span> <span data-ttu-id="efe76-149">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="efe76-149">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="efe76-150">必須。</span><span class="sxs-lookup"><span data-stu-id="efe76-150">Required.</span></span> <span data-ttu-id="efe76-151">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="efe76-151">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="efe76-152">省略可能。</span><span class="sxs-lookup"><span data-stu-id="efe76-152">Optional.</span></span> <span data-ttu-id="efe76-153">一覧表示操作に指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="efe76-153">The parameters supplied to the list operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="efe76-154">Dsc ノードの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="efe76-154">Retrieve a list of dsc nodes.</span></span>  <span data-ttu-id="efe76-155">(詳細については http://aka.ms/azureautomationsdk/dscnodeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="efe76-155">(see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="efe76-156">一覧の dsc ノードの操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="efe76-156">The response model for the list dsc nodes operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscNodeListResponse ListNext (this Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscNodeListResponse ListNext(class Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IDscNodeOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IDscNodeOperations, nextLink As String) As DscNodeListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IDscNodeOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.DscNodeListResponse" Usage="Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscNodeListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="efe76-157">Microsoft.Azure.Management.Automation.IDscNodeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="efe76-157">Reference to the Microsoft.Azure.Management.Automation.IDscNodeOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="efe76-158">必須。</span><span class="sxs-lookup"><span data-stu-id="efe76-158">Required.</span></span> <span data-ttu-id="efe76-159">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="efe76-159">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="efe76-160">構成の [次へ] の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="efe76-160">Retrieve next list of configurations.</span></span>  <span data-ttu-id="efe76-161">(詳細については http://aka.ms/azureautomationsdk/dscnodeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="efe76-161">(see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="efe76-162">一覧の dsc ノードの操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="efe76-162">The response model for the list dsc nodes operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IDscNodeOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IDscNodeOperations, nextLink As String) As Task(Of DscNodeListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IDscNodeOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="efe76-163">Microsoft.Azure.Management.Automation.IDscNodeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="efe76-163">Reference to the Microsoft.Azure.Management.Automation.IDscNodeOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="efe76-164">必須。</span><span class="sxs-lookup"><span data-stu-id="efe76-164">Required.</span></span> <span data-ttu-id="efe76-165">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="efe76-165">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="efe76-166">構成の [次へ] の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="efe76-166">Retrieve next list of configurations.</span></span>  <span data-ttu-id="efe76-167">(詳細については http://aka.ms/azureautomationsdk/dscnodeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="efe76-167">(see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="efe76-168">一覧の dsc ノードの操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="efe76-168">The response model for the list dsc nodes operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscNodePatchResponse Patch (this Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodePatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscNodePatchResponse Patch(class Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodePatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.Patch(Microsoft.Azure.Management.Automation.IDscNodeOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodePatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Patch (operations As IDscNodeOperations, resourceGroupName As String, automationAccount As String, parameters As DscNodePatchParameters) As DscNodePatchResponse" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Management.Automation.IDscNodeOperations * string * string * Microsoft.Azure.Management.Automation.Models.DscNodePatchParameters -&gt; Microsoft.Azure.Management.Automation.Models.DscNodePatchResponse" Usage="Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.Patch (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscNodePatchResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodePatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="efe76-169">Microsoft.Azure.Management.Automation.IDscNodeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="efe76-169">Reference to the Microsoft.Azure.Management.Automation.IDscNodeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="efe76-170">必須。</span><span class="sxs-lookup"><span data-stu-id="efe76-170">Required.</span></span> <span data-ttu-id="efe76-171">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="efe76-171">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="efe76-172">必須。</span><span class="sxs-lookup"><span data-stu-id="efe76-172">Required.</span></span> <span data-ttu-id="efe76-173">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="efe76-173">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="efe76-174">必須。</span><span class="sxs-lookup"><span data-stu-id="efe76-174">Required.</span></span> <span data-ttu-id="efe76-175">修正プログラムの dsc ノードに指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="efe76-175">Parameters supplied to the patch dsc node.</span></span>
            </param>
        <summary>
            <span data-ttu-id="efe76-176">Dsc ノードを更新します。</span><span class="sxs-lookup"><span data-stu-id="efe76-176">Update the dsc node.</span></span>  <span data-ttu-id="efe76-177">(詳細については http://aka.ms/azureautomationsdk/dscnodeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="efe76-177">(see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="efe76-178">修正プログラムの dsc ノードの操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="efe76-178">The response model for the patch dsc node operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodePatchResponse&gt; PatchAsync (this Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodePatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodePatchResponse&gt; PatchAsync(class Microsoft.Azure.Management.Automation.IDscNodeOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodePatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.PatchAsync(Microsoft.Azure.Management.Automation.IDscNodeOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodePatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PatchAsync (operations As IDscNodeOperations, resourceGroupName As String, automationAccount As String, parameters As DscNodePatchParameters) As Task(Of DscNodePatchResponse)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Management.Automation.IDscNodeOperations * string * string * Microsoft.Azure.Management.Automation.Models.DscNodePatchParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodePatchResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscNodeOperationsExtensions.PatchAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodePatchResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscNodeOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodePatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="efe76-179">Microsoft.Azure.Management.Automation.IDscNodeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="efe76-179">Reference to the Microsoft.Azure.Management.Automation.IDscNodeOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="efe76-180">必須。</span><span class="sxs-lookup"><span data-stu-id="efe76-180">Required.</span></span> <span data-ttu-id="efe76-181">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="efe76-181">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="efe76-182">必須。</span><span class="sxs-lookup"><span data-stu-id="efe76-182">Required.</span></span> <span data-ttu-id="efe76-183">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="efe76-183">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="efe76-184">必須。</span><span class="sxs-lookup"><span data-stu-id="efe76-184">Required.</span></span> <span data-ttu-id="efe76-185">修正プログラムの dsc ノードに指定するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="efe76-185">Parameters supplied to the patch dsc node.</span></span>
            </param>
        <summary>
            <span data-ttu-id="efe76-186">Dsc ノードを更新します。</span><span class="sxs-lookup"><span data-stu-id="efe76-186">Update the dsc node.</span></span>  <span data-ttu-id="efe76-187">(詳細については http://aka.ms/azureautomationsdk/dscnodeoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="efe76-187">(see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="efe76-188">修正プログラムの dsc ノードの操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="efe76-188">The response model for the patch dsc node operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>