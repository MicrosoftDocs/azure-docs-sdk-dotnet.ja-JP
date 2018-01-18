<Type Name="JobsOperationsExtensions" FullName="Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class JobsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit JobsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module JobsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type JobsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a8aad-101">JobsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="a8aad-101">Extension methods for JobsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCancel">
      <MemberSignature Language="C#" Value="public static void BeginCancel (this Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string deviceName, string jobName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginCancel(class Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string deviceName, string jobName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.BeginCancel(Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginCancel (operations As IJobsOperations, deviceName As String, jobName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginCancel : Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.BeginCancel (operations, deviceName, jobName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a8aad-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a8aad-102">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="a8aad-103">デバイス名</span><span class="sxs-lookup"><span data-stu-id="a8aad-103">The device name</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="a8aad-104">JobName です。</span><span class="sxs-lookup"><span data-stu-id="a8aad-104">The jobName.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a8aad-105">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="a8aad-105">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="a8aad-106">管理者名</span><span class="sxs-lookup"><span data-stu-id="a8aad-106">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="a8aad-107">デバイス上のジョブを取り消します。</span><span class="sxs-lookup"><span data-stu-id="a8aad-107">Cancels a job on the device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCancelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginCancelAsync (this Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string deviceName, string jobName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginCancelAsync(class Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string deviceName, string jobName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.BeginCancelAsync(Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCancelAsync : Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.BeginCancelAsync (operations, deviceName, jobName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions/&lt;BeginCancelAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a8aad-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a8aad-108">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="a8aad-109">デバイス名</span><span class="sxs-lookup"><span data-stu-id="a8aad-109">The device name</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="a8aad-110">JobName です。</span><span class="sxs-lookup"><span data-stu-id="a8aad-110">The jobName.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a8aad-111">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="a8aad-111">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="a8aad-112">管理者名</span><span class="sxs-lookup"><span data-stu-id="a8aad-112">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a8aad-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a8aad-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a8aad-114">デバイス上のジョブを取り消します。</span><span class="sxs-lookup"><span data-stu-id="a8aad-114">Cancels a job on the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Cancel">
      <MemberSignature Language="C#" Value="public static void Cancel (this Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string deviceName, string jobName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Cancel(class Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string deviceName, string jobName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.Cancel(Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Cancel (operations As IJobsOperations, deviceName As String, jobName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Cancel : Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.Cancel (operations, deviceName, jobName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a8aad-115">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a8aad-115">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="a8aad-116">デバイス名</span><span class="sxs-lookup"><span data-stu-id="a8aad-116">The device name</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="a8aad-117">JobName です。</span><span class="sxs-lookup"><span data-stu-id="a8aad-117">The jobName.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a8aad-118">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="a8aad-118">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="a8aad-119">管理者名</span><span class="sxs-lookup"><span data-stu-id="a8aad-119">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="a8aad-120">デバイス上のジョブを取り消します。</span><span class="sxs-lookup"><span data-stu-id="a8aad-120">Cancels a job on the device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CancelAsync (this Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string deviceName, string jobName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CancelAsync(class Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string deviceName, string jobName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.CancelAsync(Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CancelAsync : Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.CancelAsync (operations, deviceName, jobName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions/&lt;CancelAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a8aad-121">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a8aad-121">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="a8aad-122">デバイス名</span><span class="sxs-lookup"><span data-stu-id="a8aad-122">The device name</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="a8aad-123">JobName です。</span><span class="sxs-lookup"><span data-stu-id="a8aad-123">The jobName.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a8aad-124">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="a8aad-124">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="a8aad-125">管理者名</span><span class="sxs-lookup"><span data-stu-id="a8aad-125">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a8aad-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a8aad-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a8aad-127">デバイス上のジョブを取り消します。</span><span class="sxs-lookup"><span data-stu-id="a8aad-127">Cancels a job on the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.Job Get (this Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string deviceName, string jobName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.Job Get(class Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string deviceName, string jobName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.Get(Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IJobsOperations, deviceName As String, jobName As String, resourceGroupName As String, managerName As String) As Job" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Job" Usage="Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.Get (operations, deviceName, jobName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.Job</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a8aad-128">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a8aad-128">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="a8aad-129">デバイス名</span><span class="sxs-lookup"><span data-stu-id="a8aad-129">The device name</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="a8aad-130">ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="a8aad-130">The job Name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a8aad-131">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="a8aad-131">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="a8aad-132">管理者名</span><span class="sxs-lookup"><span data-stu-id="a8aad-132">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="a8aad-133">指定したジョブ名の詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="a8aad-133">Gets the details of the specified job name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt; GetAsync (this Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string deviceName, string jobName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt; GetAsync(class Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string deviceName, string jobName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.GetAsync(Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.GetAsync (operations, deviceName, jobName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a8aad-134">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a8aad-134">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="a8aad-135">デバイス名</span><span class="sxs-lookup"><span data-stu-id="a8aad-135">The device name</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="a8aad-136">ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="a8aad-136">The job Name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a8aad-137">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="a8aad-137">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="a8aad-138">管理者名</span><span class="sxs-lookup"><span data-stu-id="a8aad-138">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a8aad-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a8aad-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a8aad-140">指定したジョブ名の詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="a8aad-140">Gets the details of the specified job name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDevice">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt; ListByDevice (this Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string deviceName, string resourceGroupName, string managerName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt; ListByDevice(class Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string deviceName, string resourceGroupName, string managerName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.ListByDevice(Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDevice (operations As IJobsOperations, deviceName As String, resourceGroupName As String, managerName As String, Optional odataQuery As ODataQuery(Of JobFilter) = null) As IPage(Of Job)" />
      <MemberSignature Language="F#" Value="static member ListByDevice : Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.ListByDevice (operations, deviceName, resourceGroupName, managerName, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a8aad-141">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a8aad-141">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="a8aad-142">デバイス名</span><span class="sxs-lookup"><span data-stu-id="a8aad-142">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a8aad-143">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="a8aad-143">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="a8aad-144">管理者名</span><span class="sxs-lookup"><span data-stu-id="a8aad-144">The manager name</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="a8aad-145">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="a8aad-145">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a8aad-146">指定されたデバイスのすべてのジョブを取得します。</span><span class="sxs-lookup"><span data-stu-id="a8aad-146">Gets all the jobs for specified device.</span></span> <span data-ttu-id="a8aad-147">省略可能な OData クエリ パラメーターを持つジョブのフィルター処理されたセットが返されます。</span><span class="sxs-lookup"><span data-stu-id="a8aad-147">With optional OData query parameters, a filtered set of jobs is returned.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDeviceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt;&gt; ListByDeviceAsync (this Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string deviceName, string resourceGroupName, string managerName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt;&gt; ListByDeviceAsync(class Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string deviceName, string resourceGroupName, string managerName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.ListByDeviceAsync(Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDeviceAsync : Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.ListByDeviceAsync (operations, deviceName, resourceGroupName, managerName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions/&lt;ListByDeviceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a8aad-148">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a8aad-148">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="a8aad-149">デバイス名</span><span class="sxs-lookup"><span data-stu-id="a8aad-149">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a8aad-150">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="a8aad-150">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="a8aad-151">管理者名</span><span class="sxs-lookup"><span data-stu-id="a8aad-151">The manager name</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="a8aad-152">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="a8aad-152">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a8aad-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a8aad-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a8aad-154">指定されたデバイスのすべてのジョブを取得します。</span><span class="sxs-lookup"><span data-stu-id="a8aad-154">Gets all the jobs for specified device.</span></span> <span data-ttu-id="a8aad-155">省略可能な OData クエリ パラメーターを持つジョブのフィルター処理されたセットが返されます。</span><span class="sxs-lookup"><span data-stu-id="a8aad-155">With optional OData query parameters, a filtered set of jobs is returned.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDeviceNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt; ListByDeviceNext (this Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt; ListByDeviceNext(class Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.ListByDeviceNext(Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDeviceNext (operations As IJobsOperations, nextPageLink As String) As IPage(Of Job)" />
      <MemberSignature Language="F#" Value="static member ListByDeviceNext : Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.ListByDeviceNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a8aad-156">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a8aad-156">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="a8aad-157">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="a8aad-157">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a8aad-158">指定されたデバイスのすべてのジョブを取得します。</span><span class="sxs-lookup"><span data-stu-id="a8aad-158">Gets all the jobs for specified device.</span></span> <span data-ttu-id="a8aad-159">省略可能な OData クエリ パラメーターを持つジョブのフィルター処理されたセットが返されます。</span><span class="sxs-lookup"><span data-stu-id="a8aad-159">With optional OData query parameters, a filtered set of jobs is returned.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDeviceNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt;&gt; ListByDeviceNextAsync (this Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt;&gt; ListByDeviceNextAsync(class Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.ListByDeviceNextAsync(Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDeviceNextAsync : Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.ListByDeviceNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions/&lt;ListByDeviceNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a8aad-160">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a8aad-160">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="a8aad-161">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="a8aad-161">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a8aad-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a8aad-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a8aad-163">指定されたデバイスのすべてのジョブを取得します。</span><span class="sxs-lookup"><span data-stu-id="a8aad-163">Gets all the jobs for specified device.</span></span> <span data-ttu-id="a8aad-164">省略可能な OData クエリ パラメーターを持つジョブのフィルター処理されたセットが返されます。</span><span class="sxs-lookup"><span data-stu-id="a8aad-164">With optional OData query parameters, a filtered set of jobs is returned.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByManager">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt; ListByManager (this Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string resourceGroupName, string managerName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt; ListByManager(class Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string resourceGroupName, string managerName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.ListByManager(Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByManager (operations As IJobsOperations, resourceGroupName As String, managerName As String, Optional odataQuery As ODataQuery(Of JobFilter) = null) As IPage(Of Job)" />
      <MemberSignature Language="F#" Value="static member ListByManager : Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.ListByManager (operations, resourceGroupName, managerName, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a8aad-165">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a8aad-165">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a8aad-166">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="a8aad-166">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="a8aad-167">管理者名</span><span class="sxs-lookup"><span data-stu-id="a8aad-167">The manager name</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="a8aad-168">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="a8aad-168">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a8aad-169">指定したマネージャーのすべてのジョブを取得します。</span><span class="sxs-lookup"><span data-stu-id="a8aad-169">Gets all the jobs for the specified manager.</span></span> <span data-ttu-id="a8aad-170">省略可能な OData クエリ パラメーターを持つジョブのフィルター処理されたセットが返されます。</span><span class="sxs-lookup"><span data-stu-id="a8aad-170">With optional OData query parameters, a filtered set of jobs is returned.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByManagerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt;&gt; ListByManagerAsync (this Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string resourceGroupName, string managerName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt;&gt; ListByManagerAsync(class Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string resourceGroupName, string managerName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.ListByManagerAsync(Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByManagerAsync : Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.ListByManagerAsync (operations, resourceGroupName, managerName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions/&lt;ListByManagerAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.JobFilter&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a8aad-171">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a8aad-171">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="a8aad-172">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="a8aad-172">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="a8aad-173">管理者名</span><span class="sxs-lookup"><span data-stu-id="a8aad-173">The manager name</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="a8aad-174">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="a8aad-174">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a8aad-175">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a8aad-175">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a8aad-176">指定したマネージャーのすべてのジョブを取得します。</span><span class="sxs-lookup"><span data-stu-id="a8aad-176">Gets all the jobs for the specified manager.</span></span> <span data-ttu-id="a8aad-177">省略可能な OData クエリ パラメーターを持つジョブのフィルター処理されたセットが返されます。</span><span class="sxs-lookup"><span data-stu-id="a8aad-177">With optional OData query parameters, a filtered set of jobs is returned.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByManagerNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt; ListByManagerNext (this Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt; ListByManagerNext(class Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.ListByManagerNext(Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByManagerNext (operations As IJobsOperations, nextPageLink As String) As IPage(Of Job)" />
      <MemberSignature Language="F#" Value="static member ListByManagerNext : Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.ListByManagerNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a8aad-178">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a8aad-178">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="a8aad-179">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="a8aad-179">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a8aad-180">指定したマネージャーのすべてのジョブを取得します。</span><span class="sxs-lookup"><span data-stu-id="a8aad-180">Gets all the jobs for the specified manager.</span></span> <span data-ttu-id="a8aad-181">省略可能な OData クエリ パラメーターを持つジョブのフィルター処理されたセットが返されます。</span><span class="sxs-lookup"><span data-stu-id="a8aad-181">With optional OData query parameters, a filtered set of jobs is returned.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByManagerNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt;&gt; ListByManagerNextAsync (this Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt;&gt; ListByManagerNextAsync(class Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.ListByManagerNextAsync(Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByManagerNextAsync : Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions.ListByManagerNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.JobsOperationsExtensions/&lt;ListByManagerNextAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Job&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a8aad-182">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="a8aad-182">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="a8aad-183">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="a8aad-183">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a8aad-184">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a8aad-184">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a8aad-185">指定したマネージャーのすべてのジョブを取得します。</span><span class="sxs-lookup"><span data-stu-id="a8aad-185">Gets all the jobs for the specified manager.</span></span> <span data-ttu-id="a8aad-186">省略可能な OData クエリ パラメーターを持つジョブのフィルター処理されたセットが返されます。</span><span class="sxs-lookup"><span data-stu-id="a8aad-186">With optional OData query parameters, a filtered set of jobs is returned.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>