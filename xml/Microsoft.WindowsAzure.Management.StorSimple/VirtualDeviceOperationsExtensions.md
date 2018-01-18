<Type Name="VirtualDeviceOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.VirtualDeviceOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualDeviceOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualDeviceOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.VirtualDeviceOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualDeviceOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualDeviceOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d8745-101">これは、StorSimple のオブジェクトを管理する rest ベースの API</span><span class="sxs-lookup"><span data-stu-id="d8745-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse Create (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo virtualDeviceProvisioningInfo, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse Create(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo virtualDeviceProvisioningInfo, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDeviceOperationsExtensions.Create(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDeviceOperationsExtensions.Create (operations, virtualDeviceProvisioningInfo, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations" RefType="this" />
        <Parameter Name="virtualDeviceProvisioningInfo" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d8745-102">Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="d8745-102">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations.</span></span>
            </param>
        <param name="virtualDeviceProvisioningInfo">
            <span data-ttu-id="d8745-103">必須。</span><span class="sxs-lookup"><span data-stu-id="d8745-103">Required.</span></span> <span data-ttu-id="d8745-104">仮想デバイスのプロビジョニング情報です。</span><span class="sxs-lookup"><span data-stu-id="d8745-104">The Virtual device provisioning info.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="d8745-105">必須。</span><span class="sxs-lookup"><span data-stu-id="d8745-105">Required.</span></span> <span data-ttu-id="d8745-106">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d8745-106">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d8745-107">仮想デバイスの作成</span><span class="sxs-lookup"><span data-stu-id="d8745-107">The Create Virtual Device</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d8745-108">これは、デバイス ジョブの関連するすべての呼び出しのジョブ応答</span><span class="sxs-lookup"><span data-stu-id="d8745-108">This is the Job Response for all Device Job Related Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt; CreateAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo virtualDeviceProvisioningInfo, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt; CreateAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo virtualDeviceProvisioningInfo, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDeviceOperationsExtensions.CreateAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDeviceOperationsExtensions.CreateAsync (operations, virtualDeviceProvisioningInfo, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations" RefType="this" />
        <Parameter Name="virtualDeviceProvisioningInfo" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d8745-109">Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="d8745-109">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations.</span></span>
            </param>
        <param name="virtualDeviceProvisioningInfo">
            <span data-ttu-id="d8745-110">必須。</span><span class="sxs-lookup"><span data-stu-id="d8745-110">Required.</span></span> <span data-ttu-id="d8745-111">仮想デバイスのプロビジョニング情報です。</span><span class="sxs-lookup"><span data-stu-id="d8745-111">The Virtual device provisioning info.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="d8745-112">必須。</span><span class="sxs-lookup"><span data-stu-id="d8745-112">Required.</span></span> <span data-ttu-id="d8745-113">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d8745-113">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d8745-114">仮想デバイスの作成</span><span class="sxs-lookup"><span data-stu-id="d8745-114">The Create Virtual Device</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d8745-115">これは、デバイス ジョブの関連するすべての呼び出しのジョブ応答</span><span class="sxs-lookup"><span data-stu-id="d8745-115">This is the Job Response for all Device Job Related Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>