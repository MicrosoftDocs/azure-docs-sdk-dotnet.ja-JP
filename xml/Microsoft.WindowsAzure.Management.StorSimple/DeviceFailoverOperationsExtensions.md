<Type Name="DeviceFailoverOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DeviceFailoverOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DeviceFailoverOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DeviceFailoverOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DeviceFailoverOperationsExtensions = class" />
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
            <span data-ttu-id="d4505-101">これは、StorSimple のオブジェクトを管理する rest ベースの API</span><span class="sxs-lookup"><span data-stu-id="d4505-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListDCGroups">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse ListDCGroups (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse ListDCGroups(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions.ListDCGroups(Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListDCGroups : Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions.ListDCGroups (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d4505-102">Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="d4505-102">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="d4505-103">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d4505-103">Optional.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="d4505-104">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d4505-104">Optional.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="d4505-105">DataContainerGroups Get 呼び出しの応答のモデルを表します</span><span class="sxs-lookup"><span data-stu-id="d4505-105">Represents the response model for DataContainerGroups Get call</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDCGroupsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse&gt; ListDCGroupsAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse&gt; ListDCGroupsAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions.ListDCGroupsAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListDCGroupsAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions.ListDCGroupsAsync (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d4505-106">Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="d4505-106">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="d4505-107">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d4505-107">Optional.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="d4505-108">省略可能。</span><span class="sxs-lookup"><span data-stu-id="d4505-108">Optional.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="d4505-109">DataContainerGroups Get 呼び出しの応答のモデルを表します</span><span class="sxs-lookup"><span data-stu-id="d4505-109">Represents the response model for DataContainerGroups Get call</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Trigger">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse Trigger (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest drRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse Trigger(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest drRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions.Trigger(Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Trigger : Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions.Trigger (operations, deviceId, drRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="drRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d4505-110">Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="d4505-110">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="d4505-111">必須。</span><span class="sxs-lookup"><span data-stu-id="d4505-111">Required.</span></span> <span data-ttu-id="d4505-112">デバイス識別子</span><span class="sxs-lookup"><span data-stu-id="d4505-112">The device identifier</span></span>
            </param>
        <param name="drRequest">
            <span data-ttu-id="d4505-113">必須。</span><span class="sxs-lookup"><span data-stu-id="d4505-113">Required.</span></span> <span data-ttu-id="d4505-114">デバイスのフェールオーバーの要求の詳細。</span><span class="sxs-lookup"><span data-stu-id="d4505-114">The details of the device failover request.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="d4505-115">必須。</span><span class="sxs-lookup"><span data-stu-id="d4505-115">Required.</span></span> <span data-ttu-id="d4505-116">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d4505-116">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d4505-117">デバイスのフェールオーバーをトリガーします。</span><span class="sxs-lookup"><span data-stu-id="d4505-117">Trigger device failover.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d4505-118">これは、デバイス ジョブの関連するすべての呼び出しのジョブ応答</span><span class="sxs-lookup"><span data-stu-id="d4505-118">This is the Job Response for all Device Job Related Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt; TriggerAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest drRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt; TriggerAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest drRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions.TriggerAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member TriggerAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions.TriggerAsync (operations, deviceId, drRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="drRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d4505-119">Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="d4505-119">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="d4505-120">必須。</span><span class="sxs-lookup"><span data-stu-id="d4505-120">Required.</span></span> <span data-ttu-id="d4505-121">デバイス識別子</span><span class="sxs-lookup"><span data-stu-id="d4505-121">The device identifier</span></span>
            </param>
        <param name="drRequest">
            <span data-ttu-id="d4505-122">必須。</span><span class="sxs-lookup"><span data-stu-id="d4505-122">Required.</span></span> <span data-ttu-id="d4505-123">デバイスのフェールオーバーの要求の詳細。</span><span class="sxs-lookup"><span data-stu-id="d4505-123">The details of the device failover request.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="d4505-124">必須。</span><span class="sxs-lookup"><span data-stu-id="d4505-124">Required.</span></span> <span data-ttu-id="d4505-125">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="d4505-125">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d4505-126">デバイスのフェールオーバーをトリガーします。</span><span class="sxs-lookup"><span data-stu-id="d4505-126">Trigger device failover.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d4505-127">これは、デバイス ジョブの関連するすべての呼び出しのジョブ応答</span><span class="sxs-lookup"><span data-stu-id="d4505-127">This is the Job Response for all Device Job Related Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>