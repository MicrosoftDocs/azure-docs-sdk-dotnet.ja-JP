<Type Name="DeviceJobOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DeviceJobOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DeviceJobOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DeviceJobOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DeviceJobOperationsExtensions = class" />
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
            <span data-ttu-id="4b9f5-101">これは、StorSimple のオブジェクトを管理する rest ベースの API</span><span class="sxs-lookup"><span data-stu-id="4b9f5-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginUpdateDeviceJob">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginUpdateDeviceJob (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginUpdateDeviceJob(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.BeginUpdateDeviceJob(Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateDeviceJob : Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.BeginUpdateDeviceJob (operations, deviceId, jobId, updateRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="updateRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4b9f5-102">Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-102">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="4b9f5-103">必須。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-103">Required.</span></span> <span data-ttu-id="4b9f5-104">デバイスの id</span><span class="sxs-lookup"><span data-stu-id="4b9f5-104">id of device</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="4b9f5-105">必須。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-105">Required.</span></span> <span data-ttu-id="4b9f5-106">更新するジョブの id</span><span class="sxs-lookup"><span data-stu-id="4b9f5-106">id of job to update</span></span>
            </param>
        <param name="updateRequest">
            <span data-ttu-id="4b9f5-107">必須。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-107">Required.</span></span> <span data-ttu-id="4b9f5-108">データを要求する、実行されるアクションが含まれています</span><span class="sxs-lookup"><span data-stu-id="4b9f5-108">Request data, contains the action to be taken</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="4b9f5-109">必須。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-109">Required.</span></span> <span data-ttu-id="4b9f5-110">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-110">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4b9f5-111">デバイスのジョブを更新する非同期タスクを開始します。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-111">Begin async task to update a device job.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4b9f5-112">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="4b9f5-112">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateDeviceJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginUpdateDeviceJobAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginUpdateDeviceJobAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.BeginUpdateDeviceJobAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateDeviceJobAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.BeginUpdateDeviceJobAsync (operations, deviceId, jobId, updateRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="updateRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4b9f5-113">Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-113">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="4b9f5-114">必須。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-114">Required.</span></span> <span data-ttu-id="4b9f5-115">デバイスの id</span><span class="sxs-lookup"><span data-stu-id="4b9f5-115">id of device</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="4b9f5-116">必須。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-116">Required.</span></span> <span data-ttu-id="4b9f5-117">更新するジョブの id</span><span class="sxs-lookup"><span data-stu-id="4b9f5-117">id of job to update</span></span>
            </param>
        <param name="updateRequest">
            <span data-ttu-id="4b9f5-118">必須。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-118">Required.</span></span> <span data-ttu-id="4b9f5-119">データを要求する、実行されるアクションが含まれています</span><span class="sxs-lookup"><span data-stu-id="4b9f5-119">Request data, contains the action to be taken</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="4b9f5-120">必須。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-120">Required.</span></span> <span data-ttu-id="4b9f5-121">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-121">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4b9f5-122">デバイスのジョブを更新する非同期タスクを開始します。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-122">Begin async task to update a device job.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4b9f5-123">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="4b9f5-123">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse Get (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobType, string jobStatus, string jobId, string startTime, string endTime, int skip, int top, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse Get(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobType, string jobStatus, string jobId, string startTime, string endTime, int32 skip, int32 top, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.Get(Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Int32,System.Int32,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations * string * string * string * string * string * string * int * int * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.Get (operations, deviceId, jobType, jobStatus, jobId, startTime, endTime, skip, top, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobType" Type="System.String" />
        <Parameter Name="jobStatus" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="skip" Type="System.Int32" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4b9f5-124">Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-124">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="4b9f5-125">省略可能。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-125">Optional.</span></span> <span data-ttu-id="4b9f5-126">ジョブのデバイスのデバイス id</span><span class="sxs-lookup"><span data-stu-id="4b9f5-126">Device id of device of jobs</span></span>
            </param>
        <param name="jobType">
            <span data-ttu-id="4b9f5-127">省略可能。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-127">Optional.</span></span> <span data-ttu-id="4b9f5-128">DeviceJob の種類</span><span class="sxs-lookup"><span data-stu-id="4b9f5-128">Type of deviceJob</span></span>
            </param>
        <param name="jobStatus">
            <span data-ttu-id="4b9f5-129">省略可能。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-129">Optional.</span></span> <span data-ttu-id="4b9f5-130">ジョブの状態</span><span class="sxs-lookup"><span data-stu-id="4b9f5-130">Status of job</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="4b9f5-131">省略可能。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-131">Optional.</span></span> <span data-ttu-id="4b9f5-132">ジョブの id</span><span class="sxs-lookup"><span data-stu-id="4b9f5-132">Id of job</span></span>
            </param>
        <param name="startTime">
            <span data-ttu-id="4b9f5-133">省略可能。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-133">Optional.</span></span> <span data-ttu-id="4b9f5-134">ジョブの開始時刻、ISO 8601 形式 'yyyy'-'MM'-'表記' HH': 'mm':'ss '</span><span class="sxs-lookup"><span data-stu-id="4b9f5-134">Job start time, in ISO 8601 format 'yyyy'-'MM'-'dd'T'HH':'mm':'ss'</span></span>
            </param>
        <param name="endTime">
            <span data-ttu-id="4b9f5-135">省略可能。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-135">Optional.</span></span> <span data-ttu-id="4b9f5-136">終了時刻をジョブに、ISO 8601 形式 'yyyy'-'MM'-'表記' HH': 'mm':'ss '</span><span class="sxs-lookup"><span data-stu-id="4b9f5-136">Job end time, in ISO 8601 format 'yyyy'-'MM'-'dd'T'HH':'mm':'ss'</span></span>
            </param>
        <param name="skip">
            <span data-ttu-id="4b9f5-137">必須。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-137">Required.</span></span> <span data-ttu-id="4b9f5-138">改ページ パラメーター。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-138">Pagination parameter.</span></span> <span data-ttu-id="4b9f5-139">、つまり返される最初のエントリのインデックスをスキップするエントリの数</span><span class="sxs-lookup"><span data-stu-id="4b9f5-139">The number of entries to skip, i.e. index of the first entry to be returned</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="4b9f5-140">必須。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-140">Required.</span></span> <span data-ttu-id="4b9f5-141">改ページ パラメーター。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-141">Pagination parameter.</span></span> <span data-ttu-id="4b9f5-142">'Skip' のエントリ数をスキップした後に返される項目の数</span><span class="sxs-lookup"><span data-stu-id="4b9f5-142">The number of entries to return after skipping the 'skip' number of entries</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="4b9f5-143">必須。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-143">Required.</span></span> <span data-ttu-id="4b9f5-144">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-144">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="4b9f5-145">デバイスのジョブの取得のクエリの応答モデル</span><span class="sxs-lookup"><span data-stu-id="4b9f5-145">Response model of Get Query for a Device Job</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt; GetAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobType, string jobStatus, string jobId, string startTime, string endTime, int skip, int top, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt; GetAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobType, string jobStatus, string jobId, string startTime, string endTime, int32 skip, int32 top, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.GetAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Int32,System.Int32,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations * string * string * string * string * string * string * int * int * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.GetAsync (operations, deviceId, jobType, jobStatus, jobId, startTime, endTime, skip, top, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobType" Type="System.String" />
        <Parameter Name="jobStatus" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="skip" Type="System.Int32" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4b9f5-146">Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-146">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="4b9f5-147">省略可能。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-147">Optional.</span></span> <span data-ttu-id="4b9f5-148">ジョブのデバイスのデバイス id</span><span class="sxs-lookup"><span data-stu-id="4b9f5-148">Device id of device of jobs</span></span>
            </param>
        <param name="jobType">
            <span data-ttu-id="4b9f5-149">省略可能。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-149">Optional.</span></span> <span data-ttu-id="4b9f5-150">DeviceJob の種類</span><span class="sxs-lookup"><span data-stu-id="4b9f5-150">Type of deviceJob</span></span>
            </param>
        <param name="jobStatus">
            <span data-ttu-id="4b9f5-151">省略可能。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-151">Optional.</span></span> <span data-ttu-id="4b9f5-152">ジョブの状態</span><span class="sxs-lookup"><span data-stu-id="4b9f5-152">Status of job</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="4b9f5-153">省略可能。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-153">Optional.</span></span> <span data-ttu-id="4b9f5-154">ジョブの id</span><span class="sxs-lookup"><span data-stu-id="4b9f5-154">Id of job</span></span>
            </param>
        <param name="startTime">
            <span data-ttu-id="4b9f5-155">省略可能。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-155">Optional.</span></span> <span data-ttu-id="4b9f5-156">ジョブの開始時刻、ISO 8601 形式 'yyyy'-'MM'-'表記' HH': 'mm':'ss '</span><span class="sxs-lookup"><span data-stu-id="4b9f5-156">Job start time, in ISO 8601 format 'yyyy'-'MM'-'dd'T'HH':'mm':'ss'</span></span>
            </param>
        <param name="endTime">
            <span data-ttu-id="4b9f5-157">省略可能。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-157">Optional.</span></span> <span data-ttu-id="4b9f5-158">終了時刻をジョブに、ISO 8601 形式 'yyyy'-'MM'-'表記' HH': 'mm':'ss '</span><span class="sxs-lookup"><span data-stu-id="4b9f5-158">Job end time, in ISO 8601 format 'yyyy'-'MM'-'dd'T'HH':'mm':'ss'</span></span>
            </param>
        <param name="skip">
            <span data-ttu-id="4b9f5-159">必須。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-159">Required.</span></span> <span data-ttu-id="4b9f5-160">改ページ パラメーター。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-160">Pagination parameter.</span></span> <span data-ttu-id="4b9f5-161">、つまり返される最初のエントリのインデックスをスキップするエントリの数</span><span class="sxs-lookup"><span data-stu-id="4b9f5-161">The number of entries to skip, i.e. index of the first entry to be returned</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="4b9f5-162">必須。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-162">Required.</span></span> <span data-ttu-id="4b9f5-163">改ページ パラメーター。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-163">Pagination parameter.</span></span> <span data-ttu-id="4b9f5-164">'Skip' のエントリ数をスキップした後に返される項目の数</span><span class="sxs-lookup"><span data-stu-id="4b9f5-164">The number of entries to return after skipping the 'skip' number of entries</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="4b9f5-165">必須。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-165">Required.</span></span> <span data-ttu-id="4b9f5-166">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-166">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="4b9f5-167">デバイスのジョブの取得のクエリの応答モデル</span><span class="sxs-lookup"><span data-stu-id="4b9f5-167">Response model of Get Query for a Device Job</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceJob">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo UpdateDeviceJob (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo UpdateDeviceJob(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.UpdateDeviceJob(Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateDeviceJob : Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.UpdateDeviceJob (operations, deviceId, jobId, updateRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="updateRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4b9f5-168">Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-168">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="4b9f5-169">必須。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-169">Required.</span></span> <span data-ttu-id="4b9f5-170">デバイスの id</span><span class="sxs-lookup"><span data-stu-id="4b9f5-170">id of device</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="4b9f5-171">必須。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-171">Required.</span></span> <span data-ttu-id="4b9f5-172">更新するジョブの id</span><span class="sxs-lookup"><span data-stu-id="4b9f5-172">id of job to update</span></span>
            </param>
        <param name="updateRequest">
            <span data-ttu-id="4b9f5-173">必須。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-173">Required.</span></span> <span data-ttu-id="4b9f5-174">データを要求する、実行されるアクションが含まれています</span><span class="sxs-lookup"><span data-stu-id="4b9f5-174">Request data, contains the action to be taken</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="4b9f5-175">必須。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-175">Required.</span></span> <span data-ttu-id="4b9f5-176">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-176">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4b9f5-177">デバイスのジョブを更新します。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-177">Update a device job</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4b9f5-178">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="4b9f5-178">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDeviceJobAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDeviceJobAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.UpdateDeviceJobAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateDeviceJobAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.UpdateDeviceJobAsync (operations, deviceId, jobId, updateRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="updateRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4b9f5-179">Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations への参照。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-179">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="4b9f5-180">必須。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-180">Required.</span></span> <span data-ttu-id="4b9f5-181">デバイスの id</span><span class="sxs-lookup"><span data-stu-id="4b9f5-181">id of device</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="4b9f5-182">必須。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-182">Required.</span></span> <span data-ttu-id="4b9f5-183">更新するジョブの id</span><span class="sxs-lookup"><span data-stu-id="4b9f5-183">id of job to update</span></span>
            </param>
        <param name="updateRequest">
            <span data-ttu-id="4b9f5-184">必須。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-184">Required.</span></span> <span data-ttu-id="4b9f5-185">データを要求する、実行されるアクションが含まれています</span><span class="sxs-lookup"><span data-stu-id="4b9f5-185">Request data, contains the action to be taken</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="4b9f5-186">必須。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-186">Required.</span></span> <span data-ttu-id="4b9f5-187">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-187">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4b9f5-188">デバイスのジョブを更新します。</span><span class="sxs-lookup"><span data-stu-id="4b9f5-188">Update a device job</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4b9f5-189">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="4b9f5-189">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>