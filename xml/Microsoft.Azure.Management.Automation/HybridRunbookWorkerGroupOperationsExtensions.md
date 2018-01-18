<Type Name="HybridRunbookWorkerGroupOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class HybridRunbookWorkerGroupOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit HybridRunbookWorkerGroupOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module HybridRunbookWorkerGroupOperationsExtensions" />
  <TypeSignature Language="F#" Value="type HybridRunbookWorkerGroupOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.Delete(Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IHybridRunbookWorkerGroupOperations, resourceGroupName As String, automationAccount As String, hybridRunbookWorkerGroupName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.Delete (operations, resourceGroupName, automationAccount, hybridRunbookWorkerGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="hybridRunbookWorkerGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6d8b2-101">Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-101">Reference to the Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6d8b2-102">必須。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-102">Required.</span></span> <span data-ttu-id="6d8b2-103">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="6d8b2-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="6d8b2-104">必須。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-104">Required.</span></span> <span data-ttu-id="6d8b2-105">オートメーション アカウントの名前です。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-105">Automation account name.</span></span>
            </param>
        <param name="hybridRunbookWorkerGroupName">
            <span data-ttu-id="6d8b2-106">必須。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-106">Required.</span></span> <span data-ttu-id="6d8b2-107">ハイブリッド runbook worker グループ名</span><span class="sxs-lookup"><span data-stu-id="6d8b2-107">The hybrid runbook worker group name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6d8b2-108">Hybrid runbook worker グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-108">Delete a hybrid runbook worker group.</span></span>  <span data-ttu-id="6d8b2-109">(詳細については http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="6d8b2-109">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6d8b2-110">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="6d8b2-110">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IHybridRunbookWorkerGroupOperations, resourceGroupName As String, automationAccount As String, hybridRunbookWorkerGroupName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.DeleteAsync (operations, resourceGroupName, automationAccount, hybridRunbookWorkerGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="hybridRunbookWorkerGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6d8b2-111">Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-111">Reference to the Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6d8b2-112">必須。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-112">Required.</span></span> <span data-ttu-id="6d8b2-113">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="6d8b2-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="6d8b2-114">必須。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-114">Required.</span></span> <span data-ttu-id="6d8b2-115">オートメーション アカウントの名前です。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-115">Automation account name.</span></span>
            </param>
        <param name="hybridRunbookWorkerGroupName">
            <span data-ttu-id="6d8b2-116">必須。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-116">Required.</span></span> <span data-ttu-id="6d8b2-117">ハイブリッド runbook worker グループ名</span><span class="sxs-lookup"><span data-stu-id="6d8b2-117">The hybrid runbook worker group name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6d8b2-118">Hybrid runbook worker グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-118">Delete a hybrid runbook worker group.</span></span>  <span data-ttu-id="6d8b2-119">(詳細については http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="6d8b2-119">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6d8b2-120">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="6d8b2-120">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse Get (this Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse Get(class Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IHybridRunbookWorkerGroupOperations, resourceGroupName As String, automationAccount As String, hybridRunbookWorkerGroupName As String) As HybridRunbookWorkerGroupGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse" Usage="Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.Get (operations, resourceGroupName, automationAccount, hybridRunbookWorkerGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="hybridRunbookWorkerGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6d8b2-121">Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-121">Reference to the Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6d8b2-122">必須。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-122">Required.</span></span> <span data-ttu-id="6d8b2-123">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="6d8b2-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="6d8b2-124">必須。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-124">Required.</span></span> <span data-ttu-id="6d8b2-125">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-125">The automation account name.</span></span>
            </param>
        <param name="hybridRunbookWorkerGroupName">
            <span data-ttu-id="6d8b2-126">必須。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-126">Required.</span></span> <span data-ttu-id="6d8b2-127">ハイブリッド runbook worker グループ名</span><span class="sxs-lookup"><span data-stu-id="6d8b2-127">The hybrid runbook worker group name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6d8b2-128">Hybrid runbook worker グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-128">Retrieve a hybrid runbook worker group.</span></span>  <span data-ttu-id="6d8b2-129">(詳細については http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="6d8b2-129">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6d8b2-130">Get ハイブリッド runbook worker グループの操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-130">The response model for the get hybrid runbook worker group operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IHybridRunbookWorkerGroupOperations, resourceGroupName As String, automationAccount As String, hybridRunbookWorkerGroupName As String) As Task(Of HybridRunbookWorkerGroupGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, hybridRunbookWorkerGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="hybridRunbookWorkerGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6d8b2-131">Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-131">Reference to the Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6d8b2-132">必須。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-132">Required.</span></span> <span data-ttu-id="6d8b2-133">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="6d8b2-133">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="6d8b2-134">必須。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-134">Required.</span></span> <span data-ttu-id="6d8b2-135">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-135">The automation account name.</span></span>
            </param>
        <param name="hybridRunbookWorkerGroupName">
            <span data-ttu-id="6d8b2-136">必須。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-136">Required.</span></span> <span data-ttu-id="6d8b2-137">ハイブリッド runbook worker グループ名</span><span class="sxs-lookup"><span data-stu-id="6d8b2-137">The hybrid runbook worker group name</span></span>
            </param>
        <summary>
            <span data-ttu-id="6d8b2-138">Hybrid runbook worker グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-138">Retrieve a hybrid runbook worker group.</span></span>  <span data-ttu-id="6d8b2-139">(詳細については http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="6d8b2-139">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6d8b2-140">Get ハイブリッド runbook worker グループの操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-140">The response model for the get hybrid runbook worker group operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse List (this Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse List(class Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.List(Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IHybridRunbookWorkerGroupOperations, resourceGroupName As String, automationAccount As String) As HybridRunbookWorkerGroupsListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations * string * string -&gt; Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse" Usage="Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.List (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6d8b2-141">Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-141">Reference to the Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6d8b2-142">必須。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-142">Required.</span></span> <span data-ttu-id="6d8b2-143">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="6d8b2-143">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="6d8b2-144">必須。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-144">Required.</span></span> <span data-ttu-id="6d8b2-145">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-145">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6d8b2-146">ハイブリッド runbook worker グループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-146">Retrieve a list of hybrid runbook worker groups.</span></span>  <span data-ttu-id="6d8b2-147">(詳細については http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="6d8b2-147">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6d8b2-148">リストのハイブリッド runbook worker グループの応答モデル。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-148">The response model for the list hybrid runbook worker groups.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IHybridRunbookWorkerGroupOperations, resourceGroupName As String, automationAccount As String) As Task(Of HybridRunbookWorkerGroupsListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6d8b2-149">Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-149">Reference to the Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6d8b2-150">必須。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-150">Required.</span></span> <span data-ttu-id="6d8b2-151">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="6d8b2-151">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="6d8b2-152">必須。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-152">Required.</span></span> <span data-ttu-id="6d8b2-153">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-153">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6d8b2-154">ハイブリッド runbook worker グループの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-154">Retrieve a list of hybrid runbook worker groups.</span></span>  <span data-ttu-id="6d8b2-155">(詳細については http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="6d8b2-155">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6d8b2-156">リストのハイブリッド runbook worker グループの応答モデル。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-156">The response model for the list hybrid runbook worker groups.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse ListNext (this Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse ListNext(class Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IHybridRunbookWorkerGroupOperations, nextLink As String) As HybridRunbookWorkerGroupsListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse" Usage="Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6d8b2-157">Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-157">Reference to the Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="6d8b2-158">必須。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-158">Required.</span></span> <span data-ttu-id="6d8b2-159">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-159">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6d8b2-160">ハイブリッド runbook worker グループの [次へ] の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-160">Retrieve next list of hybrid runbook worker groups.</span></span>  <span data-ttu-id="6d8b2-161">(詳細については http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="6d8b2-161">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6d8b2-162">リストのハイブリッド runbook worker グループの応答モデル。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-162">The response model for the list hybrid runbook worker groups.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IHybridRunbookWorkerGroupOperations, nextLink As String) As Task(Of HybridRunbookWorkerGroupsListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6d8b2-163">Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-163">Reference to the Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="6d8b2-164">必須。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-164">Required.</span></span> <span data-ttu-id="6d8b2-165">次の項目のセットを取得するリンクです。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-165">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6d8b2-166">ハイブリッド runbook worker グループの [次へ] の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-166">Retrieve next list of hybrid runbook worker groups.</span></span>  <span data-ttu-id="6d8b2-167">(詳細については http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="6d8b2-167">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6d8b2-168">リストのハイブリッド runbook worker グループの応答モデル。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-168">The response model for the list hybrid runbook worker groups.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse Patch (this Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName, Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse Patch(class Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName, class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.Patch(Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Patch (operations As IHybridRunbookWorkerGroupOperations, resourceGroupName As String, automationAccount As String, hybridRunbookWorkerGroupName As String, parameters As HybridRunbookWorkerGroupPatchParameters) As HybridRunbookWorkerGroupPatchResponse" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations * string * string * string * Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters -&gt; Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse" Usage="Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.Patch (operations, resourceGroupName, automationAccount, hybridRunbookWorkerGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="hybridRunbookWorkerGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6d8b2-169">Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-169">Reference to the Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6d8b2-170">必須。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-170">Required.</span></span> <span data-ttu-id="6d8b2-171">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="6d8b2-171">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="6d8b2-172">必須。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-172">Required.</span></span> <span data-ttu-id="6d8b2-173">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-173">The automation account name.</span></span>
            </param>
        <param name="hybridRunbookWorkerGroupName">
            <span data-ttu-id="6d8b2-174">必須。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-174">Required.</span></span> <span data-ttu-id="6d8b2-175">ハイブリッド runbook worker グループ名</span><span class="sxs-lookup"><span data-stu-id="6d8b2-175">The hybrid runbook worker group name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6d8b2-176">必須。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-176">Required.</span></span> <span data-ttu-id="6d8b2-177">Hybrid runbook worker グループ</span><span class="sxs-lookup"><span data-stu-id="6d8b2-177">The hybrid runbook worker group</span></span>
            </param>
        <summary>
            <span data-ttu-id="6d8b2-178">Hybrid runbook worker グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-178">Update a hybrid runbook worker group.</span></span>  <span data-ttu-id="6d8b2-179">(詳細については http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="6d8b2-179">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6d8b2-180">修正プログラム ハイブリッド runbook worker グループの操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-180">The response model for the patch hybrid runbook worker group operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse&gt; PatchAsync (this Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName, Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse&gt; PatchAsync(class Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations operations, string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName, class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.PatchAsync(Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PatchAsync (operations As IHybridRunbookWorkerGroupOperations, resourceGroupName As String, automationAccount As String, hybridRunbookWorkerGroupName As String, parameters As HybridRunbookWorkerGroupPatchParameters) As Task(Of HybridRunbookWorkerGroupPatchResponse)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations * string * string * string * Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse&gt;" Usage="Microsoft.Azure.Management.Automation.HybridRunbookWorkerGroupOperationsExtensions.PatchAsync (operations, resourceGroupName, automationAccount, hybridRunbookWorkerGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="hybridRunbookWorkerGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6d8b2-181">Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-181">Reference to the Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6d8b2-182">必須。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-182">Required.</span></span> <span data-ttu-id="6d8b2-183">リソース グループの名前</span><span class="sxs-lookup"><span data-stu-id="6d8b2-183">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="6d8b2-184">必須。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-184">Required.</span></span> <span data-ttu-id="6d8b2-185">オートメーション アカウントの名前。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-185">The automation account name.</span></span>
            </param>
        <param name="hybridRunbookWorkerGroupName">
            <span data-ttu-id="6d8b2-186">必須。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-186">Required.</span></span> <span data-ttu-id="6d8b2-187">ハイブリッド runbook worker グループ名</span><span class="sxs-lookup"><span data-stu-id="6d8b2-187">The hybrid runbook worker group name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6d8b2-188">必須。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-188">Required.</span></span> <span data-ttu-id="6d8b2-189">Hybrid runbook worker グループ</span><span class="sxs-lookup"><span data-stu-id="6d8b2-189">The hybrid runbook worker group</span></span>
            </param>
        <summary>
            <span data-ttu-id="6d8b2-190">Hybrid runbook worker グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-190">Update a hybrid runbook worker group.</span></span>  <span data-ttu-id="6d8b2-191">(詳細については http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations を参照してください)</span><span class="sxs-lookup"><span data-stu-id="6d8b2-191">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6d8b2-192">修正プログラム ハイブリッド runbook worker グループの操作の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="6d8b2-192">The response model for the patch hybrid runbook worker group operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>