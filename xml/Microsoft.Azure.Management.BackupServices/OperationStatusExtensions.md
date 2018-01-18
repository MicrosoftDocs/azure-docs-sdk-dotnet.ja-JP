<Type Name="OperationStatusExtensions" FullName="Microsoft.Azure.Management.BackupServices.OperationStatusExtensions">
  <TypeSignature Language="C#" Value="public static class OperationStatusExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit OperationStatusExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.OperationStatusExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module OperationStatusExtensions" />
  <TypeSignature Language="F#" Value="type OperationStatusExtensions = class" />
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
    <Member MemberName="CSMGet">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.CSMOperationResult CSMGet (this Microsoft.Azure.Management.BackupServices.IOperationStatus operations, string resourceGroupName, string resourceName, string operationId, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.CSMOperationResult CSMGet(class Microsoft.Azure.Management.BackupServices.IOperationStatus operations, string resourceGroupName, string resourceName, string operationId, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.OperationStatusExtensions.CSMGet(Microsoft.Azure.Management.BackupServices.IOperationStatus,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member CSMGet : Microsoft.Azure.Management.BackupServices.IOperationStatus * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; Microsoft.Azure.Management.BackupServices.CSMOperationResult" Usage="Microsoft.Azure.Management.BackupServices.OperationStatusExtensions.CSMGet (operations, resourceGroupName, resourceName, operationId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.CSMOperationResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IOperationStatus" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22f36-101">Microsoft.Azure.Management.BackupServices.IOperationStatus への参照。</span><span class="sxs-lookup"><span data-stu-id="22f36-101">Reference to the Microsoft.Azure.Management.BackupServices.IOperationStatus.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="22f36-102">必須。</span><span class="sxs-lookup"><span data-stu-id="22f36-102">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="22f36-103">必須。</span><span class="sxs-lookup"><span data-stu-id="22f36-103">Required.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="22f36-104">必須。</span><span class="sxs-lookup"><span data-stu-id="22f36-104">Required.</span></span> <span data-ttu-id="22f36-105">OperationId です。</span><span class="sxs-lookup"><span data-stu-id="22f36-105">OperationId.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="22f36-106">省略可能。</span><span class="sxs-lookup"><span data-stu-id="22f36-106">Optional.</span></span> <span data-ttu-id="22f36-107">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="22f36-107">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="22f36-108">操作の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="22f36-108">Get the Operation Status.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="22f36-109">CSMOperationResult の定義。</span><span class="sxs-lookup"><span data-stu-id="22f36-109">The definition of a CSMOperationResult.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CSMGetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.CSMOperationResult&gt; CSMGetAsync (this Microsoft.Azure.Management.BackupServices.IOperationStatus operations, string resourceGroupName, string resourceName, string operationId, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.CSMOperationResult&gt; CSMGetAsync(class Microsoft.Azure.Management.BackupServices.IOperationStatus operations, string resourceGroupName, string resourceName, string operationId, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.OperationStatusExtensions.CSMGetAsync(Microsoft.Azure.Management.BackupServices.IOperationStatus,System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member CSMGetAsync : Microsoft.Azure.Management.BackupServices.IOperationStatus * string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.CSMOperationResult&gt;" Usage="Microsoft.Azure.Management.BackupServices.OperationStatusExtensions.CSMGetAsync (operations, resourceGroupName, resourceName, operationId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.CSMOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IOperationStatus" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="22f36-110">Microsoft.Azure.Management.BackupServices.IOperationStatus への参照。</span><span class="sxs-lookup"><span data-stu-id="22f36-110">Reference to the Microsoft.Azure.Management.BackupServices.IOperationStatus.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="22f36-111">必須。</span><span class="sxs-lookup"><span data-stu-id="22f36-111">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="22f36-112">必須。</span><span class="sxs-lookup"><span data-stu-id="22f36-112">Required.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="22f36-113">必須。</span><span class="sxs-lookup"><span data-stu-id="22f36-113">Required.</span></span> <span data-ttu-id="22f36-114">OperationId です。</span><span class="sxs-lookup"><span data-stu-id="22f36-114">OperationId.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="22f36-115">省略可能。</span><span class="sxs-lookup"><span data-stu-id="22f36-115">Optional.</span></span> <span data-ttu-id="22f36-116">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="22f36-116">Request header parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="22f36-117">操作の状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="22f36-117">Get the Operation Status.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="22f36-118">CSMOperationResult の定義。</span><span class="sxs-lookup"><span data-stu-id="22f36-118">The definition of a CSMOperationResult.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>