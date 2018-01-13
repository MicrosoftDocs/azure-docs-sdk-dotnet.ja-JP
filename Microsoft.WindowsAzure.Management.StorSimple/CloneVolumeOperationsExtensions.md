<Type Name="CloneVolumeOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.CloneVolumeOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class CloneVolumeOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CloneVolumeOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.CloneVolumeOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CloneVolumeOperationsExtensions" />
  <TypeSignature Language="F#" Value="type CloneVolumeOperationsExtensions = class" />
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
            <span data-ttu-id="d35be-101">これは、StorSimple のオブジェクトを管理する rest ベースの API</span><span class="sxs-lookup"><span data-stu-id="d35be-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Trigger">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse Trigger (this Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations operations, string sourceDeviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest triggerCloneRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse Trigger(class Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations operations, string sourceDeviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest triggerCloneRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.CloneVolumeOperationsExtensions.Trigger(Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Trigger : Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.CloneVolumeOperationsExtensions.Trigger (operations, sourceDeviceId, triggerCloneRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations" RefType="this" />
        <Parameter Name="sourceDeviceId" Type="System.String" />
        <Parameter Name="triggerCloneRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d35be-102">Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="d35be-102">Reference to the Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations.</span></span>
            </param>
        <param name="sourceDeviceId">
            <span data-ttu-id="d35be-103">必須。</span><span class="sxs-lookup"><span data-stu-id="d35be-103">Required.</span></span> <span data-ttu-id="d35be-104">どのクローンからソース デバイスの識別子がトリガーされます。</span><span class="sxs-lookup"><span data-stu-id="d35be-104">The identifier of the source device from which clone is to be triggered</span></span>
            </param>
        <param name="triggerCloneRequest">
            <span data-ttu-id="d35be-105">必須。</span><span class="sxs-lookup"><span data-stu-id="d35be-105">Required.</span></span> <span data-ttu-id="d35be-106">複製操作に必要なパラメーター</span><span class="sxs-lookup"><span data-stu-id="d35be-106">The parameters required for clone operation</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="d35be-107">必須。</span><span class="sxs-lookup"><span data-stu-id="d35be-107">Required.</span></span> <span data-ttu-id="d35be-108">カスタムの要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d35be-108">The Custom Request Headers which client must use</span></span>
            </param>
        <summary>
            <span data-ttu-id="d35be-109">Backup 要素を複製します。</span><span class="sxs-lookup"><span data-stu-id="d35be-109">Clone a backup element.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d35be-110">これは、デバイス ジョブの関連するすべての呼び出しのジョブ応答</span><span class="sxs-lookup"><span data-stu-id="d35be-110">This is the Job Response for all Device Job Related Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt; TriggerAsync (this Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations operations, string sourceDeviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest triggerCloneRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt; TriggerAsync(class Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations operations, string sourceDeviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest triggerCloneRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.CloneVolumeOperationsExtensions.TriggerAsync(Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member TriggerAsync : Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.CloneVolumeOperationsExtensions.TriggerAsync (operations, sourceDeviceId, triggerCloneRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations" RefType="this" />
        <Parameter Name="sourceDeviceId" Type="System.String" />
        <Parameter Name="triggerCloneRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d35be-111">Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="d35be-111">Reference to the Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations.</span></span>
            </param>
        <param name="sourceDeviceId">
            <span data-ttu-id="d35be-112">必須。</span><span class="sxs-lookup"><span data-stu-id="d35be-112">Required.</span></span> <span data-ttu-id="d35be-113">どのクローンからソース デバイスの識別子がトリガーされます。</span><span class="sxs-lookup"><span data-stu-id="d35be-113">The identifier of the source device from which clone is to be triggered</span></span>
            </param>
        <param name="triggerCloneRequest">
            <span data-ttu-id="d35be-114">必須。</span><span class="sxs-lookup"><span data-stu-id="d35be-114">Required.</span></span> <span data-ttu-id="d35be-115">複製操作に必要なパラメーター</span><span class="sxs-lookup"><span data-stu-id="d35be-115">The parameters required for clone operation</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="d35be-116">必須。</span><span class="sxs-lookup"><span data-stu-id="d35be-116">Required.</span></span> <span data-ttu-id="d35be-117">カスタムの要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d35be-117">The Custom Request Headers which client must use</span></span>
            </param>
        <summary>
            <span data-ttu-id="d35be-118">Backup 要素を複製します。</span><span class="sxs-lookup"><span data-stu-id="d35be-118">Clone a backup element.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d35be-119">これは、デバイス ジョブの関連するすべての呼び出しのジョブ応答</span><span class="sxs-lookup"><span data-stu-id="d35be-119">This is the Job Response for all Device Job Related Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>