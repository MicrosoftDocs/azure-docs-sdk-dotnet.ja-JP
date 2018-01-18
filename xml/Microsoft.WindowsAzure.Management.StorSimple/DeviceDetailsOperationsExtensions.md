<Type Name="DeviceDetailsOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DeviceDetailsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DeviceDetailsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DeviceDetailsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DeviceDetailsOperationsExtensions = class" />
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
            <span data-ttu-id="5b3e3-101">これは、StorSimple のオブジェクトを管理する rest ベースの API</span><span class="sxs-lookup"><span data-stu-id="5b3e3-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginUpdateDeviceDetails">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginUpdateDeviceDetails (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest deviceDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginUpdateDeviceDetails(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest deviceDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.BeginUpdateDeviceDetails(Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateDeviceDetails : Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.BeginUpdateDeviceDetails (operations, deviceDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations" RefType="this" />
        <Parameter Name="deviceDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5b3e3-102">Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-102">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations.</span></span>
            </param>
        <param name="deviceDetails">
            <span data-ttu-id="5b3e3-103">必須。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-103">Required.</span></span> <span data-ttu-id="5b3e3-104">更新された DeviceDetails です。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-104">Updated DeviceDetails.</span></span> <span data-ttu-id="5b3e3-105">対応するデバイス Id が含まれています</span><span class="sxs-lookup"><span data-stu-id="5b3e3-105">Contains the corresponding DeviceId</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="5b3e3-106">必須。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-106">Required.</span></span> <span data-ttu-id="5b3e3-107">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-107">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5b3e3-108">DeviceDetails で指定されたデバイスの詳細を更新するためのタスクを開始します。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-108">Begin task for updating device details as specified by deviceDetails.</span></span> <span data-ttu-id="5b3e3-109">返されるタスクの情報を使用して完了タスクを追跡することができますし、</span><span class="sxs-lookup"><span data-stu-id="5b3e3-109">The task can then be tracked for completion using returned task information</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5b3e3-110">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="5b3e3-110">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateDeviceDetailsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginUpdateDeviceDetailsAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest deviceDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginUpdateDeviceDetailsAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest deviceDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.BeginUpdateDeviceDetailsAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateDeviceDetailsAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.BeginUpdateDeviceDetailsAsync (operations, deviceDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations" RefType="this" />
        <Parameter Name="deviceDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5b3e3-111">Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-111">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations.</span></span>
            </param>
        <param name="deviceDetails">
            <span data-ttu-id="5b3e3-112">必須。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-112">Required.</span></span> <span data-ttu-id="5b3e3-113">更新された DeviceDetails です。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-113">Updated DeviceDetails.</span></span> <span data-ttu-id="5b3e3-114">対応するデバイス Id が含まれています</span><span class="sxs-lookup"><span data-stu-id="5b3e3-114">Contains the corresponding DeviceId</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="5b3e3-115">必須。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-115">Required.</span></span> <span data-ttu-id="5b3e3-116">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-116">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5b3e3-117">DeviceDetails で指定されたデバイスの詳細を更新するためのタスクを開始します。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-117">Begin task for updating device details as specified by deviceDetails.</span></span> <span data-ttu-id="5b3e3-118">返されるタスクの情報を使用して完了タスクを追跡することができますし、</span><span class="sxs-lookup"><span data-stu-id="5b3e3-118">The task can then be tracked for completion using returned task information</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5b3e3-119">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="5b3e3-119">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsResponse Get (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsResponse Get(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.Get(Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.Get (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5b3e3-120">Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-120">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="5b3e3-121">必須。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-121">Required.</span></span> <span data-ttu-id="5b3e3-122">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-122">The device id for which the call will be made.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="5b3e3-123">必須。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-123">Required.</span></span> <span data-ttu-id="5b3e3-124">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-124">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="5b3e3-125">デバイスの詳細の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-125">The response model for device details.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsResponse&gt; GetAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsResponse&gt; GetAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.GetAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.GetAsync (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5b3e3-126">Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-126">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="5b3e3-127">必須。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-127">Required.</span></span> <span data-ttu-id="5b3e3-128">呼び出しの作成対象のデバイス id です。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-128">The device id for which the call will be made.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="5b3e3-129">必須。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-129">Required.</span></span> <span data-ttu-id="5b3e3-130">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-130">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="5b3e3-131">デバイスの詳細の応答モデル。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-131">The response model for device details.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceDetails">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo UpdateDeviceDetails (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest deviceDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo UpdateDeviceDetails(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest deviceDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.UpdateDeviceDetails(Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateDeviceDetails : Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.UpdateDeviceDetails (operations, deviceDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations" RefType="this" />
        <Parameter Name="deviceDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5b3e3-132">Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-132">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations.</span></span>
            </param>
        <param name="deviceDetails">
            <span data-ttu-id="5b3e3-133">必須。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-133">Required.</span></span> <span data-ttu-id="5b3e3-134">更新された DeviceDetails です。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-134">Updated DeviceDetails.</span></span> <span data-ttu-id="5b3e3-135">対応するデバイス Id が含まれています</span><span class="sxs-lookup"><span data-stu-id="5b3e3-135">Contains the corresponding DeviceId</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="5b3e3-136">必須。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-136">Required.</span></span> <span data-ttu-id="5b3e3-137">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-137">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5b3e3-138">DeviceDetails で指定されたデバイスの詳細を更新します。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-138">Update device details as specified by deviceDetails</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5b3e3-139">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="5b3e3-139">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceDetailsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDeviceDetailsAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest deviceDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDeviceDetailsAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest deviceDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.UpdateDeviceDetailsAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateDeviceDetailsAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.UpdateDeviceDetailsAsync (operations, deviceDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations" RefType="this" />
        <Parameter Name="deviceDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5b3e3-140">Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-140">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations.</span></span>
            </param>
        <param name="deviceDetails">
            <span data-ttu-id="5b3e3-141">必須。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-141">Required.</span></span> <span data-ttu-id="5b3e3-142">更新された DeviceDetails です。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-142">Updated DeviceDetails.</span></span> <span data-ttu-id="5b3e3-143">対応するデバイス Id が含まれています</span><span class="sxs-lookup"><span data-stu-id="5b3e3-143">Contains the corresponding DeviceId</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="5b3e3-144">必須。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-144">Required.</span></span> <span data-ttu-id="5b3e3-145">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-145">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5b3e3-146">DeviceDetails で指定されたデバイスの詳細を更新します。</span><span class="sxs-lookup"><span data-stu-id="5b3e3-146">Update device details as specified by deviceDetails</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5b3e3-147">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="5b3e3-147">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>