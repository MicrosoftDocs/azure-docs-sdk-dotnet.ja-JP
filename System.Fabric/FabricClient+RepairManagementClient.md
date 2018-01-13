<Type Name="FabricClient+RepairManagementClient" FullName="System.Fabric.FabricClient+RepairManagementClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.RepairManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/RepairManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.RepairManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.RepairManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.RepairManagementClient = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="283cd-101">修復タスクを管理するためのメソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="283cd-101">Provides methods for managing repair tasks.</span></span></para>
      <para><span data-ttu-id="283cd-102">このクラスは、Service Fabric プラットフォームをサポートしていますコードから直接呼び出されるものではありません。</span><span class="sxs-lookup"><span data-stu-id="283cd-102">This class supports the Service Fabric platform; it is not meant to be called directly from your code.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CancelRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; CancelRepairTaskAsync (string repairTaskId, long version, bool requestAbort);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; CancelRepairTaskAsync(string repairTaskId, int64 version, bool requestAbort) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.CancelRepairTaskAsync(System.String,System.Int64,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelRepairTaskAsync (repairTaskId As String, version As Long, requestAbort As Boolean) As Task(Of Long)" />
      <MemberSignature Language="F#" Value="member this.CancelRepairTaskAsync : string * int64 * bool -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.CancelRepairTaskAsync (repairTaskId, version, requestAbort)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
        <Parameter Name="requestAbort" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para><span data-ttu-id="283cd-103">キャンセルできる修復タスクの ID。</span><span class="sxs-lookup"><span data-stu-id="283cd-103">The ID of the repair task to be cancelled.</span></span></para>
        </param>
        <param name="version">
          <para><span data-ttu-id="283cd-104">修復タスクの現在のバージョン番号。</span><span class="sxs-lookup"><span data-stu-id="283cd-104">The current version number of the repair task.</span></span> <span data-ttu-id="283cd-105">0 以外の場合、要求のみは成功します修復作業の実際の現在の値がこの値に一致する場合。</span><span class="sxs-lookup"><span data-stu-id="283cd-105">If non-zero, then the request will only succeed if this value matches the actual current value of the repair task.</span></span> <span data-ttu-id="283cd-106">0 の場合、バージョン チェックは実行されません。</span><span class="sxs-lookup"><span data-stu-id="283cd-106">If zero, then no version check is performed.</span></span></para>
        </param>
        <param name="requestAbort">
          <para>
            <span data-ttu-id="283cd-107"><languageKeyword>True</languageKeyword>かどうか、修復を停止するかできるだけ早く場合でも、実行が既に開始します。</span><span class="sxs-lookup"><span data-stu-id="283cd-107"><languageKeyword>True</languageKeyword> if the repair should be stopped as soon as possible even if it has already started executing.</span></span> <span data-ttu-id="283cd-108"><languageKeyword>False</languageKeyword>実行がまだ開始されていない場合にのみ、修復を取り消す必要がある場合。</span><span class="sxs-lookup"><span data-stu-id="283cd-108"><languageKeyword>False</languageKeyword> if the repair should be cancelled only if execution has not yet started.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="283cd-109">指定した修復タスクのキャンセルを要求します。</span><span class="sxs-lookup"><span data-stu-id="283cd-109">Requests the cancellation of the given repair task.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="283cd-110">修復タスクの新しいバージョン番号。</span><span class="sxs-lookup"><span data-stu-id="283cd-110">The new version number of the repair task.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; CancelRepairTaskAsync (string repairTaskId, long version, bool requestAbort, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; CancelRepairTaskAsync(string repairTaskId, int64 version, bool requestAbort, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.CancelRepairTaskAsync(System.String,System.Int64,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CancelRepairTaskAsync : string * int64 * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.CancelRepairTaskAsync (repairTaskId, version, requestAbort, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
        <Parameter Name="requestAbort" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para><span data-ttu-id="283cd-111">キャンセルできる修復タスクの ID。</span><span class="sxs-lookup"><span data-stu-id="283cd-111">The ID of the repair task to be cancelled.</span></span></para>
        </param>
        <param name="version">
          <para><span data-ttu-id="283cd-112">修復タスクの現在のバージョン番号。</span><span class="sxs-lookup"><span data-stu-id="283cd-112">The current version number of the repair task.</span></span> <span data-ttu-id="283cd-113">0 以外の場合、要求のみは成功します修復作業の実際の現在の値がこの値に一致する場合。</span><span class="sxs-lookup"><span data-stu-id="283cd-113">If non-zero, then the request will only succeed if this value matches the actual current value of the repair task.</span></span> <span data-ttu-id="283cd-114">0 の場合、バージョン チェックは実行されません。</span><span class="sxs-lookup"><span data-stu-id="283cd-114">If zero, then no version check is performed.</span></span></para>
        </param>
        <param name="requestAbort">
          <para>
            <span data-ttu-id="283cd-115"><languageKeyword>True</languageKeyword>かどうか、修復を停止するかできるだけ早く場合でも、実行が既に開始します。</span><span class="sxs-lookup"><span data-stu-id="283cd-115"><languageKeyword>True</languageKeyword> if the repair should be stopped as soon as possible even if it has already started executing.</span></span> <span data-ttu-id="283cd-116"><languageKeyword>False</languageKeyword>実行がまだ開始されていない場合にのみ、修復を取り消す必要がある場合。</span><span class="sxs-lookup"><span data-stu-id="283cd-116"><languageKeyword>False</languageKeyword> if the repair should be cancelled only if execution has not yet started.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="283cd-117">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="283cd-117">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="283cd-118">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="283cd-118">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="283cd-119">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="283cd-119">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="283cd-120">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="283cd-120">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="283cd-121">指定した修復タスクのキャンセルを要求します。</span><span class="sxs-lookup"><span data-stu-id="283cd-121">Requests the cancellation of the given repair task.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="283cd-122">修復タスクの新しいバージョン番号。</span><span class="sxs-lookup"><span data-stu-id="283cd-122">The new version number of the repair task.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; CreateRepairTaskAsync (System.Fabric.Repair.RepairTask repairTask);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; CreateRepairTaskAsync(class System.Fabric.Repair.RepairTask repairTask) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.CreateRepairTaskAsync(System.Fabric.Repair.RepairTask)" />
      <MemberSignature Language="F#" Value="member this.CreateRepairTaskAsync : System.Fabric.Repair.RepairTask -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.CreateRepairTaskAsync repairTask" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTask" Type="System.Fabric.Repair.RepairTask" />
      </Parameters>
      <Docs>
        <param name="repairTask">
          <para> <span data-ttu-id="283cd-123">作成する修復タスクの説明です。</span><span class="sxs-lookup"><span data-stu-id="283cd-123">The description of the repair task to be created.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="283cd-124">新しい修復タスクを作成します。</span><span class="sxs-lookup"><span data-stu-id="283cd-124">Creates a new repair task.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="283cd-125">修復の新しく作成されたタスクのバージョン番号。</span><span class="sxs-lookup"><span data-stu-id="283cd-125">The version number of the newly-created repair task.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; CreateRepairTaskAsync (System.Fabric.Repair.RepairTask repairTask, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; CreateRepairTaskAsync(class System.Fabric.Repair.RepairTask repairTask, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.CreateRepairTaskAsync(System.Fabric.Repair.RepairTask,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateRepairTaskAsync : System.Fabric.Repair.RepairTask * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.CreateRepairTaskAsync (repairTask, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTask" Type="System.Fabric.Repair.RepairTask" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="repairTask">
          <para> <span data-ttu-id="283cd-126">作成する修復タスクの説明です。</span><span class="sxs-lookup"><span data-stu-id="283cd-126">The description of the repair task to be created.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="283cd-127">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="283cd-127">The maximum amount of time Service Fabric will allow this operation to continue before returning a<see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para> <span data-ttu-id="283cd-128">操作を確認する省略可能なキャンセル トークン。操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="283cd-128">The optional cancellation token that the operation is observing.It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="283cd-129">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="283cd-129">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="283cd-130">新しい修復タスクを作成します。</span><span class="sxs-lookup"><span data-stu-id="283cd-130">Creates a new repair task.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="283cd-131">修復の新しく作成されたタスクのバージョン番号。</span><span class="sxs-lookup"><span data-stu-id="283cd-131">The version number of the newly-created repair task.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteRepairTaskAsync (string repairTaskId, long version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteRepairTaskAsync(string repairTaskId, int64 version) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.DeleteRepairTaskAsync(System.String,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteRepairTaskAsync (repairTaskId As String, version As Long) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteRepairTaskAsync : string * int64 -&gt; System.Threading.Tasks.Task" Usage="repairManagementClient.DeleteRepairTaskAsync (repairTaskId, version)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para><span data-ttu-id="283cd-132">削除する完了した修復タスクの ID。</span><span class="sxs-lookup"><span data-stu-id="283cd-132">The ID of the completed repair task to be deleted.</span></span></para>
        </param>
        <param name="version">
          <para><span data-ttu-id="283cd-133">修復タスクの現在のバージョン番号。</span><span class="sxs-lookup"><span data-stu-id="283cd-133">The current version number of the repair task.</span></span> <span data-ttu-id="283cd-134">0 以外の場合、要求のみは成功します修復作業の実際の現在の値がこの値に一致する場合。</span><span class="sxs-lookup"><span data-stu-id="283cd-134">If non-zero, then the request will only succeed if this value matches the actual current value of the repair task.</span></span> <span data-ttu-id="283cd-135">0 の場合、バージョン チェックは実行されません。</span><span class="sxs-lookup"><span data-stu-id="283cd-135">If zero, then no version check is performed.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="283cd-136">指定した修復タスクを削除します。</span><span class="sxs-lookup"><span data-stu-id="283cd-136">Deletes the given repair task.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="283cd-137">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="283cd-137">A task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteRepairTaskAsync (string repairTaskId, long version, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteRepairTaskAsync(string repairTaskId, int64 version, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.DeleteRepairTaskAsync(System.String,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteRepairTaskAsync : string * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="repairManagementClient.DeleteRepairTaskAsync (repairTaskId, version, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para><span data-ttu-id="283cd-138">削除する完了した修復タスクの ID。</span><span class="sxs-lookup"><span data-stu-id="283cd-138">The ID of the completed repair task to be deleted.</span></span></para>
        </param>
        <param name="version">
          <para><span data-ttu-id="283cd-139">修復タスクの現在のバージョン番号。</span><span class="sxs-lookup"><span data-stu-id="283cd-139">The current version number of the repair task.</span></span> <span data-ttu-id="283cd-140">0 以外の場合、要求のみは成功します修復作業の実際の現在の値がこの値に一致する場合。</span><span class="sxs-lookup"><span data-stu-id="283cd-140">If non-zero, then the request will only succeed if this value matches the actual current value of the repair task.</span></span> <span data-ttu-id="283cd-141">0 の場合、バージョン チェックは実行されません。</span><span class="sxs-lookup"><span data-stu-id="283cd-141">If zero, then no version check is performed.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="283cd-142">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="283cd-142">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="283cd-143">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="283cd-143">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="283cd-144">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="283cd-144">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="283cd-145">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="283cd-145">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="283cd-146">指定した修復タスクを削除します。</span><span class="sxs-lookup"><span data-stu-id="283cd-146">Deletes the given repair task.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="283cd-147">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="283cd-147">A task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceApproveRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ForceApproveRepairTaskAsync (string repairTaskId, long version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; ForceApproveRepairTaskAsync(string repairTaskId, int64 version) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.ForceApproveRepairTaskAsync(System.String,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function ForceApproveRepairTaskAsync (repairTaskId As String, version As Long) As Task(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ForceApproveRepairTaskAsync : string * int64 -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.ForceApproveRepairTaskAsync (repairTaskId, version)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para><span data-ttu-id="283cd-148">承認修復タスクの ID。</span><span class="sxs-lookup"><span data-stu-id="283cd-148">The ID of the repair task to be approved.</span></span></para>
        </param>
        <param name="version">
          <para><span data-ttu-id="283cd-149">修復タスクの現在のバージョン番号。</span><span class="sxs-lookup"><span data-stu-id="283cd-149">The current version number of the repair task.</span></span> <span data-ttu-id="283cd-150">0 以外の場合、要求のみは成功します修復作業の実際の現在の値がこの値に一致する場合。</span><span class="sxs-lookup"><span data-stu-id="283cd-150">If non-zero, then the request will only succeed if this value matches the actual current value of the repair task.</span></span> <span data-ttu-id="283cd-151">0 の場合、バージョン チェックは実行されません。</span><span class="sxs-lookup"><span data-stu-id="283cd-151">If zero, then no version check is performed.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="283cd-152">指定した修復タスクの承認を強制します。</span><span class="sxs-lookup"><span data-stu-id="283cd-152">Forces the approval of the given repair task.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="283cd-153">修復タスクの新しいバージョン番号。</span><span class="sxs-lookup"><span data-stu-id="283cd-153">The new version number of the repair task.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceApproveRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ForceApproveRepairTaskAsync (string repairTaskId, long version, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; ForceApproveRepairTaskAsync(string repairTaskId, int64 version, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.ForceApproveRepairTaskAsync(System.String,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ForceApproveRepairTaskAsync : string * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.ForceApproveRepairTaskAsync (repairTaskId, version, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para><span data-ttu-id="283cd-154">承認修復タスクの ID。</span><span class="sxs-lookup"><span data-stu-id="283cd-154">The ID of the repair task to be approved.</span></span></para>
        </param>
        <param name="version">
          <para><span data-ttu-id="283cd-155">修復タスクの現在のバージョン番号。</span><span class="sxs-lookup"><span data-stu-id="283cd-155">The current version number of the repair task.</span></span> <span data-ttu-id="283cd-156">0 以外の場合、要求のみは成功します修復作業の実際の現在の値がこの値に一致する場合。</span><span class="sxs-lookup"><span data-stu-id="283cd-156">If non-zero, then the request will only succeed if this value matches the actual current value of the repair task.</span></span> <span data-ttu-id="283cd-157">0 の場合、バージョン チェックは実行されません。</span><span class="sxs-lookup"><span data-stu-id="283cd-157">If zero, then no version check is performed.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="283cd-158">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="283cd-158">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="283cd-159">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="283cd-159">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="283cd-160">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="283cd-160">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="283cd-161">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="283cd-161">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="283cd-162">指定した修復タスクの承認を強制します。</span><span class="sxs-lookup"><span data-stu-id="283cd-162">Forces the approval of the given repair task.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="283cd-163">修復タスクの新しいバージョン番号。</span><span class="sxs-lookup"><span data-stu-id="283cd-163">The new version number of the repair task.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRepairTaskListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.GetRepairTaskListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRepairTaskListAsync () As Task(Of RepairTaskList)" />
      <MemberSignature Language="F#" Value="member this.GetRepairTaskListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;" Usage="repairManagementClient.GetRepairTaskListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="283cd-164">修復のすべてのタスクの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="283cd-164">Gets a list of all repair tasks.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="283cd-165">修復のすべてのタスクの一覧。</span><span class="sxs-lookup"><span data-stu-id="283cd-165">The list of all repair tasks.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRepairTaskListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.GetRepairTaskListAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRepairTaskListAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;" Usage="repairManagementClient.GetRepairTaskListAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para><span data-ttu-id="283cd-166">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="283cd-166">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="283cd-167">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="283cd-167">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="283cd-168">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="283cd-168">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="283cd-169">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="283cd-169">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="283cd-170">修復のすべてのタスクの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="283cd-170">Gets a list of all repair tasks.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="283cd-171">修復のすべてのタスクの一覧。</span><span class="sxs-lookup"><span data-stu-id="283cd-171">The list of all repair tasks.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRepairTaskListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync (string taskIdFilter, System.Fabric.Repair.RepairTaskStateFilter stateFilter, string executorFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync(string taskIdFilter, valuetype System.Fabric.Repair.RepairTaskStateFilter stateFilter, string executorFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.GetRepairTaskListAsync(System.String,System.Fabric.Repair.RepairTaskStateFilter,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRepairTaskListAsync (taskIdFilter As String, stateFilter As RepairTaskStateFilter, executorFilter As String) As Task(Of RepairTaskList)" />
      <MemberSignature Language="F#" Value="member this.GetRepairTaskListAsync : string * System.Fabric.Repair.RepairTaskStateFilter * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;" Usage="repairManagementClient.GetRepairTaskListAsync (taskIdFilter, stateFilter, executorFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="taskIdFilter" Type="System.String" />
        <Parameter Name="stateFilter" Type="System.Fabric.Repair.RepairTaskStateFilter" />
        <Parameter Name="executorFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="taskIdFilter">
          <para><span data-ttu-id="283cd-172">照合される修復タスク ID プレフィックス。</span><span class="sxs-lookup"><span data-stu-id="283cd-172">The repair task ID prefix to be matched.</span></span>  <span data-ttu-id="283cd-173">タスク ID にフィルターが適用されていない null の場合、</span><span class="sxs-lookup"><span data-stu-id="283cd-173">If null, no filter is applied to the task ID.</span></span></para>
        </param>
        <param name="stateFilter">
          <para><span data-ttu-id="283cd-174">タスクの状態を指定する状態フィルター値のビットごとの組み合わせは、リストに含まれる必要があります。</span><span class="sxs-lookup"><span data-stu-id="283cd-174">A bitwise combination of state filter values that specify which task states should be included in the list.</span></span></para>
        </param>
        <param name="executorFilter">
          <para><span data-ttu-id="283cd-175">要求されたタスクが含まれる一覧に含めるか修復の実行子の名前。</span><span class="sxs-lookup"><span data-stu-id="283cd-175">The name of the repair executor whose claimed tasks should be included in the list.</span></span> <span data-ttu-id="283cd-176">Null の場合、実行プログラム名にフィルターは適用されません。</span><span class="sxs-lookup"><span data-stu-id="283cd-176">If null, no filter is applied to the executor name.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="283cd-177">すべての指定したフィルターに一致する修復作業の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="283cd-177">Gets a list of repair tasks matching all of the given filters.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="283cd-178">すべての指定したフィルターに一致する修復作業の一覧。</span><span class="sxs-lookup"><span data-stu-id="283cd-178">The list of repair tasks matching all of the given filters.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRepairTaskListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync (string taskIdFilter, System.Fabric.Repair.RepairTaskStateFilter stateFilter, string executorFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync(string taskIdFilter, valuetype System.Fabric.Repair.RepairTaskStateFilter stateFilter, string executorFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.GetRepairTaskListAsync(System.String,System.Fabric.Repair.RepairTaskStateFilter,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRepairTaskListAsync : string * System.Fabric.Repair.RepairTaskStateFilter * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;" Usage="repairManagementClient.GetRepairTaskListAsync (taskIdFilter, stateFilter, executorFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="taskIdFilter" Type="System.String" />
        <Parameter Name="stateFilter" Type="System.Fabric.Repair.RepairTaskStateFilter" />
        <Parameter Name="executorFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="taskIdFilter">
          <para><span data-ttu-id="283cd-179">照合される修復タスク ID プレフィックス。</span><span class="sxs-lookup"><span data-stu-id="283cd-179">The repair task ID prefix to be matched.</span></span>  <span data-ttu-id="283cd-180">タスク ID にフィルターが適用されていない null の場合、</span><span class="sxs-lookup"><span data-stu-id="283cd-180">If null, no filter is applied to the task ID.</span></span></para>
        </param>
        <param name="stateFilter">
          <para><span data-ttu-id="283cd-181">タスクの状態を指定する状態フィルター値のビットごとの組み合わせは、リストに含まれる必要があります。</span><span class="sxs-lookup"><span data-stu-id="283cd-181">A bitwise combination of state filter values that specify which task states should be included in the list.</span></span></para>
        </param>
        <param name="executorFilter">
          <para><span data-ttu-id="283cd-182">要求されたタスクが含まれる一覧に含めるか修復の実行子の名前。</span><span class="sxs-lookup"><span data-stu-id="283cd-182">The name of the repair executor whose claimed tasks should be included in the list.</span></span> <span data-ttu-id="283cd-183">Null の場合、実行プログラム名にフィルターは適用されません。</span><span class="sxs-lookup"><span data-stu-id="283cd-183">If null, no filter is applied to the executor name.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="283cd-184">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="283cd-184">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="283cd-185">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="283cd-185">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="283cd-186">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="283cd-186">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="283cd-187">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="283cd-187">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="283cd-188">すべての指定したフィルターに一致する修復作業の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="283cd-188">Gets a list of repair tasks matching all of the given filters.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="283cd-189">すべての指定したフィルターに一致する修復作業の一覧。</span><span class="sxs-lookup"><span data-stu-id="283cd-189">The list of repair tasks matching all of the given filters.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateRepairExecutionStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; UpdateRepairExecutionStateAsync (System.Fabric.Repair.RepairTask repairTask);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; UpdateRepairExecutionStateAsync(class System.Fabric.Repair.RepairTask repairTask) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.UpdateRepairExecutionStateAsync(System.Fabric.Repair.RepairTask)" />
      <MemberSignature Language="F#" Value="member this.UpdateRepairExecutionStateAsync : System.Fabric.Repair.RepairTask -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.UpdateRepairExecutionStateAsync repairTask" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTask" Type="System.Fabric.Repair.RepairTask" />
      </Parameters>
      <Docs>
        <param name="repairTask"><span data-ttu-id="283cd-190">変更後の修復作業します。</span><span class="sxs-lookup"><span data-stu-id="283cd-190">The modified repair task.</span></span></param>
        <summary>
            <span data-ttu-id="283cd-191">修復タスクを更新します。</span><span class="sxs-lookup"><span data-stu-id="283cd-191">Updates a repair task.</span></span>
            </summary>
        <returns>
          <para><span data-ttu-id="283cd-192">修復タスクの新しいバージョン番号。</span><span class="sxs-lookup"><span data-stu-id="283cd-192">The new version number of the repair task.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateRepairExecutionStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; UpdateRepairExecutionStateAsync (System.Fabric.Repair.RepairTask repairTask, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; UpdateRepairExecutionStateAsync(class System.Fabric.Repair.RepairTask repairTask, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.UpdateRepairExecutionStateAsync(System.Fabric.Repair.RepairTask,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpdateRepairExecutionStateAsync : System.Fabric.Repair.RepairTask * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.UpdateRepairExecutionStateAsync (repairTask, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTask" Type="System.Fabric.Repair.RepairTask" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="repairTask"><span data-ttu-id="283cd-193">変更後の修復作業します。</span><span class="sxs-lookup"><span data-stu-id="283cd-193">The modified repair task.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="283cd-194">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="283cd-194">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="283cd-195">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="283cd-195">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="283cd-196">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="283cd-196">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="283cd-197">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="283cd-197">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="283cd-198">修復タスクを更新します。</span><span class="sxs-lookup"><span data-stu-id="283cd-198">Updates a repair task.</span></span>
            </summary>
        <returns>
          <para><span data-ttu-id="283cd-199">修復タスクの新しいバージョン番号。</span><span class="sxs-lookup"><span data-stu-id="283cd-199">The new version number of the repair task.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateRepairTaskHealthPolicyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; UpdateRepairTaskHealthPolicyAsync (string repairTaskId, long version, Nullable&lt;bool&gt; performPreparingHealthCheck, Nullable&lt;bool&gt; performRestoringHealthCheck);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; UpdateRepairTaskHealthPolicyAsync(string repairTaskId, int64 version, valuetype System.Nullable`1&lt;bool&gt; performPreparingHealthCheck, valuetype System.Nullable`1&lt;bool&gt; performRestoringHealthCheck) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.UpdateRepairTaskHealthPolicyAsync(System.String,System.Int64,System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateRepairTaskHealthPolicyAsync (repairTaskId As String, version As Long, performPreparingHealthCheck As Nullable(Of Boolean), performRestoringHealthCheck As Nullable(Of Boolean)) As Task(Of Long)" />
      <MemberSignature Language="F#" Value="member this.UpdateRepairTaskHealthPolicyAsync : string * int64 * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.UpdateRepairTaskHealthPolicyAsync (repairTaskId, version, performPreparingHealthCheck, performRestoringHealthCheck)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
        <Parameter Name="performPreparingHealthCheck" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="performRestoringHealthCheck" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para><span data-ttu-id="283cd-200">正常性ポリシーが更新される修復タスクの ID。</span><span class="sxs-lookup"><span data-stu-id="283cd-200">The ID of the repair task for which the health policy is to be updated.</span></span></para>
        </param>
        <param name="version">
          <para><span data-ttu-id="283cd-201">修復タスクの現在のバージョン番号。</span><span class="sxs-lookup"><span data-stu-id="283cd-201">The current version number of the repair task.</span></span> <span data-ttu-id="283cd-202">0 以外の場合、要求のみは成功します修復作業の実際の現在の値がこの値に一致する場合。</span><span class="sxs-lookup"><span data-stu-id="283cd-202">If non-zero, then the request will only succeed if this value matches the actual current value of the repair task.</span></span> <span data-ttu-id="283cd-203">0 の場合、バージョン チェックは実行されません。</span><span class="sxs-lookup"><span data-stu-id="283cd-203">If zero, then no version check is performed.</span></span></para>
        </param>
        <param name="performPreparingHealthCheck">
          <para>
            <span data-ttu-id="283cd-204">正常性チェックが修復作業の準備段階で実行するかどうかを示す null 許容のブール値。</span><span class="sxs-lookup"><span data-stu-id="283cd-204">A nullable boolean indicating if health check is to be performed in the Preparing stage of the repair task.</span></span>
            <span data-ttu-id="283cd-205">指定<c>null</c>このパラメーターの場合は、既存の値を変更しないようにします。</span><span class="sxs-lookup"><span data-stu-id="283cd-205">Specify <c>null</c> for this parameter if the existing value should not be altered.</span></span> <span data-ttu-id="283cd-206">それ以外の場合、目的の新しい値を指定します。</span><span class="sxs-lookup"><span data-stu-id="283cd-206">Otherwise, specify the desired new value.</span></span> 
            </para>
        </param>
        <param name="performRestoringHealthCheck">
          <para>
            <span data-ttu-id="283cd-207">正常性チェックが修復作業の復元段階で実行するかどうかを示す null 許容のブール値。</span><span class="sxs-lookup"><span data-stu-id="283cd-207">A nullable boolean indicating if health check is to be performed in the Restoring stage of the repair task.</span></span>
            <span data-ttu-id="283cd-208">指定<c>null</c>このパラメーターの場合は、既存の値を変更しないようにします。</span><span class="sxs-lookup"><span data-stu-id="283cd-208">Specify <c>null</c> for this parameter if the existing value should not be altered.</span></span> <span data-ttu-id="283cd-209">それ以外の場合、目的の新しい値を指定します。</span><span class="sxs-lookup"><span data-stu-id="283cd-209">Otherwise, specify the desired new value.</span></span> 
            </para>
        </param>
        <summary>
          <para><span data-ttu-id="283cd-210">指定した修復タスクの正常性ポリシーを更新します。</span><span class="sxs-lookup"><span data-stu-id="283cd-210">Updates the health policy of the given repair task.</span></span></para>
        </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateRepairTaskHealthPolicyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; UpdateRepairTaskHealthPolicyAsync (string repairTaskId, long version, Nullable&lt;bool&gt; performPreparingHealthCheck, Nullable&lt;bool&gt; performRestoringHealthCheck, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; UpdateRepairTaskHealthPolicyAsync(string repairTaskId, int64 version, valuetype System.Nullable`1&lt;bool&gt; performPreparingHealthCheck, valuetype System.Nullable`1&lt;bool&gt; performRestoringHealthCheck, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.UpdateRepairTaskHealthPolicyAsync(System.String,System.Int64,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpdateRepairTaskHealthPolicyAsync : string * int64 * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.UpdateRepairTaskHealthPolicyAsync (repairTaskId, version, performPreparingHealthCheck, performRestoringHealthCheck, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
        <Parameter Name="performPreparingHealthCheck" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="performRestoringHealthCheck" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para><span data-ttu-id="283cd-211">正常性ポリシーが更新される修復タスクの ID。</span><span class="sxs-lookup"><span data-stu-id="283cd-211">The ID of the repair task for which the health policy is to be updated.</span></span></para>
        </param>
        <param name="version">
          <para><span data-ttu-id="283cd-212">修復タスクの現在のバージョン番号。</span><span class="sxs-lookup"><span data-stu-id="283cd-212">The current version number of the repair task.</span></span> <span data-ttu-id="283cd-213">0 以外の場合、要求のみは成功します修復作業の実際の現在の値がこの値に一致する場合。</span><span class="sxs-lookup"><span data-stu-id="283cd-213">If non-zero, then the request will only succeed if this value matches the actual current value of the repair task.</span></span> <span data-ttu-id="283cd-214">0 の場合、バージョン チェックは実行されません。</span><span class="sxs-lookup"><span data-stu-id="283cd-214">If zero, then no version check is performed.</span></span></para>
        </param>
        <param name="performPreparingHealthCheck">
          <para>
            <span data-ttu-id="283cd-215">正常性チェックが修復作業の準備段階で実行するかどうかを示す null 許容のブール値。</span><span class="sxs-lookup"><span data-stu-id="283cd-215">A nullable boolean indicating if health check is to be performed in the Preparing stage of the repair task.</span></span>
            <span data-ttu-id="283cd-216">指定<c>null</c>このパラメーターの場合は、既存の値を変更しないようにします。</span><span class="sxs-lookup"><span data-stu-id="283cd-216">Specify <c>null</c> for this parameter if the existing value should not be altered.</span></span> <span data-ttu-id="283cd-217">それ以外の場合、適切な指定<c>bool</c>値。</span><span class="sxs-lookup"><span data-stu-id="283cd-217">Else, specify the appropriate <c>bool</c> value.</span></span> 
            </para>
        </param>
        <param name="performRestoringHealthCheck">
          <para>
            <span data-ttu-id="283cd-218">正常性チェックが修復作業の復元段階で実行するかどうかを示す null 許容のブール値。</span><span class="sxs-lookup"><span data-stu-id="283cd-218">A nullable boolean indicating if health check is to be performed in the Restoring stage of the repair task.</span></span>
            <span data-ttu-id="283cd-219">指定<c>null</c>このパラメーターの場合は、既存の値を変更しないようにします。</span><span class="sxs-lookup"><span data-stu-id="283cd-219">Specify <c>null</c> for this parameter if the existing value should not be altered.</span></span> <span data-ttu-id="283cd-220">それ以外の場合、適切な指定<c>bool</c>値。</span><span class="sxs-lookup"><span data-stu-id="283cd-220">Else, specify the appropriate <c>bool</c> value.</span></span> 
            </para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="283cd-221">時間の最大量 Service Fabric を返す前に続行するには、この操作は許可されます、<see cref="T:System.TimeoutException" />です。</span><span class="sxs-lookup"><span data-stu-id="283cd-221">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="283cd-222">操作を確認する省略可能なキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="283cd-222">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="283cd-223">操作を取り消す必要がある通知を送信するために使用します。</span><span class="sxs-lookup"><span data-stu-id="283cd-223">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="283cd-224">キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</span><span class="sxs-lookup"><span data-stu-id="283cd-224">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="283cd-225">指定した修復タスクの正常性ポリシーを更新します。</span><span class="sxs-lookup"><span data-stu-id="283cd-225">Updates the health policy of the given repair task.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="283cd-226">非同期操作を表すタスク。</span><span class="sxs-lookup"><span data-stu-id="283cd-226">A task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>