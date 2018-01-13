<Type Name="CSMProtectionPolicyOperationsExtensions" FullName="Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class CSMProtectionPolicyOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CSMProtectionPolicyOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CSMProtectionPolicyOperationsExtensions" />
  <TypeSignature Language="F#" Value="type CSMProtectionPolicyOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Add (this Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, string policyName, Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequest cSMAddProtectionPolicyRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Add(class Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, string policyName, class Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequest cSMAddProtectionPolicyRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.Add(Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Add : Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.Add (operations, resourceGroupName, resourceName, policyName, cSMAddProtectionPolicyRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="cSMAddProtectionPolicyRequest" Type="Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b6bd2-101">Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-101">Reference to the Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b6bd2-102">必須。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-102">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b6bd2-103">必須。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-103">Required.</span></span>
            </param>
        <param name="policyName">
            <span data-ttu-id="b6bd2-104">必須。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-104">Required.</span></span> <span data-ttu-id="b6bd2-105">保護ポリシーを更新する名前。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-105">The protection policy Name to be updated.</span></span>
            </param>
        <param name="cSMAddProtectionPolicyRequest">
            <span data-ttu-id="b6bd2-106">必須。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-106">Required.</span></span> <span data-ttu-id="b6bd2-107">保護ポリシーの作成要求。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-107">The protection policy creation request.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="b6bd2-108">省略可能。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-108">Optional.</span></span> <span data-ttu-id="b6bd2-109">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-109">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b6bd2-110">新しい保護ポリシーを作成します。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-110">Create new Protection Policy.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b6bd2-111">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="b6bd2-111">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; AddAsync (this Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, string policyName, Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequest cSMAddProtectionPolicyRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; AddAsync(class Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, string policyName, class Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequest cSMAddProtectionPolicyRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.AddAsync(Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member AddAsync : Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.AddAsync (operations, resourceGroupName, resourceName, policyName, cSMAddProtectionPolicyRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="cSMAddProtectionPolicyRequest" Type="Microsoft.Azure.Management.BackupServices.Models.CSMAddProtectionPolicyRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b6bd2-112">Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-112">Reference to the Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b6bd2-113">必須。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-113">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b6bd2-114">必須。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-114">Required.</span></span>
            </param>
        <param name="policyName">
            <span data-ttu-id="b6bd2-115">必須。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-115">Required.</span></span> <span data-ttu-id="b6bd2-116">保護ポリシーを更新する名前。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-116">The protection policy Name to be updated.</span></span>
            </param>
        <param name="cSMAddProtectionPolicyRequest">
            <span data-ttu-id="b6bd2-117">必須。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-117">Required.</span></span> <span data-ttu-id="b6bd2-118">保護ポリシーの作成要求。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-118">The protection policy creation request.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="b6bd2-119">省略可能。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-119">Optional.</span></span> <span data-ttu-id="b6bd2-120">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-120">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b6bd2-121">新しい保護ポリシーを作成します。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-121">Create new Protection Policy.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b6bd2-122">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="b6bd2-122">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, string policyName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, string policyName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.Delete(Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.Delete (operations, resourceGroupName, resourceName, policyName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b6bd2-123">Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-123">Reference to the Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b6bd2-124">必須。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-124">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b6bd2-125">必須。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-125">Required.</span></span>
            </param>
        <param name="policyName">
            <span data-ttu-id="b6bd2-126">必須。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-126">Required.</span></span> <span data-ttu-id="b6bd2-127">保護ポリシーを削除する名前。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-127">The protection policy Name to be deleted.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="b6bd2-128">省略可能。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-128">Optional.</span></span> <span data-ttu-id="b6bd2-129">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-129">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b6bd2-130">保護ポリシーを削除します。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-130">Delete a Protection Policy.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b6bd2-131">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="b6bd2-131">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, string policyName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, string policyName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.DeleteAsync (operations, resourceGroupName, resourceName, policyName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b6bd2-132">Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-132">Reference to the Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b6bd2-133">必須。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-133">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b6bd2-134">必須。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-134">Required.</span></span>
            </param>
        <param name="policyName">
            <span data-ttu-id="b6bd2-135">必須。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-135">Required.</span></span> <span data-ttu-id="b6bd2-136">保護ポリシーを削除する名前。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-136">The protection policy Name to be deleted.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="b6bd2-137">省略可能。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-137">Optional.</span></span> <span data-ttu-id="b6bd2-138">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-138">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b6bd2-139">保護ポリシーを削除します。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-139">Delete a Protection Policy.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b6bd2-140">HTTP ステータス コードと要求 ID を含む標準サービスの応答</span><span class="sxs-lookup"><span data-stu-id="b6bd2-140">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyListOperationResponse List (this Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyListOperationResponse List(class Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.List(Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyListOperationResponse" Usage="Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.List (operations, resourceGroupName, resourceName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyListOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b6bd2-141">Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-141">Reference to the Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b6bd2-142">必須。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-142">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b6bd2-143">必須。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-143">Required.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="b6bd2-144">省略可能。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-144">Optional.</span></span> <span data-ttu-id="b6bd2-145">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-145">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b6bd2-146">すべての保護ポリシーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-146">Get the list of all Protection Policy.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b6bd2-147">CSMProtectionPolicyListOperationResponse の定義。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-147">The definition of a CSMProtectionPolicyListOperationResponse.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyListOperationResponse&gt; ListAsync (this Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyListOperationResponse&gt; ListAsync(class Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.ListAsync(Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyListOperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.ListAsync (operations, resourceGroupName, resourceName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMProtectionPolicyListOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b6bd2-148">Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-148">Reference to the Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b6bd2-149">必須。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-149">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b6bd2-150">必須。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-150">Required.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="b6bd2-151">省略可能。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-151">Optional.</span></span> <span data-ttu-id="b6bd2-152">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-152">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b6bd2-153">すべての保護ポリシーの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-153">Get the list of all Protection Policy.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b6bd2-154">CSMProtectionPolicyListOperationResponse の定義。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-154">The definition of a CSMProtectionPolicyListOperationResponse.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.OperationResponse Update (this Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, string policyName, Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionPolicyRequest cSMUpdateProtectionPolicyRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.OperationResponse Update(class Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, string policyName, class Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionPolicyRequest cSMUpdateProtectionPolicyRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.Update(Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionPolicyRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionPolicyRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.OperationResponse" Usage="Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.Update (operations, resourceGroupName, resourceName, policyName, cSMUpdateProtectionPolicyRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.OperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="cSMUpdateProtectionPolicyRequest" Type="Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionPolicyRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b6bd2-155">Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-155">Reference to the Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b6bd2-156">必須。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-156">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b6bd2-157">必須。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-157">Required.</span></span>
            </param>
        <param name="policyName">
            <span data-ttu-id="b6bd2-158">必須。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-158">Required.</span></span> <span data-ttu-id="b6bd2-159">保護ポリシーを更新する名前。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-159">The protection policy Name to be updated.</span></span>
            </param>
        <param name="cSMUpdateProtectionPolicyRequest">
            <span data-ttu-id="b6bd2-160">必須。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-160">Required.</span></span> <span data-ttu-id="b6bd2-161">保護ポリシーの作成要求。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-161">The protection policy creation request.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="b6bd2-162">省略可能。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-162">Optional.</span></span> <span data-ttu-id="b6bd2-163">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-163">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b6bd2-164">保護ポリシーを更新します。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-164">Update Protection Policy.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b6bd2-165">操作の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-165">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UpdateAsync (this Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, string policyName, Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionPolicyRequest cSMUpdateProtectionPolicyRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UpdateAsync(class Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations operations, string resourceGroupName, string resourceName, string policyName, class Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionPolicyRequest cSMUpdateProtectionPolicyRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionPolicyRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionPolicyRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.CSMProtectionPolicyOperationsExtensions.UpdateAsync (operations, resourceGroupName, resourceName, policyName, cSMUpdateProtectionPolicyRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="cSMUpdateProtectionPolicyRequest" Type="Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionPolicyRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b6bd2-166">Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-166">Reference to the Microsoft.Azure.Management.BackupServices.ICSMProtectionPolicyOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b6bd2-167">必須。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-167">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b6bd2-168">必須。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-168">Required.</span></span>
            </param>
        <param name="policyName">
            <span data-ttu-id="b6bd2-169">必須。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-169">Required.</span></span> <span data-ttu-id="b6bd2-170">保護ポリシーを更新する名前。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-170">The protection policy Name to be updated.</span></span>
            </param>
        <param name="cSMUpdateProtectionPolicyRequest">
            <span data-ttu-id="b6bd2-171">必須。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-171">Required.</span></span> <span data-ttu-id="b6bd2-172">保護ポリシーの作成要求。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-172">The protection policy creation request.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="b6bd2-173">省略可能。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-173">Optional.</span></span> <span data-ttu-id="b6bd2-174">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-174">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b6bd2-175">保護ポリシーを更新します。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-175">Update Protection Policy.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b6bd2-176">操作の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="b6bd2-176">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>