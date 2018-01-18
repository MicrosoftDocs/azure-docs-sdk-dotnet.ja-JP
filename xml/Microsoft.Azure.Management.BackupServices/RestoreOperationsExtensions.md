<Type Name="RestoreOperationsExtensions" FullName="Microsoft.Azure.Management.BackupServices.RestoreOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RestoreOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RestoreOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.RestoreOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RestoreOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RestoreOperationsExtensions = class" />
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
    <Member MemberName="TriggerResotre">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.OperationResponse TriggerResotre (this Microsoft.Azure.Management.BackupServices.IRestoreOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, string recoveryPointName, Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.OperationResponse TriggerResotre(class Microsoft.Azure.Management.BackupServices.IRestoreOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, string recoveryPointName, class Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.RestoreOperationsExtensions.TriggerResotre(Microsoft.Azure.Management.BackupServices.IRestoreOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest)" />
      <MemberSignature Language="F#" Value="static member TriggerResotre : Microsoft.Azure.Management.BackupServices.IRestoreOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest -&gt; Microsoft.Azure.Management.BackupServices.OperationResponse" Usage="Microsoft.Azure.Management.BackupServices.RestoreOperationsExtensions.TriggerResotre (operations, resourceGroupName, resourceName, customRequestHeaders, containerName, itemName, recoveryPointName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.OperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IRestoreOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
        <Parameter Name="recoveryPointName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5e8b1-101">Microsoft.Azure.Management.BackupServices.IRestoreOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="5e8b1-101">Reference to the Microsoft.Azure.Management.BackupServices.IRestoreOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5e8b1-102">必須。</span><span class="sxs-lookup"><span data-stu-id="5e8b1-102">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="5e8b1-103">必須。</span><span class="sxs-lookup"><span data-stu-id="5e8b1-103">Required.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="5e8b1-104">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5e8b1-104">Optional.</span></span> <span data-ttu-id="5e8b1-105">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="5e8b1-105">Request header parameters.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="5e8b1-106">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5e8b1-106">Optional.</span></span>
            </param>
        <param name="itemName">
            <span data-ttu-id="5e8b1-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5e8b1-107">Optional.</span></span>
            </param>
        <param name="recoveryPointName">
            <span data-ttu-id="5e8b1-108">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5e8b1-108">Optional.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5e8b1-109">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5e8b1-109">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5e8b1-110">Azure BackUpItem を復元します。</span><span class="sxs-lookup"><span data-stu-id="5e8b1-110">Restore Azure BackUpItem.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5e8b1-111">操作の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="5e8b1-111">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerResotreAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; TriggerResotreAsync (this Microsoft.Azure.Management.BackupServices.IRestoreOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, string recoveryPointName, Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; TriggerResotreAsync(class Microsoft.Azure.Management.BackupServices.IRestoreOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, string recoveryPointName, class Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.RestoreOperationsExtensions.TriggerResotreAsync(Microsoft.Azure.Management.BackupServices.IRestoreOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest)" />
      <MemberSignature Language="F#" Value="static member TriggerResotreAsync : Microsoft.Azure.Management.BackupServices.IRestoreOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.RestoreOperationsExtensions.TriggerResotreAsync (operations, resourceGroupName, resourceName, customRequestHeaders, containerName, itemName, recoveryPointName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IRestoreOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
        <Parameter Name="recoveryPointName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BackupServices.Models.CSMRestoreRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5e8b1-112">Microsoft.Azure.Management.BackupServices.IRestoreOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="5e8b1-112">Reference to the Microsoft.Azure.Management.BackupServices.IRestoreOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5e8b1-113">必須。</span><span class="sxs-lookup"><span data-stu-id="5e8b1-113">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="5e8b1-114">必須。</span><span class="sxs-lookup"><span data-stu-id="5e8b1-114">Required.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="5e8b1-115">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5e8b1-115">Optional.</span></span> <span data-ttu-id="5e8b1-116">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="5e8b1-116">Request header parameters.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="5e8b1-117">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5e8b1-117">Optional.</span></span>
            </param>
        <param name="itemName">
            <span data-ttu-id="5e8b1-118">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5e8b1-118">Optional.</span></span>
            </param>
        <param name="recoveryPointName">
            <span data-ttu-id="5e8b1-119">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5e8b1-119">Optional.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5e8b1-120">省略可能。</span><span class="sxs-lookup"><span data-stu-id="5e8b1-120">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5e8b1-121">Azure BackUpItem を復元します。</span><span class="sxs-lookup"><span data-stu-id="5e8b1-121">Restore Azure BackUpItem.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5e8b1-122">操作の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="5e8b1-122">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>