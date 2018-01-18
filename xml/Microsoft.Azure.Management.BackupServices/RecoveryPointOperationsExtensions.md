<Type Name="RecoveryPointOperationsExtensions" FullName="Microsoft.Azure.Management.BackupServices.RecoveryPointOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RecoveryPointOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RecoveryPointOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.RecoveryPointOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RecoveryPointOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RecoveryPointOperationsExtensions = class" />
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
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointGetOperationResponse Get (this Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, string recoveryPointName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointGetOperationResponse Get(class Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, string recoveryPointName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.RecoveryPointOperationsExtensions.Get(Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string * string -&gt; Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointGetOperationResponse" Usage="Microsoft.Azure.Management.BackupServices.RecoveryPointOperationsExtensions.Get (operations, resourceGroupName, resourceName, customRequestHeaders, containerName, itemName, recoveryPointName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointGetOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
        <Parameter Name="recoveryPointName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5b811-101">Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="5b811-101">Reference to the Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5b811-102">必須。</span><span class="sxs-lookup"><span data-stu-id="5b811-102">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="5b811-103">必須。</span><span class="sxs-lookup"><span data-stu-id="5b811-103">Required.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="5b811-104">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5b811-104">Optional.</span></span> <span data-ttu-id="5b811-105">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="5b811-105">Request header parameters.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="5b811-106">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5b811-106">Optional.</span></span>
            </param>
        <param name="itemName">
            <span data-ttu-id="5b811-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5b811-107">Optional.</span></span>
            </param>
        <param name="recoveryPointName">
            <span data-ttu-id="5b811-108">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5b811-108">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5b811-109">回復ポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="5b811-109">Get the recovery point.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5b811-110">CSMRecoveryPointGetOperationResponse の定義。</span><span class="sxs-lookup"><span data-stu-id="5b811-110">The definition of a CSMRecoveryPointGetOperationResponse.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointGetOperationResponse&gt; GetAsync (this Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, string recoveryPointName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointGetOperationResponse&gt; GetAsync(class Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, string recoveryPointName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.RecoveryPointOperationsExtensions.GetAsync(Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointGetOperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.RecoveryPointOperationsExtensions.GetAsync (operations, resourceGroupName, resourceName, customRequestHeaders, containerName, itemName, recoveryPointName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointGetOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
        <Parameter Name="recoveryPointName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5b811-111">Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="5b811-111">Reference to the Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5b811-112">必須。</span><span class="sxs-lookup"><span data-stu-id="5b811-112">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="5b811-113">必須。</span><span class="sxs-lookup"><span data-stu-id="5b811-113">Required.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="5b811-114">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5b811-114">Optional.</span></span> <span data-ttu-id="5b811-115">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="5b811-115">Request header parameters.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="5b811-116">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5b811-116">Optional.</span></span>
            </param>
        <param name="itemName">
            <span data-ttu-id="5b811-117">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5b811-117">Optional.</span></span>
            </param>
        <param name="recoveryPointName">
            <span data-ttu-id="5b811-118">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5b811-118">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5b811-119">回復ポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="5b811-119">Get the recovery point.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5b811-120">CSMRecoveryPointGetOperationResponse の定義。</span><span class="sxs-lookup"><span data-stu-id="5b811-120">The definition of a CSMRecoveryPointGetOperationResponse.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointListOperationResponse List (this Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointListOperationResponse List(class Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.RecoveryPointOperationsExtensions.List(Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string -&gt; Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointListOperationResponse" Usage="Microsoft.Azure.Management.BackupServices.RecoveryPointOperationsExtensions.List (operations, resourceGroupName, resourceName, customRequestHeaders, containerName, itemName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointListOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5b811-121">Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="5b811-121">Reference to the Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5b811-122">必須。</span><span class="sxs-lookup"><span data-stu-id="5b811-122">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="5b811-123">必須。</span><span class="sxs-lookup"><span data-stu-id="5b811-123">Required.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="5b811-124">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5b811-124">Optional.</span></span> <span data-ttu-id="5b811-125">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="5b811-125">Request header parameters.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="5b811-126">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5b811-126">Optional.</span></span>
            </param>
        <param name="itemName">
            <span data-ttu-id="5b811-127">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5b811-127">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5b811-128">すべての回復ポイントの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5b811-128">Get the list of all recovery points.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5b811-129">CSMRecoveryPointListOperationResponse の定義。</span><span class="sxs-lookup"><span data-stu-id="5b811-129">The definition of a CSMRecoveryPointListOperationResponse.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointListOperationResponse&gt; ListAsync (this Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointListOperationResponse&gt; ListAsync(class Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.RecoveryPointOperationsExtensions.ListAsync(Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointListOperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.RecoveryPointOperationsExtensions.ListAsync (operations, resourceGroupName, resourceName, customRequestHeaders, containerName, itemName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMRecoveryPointListOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5b811-130">Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="5b811-130">Reference to the Microsoft.Azure.Management.BackupServices.IRecoveryPointOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5b811-131">必須。</span><span class="sxs-lookup"><span data-stu-id="5b811-131">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="5b811-132">必須。</span><span class="sxs-lookup"><span data-stu-id="5b811-132">Required.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="5b811-133">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5b811-133">Optional.</span></span> <span data-ttu-id="5b811-134">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="5b811-134">Request header parameters.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="5b811-135">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5b811-135">Optional.</span></span>
            </param>
        <param name="itemName">
            <span data-ttu-id="5b811-136">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5b811-136">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5b811-137">すべての回復ポイントの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="5b811-137">Get the list of all recovery points.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5b811-138">CSMRecoveryPointListOperationResponse の定義。</span><span class="sxs-lookup"><span data-stu-id="5b811-138">The definition of a CSMRecoveryPointListOperationResponse.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>