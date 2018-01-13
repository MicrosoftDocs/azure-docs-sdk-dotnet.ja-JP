<Type Name="JobScheduleOperationsExtensions" FullName="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class JobScheduleOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit JobScheduleOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module JobScheduleOperationsExtensions" />
  <TypeSignature Language="F#" Value="type JobScheduleOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8ff76-101">JobScheduleOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="8ff76-101">Extension methods for JobScheduleOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddHeaders Add (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter cloudJobSchedule, Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions jobScheduleAddOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddHeaders Add(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter cloudJobSchedule, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions jobScheduleAddOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Add(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter,Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions)" />
      <MemberSignature Language="F#" Value="static member Add : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter * Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Add (operations, cloudJobSchedule, jobScheduleAddOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="cloudJobSchedule" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter" />
        <Parameter Name="jobScheduleAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ff76-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-102">The operations group for this extension method.</span></span>
            </param>
        <param name="cloudJobSchedule">
            <span data-ttu-id="8ff76-103">追加するジョブ スケジュールです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-103">The job schedule to be added.</span></span>
            </param>
        <param name="jobScheduleAddOptions">
            <span data-ttu-id="8ff76-104">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8ff76-104">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ff76-105">指定されたアカウントには、ジョブのスケジュールを追加します。</span><span class="sxs-lookup"><span data-stu-id="8ff76-105">Adds a job schedule to the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddHeaders&gt; AddAsync (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter cloudJobSchedule, Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions jobScheduleAddOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddHeaders&gt; AddAsync(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter cloudJobSchedule, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions jobScheduleAddOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.AddAsync(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter,Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddAsync : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter * Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.AddAsync (operations, cloudJobSchedule, jobScheduleAddOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions/&lt;AddAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="cloudJobSchedule" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter" />
        <Parameter Name="jobScheduleAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ff76-106">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-106">The operations group for this extension method.</span></span>
            </param>
        <param name="cloudJobSchedule">
            <span data-ttu-id="8ff76-107">追加するジョブ スケジュールです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-107">The job schedule to be added.</span></span>
            </param>
        <param name="jobScheduleAddOptions">
            <span data-ttu-id="8ff76-108">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8ff76-108">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8ff76-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8ff76-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ff76-110">指定されたアカウントには、ジョブのスケジュールを追加します。</span><span class="sxs-lookup"><span data-stu-id="8ff76-110">Adds a job schedule to the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteHeaders Delete (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions jobScheduleDeleteOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteHeaders Delete(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions jobScheduleDeleteOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Delete(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Delete (operations, jobScheduleId, jobScheduleDeleteOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ff76-111">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-111">The operations group for this extension method.</span></span>
            </param>
        <param name="jobScheduleId">
            <span data-ttu-id="8ff76-112">削除するジョブのスケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="8ff76-112">The ID of the job schedule to delete.</span></span>
            </param>
        <param name="jobScheduleDeleteOptions">
            <span data-ttu-id="8ff76-113">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8ff76-113">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ff76-114">指定されたアカウントからジョブのスケジュールを削除します。</span><span class="sxs-lookup"><span data-stu-id="8ff76-114">Deletes a job schedule from the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8ff76-115">ジョブのスケジュールを削除するときにすべてのジョブとそのスケジュールの下にあるタスクも削除します。</span><span class="sxs-lookup"><span data-stu-id="8ff76-115">When you delete a job schedule, this also deletes all jobs and tasks under that schedule.</span></span> <span data-ttu-id="8ff76-116">タスクが削除されると、すべてのファイルを作業ディレクトリをコンピューティング ノードにも削除 (保有期間は無視されます)。</span><span class="sxs-lookup"><span data-stu-id="8ff76-116">When tasks are deleted, all the files in their working directories on the compute nodes are also deleted (the retention period is ignored).</span></span> <span data-ttu-id="8ff76-117">ジョブ スケジュールの統計はアクセスできなくジョブのスケジュールが削除されると、アカウントの有効期間の統計情報に反映させるまだもします。</span><span class="sxs-lookup"><span data-stu-id="8ff76-117">The job schedule statistics are no longer accessible once the job schedule is deleted, though they are still counted towards account lifetime statistics.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteHeaders&gt; DeleteAsync (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions jobScheduleDeleteOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteHeaders&gt; DeleteAsync(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions jobScheduleDeleteOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.DeleteAsync(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.DeleteAsync (operations, jobScheduleId, jobScheduleDeleteOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ff76-118">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-118">The operations group for this extension method.</span></span>
            </param>
        <param name="jobScheduleId">
            <span data-ttu-id="8ff76-119">削除するジョブのスケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="8ff76-119">The ID of the job schedule to delete.</span></span>
            </param>
        <param name="jobScheduleDeleteOptions">
            <span data-ttu-id="8ff76-120">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8ff76-120">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8ff76-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8ff76-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ff76-122">指定されたアカウントからジョブのスケジュールを削除します。</span><span class="sxs-lookup"><span data-stu-id="8ff76-122">Deletes a job schedule from the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8ff76-123">ジョブのスケジュールを削除するときにすべてのジョブとそのスケジュールの下にあるタスクも削除します。</span><span class="sxs-lookup"><span data-stu-id="8ff76-123">When you delete a job schedule, this also deletes all jobs and tasks under that schedule.</span></span> <span data-ttu-id="8ff76-124">タスクが削除されると、すべてのファイルを作業ディレクトリをコンピューティング ノードにも削除 (保有期間は無視されます)。</span><span class="sxs-lookup"><span data-stu-id="8ff76-124">When tasks are deleted, all the files in their working directories on the compute nodes are also deleted (the retention period is ignored).</span></span> <span data-ttu-id="8ff76-125">ジョブ スケジュールの統計はアクセスできなくジョブのスケジュールが削除されると、アカウントの有効期間の統計情報に反映させるまだもします。</span><span class="sxs-lookup"><span data-stu-id="8ff76-125">The job schedule statistics are no longer accessible once the job schedule is deleted, though they are still counted towards account lifetime statistics.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Disable">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableHeaders Disable (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions jobScheduleDisableOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableHeaders Disable(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions jobScheduleDisableOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Disable(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions)" />
      <MemberSignature Language="F#" Value="static member Disable : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Disable (operations, jobScheduleId, jobScheduleDisableOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleDisableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ff76-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-126">The operations group for this extension method.</span></span>
            </param>
        <param name="jobScheduleId">
            <span data-ttu-id="8ff76-127">無効にするジョブ スケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="8ff76-127">The ID of the job schedule to disable.</span></span>
            </param>
        <param name="jobScheduleDisableOptions">
            <span data-ttu-id="8ff76-128">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8ff76-128">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ff76-129">ジョブのスケジュールを無効にします。</span><span class="sxs-lookup"><span data-stu-id="8ff76-129">Disables a job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8ff76-130">ジョブのスケジュールが再度有効にするまで、新しいジョブは作成されません。</span><span class="sxs-lookup"><span data-stu-id="8ff76-130">No new jobs will be created until the job schedule is enabled again.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableHeaders&gt; DisableAsync (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions jobScheduleDisableOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableHeaders&gt; DisableAsync(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions jobScheduleDisableOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.DisableAsync(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DisableAsync : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.DisableAsync (operations, jobScheduleId, jobScheduleDisableOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions/&lt;DisableAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleDisableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ff76-131">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-131">The operations group for this extension method.</span></span>
            </param>
        <param name="jobScheduleId">
            <span data-ttu-id="8ff76-132">無効にするジョブ スケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="8ff76-132">The ID of the job schedule to disable.</span></span>
            </param>
        <param name="jobScheduleDisableOptions">
            <span data-ttu-id="8ff76-133">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8ff76-133">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8ff76-134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8ff76-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ff76-135">ジョブのスケジュールを無効にします。</span><span class="sxs-lookup"><span data-stu-id="8ff76-135">Disables a job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8ff76-136">ジョブのスケジュールが再度有効にするまで、新しいジョブは作成されません。</span><span class="sxs-lookup"><span data-stu-id="8ff76-136">No new jobs will be created until the job schedule is enabled again.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Enable">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableHeaders Enable (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions jobScheduleEnableOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableHeaders Enable(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions jobScheduleEnableOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Enable(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions)" />
      <MemberSignature Language="F#" Value="static member Enable : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Enable (operations, jobScheduleId, jobScheduleEnableOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleEnableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ff76-137">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-137">The operations group for this extension method.</span></span>
            </param>
        <param name="jobScheduleId">
            <span data-ttu-id="8ff76-138">有効にするジョブのスケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="8ff76-138">The ID of the job schedule to enable.</span></span>
            </param>
        <param name="jobScheduleEnableOptions">
            <span data-ttu-id="8ff76-139">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8ff76-139">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ff76-140">ジョブのスケジュールを有効にします。</span><span class="sxs-lookup"><span data-stu-id="8ff76-140">Enables a job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableHeaders&gt; EnableAsync (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions jobScheduleEnableOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableHeaders&gt; EnableAsync(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions jobScheduleEnableOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.EnableAsync(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EnableAsync : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.EnableAsync (operations, jobScheduleId, jobScheduleEnableOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions/&lt;EnableAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleEnableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ff76-141">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-141">The operations group for this extension method.</span></span>
            </param>
        <param name="jobScheduleId">
            <span data-ttu-id="8ff76-142">有効にするジョブのスケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="8ff76-142">The ID of the job schedule to enable.</span></span>
            </param>
        <param name="jobScheduleEnableOptions">
            <span data-ttu-id="8ff76-143">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8ff76-143">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8ff76-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8ff76-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ff76-145">ジョブのスケジュールを有効にします。</span><span class="sxs-lookup"><span data-stu-id="8ff76-145">Enables a job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public static bool Exists (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions jobScheduleExistsOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool Exists(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions jobScheduleExistsOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Exists(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions)" />
      <MemberSignature Language="F#" Value="static member Exists : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions -&gt; bool" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Exists (operations, jobScheduleId, jobScheduleExistsOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleExistsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ff76-146">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-146">The operations group for this extension method.</span></span>
            </param>
        <param name="jobScheduleId">
            <span data-ttu-id="8ff76-147">確認するジョブのスケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="8ff76-147">The ID of the job schedule which you want to check.</span></span>
            </param>
        <param name="jobScheduleExistsOptions">
            <span data-ttu-id="8ff76-148">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8ff76-148">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ff76-149">指定されたジョブのスケジュールを確認します。</span><span class="sxs-lookup"><span data-stu-id="8ff76-149">Checks the specified job schedule exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions jobScheduleExistsOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions jobScheduleExistsOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.ExistsAsync(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExistsAsync : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.ExistsAsync (operations, jobScheduleId, jobScheduleExistsOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions/&lt;ExistsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleExistsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ff76-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-150">The operations group for this extension method.</span></span>
            </param>
        <param name="jobScheduleId">
            <span data-ttu-id="8ff76-151">確認するジョブのスケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="8ff76-151">The ID of the job schedule which you want to check.</span></span>
            </param>
        <param name="jobScheduleExistsOptions">
            <span data-ttu-id="8ff76-152">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8ff76-152">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8ff76-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8ff76-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ff76-154">指定されたジョブのスケジュールを確認します。</span><span class="sxs-lookup"><span data-stu-id="8ff76-154">Checks the specified job schedule exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule Get (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions jobScheduleGetOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule Get(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions jobScheduleGetOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Get(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Get (operations, jobScheduleId, jobScheduleGetOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ff76-155">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-155">The operations group for this extension method.</span></span>
            </param>
        <param name="jobScheduleId">
            <span data-ttu-id="8ff76-156">取得するジョブ スケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="8ff76-156">The ID of the job schedule to get.</span></span>
            </param>
        <param name="jobScheduleGetOptions">
            <span data-ttu-id="8ff76-157">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8ff76-157">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ff76-158">指定されたジョブのスケジュールに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="8ff76-158">Gets information about the specified job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt; GetAsync (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions jobScheduleGetOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt; GetAsync(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions jobScheduleGetOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.GetAsync(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.GetAsync (operations, jobScheduleId, jobScheduleGetOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ff76-159">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-159">The operations group for this extension method.</span></span>
            </param>
        <param name="jobScheduleId">
            <span data-ttu-id="8ff76-160">取得するジョブ スケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="8ff76-160">The ID of the job schedule to get.</span></span>
            </param>
        <param name="jobScheduleGetOptions">
            <span data-ttu-id="8ff76-161">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8ff76-161">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8ff76-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8ff76-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ff76-163">指定されたジョブのスケジュールに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="8ff76-163">Gets information about the specified job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt; List (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions jobScheduleListOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt; List(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions jobScheduleListOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.List(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.List (operations, jobScheduleListOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ff76-164">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-164">The operations group for this extension method.</span></span>
            </param>
        <param name="jobScheduleListOptions">
            <span data-ttu-id="8ff76-165">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8ff76-165">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ff76-166">指定されたアカウント内のジョブ スケジュールのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="8ff76-166">Lists all of the job schedules in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;&gt; ListAsync (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions jobScheduleListOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;&gt; ListAsync(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions jobScheduleListOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.ListAsync(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.ListAsync (operations, jobScheduleListOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions/&lt;ListAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ff76-167">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-167">The operations group for this extension method.</span></span>
            </param>
        <param name="jobScheduleListOptions">
            <span data-ttu-id="8ff76-168">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8ff76-168">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8ff76-169">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8ff76-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ff76-170">指定されたアカウント内のジョブ スケジュールのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="8ff76-170">Lists all of the job schedules in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt; ListNext (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions jobScheduleListNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt; ListNext(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions jobScheduleListNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.ListNext(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.ListNext (operations, nextPageLink, jobScheduleListNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobScheduleListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ff76-171">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-171">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8ff76-172">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8ff76-172">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="jobScheduleListNextOptions">
            <span data-ttu-id="8ff76-173">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8ff76-173">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ff76-174">指定されたアカウント内のジョブ スケジュールのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="8ff76-174">Lists all of the job schedules in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;&gt; ListNextAsync (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions jobScheduleListNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;&gt; ListNextAsync(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions jobScheduleListNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.ListNextAsync(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.ListNextAsync (operations, nextPageLink, jobScheduleListNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions/&lt;ListNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobScheduleListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ff76-175">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-175">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8ff76-176">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="8ff76-176">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="jobScheduleListNextOptions">
            <span data-ttu-id="8ff76-177">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8ff76-177">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8ff76-178">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8ff76-178">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ff76-179">指定されたアカウント内のジョブ スケジュールのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="8ff76-179">Lists all of the job schedules in the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders Patch (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter jobSchedulePatchParameter, Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions jobSchedulePatchOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders Patch(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter jobSchedulePatchParameter, class Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions jobSchedulePatchOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Patch(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter,Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions)" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter * Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Patch (operations, jobScheduleId, jobSchedulePatchParameter, jobSchedulePatchOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobSchedulePatchParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter" />
        <Parameter Name="jobSchedulePatchOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ff76-180">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-180">The operations group for this extension method.</span></span>
            </param>
        <param name="jobScheduleId">
            <span data-ttu-id="8ff76-181">更新するジョブのスケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="8ff76-181">The ID of the job schedule to update.</span></span>
            </param>
        <param name="jobSchedulePatchParameter">
            <span data-ttu-id="8ff76-182">要求のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-182">The parameters for the request.</span></span>
            </param>
        <param name="jobSchedulePatchOptions">
            <span data-ttu-id="8ff76-183">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8ff76-183">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ff76-184">指定したジョブ スケジュールのプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="8ff76-184">Updates the properties of the specified job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8ff76-185">これには、要求で指定されたジョブのスケジュールのプロパティのみが置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="8ff76-185">This replaces only the job schedule properties specified in the request.</span></span>
            <span data-ttu-id="8ff76-186">たとえば、スケジュールのプロパティがこの要求に指定されていない場合、Batch service、既存のスケジュールは保持します。</span><span class="sxs-lookup"><span data-stu-id="8ff76-186">For example, if the schedule property is not specified with this request, then the Batch service will keep the existing schedule.</span></span> <span data-ttu-id="8ff76-187">ジョブに変更が行われた後、更新プログラムが; スケジュールによって作成された影響ジョブのみをスケジュールします。現在実行中のジョブは、影響を受けません。</span><span class="sxs-lookup"><span data-stu-id="8ff76-187">Changes to a job schedule only impact jobs created by the schedule after the update has taken place; currently running jobs are unaffected.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders&gt; PatchAsync (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter jobSchedulePatchParameter, Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions jobSchedulePatchOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders&gt; PatchAsync(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter jobSchedulePatchParameter, class Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions jobSchedulePatchOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.PatchAsync(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter,Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter * Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.PatchAsync (operations, jobScheduleId, jobSchedulePatchParameter, jobSchedulePatchOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions/&lt;PatchAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobSchedulePatchParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter" />
        <Parameter Name="jobSchedulePatchOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ff76-188">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-188">The operations group for this extension method.</span></span>
            </param>
        <param name="jobScheduleId">
            <span data-ttu-id="8ff76-189">更新するジョブのスケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="8ff76-189">The ID of the job schedule to update.</span></span>
            </param>
        <param name="jobSchedulePatchParameter">
            <span data-ttu-id="8ff76-190">要求のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-190">The parameters for the request.</span></span>
            </param>
        <param name="jobSchedulePatchOptions">
            <span data-ttu-id="8ff76-191">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8ff76-191">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8ff76-192">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8ff76-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ff76-193">指定したジョブ スケジュールのプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="8ff76-193">Updates the properties of the specified job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8ff76-194">これには、要求で指定されたジョブのスケジュールのプロパティのみが置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="8ff76-194">This replaces only the job schedule properties specified in the request.</span></span>
            <span data-ttu-id="8ff76-195">たとえば、スケジュールのプロパティがこの要求に指定されていない場合、Batch service、既存のスケジュールは保持します。</span><span class="sxs-lookup"><span data-stu-id="8ff76-195">For example, if the schedule property is not specified with this request, then the Batch service will keep the existing schedule.</span></span> <span data-ttu-id="8ff76-196">ジョブに変更が行われた後、更新プログラムが; スケジュールによって作成された影響ジョブのみをスケジュールします。現在実行中のジョブは、影響を受けません。</span><span class="sxs-lookup"><span data-stu-id="8ff76-196">Changes to a job schedule only impact jobs created by the schedule after the update has taken place; currently running jobs are unaffected.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateHeaders Terminate (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions jobScheduleTerminateOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateHeaders Terminate(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions jobScheduleTerminateOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Terminate(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions)" />
      <MemberSignature Language="F#" Value="static member Terminate : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Terminate (operations, jobScheduleId, jobScheduleTerminateOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ff76-197">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-197">The operations group for this extension method.</span></span>
            </param>
        <param name="jobScheduleId">
            <span data-ttu-id="8ff76-198">終了するジョブのスケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="8ff76-198">The ID of the job schedule to terminates.</span></span>
            </param>
        <param name="jobScheduleTerminateOptions">
            <span data-ttu-id="8ff76-199">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8ff76-199">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ff76-200">ジョブのスケジュールを終了します。</span><span class="sxs-lookup"><span data-stu-id="8ff76-200">Terminates a job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateHeaders&gt; TerminateAsync (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions jobScheduleTerminateOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateHeaders&gt; TerminateAsync(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions jobScheduleTerminateOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.TerminateAsync(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TerminateAsync : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.TerminateAsync (operations, jobScheduleId, jobScheduleTerminateOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions/&lt;TerminateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ff76-201">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-201">The operations group for this extension method.</span></span>
            </param>
        <param name="jobScheduleId">
            <span data-ttu-id="8ff76-202">終了するジョブのスケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="8ff76-202">The ID of the job schedule to terminates.</span></span>
            </param>
        <param name="jobScheduleTerminateOptions">
            <span data-ttu-id="8ff76-203">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8ff76-203">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8ff76-204">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8ff76-204">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ff76-205">ジョブのスケジュールを終了します。</span><span class="sxs-lookup"><span data-stu-id="8ff76-205">Terminates a job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateHeaders Update (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter jobScheduleUpdateParameter, Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions jobScheduleUpdateOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateHeaders Update(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter jobScheduleUpdateParameter, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions jobScheduleUpdateOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Update(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter,Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter * Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Update (operations, jobScheduleId, jobScheduleUpdateParameter, jobScheduleUpdateOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleUpdateParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter" />
        <Parameter Name="jobScheduleUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ff76-206">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-206">The operations group for this extension method.</span></span>
            </param>
        <param name="jobScheduleId">
            <span data-ttu-id="8ff76-207">更新するジョブのスケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="8ff76-207">The ID of the job schedule to update.</span></span>
            </param>
        <param name="jobScheduleUpdateParameter">
            <span data-ttu-id="8ff76-208">要求のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-208">The parameters for the request.</span></span>
            </param>
        <param name="jobScheduleUpdateOptions">
            <span data-ttu-id="8ff76-209">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8ff76-209">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ff76-210">指定したジョブ スケジュールのプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="8ff76-210">Updates the properties of the specified job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8ff76-211">これには、ジョブ スケジュールの更新可能なプロパティがすべて完全に置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="8ff76-211">This fully replaces all the updateable properties of the job schedule.</span></span> <span data-ttu-id="8ff76-212">たとえば、この要求には、スケジュールのプロパティが指定されていない、バッチ サービスは、既存のスケジュールを削除します。</span><span class="sxs-lookup"><span data-stu-id="8ff76-212">For example, if the schedule property is not specified with this request, then the Batch service will remove the existing schedule.</span></span> <span data-ttu-id="8ff76-213">ジョブに変更が行われた後、更新プログラムが; スケジュールによって作成された影響ジョブのみをスケジュールします。現在実行中のジョブは、影響を受けません。</span><span class="sxs-lookup"><span data-stu-id="8ff76-213">Changes to a job schedule only impact jobs created by the schedule after the update has taken place; currently running jobs are unaffected.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateHeaders&gt; UpdateAsync (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter jobScheduleUpdateParameter, Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions jobScheduleUpdateOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateHeaders&gt; UpdateAsync(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter jobScheduleUpdateParameter, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions jobScheduleUpdateOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.UpdateAsync(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter,Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter * Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.UpdateAsync (operations, jobScheduleId, jobScheduleUpdateParameter, jobScheduleUpdateOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions/&lt;UpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleUpdateParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter" />
        <Parameter Name="jobScheduleUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8ff76-214">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-214">The operations group for this extension method.</span></span>
            </param>
        <param name="jobScheduleId">
            <span data-ttu-id="8ff76-215">更新するジョブのスケジュールの ID。</span><span class="sxs-lookup"><span data-stu-id="8ff76-215">The ID of the job schedule to update.</span></span>
            </param>
        <param name="jobScheduleUpdateParameter">
            <span data-ttu-id="8ff76-216">要求のパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="8ff76-216">The parameters for the request.</span></span>
            </param>
        <param name="jobScheduleUpdateOptions">
            <span data-ttu-id="8ff76-217">操作の追加パラメーター</span><span class="sxs-lookup"><span data-stu-id="8ff76-217">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8ff76-218">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8ff76-218">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8ff76-219">指定したジョブ スケジュールのプロパティを更新します。</span><span class="sxs-lookup"><span data-stu-id="8ff76-219">Updates the properties of the specified job schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8ff76-220">これには、ジョブ スケジュールの更新可能なプロパティがすべて完全に置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="8ff76-220">This fully replaces all the updateable properties of the job schedule.</span></span> <span data-ttu-id="8ff76-221">たとえば、この要求には、スケジュールのプロパティが指定されていない、バッチ サービスは、既存のスケジュールを削除します。</span><span class="sxs-lookup"><span data-stu-id="8ff76-221">For example, if the schedule property is not specified with this request, then the Batch service will remove the existing schedule.</span></span> <span data-ttu-id="8ff76-222">ジョブに変更が行われた後、更新プログラムが; スケジュールによって作成された影響ジョブのみをスケジュールします。現在実行中のジョブは、影響を受けません。</span><span class="sxs-lookup"><span data-stu-id="8ff76-222">Changes to a job schedule only impact jobs created by the schedule after the update has taken place; currently running jobs are unaffected.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>