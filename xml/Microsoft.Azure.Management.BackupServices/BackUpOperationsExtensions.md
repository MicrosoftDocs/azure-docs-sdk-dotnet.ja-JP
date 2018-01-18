<Type Name="BackUpOperationsExtensions" FullName="Microsoft.Azure.Management.BackupServices.BackUpOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackUpOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackUpOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.BackUpOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackUpOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackUpOperationsExtensions = class" />
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
    <Member MemberName="TriggerBackUp">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BackupServices.OperationResponse TriggerBackUp (this Microsoft.Azure.Management.BackupServices.IBackUpOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BackupServices.OperationResponse TriggerBackUp(class Microsoft.Azure.Management.BackupServices.IBackUpOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.BackUpOperationsExtensions.TriggerBackUp(Microsoft.Azure.Management.BackupServices.IBackUpOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member TriggerBackUp : Microsoft.Azure.Management.BackupServices.IBackUpOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string -&gt; Microsoft.Azure.Management.BackupServices.OperationResponse" Usage="Microsoft.Azure.Management.BackupServices.BackUpOperationsExtensions.TriggerBackUp (operations, resourceGroupName, resourceName, customRequestHeaders, containerName, itemName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.OperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IBackUpOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="89328-101">Microsoft.Azure.Management.BackupServices.IBackUpOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="89328-101">Reference to the Microsoft.Azure.Management.BackupServices.IBackUpOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="89328-102">必須。</span><span class="sxs-lookup"><span data-stu-id="89328-102">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="89328-103">必須。</span><span class="sxs-lookup"><span data-stu-id="89328-103">Required.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="89328-104">省略可能。</span><span class="sxs-lookup"><span data-stu-id="89328-104">Optional.</span></span> <span data-ttu-id="89328-105">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="89328-105">Request header parameters.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="89328-106">省略可能。</span><span class="sxs-lookup"><span data-stu-id="89328-106">Optional.</span></span>
            </param>
        <param name="itemName">
            <span data-ttu-id="89328-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="89328-107">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="89328-108">バックアップ、AzureBackUpItem です。</span><span class="sxs-lookup"><span data-stu-id="89328-108">BackUp the AzureBackUpItem.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="89328-109">操作の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="89328-109">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerBackUpAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; TriggerBackUpAsync (this Microsoft.Azure.Management.BackupServices.IBackUpOperations operations, string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; TriggerBackUpAsync(class Microsoft.Azure.Management.BackupServices.IBackUpOperations operations, string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.BackUpOperationsExtensions.TriggerBackUpAsync(Microsoft.Azure.Management.BackupServices.IBackUpOperations,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member TriggerBackUpAsync : Microsoft.Azure.Management.BackupServices.IBackUpOperations * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="Microsoft.Azure.Management.BackupServices.BackUpOperationsExtensions.TriggerBackUpAsync (operations, resourceGroupName, resourceName, customRequestHeaders, containerName, itemName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BackupServices.IBackUpOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="89328-110">Microsoft.Azure.Management.BackupServices.IBackUpOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="89328-110">Reference to the Microsoft.Azure.Management.BackupServices.IBackUpOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="89328-111">必須。</span><span class="sxs-lookup"><span data-stu-id="89328-111">Required.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="89328-112">必須。</span><span class="sxs-lookup"><span data-stu-id="89328-112">Required.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="89328-113">省略可能。</span><span class="sxs-lookup"><span data-stu-id="89328-113">Optional.</span></span> <span data-ttu-id="89328-114">ヘッダーのパラメーターを要求します。</span><span class="sxs-lookup"><span data-stu-id="89328-114">Request header parameters.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="89328-115">省略可能。</span><span class="sxs-lookup"><span data-stu-id="89328-115">Optional.</span></span>
            </param>
        <param name="itemName">
            <span data-ttu-id="89328-116">省略可能。</span><span class="sxs-lookup"><span data-stu-id="89328-116">Optional.</span></span>
            </param>
        <summary>
            <span data-ttu-id="89328-117">バックアップ、AzureBackUpItem です。</span><span class="sxs-lookup"><span data-stu-id="89328-117">BackUp the AzureBackUpItem.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="89328-118">操作の応答の定義。</span><span class="sxs-lookup"><span data-stu-id="89328-118">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>