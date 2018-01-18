<Type Name="StreamingJobsOperationsExtensions" FullName="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class StreamingJobsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit StreamingJobsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module StreamingJobsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type StreamingJobsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8d748-101">StreamingJobsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="8d748-101">Extension methods for StreamingJobsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrReplace">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob BeginCreateOrReplace (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob BeginCreateOrReplace(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginCreateOrReplace(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrReplace : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginCreateOrReplace (operations, streamingJob, resourceGroupName, jobName, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="streamingJob" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-102">The operations group for this extension method.</span></span>
            </param>
        <param name="streamingJob">
            <span data-ttu-id="8d748-103">新しいストリーミング ジョブを作成または既存の置換に使用される、ストリーミング ジョブの定義。</span><span class="sxs-lookup"><span data-stu-id="8d748-103">The definition of the streaming job that will be used to create a new streaming job or replace the existing one.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8d748-104">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-104">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8d748-105">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="8d748-105">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="8d748-106">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-106">The name of the streaming job.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="8d748-107">ストリーミング ジョブの ETag。</span><span class="sxs-lookup"><span data-stu-id="8d748-107">The ETag of the streaming job.</span></span> <span data-ttu-id="8d748-108">常に、現在のレコード セットを上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="8d748-108">Omit this value to always overwrite the current record set.</span></span> <span data-ttu-id="8d748-109">誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="8d748-109">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="8d748-110">設定 ' \*' セットを記録が、既存の更新を防ぐために、新しいストリーミング ジョブを作成するには、します。</span><span class="sxs-lookup"><span data-stu-id="8d748-110">Set to '\*' to allow a new streaming job to be created, but to prevent updating an existing record set.</span></span> <span data-ttu-id="8d748-111">その他の値は、412 の前提条件が失敗の応答になります。</span><span class="sxs-lookup"><span data-stu-id="8d748-111">Other values will result in a 412 Pre-condition Failed response.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-112">ストリーミング ジョブを作成するか、既存のストリーミング ジョブを置き換えます。</span><span class="sxs-lookup"><span data-stu-id="8d748-112">Creates a streaming job or replaces an already existing streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrReplaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; BeginCreateOrReplaceAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; BeginCreateOrReplaceAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginCreateOrReplaceAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrReplaceAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginCreateOrReplaceAsync (operations, streamingJob, resourceGroupName, jobName, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;BeginCreateOrReplaceAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="streamingJob" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-113">The operations group for this extension method.</span></span>
            </param>
        <param name="streamingJob">
            <span data-ttu-id="8d748-114">新しいストリーミング ジョブを作成または既存の置換に使用される、ストリーミング ジョブの定義。</span><span class="sxs-lookup"><span data-stu-id="8d748-114">The definition of the streaming job that will be used to create a new streaming job or replace the existing one.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8d748-115">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-115">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8d748-116">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="8d748-116">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="8d748-117">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-117">The name of the streaming job.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="8d748-118">ストリーミング ジョブの ETag。</span><span class="sxs-lookup"><span data-stu-id="8d748-118">The ETag of the streaming job.</span></span> <span data-ttu-id="8d748-119">常に、現在のレコード セットを上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="8d748-119">Omit this value to always overwrite the current record set.</span></span> <span data-ttu-id="8d748-120">誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="8d748-120">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="8d748-121">設定 ' \*' セットを記録が、既存の更新を防ぐために、新しいストリーミング ジョブを作成するには、します。</span><span class="sxs-lookup"><span data-stu-id="8d748-121">Set to '\*' to allow a new streaming job to be created, but to prevent updating an existing record set.</span></span> <span data-ttu-id="8d748-122">その他の値は、412 の前提条件が失敗の応答になります。</span><span class="sxs-lookup"><span data-stu-id="8d748-122">Other values will result in a 412 Pre-condition Failed response.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8d748-123">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8d748-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-124">ストリーミング ジョブを作成するか、既存のストリーミング ジョブを置き換えます。</span><span class="sxs-lookup"><span data-stu-id="8d748-124">Creates a streaming job or replaces an already existing streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginDelete (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-125">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-125">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8d748-126">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-126">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8d748-127">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="8d748-127">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="8d748-128">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-128">The name of the streaming job.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-129">ストリーミング ジョブを削除します。</span><span class="sxs-lookup"><span data-stu-id="8d748-129">Deletes a streaming job.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-130">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8d748-131">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-131">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8d748-132">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="8d748-132">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="8d748-133">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-133">The name of the streaming job.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8d748-134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8d748-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-135">ストリーミング ジョブを削除します。</span><span class="sxs-lookup"><span data-stu-id="8d748-135">Deletes a streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStart">
      <MemberSignature Language="C#" Value="public static void BeginStart (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginStart(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStart(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginStart (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String, Optional startJobParameters As StartStreamingJobParameters = null)" />
      <MemberSignature Language="F#" Value="static member BeginStart : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStart (operations, resourceGroupName, jobName, startJobParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="startJobParameters" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-136">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8d748-137">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-137">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8d748-138">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="8d748-138">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="8d748-139">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-139">The name of the streaming job.</span></span>
            </param>
        <param name="startJobParameters">
            <span data-ttu-id="8d748-140">ストリーミング ジョブ操作の開始に適用可能なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="8d748-140">Parameters applicable to a start streaming job operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-141">ストリーミング ジョブを開始します。</span><span class="sxs-lookup"><span data-stu-id="8d748-141">Starts a streaming job.</span></span> <span data-ttu-id="8d748-142">ジョブが開始される入力イベントの処理を開始、出力が生成されます。</span><span class="sxs-lookup"><span data-stu-id="8d748-142">Once a job is started it will start processing input events and produce output.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginStartAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginStartAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStartAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStartAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStartAsync (operations, resourceGroupName, jobName, startJobParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;BeginStartAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="startJobParameters" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8d748-144">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-144">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8d748-145">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="8d748-145">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="8d748-146">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-146">The name of the streaming job.</span></span>
            </param>
        <param name="startJobParameters">
            <span data-ttu-id="8d748-147">ストリーミング ジョブ操作の開始に適用可能なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="8d748-147">Parameters applicable to a start streaming job operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8d748-148">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8d748-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-149">ストリーミング ジョブを開始します。</span><span class="sxs-lookup"><span data-stu-id="8d748-149">Starts a streaming job.</span></span> <span data-ttu-id="8d748-150">ジョブが開始される入力イベントの処理を開始、出力が生成されます。</span><span class="sxs-lookup"><span data-stu-id="8d748-150">Once a job is started it will start processing input events and produce output.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStop">
      <MemberSignature Language="C#" Value="public static void BeginStop (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginStop(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStop(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginStop (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String)" />
      <MemberSignature Language="F#" Value="static member BeginStop : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStop (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-151">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-151">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8d748-152">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-152">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8d748-153">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="8d748-153">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="8d748-154">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-154">The name of the streaming job.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-155">実行中のストリーミング ジョブを停止します。</span><span class="sxs-lookup"><span data-stu-id="8d748-155">Stops a running streaming job.</span></span> <span data-ttu-id="8d748-156">これにより、実行中のストリーミング ジョブの入力イベントを処理して、出力を生成を停止します。</span><span class="sxs-lookup"><span data-stu-id="8d748-156">This will cause a running streaming job to stop processing input events and producing output.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginStopAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginStopAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStopAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStopAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStopAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;BeginStopAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-157">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-157">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8d748-158">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-158">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8d748-159">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="8d748-159">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="8d748-160">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-160">The name of the streaming job.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8d748-161">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8d748-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-162">実行中のストリーミング ジョブを停止します。</span><span class="sxs-lookup"><span data-stu-id="8d748-162">Stops a running streaming job.</span></span> <span data-ttu-id="8d748-163">これにより、実行中のストリーミング ジョブの入力イベントを処理して、出力を生成を停止します。</span><span class="sxs-lookup"><span data-stu-id="8d748-163">This will cause a running streaming job to stop processing input events and producing output.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplace">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob CreateOrReplace (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob CreateOrReplace(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.CreateOrReplace(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplace : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.CreateOrReplace (operations, streamingJob, resourceGroupName, jobName, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="streamingJob" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-164">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-164">The operations group for this extension method.</span></span>
            </param>
        <param name="streamingJob">
            <span data-ttu-id="8d748-165">新しいストリーミング ジョブを作成または既存の置換に使用される、ストリーミング ジョブの定義。</span><span class="sxs-lookup"><span data-stu-id="8d748-165">The definition of the streaming job that will be used to create a new streaming job or replace the existing one.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8d748-166">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-166">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8d748-167">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="8d748-167">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="8d748-168">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-168">The name of the streaming job.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="8d748-169">ストリーミング ジョブの ETag。</span><span class="sxs-lookup"><span data-stu-id="8d748-169">The ETag of the streaming job.</span></span> <span data-ttu-id="8d748-170">常に、現在のレコード セットを上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="8d748-170">Omit this value to always overwrite the current record set.</span></span> <span data-ttu-id="8d748-171">誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="8d748-171">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="8d748-172">設定 ' \*' セットを記録が、既存の更新を防ぐために、新しいストリーミング ジョブを作成するには、します。</span><span class="sxs-lookup"><span data-stu-id="8d748-172">Set to '\*' to allow a new streaming job to be created, but to prevent updating an existing record set.</span></span> <span data-ttu-id="8d748-173">その他の値は、412 の前提条件が失敗の応答になります。</span><span class="sxs-lookup"><span data-stu-id="8d748-173">Other values will result in a 412 Pre-condition Failed response.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-174">ストリーミング ジョブを作成するか、既存のストリーミング ジョブを置き換えます。</span><span class="sxs-lookup"><span data-stu-id="8d748-174">Creates a streaming job or replaces an already existing streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; CreateOrReplaceAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; CreateOrReplaceAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.CreateOrReplaceAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplaceAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.CreateOrReplaceAsync (operations, streamingJob, resourceGroupName, jobName, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;CreateOrReplaceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="streamingJob" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-175">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-175">The operations group for this extension method.</span></span>
            </param>
        <param name="streamingJob">
            <span data-ttu-id="8d748-176">新しいストリーミング ジョブを作成または既存の置換に使用される、ストリーミング ジョブの定義。</span><span class="sxs-lookup"><span data-stu-id="8d748-176">The definition of the streaming job that will be used to create a new streaming job or replace the existing one.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8d748-177">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-177">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8d748-178">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="8d748-178">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="8d748-179">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-179">The name of the streaming job.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="8d748-180">ストリーミング ジョブの ETag。</span><span class="sxs-lookup"><span data-stu-id="8d748-180">The ETag of the streaming job.</span></span> <span data-ttu-id="8d748-181">常に、現在のレコード セットを上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="8d748-181">Omit this value to always overwrite the current record set.</span></span> <span data-ttu-id="8d748-182">誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="8d748-182">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="8d748-183">設定 ' \*' セットを記録が、既存の更新を防ぐために、新しいストリーミング ジョブを作成するには、します。</span><span class="sxs-lookup"><span data-stu-id="8d748-183">Set to '\*' to allow a new streaming job to be created, but to prevent updating an existing record set.</span></span> <span data-ttu-id="8d748-184">その他の値は、412 の前提条件が失敗の応答になります。</span><span class="sxs-lookup"><span data-stu-id="8d748-184">Other values will result in a 412 Pre-condition Failed response.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8d748-185">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8d748-185">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-186">ストリーミング ジョブを作成するか、既存のストリーミング ジョブを置き換えます。</span><span class="sxs-lookup"><span data-stu-id="8d748-186">Creates a streaming job or replaces an already existing streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Delete(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Delete (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-187">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-187">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8d748-188">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-188">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8d748-189">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="8d748-189">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="8d748-190">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-190">The name of the streaming job.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-191">ストリーミング ジョブを削除します。</span><span class="sxs-lookup"><span data-stu-id="8d748-191">Deletes a streaming job.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.DeleteAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-192">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-192">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8d748-193">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-193">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8d748-194">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="8d748-194">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="8d748-195">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-195">The name of the streaming job.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8d748-196">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8d748-196">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-197">ストリーミング ジョブを削除します。</span><span class="sxs-lookup"><span data-stu-id="8d748-197">Deletes a streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob Get (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob Get(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Get(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String, Optional expand As String = null) As StreamingJob" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Get (operations, resourceGroupName, jobName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-198">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-198">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8d748-199">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-199">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8d748-200">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="8d748-200">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="8d748-201">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-201">The name of the streaming job.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="8d748-202">$ は、OData クエリ パラメーターを展開します。</span><span class="sxs-lookup"><span data-stu-id="8d748-202">The $expand OData query parameter.</span></span> <span data-ttu-id="8d748-203">これは、このパラメーターがない場合に返される設定の既定以外の応答に含める追加のストリーミング ジョブ プロパティのコンマ区切りの一覧です。</span><span class="sxs-lookup"><span data-stu-id="8d748-203">This is a comma-separated list of additional streaming job properties to include in the response, beyond the default set returned when this parameter is absent.</span></span> <span data-ttu-id="8d748-204">既定のセットは、'の入力'、'変換'、'outputs' および '関数' 以外のすべてのストリーミング ジョブ プロパティです。</span><span class="sxs-lookup"><span data-stu-id="8d748-204">The default set is all streaming job properties other than 'inputs', 'transformation', 'outputs', and 'functions'.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-205">指定したストリーミング ジョブの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="8d748-205">Gets details about the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; GetAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; GetAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.GetAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.GetAsync (operations, resourceGroupName, jobName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-206">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-206">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8d748-207">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-207">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8d748-208">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="8d748-208">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="8d748-209">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-209">The name of the streaming job.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="8d748-210">$ は、OData クエリ パラメーターを展開します。</span><span class="sxs-lookup"><span data-stu-id="8d748-210">The $expand OData query parameter.</span></span> <span data-ttu-id="8d748-211">これは、このパラメーターがない場合に返される設定の既定以外の応答に含める追加のストリーミング ジョブ プロパティのコンマ区切りの一覧です。</span><span class="sxs-lookup"><span data-stu-id="8d748-211">This is a comma-separated list of additional streaming job properties to include in the response, beyond the default set returned when this parameter is absent.</span></span> <span data-ttu-id="8d748-212">既定のセットは、'の入力'、'変換'、'outputs' および '関数' 以外のすべてのストリーミング ジョブ プロパティです。</span><span class="sxs-lookup"><span data-stu-id="8d748-212">The default set is all streaming job properties other than 'inputs', 'transformation', 'outputs', and 'functions'.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8d748-213">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8d748-213">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-214">指定したストリーミング ジョブの詳細を取得します。</span><span class="sxs-lookup"><span data-stu-id="8d748-214">Gets details about the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; List (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; List(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.List(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IStreamingJobsOperations, Optional expand As String = null) As IPage(Of StreamingJob)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.List (operations, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-215">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-215">The operations group for this extension method.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="8d748-216">$ は、OData クエリ パラメーターを展開します。</span><span class="sxs-lookup"><span data-stu-id="8d748-216">The $expand OData query parameter.</span></span> <span data-ttu-id="8d748-217">これは、このパラメーターがない場合に返される設定の既定以外の応答に含める追加のストリーミング ジョブ プロパティのコンマ区切りの一覧です。</span><span class="sxs-lookup"><span data-stu-id="8d748-217">This is a comma-separated list of additional streaming job properties to include in the response, beyond the default set returned when this parameter is absent.</span></span> <span data-ttu-id="8d748-218">既定のセットは、'の入力'、'変換'、'outputs' および '関数' 以外のすべてのストリーミング ジョブ プロパティです。</span><span class="sxs-lookup"><span data-stu-id="8d748-218">The default set is all streaming job properties other than 'inputs', 'transformation', 'outputs', and 'functions'.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-219">すべての所定のサブスクリプションでストリーミング ジョブの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="8d748-219">Lists all of the streaming jobs in the given subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListAsync (operations, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-220">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-220">The operations group for this extension method.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="8d748-221">$ は、OData クエリ パラメーターを展開します。</span><span class="sxs-lookup"><span data-stu-id="8d748-221">The $expand OData query parameter.</span></span> <span data-ttu-id="8d748-222">これは、このパラメーターがない場合に返される設定の既定以外の応答に含める追加のストリーミング ジョブ プロパティのコンマ区切りの一覧です。</span><span class="sxs-lookup"><span data-stu-id="8d748-222">This is a comma-separated list of additional streaming job properties to include in the response, beyond the default set returned when this parameter is absent.</span></span> <span data-ttu-id="8d748-223">既定のセットは、'の入力'、'変換'、'outputs' および '関数' 以外のすべてのストリーミング ジョブ プロパティです。</span><span class="sxs-lookup"><span data-stu-id="8d748-223">The default set is all streaming job properties other than 'inputs', 'transformation', 'outputs', and 'functions'.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8d748-224">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8d748-224">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-225">すべての所定のサブスクリプションでストリーミング ジョブの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="8d748-225">Lists all of the streaming jobs in the given subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; ListByResourceGroup (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; ListByResourceGroup(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IStreamingJobsOperations, resourceGroupName As String, Optional expand As String = null) As IPage(Of StreamingJob)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-226">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-226">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8d748-227">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-227">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8d748-228">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="8d748-228">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="8d748-229">$ は、OData クエリ パラメーターを展開します。</span><span class="sxs-lookup"><span data-stu-id="8d748-229">The $expand OData query parameter.</span></span> <span data-ttu-id="8d748-230">これは、このパラメーターがない場合に返される設定の既定以外の応答に含める追加のストリーミング ジョブ プロパティのコンマ区切りの一覧です。</span><span class="sxs-lookup"><span data-stu-id="8d748-230">This is a comma-separated list of additional streaming job properties to include in the response, beyond the default set returned when this parameter is absent.</span></span> <span data-ttu-id="8d748-231">既定のセットは、'の入力'、'変換'、'outputs' および '関数' 以外のすべてのストリーミング ジョブ プロパティです。</span><span class="sxs-lookup"><span data-stu-id="8d748-231">The default set is all streaming job properties other than 'inputs', 'transformation', 'outputs', and 'functions'.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-232">指定されたリソース グループ内のストリーミング ジョブのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="8d748-232">Lists all of the streaming jobs in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-233">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-233">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8d748-234">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-234">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8d748-235">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="8d748-235">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="8d748-236">$ は、OData クエリ パラメーターを展開します。</span><span class="sxs-lookup"><span data-stu-id="8d748-236">The $expand OData query parameter.</span></span> <span data-ttu-id="8d748-237">これは、このパラメーターがない場合に返される設定の既定以外の応答に含める追加のストリーミング ジョブ プロパティのコンマ区切りの一覧です。</span><span class="sxs-lookup"><span data-stu-id="8d748-237">This is a comma-separated list of additional streaming job properties to include in the response, beyond the default set returned when this parameter is absent.</span></span> <span data-ttu-id="8d748-238">既定のセットは、'の入力'、'変換'、'outputs' および '関数' 以外のすべてのストリーミング ジョブ プロパティです。</span><span class="sxs-lookup"><span data-stu-id="8d748-238">The default set is all streaming job properties other than 'inputs', 'transformation', 'outputs', and 'functions'.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8d748-239">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8d748-239">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-240">指定されたリソース グループ内のストリーミング ジョブのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="8d748-240">Lists all of the streaming jobs in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IStreamingJobsOperations, nextPageLink As String) As IPage(Of StreamingJob)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-241">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-241">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8d748-242">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8d748-242">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-243">指定されたリソース グループ内のストリーミング ジョブのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="8d748-243">Lists all of the streaming jobs in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-244">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-244">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8d748-245">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8d748-245">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8d748-246">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8d748-246">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-247">指定されたリソース グループ内のストリーミング ジョブのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="8d748-247">Lists all of the streaming jobs in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; ListNext (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; ListNext(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListNext(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IStreamingJobsOperations, nextPageLink As String) As IPage(Of StreamingJob)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-248">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-248">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8d748-249">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8d748-249">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-250">すべての所定のサブスクリプションでストリーミング ジョブの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="8d748-250">Lists all of the streaming jobs in the given subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;ListNextAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-251">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-251">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8d748-252">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8d748-252">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8d748-253">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8d748-253">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-254">すべての所定のサブスクリプションでストリーミング ジョブの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="8d748-254">Lists all of the streaming jobs in the given subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public static void Start (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Start(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Start(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Start (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String, Optional startJobParameters As StartStreamingJobParameters = null)" />
      <MemberSignature Language="F#" Value="static member Start : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Start (operations, resourceGroupName, jobName, startJobParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="startJobParameters" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-255">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-255">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8d748-256">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-256">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8d748-257">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="8d748-257">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="8d748-258">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-258">The name of the streaming job.</span></span>
            </param>
        <param name="startJobParameters">
            <span data-ttu-id="8d748-259">ストリーミング ジョブ操作の開始に適用可能なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="8d748-259">Parameters applicable to a start streaming job operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-260">ストリーミング ジョブを開始します。</span><span class="sxs-lookup"><span data-stu-id="8d748-260">Starts a streaming job.</span></span> <span data-ttu-id="8d748-261">ジョブが開始される入力イベントの処理を開始、出力が生成されます。</span><span class="sxs-lookup"><span data-stu-id="8d748-261">Once a job is started it will start processing input events and produce output.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task StartAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task StartAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.StartAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StartAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.StartAsync (operations, resourceGroupName, jobName, startJobParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;StartAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="startJobParameters" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-262">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-262">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8d748-263">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-263">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8d748-264">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="8d748-264">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="8d748-265">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-265">The name of the streaming job.</span></span>
            </param>
        <param name="startJobParameters">
            <span data-ttu-id="8d748-266">ストリーミング ジョブ操作の開始に適用可能なパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="8d748-266">Parameters applicable to a start streaming job operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8d748-267">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8d748-267">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-268">ストリーミング ジョブを開始します。</span><span class="sxs-lookup"><span data-stu-id="8d748-268">Starts a streaming job.</span></span> <span data-ttu-id="8d748-269">ジョブが開始される入力イベントの処理を開始、出力が生成されます。</span><span class="sxs-lookup"><span data-stu-id="8d748-269">Once a job is started it will start processing input events and produce output.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stop">
      <MemberSignature Language="C#" Value="public static void Stop (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Stop(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Stop(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Stop (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String)" />
      <MemberSignature Language="F#" Value="static member Stop : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Stop (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-270">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-270">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8d748-271">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-271">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8d748-272">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="8d748-272">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="8d748-273">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-273">The name of the streaming job.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-274">実行中のストリーミング ジョブを停止します。</span><span class="sxs-lookup"><span data-stu-id="8d748-274">Stops a running streaming job.</span></span> <span data-ttu-id="8d748-275">これにより、実行中のストリーミング ジョブの入力イベントを処理して、出力を生成を停止します。</span><span class="sxs-lookup"><span data-stu-id="8d748-275">This will cause a running streaming job to stop processing input events and producing output.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task StopAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task StopAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.StopAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StopAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.StopAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;StopAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-276">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-276">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8d748-277">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-277">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8d748-278">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="8d748-278">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="8d748-279">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-279">The name of the streaming job.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8d748-280">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8d748-280">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-281">実行中のストリーミング ジョブを停止します。</span><span class="sxs-lookup"><span data-stu-id="8d748-281">Stops a running streaming job.</span></span> <span data-ttu-id="8d748-282">これにより、実行中のストリーミング ジョブの入力イベントを処理して、出力を生成を停止します。</span><span class="sxs-lookup"><span data-stu-id="8d748-282">This will cause a running streaming job to stop processing input events and producing output.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob Update (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob Update(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Update(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Update (operations, streamingJob, resourceGroupName, jobName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="streamingJob" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-283">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-283">The operations group for this extension method.</span></span>
            </param>
        <param name="streamingJob">
            <span data-ttu-id="8d748-284">ストリーミング ジョブ オブジェクトを使用します。</span><span class="sxs-lookup"><span data-stu-id="8d748-284">A streaming job object.</span></span> <span data-ttu-id="8d748-285">ここで指定したプロパティで既存のストリーミング ジョブ (ie 対応するプロパティが上書きされます。そのプロパティが更新されます)。</span><span class="sxs-lookup"><span data-stu-id="8d748-285">The properties specified here will overwrite the corresponding properties in the existing streaming job (ie. Those properties will be updated).</span></span> <span data-ttu-id="8d748-286">ここでは null に設定されている任意のプロパティがありことを意味既存の入力の対応するプロパティは同じままこの PATCH 操作の結果として変更されません。</span><span class="sxs-lookup"><span data-stu-id="8d748-286">Any properties that are set to null here will mean that the corresponding property in the existing input will remain the same and not change as a result of this PATCH operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8d748-287">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-287">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8d748-288">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="8d748-288">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="8d748-289">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-289">The name of the streaming job.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="8d748-290">ストリーミング ジョブの ETag。</span><span class="sxs-lookup"><span data-stu-id="8d748-290">The ETag of the streaming job.</span></span> <span data-ttu-id="8d748-291">常に、現在のレコード セットを上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="8d748-291">Omit this value to always overwrite the current record set.</span></span> <span data-ttu-id="8d748-292">誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="8d748-292">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-293">既存のストリーミング ジョブを更新します。</span><span class="sxs-lookup"><span data-stu-id="8d748-293">Updates an existing streaming job.</span></span> <span data-ttu-id="8d748-294">これは、(ie 部分的に更新を使用できます。</span><span class="sxs-lookup"><span data-stu-id="8d748-294">This can be used to partially update (ie.</span></span> <span data-ttu-id="8d748-295">1 つまたは 2 つのプロパティの更新)、残りのジョブ定義の影響を与えずに、ストリーミング ジョブです。</span><span class="sxs-lookup"><span data-stu-id="8d748-295">update one or two properties) a streaming job without affecting the rest the job definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; UpdateAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; UpdateAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.UpdateAsync (operations, streamingJob, resourceGroupName, jobName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="streamingJob" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8d748-296">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8d748-296">The operations group for this extension method.</span></span>
            </param>
        <param name="streamingJob">
            <span data-ttu-id="8d748-297">ストリーミング ジョブ オブジェクトを使用します。</span><span class="sxs-lookup"><span data-stu-id="8d748-297">A streaming job object.</span></span> <span data-ttu-id="8d748-298">ここで指定したプロパティで既存のストリーミング ジョブ (ie 対応するプロパティが上書きされます。そのプロパティが更新されます)。</span><span class="sxs-lookup"><span data-stu-id="8d748-298">The properties specified here will overwrite the corresponding properties in the existing streaming job (ie. Those properties will be updated).</span></span> <span data-ttu-id="8d748-299">ここでは null に設定されている任意のプロパティがありことを意味既存の入力の対応するプロパティは同じままこの PATCH 操作の結果として変更されません。</span><span class="sxs-lookup"><span data-stu-id="8d748-299">Any properties that are set to null here will mean that the corresponding property in the existing input will remain the same and not change as a result of this PATCH operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8d748-300">リソースを格納するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-300">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="8d748-301">この値は、Azure リソース マネージャー API またはポータルから取得できます。</span><span class="sxs-lookup"><span data-stu-id="8d748-301">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="8d748-302">ストリーミング ジョブの名前。</span><span class="sxs-lookup"><span data-stu-id="8d748-302">The name of the streaming job.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="8d748-303">ストリーミング ジョブの ETag。</span><span class="sxs-lookup"><span data-stu-id="8d748-303">The ETag of the streaming job.</span></span> <span data-ttu-id="8d748-304">常に、現在のレコード セットを上書きするには、この値を省略します。</span><span class="sxs-lookup"><span data-stu-id="8d748-304">Omit this value to always overwrite the current record set.</span></span> <span data-ttu-id="8d748-305">誤って overwritting 同時変更を防ぐために最後に、発生の ETag 値を指定します。</span><span class="sxs-lookup"><span data-stu-id="8d748-305">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8d748-306">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8d748-306">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8d748-307">既存のストリーミング ジョブを更新します。</span><span class="sxs-lookup"><span data-stu-id="8d748-307">Updates an existing streaming job.</span></span> <span data-ttu-id="8d748-308">これは、(ie 部分的に更新を使用できます。</span><span class="sxs-lookup"><span data-stu-id="8d748-308">This can be used to partially update (ie.</span></span> <span data-ttu-id="8d748-309">1 つまたは 2 つのプロパティの更新)、残りのジョブ定義の影響を与えずに、ストリーミング ジョブです。</span><span class="sxs-lookup"><span data-stu-id="8d748-309">update one or two properties) a streaming job without affecting the rest the job definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>