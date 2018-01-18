<Type Name="IDeviceJobOperations" FullName="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations">
  <TypeSignature Language="C#" Value="public interface IDeviceJobOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDeviceJobOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDeviceJobOperations" />
  <TypeSignature Language="F#" Value="type IDeviceJobOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ecd1c-101">デバイスのジョブに関連するすべての操作</span><span class="sxs-lookup"><span data-stu-id="ecd1c-101">All Operations related to Device Jobs</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginUpdateDeviceJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginUpdateDeviceJobAsync (string deviceId, string jobId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginUpdateDeviceJobAsync(string deviceId, string jobId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.BeginUpdateDeviceJobAsync(System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateDeviceJobAsync : string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;" Usage="iDeviceJobOperations.BeginUpdateDeviceJobAsync (deviceId, jobId, updateRequest, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="updateRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="ecd1c-102">デバイスの id</span><span class="sxs-lookup"><span data-stu-id="ecd1c-102">id of device</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="ecd1c-103">更新するジョブの id</span><span class="sxs-lookup"><span data-stu-id="ecd1c-103">id of job to update</span></span>
            </param>
        <param name="updateRequest">
            <span data-ttu-id="ecd1c-104">データを要求する、実行されるアクションが含まれています</span><span class="sxs-lookup"><span data-stu-id="ecd1c-104">Request data, contains the action to be taken</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="ecd1c-105">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="ecd1c-105">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ecd1c-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ecd1c-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ecd1c-107">デバイスのジョブを更新する非同期タスクを開始します。</span><span class="sxs-lookup"><span data-stu-id="ecd1c-107">Begin async task to update a device job.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ecd1c-108">これは、非同期呼び出しは、すべてのタスク応答</span><span class="sxs-lookup"><span data-stu-id="ecd1c-108">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt; GetAsync (string deviceId, string jobType, string jobStatus, string jobId, string startTime, string endTime, int skip, int top, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt; GetAsync(string deviceId, string jobType, string jobStatus, string jobId, string startTime, string endTime, int32 skip, int32 top, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.GetAsync(System.String,System.String,System.String,System.String,System.String,System.String,System.Int32,System.Int32,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * string * string * string * int * int * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt;" Usage="iDeviceJobOperations.GetAsync (deviceId, jobType, jobStatus, jobId, startTime, endTime, skip, top, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobType" Type="System.String" />
        <Parameter Name="jobStatus" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="skip" Type="System.Int32" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="ecd1c-109">ジョブのデバイスのデバイス id</span><span class="sxs-lookup"><span data-stu-id="ecd1c-109">Device id of device of jobs</span></span>
            </param>
        <param name="jobType">
            <span data-ttu-id="ecd1c-110">DeviceJob の種類</span><span class="sxs-lookup"><span data-stu-id="ecd1c-110">Type of deviceJob</span></span>
            </param>
        <param name="jobStatus">
            <span data-ttu-id="ecd1c-111">ジョブの状態</span><span class="sxs-lookup"><span data-stu-id="ecd1c-111">Status of job</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="ecd1c-112">ジョブの id</span><span class="sxs-lookup"><span data-stu-id="ecd1c-112">Id of job</span></span>
            </param>
        <param name="startTime">
            <span data-ttu-id="ecd1c-113">ジョブの開始時刻、ISO 8601 形式 'yyyy'-'MM'-'表記' HH': 'mm':'ss '</span><span class="sxs-lookup"><span data-stu-id="ecd1c-113">Job start time, in ISO 8601 format 'yyyy'-'MM'-'dd'T'HH':'mm':'ss'</span></span>
            </param>
        <param name="endTime">
            <span data-ttu-id="ecd1c-114">終了時刻をジョブに、ISO 8601 形式 'yyyy'-'MM'-'表記' HH': 'mm':'ss '</span><span class="sxs-lookup"><span data-stu-id="ecd1c-114">Job end time, in ISO 8601 format 'yyyy'-'MM'-'dd'T'HH':'mm':'ss'</span></span>
            </param>
        <param name="skip">
            <span data-ttu-id="ecd1c-115">改ページ パラメーター。</span><span class="sxs-lookup"><span data-stu-id="ecd1c-115">Pagination parameter.</span></span> <span data-ttu-id="ecd1c-116">、つまり返される最初のエントリのインデックスをスキップするエントリの数</span><span class="sxs-lookup"><span data-stu-id="ecd1c-116">The number of entries to skip, i.e. index of the first entry to be returned</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="ecd1c-117">改ページ パラメーター。</span><span class="sxs-lookup"><span data-stu-id="ecd1c-117">Pagination parameter.</span></span> <span data-ttu-id="ecd1c-118">'Skip' のエントリ数をスキップした後に返される項目の数</span><span class="sxs-lookup"><span data-stu-id="ecd1c-118">The number of entries to return after skipping the 'skip' number of entries</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="ecd1c-119">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="ecd1c-119">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ecd1c-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ecd1c-120">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="ecd1c-121">デバイスのジョブの取得のクエリの応答モデル</span><span class="sxs-lookup"><span data-stu-id="ecd1c-121">Response model of Get Query for a Device Job</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDeviceJobAsync (string deviceId, string jobId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDeviceJobAsync(string deviceId, string jobId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.UpdateDeviceJobAsync(System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDeviceJobAsync : string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="iDeviceJobOperations.UpdateDeviceJobAsync (deviceId, jobId, updateRequest, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="updateRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="ecd1c-122">デバイスの id</span><span class="sxs-lookup"><span data-stu-id="ecd1c-122">id of device</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="ecd1c-123">更新するジョブの id</span><span class="sxs-lookup"><span data-stu-id="ecd1c-123">id of job to update</span></span>
            </param>
        <param name="updateRequest">
            <span data-ttu-id="ecd1c-124">データを要求する、実行されるアクションが含まれています</span><span class="sxs-lookup"><span data-stu-id="ecd1c-124">Request data, contains the action to be taken</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="ecd1c-125">カスタム要求ヘッダーをクライアントが使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="ecd1c-125">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ecd1c-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="ecd1c-126">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ecd1c-127">デバイスのジョブを更新します。</span><span class="sxs-lookup"><span data-stu-id="ecd1c-127">Update a device job</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ecd1c-128">非同期タスクに関する情報</span><span class="sxs-lookup"><span data-stu-id="ecd1c-128">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>