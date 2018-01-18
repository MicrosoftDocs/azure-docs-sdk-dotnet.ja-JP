<Type Name="FabricClient+TestManagementClient" FullName="System.Fabric.FabricClient+TestManagementClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.TestManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/TestManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.TestManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.TestManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.TestManagementClient = class" />
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
      <para><span data-ttu-id="f599e-101">発行し、テスト コマンドを制御するためのメソッドを提供します。</span><span class="sxs-lookup"><span data-stu-id="f599e-101">Provides methods for issuing and controlling test commands.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CancelTestCommandAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelTestCommandAsync (Guid operationId, bool force);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelTestCommandAsync(valuetype System.Guid operationId, bool force) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.CancelTestCommandAsync(System.Guid,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelTestCommandAsync (operationId As Guid, force As Boolean) As Task" />
      <MemberSignature Language="F#" Value="member this.CancelTestCommandAsync : Guid * bool -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.CancelTestCommandAsync (operationId, force)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="force" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="f599e-102">テスト コマンドを取り消すの operationId を示します。</span><span class="sxs-lookup"><span data-stu-id="f599e-102">Indicates the operationId of the test command to cancel.</span></span></param>
        <param name="force"><span data-ttu-id="f599e-103">正常にロールバックして、内部システム状態をクリーンアップがテスト コマンドを実行することによって変更するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="f599e-103">Indicates whether to gracefully rollback and clean up internal system state modified by executing the test command.</span></span>  <span data-ttu-id="f599e-104">「解説」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f599e-104">See Remarks.</span></span></param>
        <summary>
            <span data-ttu-id="f599e-105">テスト コマンドを取り消します。</span><span class="sxs-lookup"><span data-stu-id="f599e-105">Cancels a test command.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-106">タスク。</span><span class="sxs-lookup"><span data-stu-id="f599e-106">A Task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-107">Force が false の場合、指定されたテスト コマンド適切を停止し、クリーンアップします。</span><span class="sxs-lookup"><span data-stu-id="f599e-107">If force is false, then the specified test command will be gracefully stopped and cleaned up.</span></span>  <span data-ttu-id="f599e-108">Force が true の場合は、コマンドは中止され、何らかの内部状態の残る可能性があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-108">If force is true, the command will be aborted, and some internal state may be left behind.</span></span>  <span data-ttu-id="f599e-109">True として force を指定することは、注意して使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-109">Specifying force as true should be used with care.</span></span>  <span data-ttu-id="f599e-110">CancelTestCommandAsync() が false の最初に強制セットで同じテスト コマンドで呼び出されるまで、またはテスト コマンドには既にの TestCommandProgressState を除き、true に設定された force 通話 CancelTestCommandAsync() は許可されていませんTestCommandProgressState.RollingBack です。</span><span class="sxs-lookup"><span data-stu-id="f599e-110">Calling CancelTestCommandAsync() with force set to true is not allowed until CancelTestCommandAsync() has been called on the same test command with force set to false first, or unless the test command already has a TestCommandProgressState of TestCommandProgressState.RollingBack.</span></span>
            <span data-ttu-id="f599e-111">説明: TestCommandProgressState.RollingBack では、システムは/コマンドを実行しての原因となった内部システム状態をクリーンアップします。</span><span class="sxs-lookup"><span data-stu-id="f599e-111">Clarification: TestCommandProgressState.RollingBack means that the system will/is cleaning up internal system state caused by executing the command.</span></span>  <span data-ttu-id="f599e-112">テスト コマンドのデータの損失が発生する場合のデータは復元されません。</span><span class="sxs-lookup"><span data-stu-id="f599e-112">It will not restore data if the test command was to cause data loss.</span></span>  <span data-ttu-id="f599e-113">たとえば、StartPartitionDataLossAsync() を呼び出す場合は CancelTestCommandAsync() を呼び出して、システムはコマンドを実行してから内部状態をクリーンアップのみ。</span><span class="sxs-lookup"><span data-stu-id="f599e-113">For example, if you call StartPartitionDataLossAsync() then call CancelTestCommandAsync() the system will only clean up internal state from running the command.</span></span>  
            <span data-ttu-id="f599e-114">コマンドが進行して十分なデータの損失が発生する場合、ターゲット パーティションのデータは復元されません。</span><span class="sxs-lookup"><span data-stu-id="f599e-114">It will not restore the target partition's data, if the command progressed far enough to cause data loss.</span></span>
            
            
            </para>
          <para>
            <span data-ttu-id="f599e-115">重要な注意事項: この API は強制的に起動された場合の = = true、内部の状態の残る可能性があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-115">Important note:  if this API is invoked with force==true, internal state may be left behind.</span></span>  <span data-ttu-id="f599e-116">残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-116">CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-117">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-117">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelTestCommandAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelTestCommandAsync (Guid operationId, bool force, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelTestCommandAsync(valuetype System.Guid operationId, bool force, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.CancelTestCommandAsync(System.Guid,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CancelTestCommandAsync : Guid * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.CancelTestCommandAsync (operationId, force, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="force" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="f599e-118">テスト コマンドを取り消すの operationId を示します。</span><span class="sxs-lookup"><span data-stu-id="f599e-118">Indicates the operationId of the test command to cancel.</span></span></param>
        <param name="force"><span data-ttu-id="f599e-119">正常にロールバックして、内部システム状態をクリーンアップがテスト コマンドを実行することによって変更するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="f599e-119">Indicates whether to gracefully rollback and clean up internal system state modified by executing the test command.</span></span>  <span data-ttu-id="f599e-120">「解説」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f599e-120">See Remarks.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-121">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-121">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-122">テスト コマンドを取り消します。</span><span class="sxs-lookup"><span data-stu-id="f599e-122">Cancels a test command.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-123">タスク。</span><span class="sxs-lookup"><span data-stu-id="f599e-123">A Task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-124">Force が false の場合、指定されたテスト コマンド適切を停止し、クリーンアップします。</span><span class="sxs-lookup"><span data-stu-id="f599e-124">If force is false, then the specified test command will be gracefully stopped and cleaned up.</span></span>  <span data-ttu-id="f599e-125">Force が true の場合は、コマンドは中止され、何らかの内部状態の残る可能性があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-125">If force is true, the command will be aborted, and some internal state may be left behind.</span></span>  <span data-ttu-id="f599e-126">True として force を指定することは、注意して使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-126">Specifying force as true should be used with care.</span></span>  <span data-ttu-id="f599e-127">CancelTestCommandAsync() が false の最初に強制セットで同じテスト コマンドで呼び出されるまで、またはテスト コマンドには既にの TestCommandProgressState を除き、true に設定された force 通話 CancelTestCommandAsync() は許可されていませんTestCommandProgressState.RollingBack です。</span><span class="sxs-lookup"><span data-stu-id="f599e-127">Calling CancelTestCommandAsync() with force set to true is not allowed until CancelTestCommandAsync() has been called on the same test command with force set to false first, or unless the test command already has a TestCommandProgressState of TestCommandProgressState.RollingBack.</span></span>
            <span data-ttu-id="f599e-128">説明: TestCommandProgressState.RollingBack では、システムは/コマンドを実行しての原因となった内部システム状態をクリーンアップします。</span><span class="sxs-lookup"><span data-stu-id="f599e-128">Clarification: TestCommandProgressState.RollingBack means that the system will/is cleaning up internal system state caused by executing the command.</span></span>  <span data-ttu-id="f599e-129">テスト コマンドのデータの損失が発生する場合のデータは復元されません。</span><span class="sxs-lookup"><span data-stu-id="f599e-129">It will not restore data if the test command was to cause data loss.</span></span>  <span data-ttu-id="f599e-130">たとえば、StartPartitionDataLossAsync() を呼び出す場合は CancelTestCommandAsync() を呼び出して、システムはコマンドを実行してから内部状態をクリーンアップのみ。</span><span class="sxs-lookup"><span data-stu-id="f599e-130">For example, if you call StartPartitionDataLossAsync() then call CancelTestCommandAsync() the system will only clean up internal state from running the command.</span></span>  
            <span data-ttu-id="f599e-131">コマンドが進行して十分なデータの損失が発生する場合、ターゲット パーティションのデータは復元されません。</span><span class="sxs-lookup"><span data-stu-id="f599e-131">It will not restore the target partition's data, if the command progressed far enough to cause data loss.</span></span>
            
            
            
            </para>
          <para>
            <span data-ttu-id="f599e-132">重要な注意事項: この API は強制的に起動された場合の = = true、内部の状態の残る可能性があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-132">Important note:  if this API is invoked with force==true, internal state may be left behind.</span></span>  <span data-ttu-id="f599e-133">残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-133">CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-134">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-134">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelTestCommandAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelTestCommandAsync (Guid operationId, bool force, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelTestCommandAsync(valuetype System.Guid operationId, bool force, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.CancelTestCommandAsync(System.Guid,System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelTestCommandAsync (operationId As Guid, force As Boolean, timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="member this.CancelTestCommandAsync : Guid * bool * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.CancelTestCommandAsync (operationId, force, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="force" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="f599e-135">テスト コマンドを取り消すの operationId を示します。</span><span class="sxs-lookup"><span data-stu-id="f599e-135">Indicates the operationId of the test command to cancel.</span></span></param>
        <param name="force"><span data-ttu-id="f599e-136">正常にロールバックして、内部システム状態をクリーンアップがテスト コマンドを実行することによって変更するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="f599e-136">Indicates whether to gracefully rollback and clean up internal system state modified by executing the test command.</span></span>  <span data-ttu-id="f599e-137">「解説」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f599e-137">See Remarks.</span></span></param>
        <param name="timeout"><span data-ttu-id="f599e-138">API の呼び出しを使用するタイムアウト値。</span><span class="sxs-lookup"><span data-stu-id="f599e-138">The timeout to use for the API call.</span></span></param>
        <summary>
            <span data-ttu-id="f599e-139">テスト コマンドを取り消します。</span><span class="sxs-lookup"><span data-stu-id="f599e-139">Cancels a test command.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-140">タスク。</span><span class="sxs-lookup"><span data-stu-id="f599e-140">A Task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-141">Force が false の場合、指定されたテスト コマンド適切を停止し、クリーンアップします。</span><span class="sxs-lookup"><span data-stu-id="f599e-141">If force is false, then the specified test command will be gracefully stopped and cleaned up.</span></span>  <span data-ttu-id="f599e-142">Force が true の場合は、コマンドは中止され、何らかの内部状態の残る可能性があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-142">If force is true, the command will be aborted, and some internal state may be left behind.</span></span>  <span data-ttu-id="f599e-143">True として force を指定することは、注意して使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-143">Specifying force as true should be used with care.</span></span>  <span data-ttu-id="f599e-144">CancelTestCommandAsync() が false の最初に強制セットで同じテスト コマンドで呼び出されるまで、またはテスト コマンドには既にの TestCommandProgressState を除き、true に設定された force 通話 CancelTestCommandAsync() は許可されていませんTestCommandProgressState.RollingBack です。</span><span class="sxs-lookup"><span data-stu-id="f599e-144">Calling CancelTestCommandAsync() with force set to true is not allowed until CancelTestCommandAsync() has been called on the same test command with force set to false first, or unless the test command already has a TestCommandProgressState of TestCommandProgressState.RollingBack.</span></span>
            <span data-ttu-id="f599e-145">説明: TestCommandProgressState.RollingBack では、システムは/コマンドを実行しての原因となった内部システム状態をクリーンアップします。</span><span class="sxs-lookup"><span data-stu-id="f599e-145">Clarification: TestCommandProgressState.RollingBack means that the system will/is cleaning up internal system state caused by executing the command.</span></span>  <span data-ttu-id="f599e-146">テスト コマンドのデータの損失が発生する場合のデータは復元されません。</span><span class="sxs-lookup"><span data-stu-id="f599e-146">It will not restore data if the test command was to cause data loss.</span></span>  <span data-ttu-id="f599e-147">たとえば、StartPartitionDataLossAsync() を呼び出す場合は CancelTestCommandAsync() を呼び出して、システムはコマンドを実行してから内部状態をクリーンアップのみ。</span><span class="sxs-lookup"><span data-stu-id="f599e-147">For example, if you call StartPartitionDataLossAsync() then call CancelTestCommandAsync() the system will only clean up internal state from running the command.</span></span>  
            <span data-ttu-id="f599e-148">コマンドが進行して十分なデータの損失が発生する場合、ターゲット パーティションのデータは復元されません。</span><span class="sxs-lookup"><span data-stu-id="f599e-148">It will not restore the target partition's data, if the command progressed far enough to cause data loss.</span></span>
            
            
            
            </para>
          <para>
            <span data-ttu-id="f599e-149">重要な注意事項: この API は強制的に起動された場合の = = true、内部の状態の残る可能性があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-149">Important note:  if this API is invoked with force==true, internal state may be left behind.</span></span>  <span data-ttu-id="f599e-150">残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-150">CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-151">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-151">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelTestCommandAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelTestCommandAsync (Guid operationId, bool force, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelTestCommandAsync(valuetype System.Guid operationId, bool force, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.CancelTestCommandAsync(System.Guid,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CancelTestCommandAsync : Guid * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.CancelTestCommandAsync (operationId, force, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="force" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="f599e-152">テスト コマンドを取り消すの operationId を示します。</span><span class="sxs-lookup"><span data-stu-id="f599e-152">Indicates the operationId of the test command to cancel.</span></span></param>
        <param name="force"><span data-ttu-id="f599e-153">正常にロールバックして、内部システム状態をクリーンアップがテスト コマンドを実行することによって変更するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="f599e-153">Indicates whether to gracefully rollback and clean up internal system state modified by executing the test command.</span></span>  <span data-ttu-id="f599e-154">「解説」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f599e-154">See Remarks.</span></span></param>
        <param name="timeout"><span data-ttu-id="f599e-155">API の呼び出しを使用するタイムアウト値。</span><span class="sxs-lookup"><span data-stu-id="f599e-155">The timeout to use for the API call.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-156">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-156">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-157">テスト コマンドを取り消します。</span><span class="sxs-lookup"><span data-stu-id="f599e-157">Cancels a test command.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-158">タスク。</span><span class="sxs-lookup"><span data-stu-id="f599e-158">A Task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-159">Force が false の場合、指定されたテスト コマンド適切を停止し、クリーンアップします。</span><span class="sxs-lookup"><span data-stu-id="f599e-159">If force is false, then the specified test command will be gracefully stopped and cleaned up.</span></span>  <span data-ttu-id="f599e-160">Force が true の場合は、コマンドは中止され、何らかの内部状態の残る可能性があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-160">If force is true, the command will be aborted, and some internal state may be left behind.</span></span>  <span data-ttu-id="f599e-161">True として force を指定することは、注意して使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-161">Specifying force as true should be used with care.</span></span>  <span data-ttu-id="f599e-162">CancelTestCommandAsync() が false の最初に強制セットで同じテスト コマンドで呼び出されるまで、またはテスト コマンドには既にの TestCommandProgressState を除き、true に設定された force 通話 CancelTestCommandAsync() は許可されていませんTestCommandProgressState.RollingBack です。</span><span class="sxs-lookup"><span data-stu-id="f599e-162">Calling CancelTestCommandAsync() with force set to true is not allowed until CancelTestCommandAsync() has been called on the same test command with force set to false first, or unless the test command already has a TestCommandProgressState of TestCommandProgressState.RollingBack.</span></span>
            <span data-ttu-id="f599e-163">説明: TestCommandProgressState.RollingBack では、システムは/コマンドを実行しての原因となった内部システム状態をクリーンアップします。</span><span class="sxs-lookup"><span data-stu-id="f599e-163">Clarification: TestCommandProgressState.RollingBack means that the system will/is cleaning up internal system state caused by executing the command.</span></span>  <span data-ttu-id="f599e-164">テスト コマンドのデータの損失が発生する場合のデータは復元されません。</span><span class="sxs-lookup"><span data-stu-id="f599e-164">It will not restore data if the test command was to cause data loss.</span></span>  <span data-ttu-id="f599e-165">たとえば、StartPartitionDataLossAsync() を呼び出す場合は CancelTestCommandAsync() を呼び出して、システムはコマンドを実行してから内部状態をクリーンアップのみ。</span><span class="sxs-lookup"><span data-stu-id="f599e-165">For example, if you call StartPartitionDataLossAsync() then call CancelTestCommandAsync() the system will only clean up internal state from running the command.</span></span>  
            <span data-ttu-id="f599e-166">コマンドが進行して十分なデータの損失が発生する場合、ターゲット パーティションのデータは復元されません。</span><span class="sxs-lookup"><span data-stu-id="f599e-166">It will not restore the target partition's data, if the command progressed far enough to cause data loss.</span></span>
            
            
            
            </para>
          <para>
            <span data-ttu-id="f599e-167">重要な注意事項: この API は強制的に起動された場合の = = true、内部の状態の残る可能性があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-167">Important note:  if this API is invoked with force==true, internal state may be left behind.</span></span>  <span data-ttu-id="f599e-168">残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-168">CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-169">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-169">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CleanTestStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CleanTestStateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CleanTestStateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.CleanTestStateAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CleanTestStateAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.CleanTestStateAsync : unit -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.CleanTestStateAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f599e-170">クラスターのすべてのテストの状態をクリーンアップします。</span><span class="sxs-lookup"><span data-stu-id="f599e-170">Cleans up all the test state in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-171">タスク</span><span class="sxs-lookup"><span data-stu-id="f599e-171">Task</span></span></returns>
        <remarks>
            <span data-ttu-id="f599e-172">フォールト操作; に設定されているクラスター内のすべてのテスト状態をクリーンアップします。StopNode と同様に、またはテスト ドライバーが処理するかどうかは死亡またはクラスターが通常の状態に戻すことを確認する飛行中に、操作が取り消されるこれらの操作の失敗した場合は InvokeDataLoss、RestartPartition および InvokeQuorumLoss この API を呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-172">Cleans up all the test state in the cluster which has been set for fault operations; like StopNode, InvokeDataLoss, RestartPartition and InvokeQuorumLoss This API should be called if any of these operations fail or if the test driver process dies or an operation is canceled while in flight to ensure that the cluster is back into the normal state.</span></span> <span data-ttu-id="f599e-173">通常のすべてのエラー操作 CleanTestState のみ呼び出す必要がある場合は、API 操作が中断されるため、API の実行の終了時の状態をクリーンアップします。</span><span class="sxs-lookup"><span data-stu-id="f599e-173">Normally all the fault operations clean up their state at the end of the execution of the API so CleanTestState only needs to be called if the API operation is interrupted.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-174">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-174">Action took more than its allocated time.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CleanTestStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CleanTestStateAsync (TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CleanTestStateAsync(valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.CleanTestStateAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function CleanTestStateAsync (operationTimeout As TimeSpan, token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="member this.CleanTestStateAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.CleanTestStateAsync (operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationTimeout"><span data-ttu-id="f599e-175">操作の全体的なタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="f599e-175">The overall timeout for the operation.</span></span></param>
        <param name="token"><span data-ttu-id="f599e-176">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-176">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-177">クラスターのすべてのテストの状態をクリーンアップします。</span><span class="sxs-lookup"><span data-stu-id="f599e-177">Cleans up all the test state in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-178">タスク</span><span class="sxs-lookup"><span data-stu-id="f599e-178">Task</span></span></returns>
        <remarks>
            <span data-ttu-id="f599e-179">これらの操作が失敗した場合は、フォールト操作で、InvokeDataLoss、RestartPartition および InvokeQuorumLoss この API に設定されているクラスター内のテストの状態を呼び出す必要がありますすべてがクリーンアップ テスト ドライバーのプロセスが停止または操作が取り消されたかどうか、または中フライト クラスターが通常の状態に戻すことを確認します。</span><span class="sxs-lookup"><span data-stu-id="f599e-179">Cleans up all the test state in the cluster which has been set for fault operations, InvokeDataLoss, RestartPartition and InvokeQuorumLoss This API should be called if any of these operations fail or if the test driver process dies or an operation is canceled while in flight to ensure that the cluster is back into the normal state.</span></span> <span data-ttu-id="f599e-180">通常のすべてのエラー操作 CleanTestState のみ呼び出す必要がある場合は、API 操作が中断されるため、API の実行の終了時の状態をクリーンアップします。</span><span class="sxs-lookup"><span data-stu-id="f599e-180">Normally all the fault operations clean up their state at the end of the execution of the API so CleanTestState only needs to be called if the API operation is interrupted .</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-181">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-181">Action took more than its allocated time.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetChaosReportAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync (System.Fabric.Chaos.DataStructures.ChaosReportFilter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync(class System.Fabric.Chaos.DataStructures.ChaosReportFilter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetChaosReportAsync(System.Fabric.Chaos.DataStructures.ChaosReportFilter)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetChaosReportAsync (filter As ChaosReportFilter) As Task(Of ChaosReport)" />
      <MemberSignature Language="F#" Value="member this.GetChaosReportAsync : System.Fabric.Chaos.DataStructures.ChaosReportFilter -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;" Usage="testManagementClient.GetChaosReportAsync filter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.Fabric.Chaos.DataStructures.ChaosReportFilter" />
      </Parameters>
      <Docs>
        <param name="filter"><span data-ttu-id="f599e-182">フィルター処理、<see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />レポートに含まれる秒です。</span><span class="sxs-lookup"><span data-stu-id="f599e-182">Filter for the <see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />s to be included in the report.</span></span></param>
        <summary>
            <span data-ttu-id="f599e-183">Chaos 実行のレポートを取得します。</span><span class="sxs-lookup"><span data-stu-id="f599e-183">Retrieves the report of Chaos runs.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-184">御礼状レポートを実行します。</span><span class="sxs-lookup"><span data-stu-id="f599e-184">Report of Chaos runs.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-185">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-185">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="f599e-186">これらは Service Fabric の例外と、次のエラー コードを検査する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-186">These are Service Fabric exceptions and the following error codes should be inspected.</span></span>
            <span data-ttu-id="f599e-187">FabricErrorCode.NotReady - Chaos を開始する前にこの API が呼び出された場合。</span><span class="sxs-lookup"><span data-stu-id="f599e-187">FabricErrorCode.NotReady - if this API is called before starting Chaos.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetChaosReportAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync (string continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync(string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetChaosReportAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetChaosReportAsync (continuationToken As String) As Task(Of ChaosReport)" />
      <MemberSignature Language="F#" Value="member this.GetChaosReportAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;" Usage="testManagementClient.GetChaosReportAsync continuationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="continuationToken"><span data-ttu-id="f599e-188">継続トークンの一覧については<see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />内、<see cref="T:System.Fabric.Chaos.DataStructures.ChaosReport" />です。</span><span class="sxs-lookup"><span data-stu-id="f599e-188">Continuation token for the list of <see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />s in the <see cref="T:System.Fabric.Chaos.DataStructures.ChaosReport" />.</span></span></param>
        <summary>
            <span data-ttu-id="f599e-189">Chaos 実行のレポートを取得します。</span><span class="sxs-lookup"><span data-stu-id="f599e-189">Retrieves the report of Chaos runs.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-190">御礼状レポートを実行します。</span><span class="sxs-lookup"><span data-stu-id="f599e-190">Report of Chaos runs.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-191">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="f599e-191">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="f599e-192">これらは Service Fabric の例外と、次のエラー コードを検査する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-192">These are Service Fabric exceptions and the following error codes should be inspected.</span></span>
            <span data-ttu-id="f599e-193">FabricErrorCode.NotReady - Chaos を開始する前にこの API が呼び出された場合。</span><span class="sxs-lookup"><span data-stu-id="f599e-193">FabricErrorCode.NotReady - if this API is called before starting Chaos.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetChaosReportAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync (System.Fabric.Chaos.DataStructures.ChaosReportFilter filter, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync(class System.Fabric.Chaos.DataStructures.ChaosReportFilter filter, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetChaosReportAsync(System.Fabric.Chaos.DataStructures.ChaosReportFilter,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetChaosReportAsync : System.Fabric.Chaos.DataStructures.ChaosReportFilter * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;" Usage="testManagementClient.GetChaosReportAsync (filter, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.Fabric.Chaos.DataStructures.ChaosReportFilter" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="filter"><span data-ttu-id="f599e-194">フィルター処理、<see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />に含まれる秒、<see cref="T:System.Fabric.Chaos.DataStructures.ChaosReport" />です。</span><span class="sxs-lookup"><span data-stu-id="f599e-194">Filter for the <see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />s to be included in the <see cref="T:System.Fabric.Chaos.DataStructures.ChaosReport" />.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="f599e-195">操作の全体的なタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="f599e-195">The overall timeout for the operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-196">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f599e-196">Cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="f599e-197">Chaos 実行のレポートを取得します。</span><span class="sxs-lookup"><span data-stu-id="f599e-197">Retrieves the report of Chaos runs.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-198">御礼状レポートを実行します。</span><span class="sxs-lookup"><span data-stu-id="f599e-198">Report of Chaos runs.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-199">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-199">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-200">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="f599e-200">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="f599e-201">これらは Service Fabric の例外と、次のエラー コードを検査する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-201">These are Service Fabric exceptions and the following error codes should be inspected.</span></span>
            <span data-ttu-id="f599e-202">FabricErrorCode.NotReady - Chaos を開始する前にこの API が呼び出された場合。</span><span class="sxs-lookup"><span data-stu-id="f599e-202">FabricErrorCode.NotReady - if this API is called before starting Chaos.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetChaosReportAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync (string continuationToken, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync(string continuationToken, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetChaosReportAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetChaosReportAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;" Usage="testManagementClient.GetChaosReportAsync (continuationToken, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="continuationToken"><span data-ttu-id="f599e-203">継続トークンの一覧については<see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />内、<see cref="T:System.Fabric.Chaos.DataStructures.ChaosReport" />です。</span><span class="sxs-lookup"><span data-stu-id="f599e-203">Continuation token for the list of <see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />s in the <see cref="T:System.Fabric.Chaos.DataStructures.ChaosReport" />.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="f599e-204">操作の全体的なタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="f599e-204">The overall timeout for the operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-205">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f599e-205">Cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="f599e-206">Chaos 実行のレポートを取得します。</span><span class="sxs-lookup"><span data-stu-id="f599e-206">Retrieves the report of Chaos runs.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-207">御礼状レポートを実行します。</span><span class="sxs-lookup"><span data-stu-id="f599e-207">Report of Chaos runs.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="f599e-208">これらは Service Fabric の例外と、次のエラー コードを検査する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-208">These are Service Fabric exceptions and the following error codes should be inspected.</span></span>
            <span data-ttu-id="f599e-209">FabricErrorCode.NotReady - Chaos を開始する前にこの API が呼び出された場合。</span><span class="sxs-lookup"><span data-stu-id="f599e-209">FabricErrorCode.NotReady - if this API is called before starting Chaos.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeTransitionProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NodeTransitionProgress&gt; GetNodeTransitionProgressAsync (Guid operationId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NodeTransitionProgress&gt; GetNodeTransitionProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetNodeTransitionProgressAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeTransitionProgressAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NodeTransitionProgress&gt;" Usage="testManagementClient.GetNodeTransitionProgressAsync (operationId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NodeTransitionProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="f599e-210">StartNodeTransitionAsync() を使用して test コマンドが開始されたときに、operationId に渡されます。</span><span class="sxs-lookup"><span data-stu-id="f599e-210">The operationId passed in when the test command was started using StartNodeTransitionAsync().</span></span></param>
        <param name="timeout"><span data-ttu-id="f599e-211">タイムアウトになった。</span><span class="sxs-lookup"><span data-stu-id="f599e-211">Timeout.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-212">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-212">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-213">StartNodeTransitionAsync() を使用して開始されたコマンドの進行状況を取得します。</span><span class="sxs-lookup"><span data-stu-id="f599e-213">Gets the progress of a command started using StartNodeTransitionAsync().</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-214">TestCommandProgressState と PartitionRestartResult を含む PartitionRestartProgress オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f599e-214">A PartitionRestartProgress object, containing TestCommandProgressState and PartitionRestartResult.</span></span></returns>
        <remarks><span data-ttu-id="f599e-215">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-215">The FaultAnalysisService must be enabled to use this API.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionDataLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync (Guid operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync(valuetype System.Guid operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionDataLossProgressAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionDataLossProgressAsync (operationId As Guid) As Task(Of PartitionDataLossProgress)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionDataLossProgressAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;" Usage="testManagementClient.GetPartitionDataLossProgressAsync operationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="f599e-216">StartPartitionDataLossAsync() を使用して test コマンドが開始されたときに、operationId に渡されます。</span><span class="sxs-lookup"><span data-stu-id="f599e-216">The operationId passed in when the test command was starting using StartPartitionDataLossAsync().</span></span></param>
        <summary>
            <span data-ttu-id="f599e-217">StartPartitionDataLossAsync() を使用して開始されたテスト コマンドの進行状況を取得します。</span><span class="sxs-lookup"><span data-stu-id="f599e-217">Gets the progress of a test command started using StartPartitionDataLossAsync().</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-218">TestCommandProgressState と PartitionDataLossResult を含む PartitionDataLossProgress オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f599e-218">A PartitionDataLossProgress object, containing TestCommandProgressState and PartitionDataLossResult.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="f599e-219">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-219">The FaultAnalysisService must be enabled to use this API.</span></span></para>
          <para><span data-ttu-id="f599e-220">場合、返された PartitionDataLossProgress.State Faulted、= = PartitionDataLossProgress.Result.Exception 原因を特定するを確認します。</span><span class="sxs-lookup"><span data-stu-id="f599e-220">If the returned PartitionDataLossProgress.State == Faulted, examine PartitionDataLossProgress.Result.Exception to determine why.</span></span>
            <span data-ttu-id="f599e-221">PartitionDataLossProgress.Result.Exception 値:</span><span class="sxs-lookup"><span data-stu-id="f599e-221">PartitionDataLossProgress.Result.Exception values:</span></span>
              - <span data-ttu-id="f599e-222">ArgumentException の入力が無効でした。</span><span class="sxs-lookup"><span data-stu-id="f599e-222">ArgumentException - the input was invalid.</span></span>
              - <span data-ttu-id="f599e-223">ErrorCode プロパティを持つ場合は、FabricException:</span><span class="sxs-lookup"><span data-stu-id="f599e-223">FabricException, with an ErrorCode property of:</span></span>
                - <span data-ttu-id="f599e-224">PartitionNotFound - 指定されたパーティションが見つからないか、指定されたサービスが属するパーティションではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-224">PartitionNotFound - the specified partition was not found, or is not a partition that belongs to the specified service.</span></span>       
                - <span data-ttu-id="f599e-225">FabricInvalidForStatelessServicesException - この操作はステートレスなサービスに対して有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-225">FabricInvalidForStatelessServicesException - this operation is not valid for stateless services.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionDataLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync (Guid operationId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync(valuetype System.Guid operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionDataLossProgressAsync(System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionDataLossProgressAsync : Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;" Usage="testManagementClient.GetPartitionDataLossProgressAsync (operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="f599e-226">StartPartitionDataLossAsync() を使用して test コマンドが開始されたときに、operationId に渡されます。</span><span class="sxs-lookup"><span data-stu-id="f599e-226">The operationId passed in when the test command was starting using StartPartitionDataLossAsync().</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-227">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-227">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-228">StartPartitionDataLossAsync() を使用して開始されたテスト コマンドの進行状況を取得します。</span><span class="sxs-lookup"><span data-stu-id="f599e-228">Gets the progress of a test command started using StartPartitionDataLossAsync().</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-229">TestCommandProgressState と PartitionDataLossResult を含む PartitionDataLossProgress オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f599e-229">A PartitionDataLossProgress object, containing TestCommandProgressState and PartitionDataLossResult.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="f599e-230">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-230">The FaultAnalysisService must be enabled to use this API.</span></span></para>
          <para><span data-ttu-id="f599e-231">場合、返された PartitionDataLossProgress.State Faulted、= = PartitionDataLossProgress.Result.Exception 原因を特定するを確認します。</span><span class="sxs-lookup"><span data-stu-id="f599e-231">If the returned PartitionDataLossProgress.State == Faulted, examine PartitionDataLossProgress.Result.Exception to determine why.</span></span>
            <span data-ttu-id="f599e-232">PartitionDataLossProgress.Result.Exception 値:</span><span class="sxs-lookup"><span data-stu-id="f599e-232">PartitionDataLossProgress.Result.Exception values:</span></span>
              - <span data-ttu-id="f599e-233">ArgumentException の入力が無効でした。</span><span class="sxs-lookup"><span data-stu-id="f599e-233">ArgumentException - the input was invalid.</span></span>
              - <span data-ttu-id="f599e-234">ErrorCode プロパティを持つ場合は、FabricException:</span><span class="sxs-lookup"><span data-stu-id="f599e-234">FabricException, with an ErrorCode property of:</span></span>
                - <span data-ttu-id="f599e-235">PartitionNotFound - 指定されたパーティションが見つからないか、指定されたサービスが属するパーティションではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-235">PartitionNotFound - the specified partition was not found, or is not a partition that belongs to the specified service.</span></span>       
                - <span data-ttu-id="f599e-236">FabricInvalidForStatelessServicesException - この操作はステートレスなサービスに対して有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-236">FabricInvalidForStatelessServicesException - this operation is not valid for stateless services.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionDataLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync (Guid operationId, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionDataLossProgressAsync(System.Guid,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionDataLossProgressAsync (operationId As Guid, timeout As TimeSpan) As Task(Of PartitionDataLossProgress)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionDataLossProgressAsync : Guid * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;" Usage="testManagementClient.GetPartitionDataLossProgressAsync (operationId, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="f599e-237">StartPartitionDataLossAsync() を使用して test コマンドが開始されたときに、operationId に渡されます。</span><span class="sxs-lookup"><span data-stu-id="f599e-237">The operationId passed in when the test command was starting using StartPartitionDataLossAsync().</span></span></param>
        <param name="timeout"><span data-ttu-id="f599e-238">タイムアウトになった。</span><span class="sxs-lookup"><span data-stu-id="f599e-238">Timeout.</span></span></param>
        <summary>
            <span data-ttu-id="f599e-239">StartPartitionDataLossAsync() を使用して開始されたテスト コマンドの進行状況を取得します。</span><span class="sxs-lookup"><span data-stu-id="f599e-239">Gets the progress of a test command started using StartPartitionDataLossAsync().</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-240">TestCommandProgressState と PartitionDataLossResult を含む PartitionDataLossProgress オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f599e-240">A PartitionDataLossProgress object, containing TestCommandProgressState and PartitionDataLossResult.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="f599e-241">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-241">The FaultAnalysisService must be enabled to use this API.</span></span></para>
          <para><span data-ttu-id="f599e-242">場合、返された PartitionDataLossProgress.State Faulted、= = PartitionDataLossProgress.Result.Exception 原因を特定するを確認します。</span><span class="sxs-lookup"><span data-stu-id="f599e-242">If the returned PartitionDataLossProgress.State == Faulted, examine PartitionDataLossProgress.Result.Exception to determine why.</span></span>
            <span data-ttu-id="f599e-243">PartitionDataLossProgress.Result.Exception 値:</span><span class="sxs-lookup"><span data-stu-id="f599e-243">PartitionDataLossProgress.Result.Exception values:</span></span>
              - <span data-ttu-id="f599e-244">ArgumentException の入力が無効でした。</span><span class="sxs-lookup"><span data-stu-id="f599e-244">ArgumentException - the input was invalid.</span></span>
              - <span data-ttu-id="f599e-245">ErrorCode プロパティを持つ場合は、FabricException:</span><span class="sxs-lookup"><span data-stu-id="f599e-245">FabricException, with an ErrorCode property of:</span></span>
                - <span data-ttu-id="f599e-246">PartitionNotFound - 指定されたパーティションが見つからないか、指定されたサービスが属するパーティションではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-246">PartitionNotFound - the specified partition was not found, or is not a partition that belongs to the specified service.</span></span>       
                - <span data-ttu-id="f599e-247">FabricInvalidForStatelessServicesException - この操作はステートレスなサービスに対して有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-247">FabricInvalidForStatelessServicesException - this operation is not valid for stateless services.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionDataLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync (Guid operationId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionDataLossProgressAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionDataLossProgressAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;" Usage="testManagementClient.GetPartitionDataLossProgressAsync (operationId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="f599e-248">StartPartitionDataLossAsync() を使用して test コマンドが開始されたときに、operationId に渡されます。</span><span class="sxs-lookup"><span data-stu-id="f599e-248">The operationId passed in when the test command was starting using StartPartitionDataLossAsync().</span></span></param>
        <param name="timeout"><span data-ttu-id="f599e-249">タイムアウトになった。</span><span class="sxs-lookup"><span data-stu-id="f599e-249">Timeout.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-250">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-250">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-251">StartPartitionDataLossAsync() を使用して開始されたテスト コマンドの進行状況を取得します。</span><span class="sxs-lookup"><span data-stu-id="f599e-251">Gets the progress of a test command started using StartPartitionDataLossAsync().</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-252">TestCommandProgressState と PartitionDataLossResult を含む PartitionDataLossProgress オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f599e-252">A PartitionDataLossProgress object, containing TestCommandProgressState and PartitionDataLossResult.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="f599e-253">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-253">The FaultAnalysisService must be enabled to use this API.</span></span></para>
          <para><span data-ttu-id="f599e-254">場合、返された PartitionDataLossProgress.State Faulted、= = PartitionDataLossProgress.Result.Exception 原因を特定するを確認します。</span><span class="sxs-lookup"><span data-stu-id="f599e-254">If the returned PartitionDataLossProgress.State == Faulted, examine PartitionDataLossProgress.Result.Exception to determine why.</span></span>
            <span data-ttu-id="f599e-255">PartitionDataLossProgress.Result.Exception 値:</span><span class="sxs-lookup"><span data-stu-id="f599e-255">PartitionDataLossProgress.Result.Exception values:</span></span>
              - <span data-ttu-id="f599e-256">ArgumentException の入力が無効でした。</span><span class="sxs-lookup"><span data-stu-id="f599e-256">ArgumentException - the input was invalid.</span></span>
              - <span data-ttu-id="f599e-257">ErrorCode プロパティを持つ場合は、FabricException:</span><span class="sxs-lookup"><span data-stu-id="f599e-257">FabricException, with an ErrorCode property of:</span></span>
                - <span data-ttu-id="f599e-258">PartitionNotFound - 指定されたパーティションが見つからないか、指定されたサービスが属するパーティションではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-258">PartitionNotFound - the specified partition was not found, or is not a partition that belongs to the specified service.</span></span>       
                - <span data-ttu-id="f599e-259">FabricInvalidForStatelessServicesException - この操作はステートレスなサービスに対して有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-259">FabricInvalidForStatelessServicesException - this operation is not valid for stateless services.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionQuorumLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync (Guid operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync(valuetype System.Guid operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionQuorumLossProgressAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionQuorumLossProgressAsync (operationId As Guid) As Task(Of PartitionQuorumLossProgress)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionQuorumLossProgressAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;" Usage="testManagementClient.GetPartitionQuorumLossProgressAsync operationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="f599e-260">StartPartitionQuorumLossAsync() を使用して test コマンドが開始されたときに、operationId に渡されます。</span><span class="sxs-lookup"><span data-stu-id="f599e-260">The operationId passed in when the test command was starting using StartPartitionQuorumLossAsync().</span></span></param>
        <summary>
            <span data-ttu-id="f599e-261">StartPartitionQuorumLossAsync() を使用して開始されたテスト コマンドの進行状況を取得します。</span><span class="sxs-lookup"><span data-stu-id="f599e-261">Gets the progress of a test command started using StartPartitionQuorumLossAsync().</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-262">TestCommandProgressState と PartitionQuorumLossResult を含む PartitionQuorumLossProgress オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f599e-262">A PartitionQuorumLossProgress object, containing TestCommandProgressState and PartitionQuorumLossResult.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="f599e-263">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-263">The FaultAnalysisService must be enabled to use this API.</span></span></para>
          <para>
            <span data-ttu-id="f599e-264">場合、返された PartitionQuorumLossProgress.State Faulted、= = PartitionQuorumLossProgress.Result.Exception 原因を特定するを確認します。</span><span class="sxs-lookup"><span data-stu-id="f599e-264">If the returned PartitionQuorumLossProgress.State == Faulted, examine PartitionQuorumLossProgress.Result.Exception to determine why.</span></span>
            <span data-ttu-id="f599e-265">PartitionQuorumLossProgress.Result.Exception 値:</span><span class="sxs-lookup"><span data-stu-id="f599e-265">PartitionQuorumLossProgress.Result.Exception values:</span></span>
              - <span data-ttu-id="f599e-266">ArgumentException の入力が無効でした。</span><span class="sxs-lookup"><span data-stu-id="f599e-266">ArgumentException - the input was invalid.</span></span>
              - <span data-ttu-id="f599e-267">ErrorCode プロパティを持つ場合は、FabricException:</span><span class="sxs-lookup"><span data-stu-id="f599e-267">FabricException, with an ErrorCode property of:</span></span>
                - <span data-ttu-id="f599e-268">PartitionNotFound - 指定されたパーティションが見つからないか、指定されたサービスが属するパーティションではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-268">PartitionNotFound - the specified partition was not found, or is not a partition that belongs to the specified service.</span></span>       
                - <span data-ttu-id="f599e-269">FabricInvalidForStatelessServicesException - この操作はステートレスなサービスに対して有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-269">FabricInvalidForStatelessServicesException - this operation is not valid for stateless services.</span></span>
                - <span data-ttu-id="f599e-270">FabricOnlyValidForStatefulPersistentServicesException - この操作はメモリ内のステートフル サービスに対して有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-270">FabricOnlyValidForStatefulPersistentServicesException - this operation is not valid for stateful in-memory services.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionQuorumLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync (Guid operationId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync(valuetype System.Guid operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionQuorumLossProgressAsync(System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionQuorumLossProgressAsync : Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;" Usage="testManagementClient.GetPartitionQuorumLossProgressAsync (operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="f599e-271">StartPartitionQuorumLossAsync() を使用して test コマンドが開始されたときに、operationId に渡されます。</span><span class="sxs-lookup"><span data-stu-id="f599e-271">The operationId passed in when the test command was starting using StartPartitionQuorumLossAsync().</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-272">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-272">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-273">StartPartitionQuorumLossAsync() を使用して開始されたテスト コマンドの進行状況を取得します。</span><span class="sxs-lookup"><span data-stu-id="f599e-273">Gets the progress of a test command started using StartPartitionQuorumLossAsync().</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-274">TestCommandProgressState と PartitionQuorumLossResult を含む PartitionQuorumLossProgress オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f599e-274">A PartitionQuorumLossProgress object, containing TestCommandProgressState and PartitionQuorumLossResult.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="f599e-275">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-275">The FaultAnalysisService must be enabled to use this API.</span></span></para>
          <para>
            <span data-ttu-id="f599e-276">場合、返された PartitionQuorumLossProgress.State Faulted、= = PartitionQuorumLossProgress.Result.Exception 原因を特定するを確認します。</span><span class="sxs-lookup"><span data-stu-id="f599e-276">If the returned PartitionQuorumLossProgress.State == Faulted, examine PartitionQuorumLossProgress.Result.Exception to determine why.</span></span>
            <span data-ttu-id="f599e-277">PartitionQuorumLossProgress.Result.Exception 値:</span><span class="sxs-lookup"><span data-stu-id="f599e-277">PartitionQuorumLossProgress.Result.Exception values:</span></span>
              - <span data-ttu-id="f599e-278">ArgumentException の入力が無効でした。</span><span class="sxs-lookup"><span data-stu-id="f599e-278">ArgumentException - the input was invalid.</span></span>
              - <span data-ttu-id="f599e-279">ErrorCode プロパティを持つ場合は、FabricException:</span><span class="sxs-lookup"><span data-stu-id="f599e-279">FabricException, with an ErrorCode property of:</span></span>
                - <span data-ttu-id="f599e-280">PartitionNotFound - 指定されたパーティションが見つからないか、指定されたサービスが属するパーティションではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-280">PartitionNotFound - the specified partition was not found, or is not a partition that belongs to the specified service.</span></span>       
                - <span data-ttu-id="f599e-281">FabricInvalidForStatelessServicesException - この操作はステートレスなサービスに対して有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-281">FabricInvalidForStatelessServicesException - this operation is not valid for stateless services.</span></span>
                - <span data-ttu-id="f599e-282">FabricOnlyValidForStatefulPersistentServicesException - この操作はメモリ内のステートフル サービスに対して有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-282">FabricOnlyValidForStatefulPersistentServicesException - this operation is not valid for stateful in-memory services.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionQuorumLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync (Guid operationId, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionQuorumLossProgressAsync(System.Guid,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionQuorumLossProgressAsync (operationId As Guid, timeout As TimeSpan) As Task(Of PartitionQuorumLossProgress)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionQuorumLossProgressAsync : Guid * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;" Usage="testManagementClient.GetPartitionQuorumLossProgressAsync (operationId, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="f599e-283">StartPartitionQuorumLossAsync() を使用して test コマンドが開始されたときに、operationId に渡されます。</span><span class="sxs-lookup"><span data-stu-id="f599e-283">The operationId passed in when the test command was starting using StartPartitionQuorumLossAsync().</span></span></param>
        <param name="timeout"><span data-ttu-id="f599e-284">タイムアウトになった。</span><span class="sxs-lookup"><span data-stu-id="f599e-284">Timeout.</span></span></param>
        <summary>
            <span data-ttu-id="f599e-285">StartPartitionQuorumLossAsync() を使用して開始されたテスト コマンドの進行状況を取得します。</span><span class="sxs-lookup"><span data-stu-id="f599e-285">Gets the progress of a test command started using StartPartitionQuorumLossAsync().</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-286">TestCommandProgressState と PartitionQuorumLossResult を含む PartitionQuorumLossProgress オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f599e-286">A PartitionQuorumLossProgress object, containing TestCommandProgressState and PartitionQuorumLossResult.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="f599e-287">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-287">The FaultAnalysisService must be enabled to use this API.</span></span></para>
          <para>
            <span data-ttu-id="f599e-288">場合、返された PartitionQuorumLossProgress.State Faulted、= = PartitionQuorumLossProgress.Result.Exception 原因を特定するを確認します。</span><span class="sxs-lookup"><span data-stu-id="f599e-288">If the returned PartitionQuorumLossProgress.State == Faulted, examine PartitionQuorumLossProgress.Result.Exception to determine why.</span></span>
            <span data-ttu-id="f599e-289">PartitionQuorumLossProgress.Result.Exception 値:</span><span class="sxs-lookup"><span data-stu-id="f599e-289">PartitionQuorumLossProgress.Result.Exception values:</span></span>
              - <span data-ttu-id="f599e-290">ArgumentException の入力が無効でした。</span><span class="sxs-lookup"><span data-stu-id="f599e-290">ArgumentException - the input was invalid.</span></span>
              - <span data-ttu-id="f599e-291">ErrorCode プロパティを持つ場合は、FabricException:</span><span class="sxs-lookup"><span data-stu-id="f599e-291">FabricException, with an ErrorCode property of:</span></span>
                - <span data-ttu-id="f599e-292">PartitionNotFound - 指定されたパーティションが見つからないか、指定されたサービスが属するパーティションではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-292">PartitionNotFound - the specified partition was not found, or is not a partition that belongs to the specified service.</span></span>       
                - <span data-ttu-id="f599e-293">FabricInvalidForStatelessServicesException - この操作はステートレスなサービスに対して有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-293">FabricInvalidForStatelessServicesException - this operation is not valid for stateless services.</span></span>
                - <span data-ttu-id="f599e-294">FabricOnlyValidForStatefulPersistentServicesException - この操作はメモリ内のステートフル サービスに対して有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-294">FabricOnlyValidForStatefulPersistentServicesException - this operation is not valid for stateful in-memory services.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionQuorumLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync (Guid operationId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionQuorumLossProgressAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionQuorumLossProgressAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;" Usage="testManagementClient.GetPartitionQuorumLossProgressAsync (operationId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="f599e-295">StartPartitionQuorumLossAsync() を使用して test コマンドが開始されたときに、operationId に渡されます。</span><span class="sxs-lookup"><span data-stu-id="f599e-295">The operationId passed in when the test command was starting using StartPartitionQuorumLossAsync().</span></span></param>
        <param name="timeout"><span data-ttu-id="f599e-296">タイムアウトになった。</span><span class="sxs-lookup"><span data-stu-id="f599e-296">Timeout.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-297">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-297">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-298">StartPartitionQuorumLossAsync() を使用して開始されたテスト コマンドの進行状況を取得します。</span><span class="sxs-lookup"><span data-stu-id="f599e-298">Gets the progress of a test command started using StartPartitionQuorumLossAsync().</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-299">TestCommandProgressState と PartitionQuorumLossResult を含む PartitionQuorumLossProgress オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f599e-299">A PartitionQuorumLossProgress object, containing TestCommandProgressState and PartitionQuorumLossResult.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="f599e-300">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-300">The FaultAnalysisService must be enabled to use this API.</span></span></para>
          <para>
            <span data-ttu-id="f599e-301">場合、返された PartitionQuorumLossProgress.State Faulted、= = PartitionQuorumLossProgress.Result.Exception 原因を特定するを確認します。</span><span class="sxs-lookup"><span data-stu-id="f599e-301">If the returned PartitionQuorumLossProgress.State == Faulted, examine PartitionQuorumLossProgress.Result.Exception to determine why.</span></span>
            <span data-ttu-id="f599e-302">PartitionQuorumLossProgress.Result.Exception 値:</span><span class="sxs-lookup"><span data-stu-id="f599e-302">PartitionQuorumLossProgress.Result.Exception values:</span></span>
              - <span data-ttu-id="f599e-303">ArgumentException の入力が無効でした。</span><span class="sxs-lookup"><span data-stu-id="f599e-303">ArgumentException - the input was invalid.</span></span>
              - <span data-ttu-id="f599e-304">ErrorCode プロパティを持つ場合は、FabricException:</span><span class="sxs-lookup"><span data-stu-id="f599e-304">FabricException, with an ErrorCode property of:</span></span>
                - <span data-ttu-id="f599e-305">PartitionNotFound - 指定されたパーティションが見つからないか、指定されたサービスが属するパーティションではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-305">PartitionNotFound - the specified partition was not found, or is not a partition that belongs to the specified service.</span></span>       
                - <span data-ttu-id="f599e-306">FabricInvalidForStatelessServicesException - この操作はステートレスなサービスに対して有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-306">FabricInvalidForStatelessServicesException - this operation is not valid for stateless services.</span></span>
                - <span data-ttu-id="f599e-307">FabricOnlyValidForStatefulPersistentServicesException - この操作はメモリ内のステートフル サービスに対して有効ではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-307">FabricOnlyValidForStatefulPersistentServicesException - this operation is not valid for stateful in-memory services.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionRestartProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync (Guid operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync(valuetype System.Guid operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionRestartProgressAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionRestartProgressAsync (operationId As Guid) As Task(Of PartitionRestartProgress)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionRestartProgressAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;" Usage="testManagementClient.GetPartitionRestartProgressAsync operationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="f599e-308">StartPartitionRestartAsync() を使用して test コマンドが開始されたときに、operationId に渡されます。</span><span class="sxs-lookup"><span data-stu-id="f599e-308">The operationId passed in when the test command was starting using StartPartitionRestartAsync().</span></span></param>
        <summary>
            <span data-ttu-id="f599e-309">StartPartitionRestartAsync() を使用して開始されたテスト コマンドの進行状況を取得します。</span><span class="sxs-lookup"><span data-stu-id="f599e-309">Gets the progress of a test command started using StartPartitionRestartAsync().</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-310">TestCommandProgressState と PartitionRestartResult を含む PartitionRestartProgress オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f599e-310">A PartitionRestartProgress object, containing TestCommandProgressState and PartitionRestartResult.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="f599e-311">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-311">The FaultAnalysisService must be enabled to use this API.</span></span></para>
          <para><span data-ttu-id="f599e-312">場合、返された PartitionRestartProgress.State Faulted、= = PartitionRestartProgress.Result.Exception 原因を特定するを確認します。</span><span class="sxs-lookup"><span data-stu-id="f599e-312">If the returned PartitionRestartProgress.State == Faulted, examine PartitionRestartProgress.Result.Exception to determine why.</span></span>
            <span data-ttu-id="f599e-313">PartitionRestartProgress.Result.Exception 値:</span><span class="sxs-lookup"><span data-stu-id="f599e-313">PartitionRestartProgress.Result.Exception values:</span></span>
              - <span data-ttu-id="f599e-314">ArgumentException の入力が無効でした。</span><span class="sxs-lookup"><span data-stu-id="f599e-314">ArgumentException - the input was invalid.</span></span>
              - <span data-ttu-id="f599e-315">ErrorCode プロパティを持つ場合は、FabricException:</span><span class="sxs-lookup"><span data-stu-id="f599e-315">FabricException, with an ErrorCode property of:</span></span>
                - <span data-ttu-id="f599e-316">PartitionNotFound - 指定されたパーティションが見つからないか、指定されたサービスが属するパーティションではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-316">PartitionNotFound - the specified partition was not found, or is not a partition that belongs to the specified service.</span></span>       
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionRestartProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync (Guid operationId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync(valuetype System.Guid operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionRestartProgressAsync(System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionRestartProgressAsync : Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;" Usage="testManagementClient.GetPartitionRestartProgressAsync (operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="f599e-317">StartPartitionRestartAsync() を使用して test コマンドが開始されたときに、operationId に渡されます。</span><span class="sxs-lookup"><span data-stu-id="f599e-317">The operationId passed in when the test command was starting using StartPartitionRestartAsync().</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-318">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-318">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-319">StartPartitionRestartAsync() を使用して開始されたテスト コマンドの進行状況を取得します。</span><span class="sxs-lookup"><span data-stu-id="f599e-319">Gets the progress of a test command started using StartPartitionRestartAsync().</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-320">TestCommandProgressState と PartitionRestartResult を含む PartitionRestartProgress オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f599e-320">A PartitionRestartProgress object, containing TestCommandProgressState and PartitionRestartResult.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="f599e-321">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-321">The FaultAnalysisService must be enabled to use this API.</span></span></para>
          <para><span data-ttu-id="f599e-322">場合、返された PartitionRestartProgress.State Faulted、= = PartitionRestartProgress.Result.Exception 原因を特定するを確認します。</span><span class="sxs-lookup"><span data-stu-id="f599e-322">If the returned PartitionRestartProgress.State == Faulted, examine PartitionRestartProgress.Result.Exception to determine why.</span></span>
            <span data-ttu-id="f599e-323">PartitionRestartProgress.Result.Exception 値:</span><span class="sxs-lookup"><span data-stu-id="f599e-323">PartitionRestartProgress.Result.Exception values:</span></span>
              - <span data-ttu-id="f599e-324">ArgumentException の入力が無効でした。</span><span class="sxs-lookup"><span data-stu-id="f599e-324">ArgumentException - the input was invalid.</span></span>
              - <span data-ttu-id="f599e-325">ErrorCode プロパティを持つ場合は、FabricException:</span><span class="sxs-lookup"><span data-stu-id="f599e-325">FabricException, with an ErrorCode property of:</span></span>
                - <span data-ttu-id="f599e-326">PartitionNotFound - 指定されたパーティションが見つからないか、指定されたサービスが属するパーティションではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-326">PartitionNotFound - the specified partition was not found, or is not a partition that belongs to the specified service.</span></span>       
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionRestartProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync (Guid operationId, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionRestartProgressAsync(System.Guid,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionRestartProgressAsync (operationId As Guid, timeout As TimeSpan) As Task(Of PartitionRestartProgress)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionRestartProgressAsync : Guid * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;" Usage="testManagementClient.GetPartitionRestartProgressAsync (operationId, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="f599e-327">StartPartitionRestartAsync() を使用して test コマンドが開始されたときに、operationId に渡されます。</span><span class="sxs-lookup"><span data-stu-id="f599e-327">The operationId passed in when the test command was starting using StartPartitionRestartAsync().</span></span></param>
        <param name="timeout"><span data-ttu-id="f599e-328">タイムアウトになった。</span><span class="sxs-lookup"><span data-stu-id="f599e-328">Timeout.</span></span></param>
        <summary>
            <span data-ttu-id="f599e-329">StartPartitionRestartAsync() を使用して開始されたテスト コマンドの進行状況を取得します。</span><span class="sxs-lookup"><span data-stu-id="f599e-329">Gets the progress of a test command started using StartPartitionRestartAsync().</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-330">TestCommandProgressState と PartitionRestartResult を含む PartitionRestartProgress オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f599e-330">A PartitionRestartProgress object, containing TestCommandProgressState and PartitionRestartResult.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="f599e-331">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-331">The FaultAnalysisService must be enabled to use this API.</span></span></para>
          <para><span data-ttu-id="f599e-332">場合、返された PartitionRestartProgress.State Faulted、= = PartitionRestartProgress.Result.Exception 原因を特定するを確認します。</span><span class="sxs-lookup"><span data-stu-id="f599e-332">If the returned PartitionRestartProgress.State == Faulted, examine PartitionRestartProgress.Result.Exception to determine why.</span></span>
            <span data-ttu-id="f599e-333">PartitionRestartProgress.Result.Exception 値:</span><span class="sxs-lookup"><span data-stu-id="f599e-333">PartitionRestartProgress.Result.Exception values:</span></span>
              - <span data-ttu-id="f599e-334">ArgumentException の入力が無効でした。</span><span class="sxs-lookup"><span data-stu-id="f599e-334">ArgumentException - the input was invalid.</span></span>
              - <span data-ttu-id="f599e-335">ErrorCode プロパティを持つ場合は、FabricException:</span><span class="sxs-lookup"><span data-stu-id="f599e-335">FabricException, with an ErrorCode property of:</span></span>
                - <span data-ttu-id="f599e-336">PartitionNotFound - 指定されたパーティションが見つからないか、指定されたサービスが属するパーティションではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-336">PartitionNotFound - the specified partition was not found, or is not a partition that belongs to the specified service.</span></span>       
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionRestartProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync (Guid operationId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionRestartProgressAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionRestartProgressAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;" Usage="testManagementClient.GetPartitionRestartProgressAsync (operationId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="f599e-337">StartPartitionRestartAsync() を使用して test コマンドが開始されたときに、operationId に渡されます。</span><span class="sxs-lookup"><span data-stu-id="f599e-337">The operationId passed in when the test command was starting using StartPartitionRestartAsync().</span></span></param>
        <param name="timeout"><span data-ttu-id="f599e-338">タイムアウトになった。</span><span class="sxs-lookup"><span data-stu-id="f599e-338">Timeout.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-339">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-339">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-340">StartPartitionRestartAsync() を使用して開始されたテスト コマンドの進行状況を取得します。</span><span class="sxs-lookup"><span data-stu-id="f599e-340">Gets the progress of a test command started using StartPartitionRestartAsync().</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-341">TestCommandProgressState と PartitionRestartResult を含む PartitionRestartProgress オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f599e-341">A PartitionRestartProgress object, containing TestCommandProgressState and PartitionRestartResult.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="f599e-342">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-342">The FaultAnalysisService must be enabled to use this API.</span></span></para>
          <para><span data-ttu-id="f599e-343">場合、返された PartitionRestartProgress.State Faulted、= = PartitionRestartProgress.Result.Exception 原因を特定するを確認します。</span><span class="sxs-lookup"><span data-stu-id="f599e-343">If the returned PartitionRestartProgress.State == Faulted, examine PartitionRestartProgress.Result.Exception to determine why.</span></span>
            <span data-ttu-id="f599e-344">PartitionRestartProgress.Result.Exception 値:</span><span class="sxs-lookup"><span data-stu-id="f599e-344">PartitionRestartProgress.Result.Exception values:</span></span>
              - <span data-ttu-id="f599e-345">ArgumentException の入力が無効でした。</span><span class="sxs-lookup"><span data-stu-id="f599e-345">ArgumentException - the input was invalid.</span></span>
              - <span data-ttu-id="f599e-346">ErrorCode プロパティを持つ場合は、FabricException:</span><span class="sxs-lookup"><span data-stu-id="f599e-346">FabricException, with an ErrorCode property of:</span></span>
                - <span data-ttu-id="f599e-347">PartitionNotFound - 指定されたパーティションが見つからないか、指定されたサービスが属するパーティションではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-347">PartitionNotFound - the specified partition was not found, or is not a partition that belongs to the specified service.</span></span>       
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestCommandStatusListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTestCommandStatusListAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;" Usage="testManagementClient.GetTestCommandStatusListAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="f599e-348">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-348">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-349">テスト コマンドの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="f599e-349">Gets the status of test commands.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-350">IList の TestCommandStatus オブジェクトであるの TestCommandStatusList</span><span class="sxs-lookup"><span data-stu-id="f599e-350">A TestCommandStatusList, which is an IList of TestCommandStatus objects</span></span></returns>
        <remarks><span data-ttu-id="f599e-351">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-351">The FaultAnalysisService must be enabled to use this API.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestCommandStatusListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync (TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync(valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTestCommandStatusListAsync (operationTimeout As TimeSpan) As Task(Of TestCommandStatusList)" />
      <MemberSignature Language="F#" Value="member this.GetTestCommandStatusListAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;" Usage="testManagementClient.GetTestCommandStatusListAsync operationTimeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationTimeout"><span data-ttu-id="f599e-352">API 呼び出しのタイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="f599e-352">A timeout for the API call.</span></span></param>
        <summary>
            <span data-ttu-id="f599e-353">テスト コマンドの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="f599e-353">Gets the status of test commands.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-354">IList の TestCommandStatus オブジェクトであるの TestCommandStatusList</span><span class="sxs-lookup"><span data-stu-id="f599e-354">A TestCommandStatusList, which is an IList of TestCommandStatus objects</span></span></returns>
        <remarks><span data-ttu-id="f599e-355">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-355">The FaultAnalysisService must be enabled to use this API.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestCommandStatusListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync (TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync(valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTestCommandStatusListAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;" Usage="testManagementClient.GetTestCommandStatusListAsync (operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationTimeout"><span data-ttu-id="f599e-356">API 呼び出しのタイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="f599e-356">A timeout for the API call.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-357">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-357">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-358">テスト コマンドの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="f599e-358">Gets the status of test commands.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-359">IList の TestCommandStatus オブジェクトであるの TestCommandStatusList</span><span class="sxs-lookup"><span data-stu-id="f599e-359">A TestCommandStatusList, which is an IList of TestCommandStatus objects</span></span></returns>
        <remarks><span data-ttu-id="f599e-360">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-360">The FaultAnalysisService must be enabled to use this API.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestCommandStatusListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync (System.Fabric.Query.TestCommandStateFilter stateFilter, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync(valuetype System.Fabric.Query.TestCommandStateFilter stateFilter, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.Fabric.Query.TestCommandStateFilter,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTestCommandStatusListAsync : System.Fabric.Query.TestCommandStateFilter * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;" Usage="testManagementClient.GetTestCommandStatusListAsync (stateFilter, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stateFilter" Type="System.Fabric.Query.TestCommandStateFilter" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="stateFilter"><span data-ttu-id="f599e-361">このパラメーターは TestCommandState によるフィルター処理に使用することができます。</span><span class="sxs-lookup"><span data-stu-id="f599e-361">This parameter can be used to filter by TestCommandState</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="f599e-362">API 呼び出しのタイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="f599e-362">A timeout for the API call.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-363">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-363">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-364">テスト コマンドの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="f599e-364">Gets the status of test commands.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-365">IList の TestCommandStatus オブジェクトであるの TestCommandStatusList</span><span class="sxs-lookup"><span data-stu-id="f599e-365">A TestCommandStatusList, which is an IList of TestCommandStatus objects</span></span></returns>
        <remarks><span data-ttu-id="f599e-366">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-366">The FaultAnalysisService must be enabled to use this API.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestCommandStatusListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync (System.Fabric.Query.TestCommandTypeFilter typeFilter, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync(valuetype System.Fabric.Query.TestCommandTypeFilter typeFilter, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.Fabric.Query.TestCommandTypeFilter,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTestCommandStatusListAsync : System.Fabric.Query.TestCommandTypeFilter * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;" Usage="testManagementClient.GetTestCommandStatusListAsync (typeFilter, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="typeFilter" Type="System.Fabric.Query.TestCommandTypeFilter" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="typeFilter"><span data-ttu-id="f599e-367">このパラメーターは TestCommandType によるフィルター処理に使用することができます。</span><span class="sxs-lookup"><span data-stu-id="f599e-367">This parameter can be used to filter by TestCommandType</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="f599e-368">API 呼び出しのタイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="f599e-368">A timeout for the API call.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-369">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-369">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-370">テスト コマンドの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="f599e-370">Gets the status of test commands.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-371">IList の TestCommandStatus オブジェクトであるの TestCommandStatusList</span><span class="sxs-lookup"><span data-stu-id="f599e-371">A TestCommandStatusList, which is an IList of TestCommandStatus objects</span></span></returns>
        <remarks><span data-ttu-id="f599e-372">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-372">The FaultAnalysisService must be enabled to use this API.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestCommandStatusListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync (System.Fabric.Query.TestCommandStateFilter stateFilter, System.Fabric.Query.TestCommandTypeFilter typeFilter, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync(valuetype System.Fabric.Query.TestCommandStateFilter stateFilter, valuetype System.Fabric.Query.TestCommandTypeFilter typeFilter, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.Fabric.Query.TestCommandStateFilter,System.Fabric.Query.TestCommandTypeFilter,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTestCommandStatusListAsync : System.Fabric.Query.TestCommandStateFilter * System.Fabric.Query.TestCommandTypeFilter * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;" Usage="testManagementClient.GetTestCommandStatusListAsync (stateFilter, typeFilter, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stateFilter" Type="System.Fabric.Query.TestCommandStateFilter" />
        <Parameter Name="typeFilter" Type="System.Fabric.Query.TestCommandTypeFilter" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="stateFilter"><span data-ttu-id="f599e-373">このパラメーターは TestCommandState によるフィルター処理に使用することができます。</span><span class="sxs-lookup"><span data-stu-id="f599e-373">This parameter can be used to filter by TestCommandState</span></span></param>
        <param name="typeFilter"><span data-ttu-id="f599e-374">このパラメーターは TestCommandType によるフィルター処理に使用することができます。</span><span class="sxs-lookup"><span data-stu-id="f599e-374">This parameter can be used to filter by TestCommandType</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="f599e-375">API 呼び出しのタイムアウト期間。</span><span class="sxs-lookup"><span data-stu-id="f599e-375">A timeout for the API call.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-376">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-376">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-377">テスト コマンドの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="f599e-377">Gets the status of test commands.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-378">IList の TestCommandStatus オブジェクトであるの TestCommandStatusList</span><span class="sxs-lookup"><span data-stu-id="f599e-378">A TestCommandStatusList, which is an IList of TestCommandStatus objects</span></span></returns>
        <remarks><span data-ttu-id="f599e-379">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-379">The FaultAnalysisService must be enabled to use this API.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeDataLossAsync(System.Fabric.PartitionSelector,System.Fabric.DataLossMode)" />
      <MemberSignature Language="F#" Value="member this.InvokeDataLossAsync : System.Fabric.PartitionSelector * System.Fabric.DataLossMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;" Usage="testManagementClient.InvokeDataLossAsync (partitionSelector, dataLossMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionDataLossAsync instead.  StartPartitionDataLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="f599e-380"><see cref="T:System.Fabric.PartitionSelector" />するパーティションを指定するデータの損失に起因する必要があります</span><span class="sxs-lookup"><span data-stu-id="f599e-380">The <see cref="T:System.Fabric.PartitionSelector" /> to specify which partition data loss needs to be induced for</span></span></param>
        <param name="dataLossMode"><span data-ttu-id="f599e-381">指定します、<see cref="T:System.Fabric.DataLossMode" />データの損失を発生させることのオプションなどです。</span><span class="sxs-lookup"><span data-stu-id="f599e-381">Specifies the <see cref="T:System.Fabric.DataLossMode" /> i.e. the options for inducing data loss.</span></span></param>
        <summary>
            <span data-ttu-id="f599e-382">この API は、指定されたパーティションのデータ損失を強制的に実行します。</span><span class="sxs-lookup"><span data-stu-id="f599e-382">This API will induce data loss for the specified partition.</span></span> <span data-ttu-id="f599e-383">パーティションの OnDataLoss API への呼び出しがトリガーされます。</span><span class="sxs-lookup"><span data-stu-id="f599e-383">It will trigger a call to the OnDataLoss API of the partition.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-384">データ損失のパーティションに関する情報を提供する InvokeDataLossResult が選択されました。</span><span class="sxs-lookup"><span data-stu-id="f599e-384">InvokeDataLossResult which gives information about the Partition that was selected for data loss.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-385">指定した実際のデータ損失が異なります<see cref="T:System.Fabric.DataLossMode" />PartialDataLoss - PartialDataLoss - クォーラムのみのレプリカを削除し、パーティションの OnDataLoss がトリガーされますが実際のデータ損失がインフライトのレプリケーションの存在に依存します。</span><span class="sxs-lookup"><span data-stu-id="f599e-385">Actual data loss will depend on the specified <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - Only a quorum of replicas are removed and OnDataLoss is triggered for the partition but actual data loss depends on presence of in-flight replication.</span></span>
            <span data-ttu-id="f599e-386">FullDataLoss - すべてのレプリカは、すべてのデータが失われるため削除し、OnDataLoss がトリガーされます。</span><span class="sxs-lookup"><span data-stu-id="f599e-386">FullDataLoss - All replicas are removed hence all data is lost and OnDataLoss is triggered.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-387">この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-387">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-388">ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。</span><span class="sxs-lookup"><span data-stu-id="f599e-388">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-389">重要な注意事項: この API は、実行中に中断できないする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-389">Important note:  this API should not be aborted while running.</span></span>  <span data-ttu-id="f599e-390">実行中に、この API を中止する可能性があります残した状態です。</span><span class="sxs-lookup"><span data-stu-id="f599e-390">Aborting this API while it is running may leave state behind.</span></span>  
            <span data-ttu-id="f599e-391">この API は、実行中に中止されましたが場合に、残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-391">If this API is aborted while running, CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-392">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-392">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-393">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="f599e-393">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="f599e-394">場合は、API は、ステートレスなサービスに属しているパーティションに対して呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="f599e-394">If the API is called for a partition belonging to a stateless service.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="f599e-395">これらは、選択されている、指定されたパーティションが存在しない場合に、ファブリック エラー FabricErrorCode.PartitionNotFound - です。</span><span class="sxs-lookup"><span data-stu-id="f599e-395">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeDataLossAsync(System.Fabric.PartitionSelector,System.Fabric.DataLossMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeDataLossAsync : System.Fabric.PartitionSelector * System.Fabric.DataLossMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;" Usage="testManagementClient.InvokeDataLossAsync (partitionSelector, dataLossMode, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionDataLossAsync instead.  StartPartitionDataLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="f599e-396"><see cref="T:System.Fabric.PartitionSelector" />するパーティションを指定するデータの損失に起因する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-396">The <see cref="T:System.Fabric.PartitionSelector" /> to specify which partition data loss needs to be induced for.</span></span></param>
        <param name="dataLossMode"><span data-ttu-id="f599e-397">指定します、<see cref="T:System.Fabric.DataLossMode" />データの損失を発生させることのオプションなどです。</span><span class="sxs-lookup"><span data-stu-id="f599e-397">Specifies the <see cref="T:System.Fabric.DataLossMode" /> i.e. the options for inducing data loss.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-398">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-398">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-399">この API は、指定されたパーティションのデータ損失を強制的に実行します。</span><span class="sxs-lookup"><span data-stu-id="f599e-399">This API will induce data loss for the specified partition.</span></span> <span data-ttu-id="f599e-400">パーティションの OnDataLoss API への呼び出しがトリガーされます。</span><span class="sxs-lookup"><span data-stu-id="f599e-400">It will trigger a call to the OnDataLoss API of the partition.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-401">データ損失のパーティションに関する情報を提供する InvokeDataLossResult が選択されました。</span><span class="sxs-lookup"><span data-stu-id="f599e-401">InvokeDataLossResult which gives information about the Partition that was selected for data loss.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-402">指定した実際のデータ損失が異なります<see cref="T:System.Fabric.DataLossMode" />PartialDataLoss - PartialDataLoss - クォーラムのみのレプリカを削除し、パーティションの OnDataLoss がトリガーされますが実際のデータ損失がインフライトのレプリケーションの存在に依存します。</span><span class="sxs-lookup"><span data-stu-id="f599e-402">Actual data loss will depend on the specified <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - Only a quorum of replicas are removed and OnDataLoss is triggered for the partition but actual data loss depends on presence of in-flight replication.</span></span>
            <span data-ttu-id="f599e-403">FullDataLoss - すべてのレプリカは、すべてのデータが失われるため削除し、OnDataLoss がトリガーされます。</span><span class="sxs-lookup"><span data-stu-id="f599e-403">FullDataLoss - All replicas are removed hence all data is lost and OnDataLoss is triggered.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-404">この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-404">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-405">ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。</span><span class="sxs-lookup"><span data-stu-id="f599e-405">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-406">重要な注意事項: この API は、実行中に中断できないする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-406">Important note:  this API should not be aborted while running.</span></span>  <span data-ttu-id="f599e-407">実行中に、この API を中止する可能性があります残した状態です。</span><span class="sxs-lookup"><span data-stu-id="f599e-407">Aborting this API while it is running may leave state behind.</span></span>  
            <span data-ttu-id="f599e-408">この API は、実行中に中止されましたが場合に、残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-408">If this API is aborted while running, CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-409">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-409">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-410">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="f599e-410">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="f599e-411">場合は、API は、ステートレスなサービスに属しているパーティションに対して呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="f599e-411">If the API is called for a partition belonging to a stateless service.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="f599e-412">これらは、選択されている、指定されたパーティションが存在しない場合に、ファブリック エラー FabricErrorCode.PartitionNotFound - です。</span><span class="sxs-lookup"><span data-stu-id="f599e-412">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeDataLossAsync(System.Fabric.PartitionSelector,System.Fabric.DataLossMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.InvokeDataLossAsync : System.Fabric.PartitionSelector * System.Fabric.DataLossMode * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;" Usage="testManagementClient.InvokeDataLossAsync (partitionSelector, dataLossMode, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionDataLossAsync instead.  StartPartitionDataLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="f599e-413"><see cref="T:System.Fabric.PartitionSelector" />するパーティションを指定するデータの損失に起因する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-413">The <see cref="T:System.Fabric.PartitionSelector" /> to specify which partition data loss needs to be induced for.</span></span></param>
        <param name="dataLossMode"><span data-ttu-id="f599e-414">指定します、<see cref="T:System.Fabric.DataLossMode" />データの損失を発生させることのオプションなどです。</span><span class="sxs-lookup"><span data-stu-id="f599e-414">Specifies the <see cref="T:System.Fabric.DataLossMode" /> i.e. the options for inducing data loss.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="f599e-415">操作の全体的なタイムアウト</span><span class="sxs-lookup"><span data-stu-id="f599e-415">The overall timeout for the operation</span></span></param>
        <summary>
            <span data-ttu-id="f599e-416">この API は、指定されたパーティションのデータ損失を強制的に実行します。</span><span class="sxs-lookup"><span data-stu-id="f599e-416">This API will induce data loss for the specified partition.</span></span> <span data-ttu-id="f599e-417">パーティションの OnDataLoss API への呼び出しがトリガーされます。</span><span class="sxs-lookup"><span data-stu-id="f599e-417">It will trigger a call to the OnDataLoss API of the partition.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-418">データ損失のパーティションに関する情報を提供する InvokeDataLossResult が選択されました。</span><span class="sxs-lookup"><span data-stu-id="f599e-418">InvokeDataLossResult which gives information about the Partition that was selected for data loss.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-419">指定した実際のデータ損失が異なります<see cref="T:System.Fabric.DataLossMode" />PartialDataLoss - PartialDataLoss - クォーラムのみのレプリカを削除し、パーティションの OnDataLoss がトリガーされますが実際のデータ損失がインフライトのレプリケーションの存在に依存します。</span><span class="sxs-lookup"><span data-stu-id="f599e-419">Actual data loss will depend on the specified <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - Only a quorum of replicas are removed and OnDataLoss is triggered for the partition but actual data loss depends on presence of in-flight replication.</span></span>
            <span data-ttu-id="f599e-420">FullDataLoss - すべてのレプリカは、すべてのデータが失われるため削除し、OnDataLoss がトリガーされます。</span><span class="sxs-lookup"><span data-stu-id="f599e-420">FullDataLoss - All replicas are removed hence all data is lost and OnDataLoss is triggered.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-421">この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-421">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-422">ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。</span><span class="sxs-lookup"><span data-stu-id="f599e-422">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-423">重要な注意事項: この API は、実行中に中断できないする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-423">Important note:  this API should not be aborted while running.</span></span>  <span data-ttu-id="f599e-424">実行中に、この API を中止する可能性があります残した状態です。</span><span class="sxs-lookup"><span data-stu-id="f599e-424">Aborting this API while it is running may leave state behind.</span></span>  
            <span data-ttu-id="f599e-425">この API は、実行中に中止されましたが場合に、残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-425">If this API is aborted while running, CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-426">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-426">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-427">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="f599e-427">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="f599e-428">場合は、API は、ステートレスなサービスに属しているパーティションに対して呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="f599e-428">If the API is called for a partition belonging to a stateless service.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="f599e-429">これらは、選択されている、指定されたパーティションが存在しない場合に、ファブリック エラー FabricErrorCode.PartitionNotFound - です。</span><span class="sxs-lookup"><span data-stu-id="f599e-429">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeDataLossAsync(System.Fabric.PartitionSelector,System.Fabric.DataLossMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeDataLossAsync : System.Fabric.PartitionSelector * System.Fabric.DataLossMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;" Usage="testManagementClient.InvokeDataLossAsync (partitionSelector, dataLossMode, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionDataLossAsync instead.  StartPartitionDataLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="f599e-430"><see cref="T:System.Fabric.PartitionSelector" />するパーティションを指定するデータの損失に起因する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-430">The <see cref="T:System.Fabric.PartitionSelector" /> to specify which partition data loss needs to be induced for.</span></span></param>
        <param name="dataLossMode"><span data-ttu-id="f599e-431">指定します、<see cref="T:System.Fabric.DataLossMode" />データの損失を発生させることのオプションなどです。</span><span class="sxs-lookup"><span data-stu-id="f599e-431">Specifies the <see cref="T:System.Fabric.DataLossMode" /> i.e. the options for inducing data loss.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="f599e-432">操作の全体的なタイムアウト</span><span class="sxs-lookup"><span data-stu-id="f599e-432">The overall timeout for the operation</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-433">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-433">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-434">この API は、指定されたパーティションのデータ損失を強制的に実行します。</span><span class="sxs-lookup"><span data-stu-id="f599e-434">This API will induce data loss for the specified partition.</span></span> <span data-ttu-id="f599e-435">パーティションの OnDataLoss API への呼び出しがトリガーされます。</span><span class="sxs-lookup"><span data-stu-id="f599e-435">It will trigger a call to the OnDataLoss API of the partition.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-436">データ損失のパーティションに関する情報を提供する InvokeDataLossResult が選択されました。</span><span class="sxs-lookup"><span data-stu-id="f599e-436">InvokeDataLossResult which gives information about the Partition that was selected for data loss.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-437">指定した実際のデータ損失が異なります<see cref="T:System.Fabric.DataLossMode" />PartialDataLoss - PartialDataLoss - クォーラムのみのレプリカを削除し、パーティションの OnDataLoss がトリガーされますが実際のデータ損失がインフライトのレプリケーションの存在に依存します。</span><span class="sxs-lookup"><span data-stu-id="f599e-437">Actual data loss will depend on the specified <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - Only a quorum of replicas are removed and OnDataLoss is triggered for the partition but actual data loss depends on presence of in-flight replication.</span></span>
            <span data-ttu-id="f599e-438">FullDataLoss - すべてのレプリカは、すべてのデータが失われるため削除し、OnDataLoss がトリガーされます。</span><span class="sxs-lookup"><span data-stu-id="f599e-438">FullDataLoss - All replicas are removed hence all data is lost and OnDataLoss is triggered.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-439">この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-439">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-440">ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。</span><span class="sxs-lookup"><span data-stu-id="f599e-440">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-441">重要な注意事項: この API は、実行中に中断できないする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-441">Important note:  this API should not be aborted while running.</span></span>  <span data-ttu-id="f599e-442">実行中に、この API を中止する可能性があります残した状態です。</span><span class="sxs-lookup"><span data-stu-id="f599e-442">Aborting this API while it is running may leave state behind.</span></span>  
            <span data-ttu-id="f599e-443">この API は、実行中に中止されましたが場合に、残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-443">If this API is aborted while running, CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-444">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-444">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-445">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="f599e-445">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="f599e-446">場合は、API は、ステートレスなサービスに属しているパーティションに対して呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="f599e-446">If the API is called for a partition belonging to a stateless service.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="f599e-447">これらは、選択されている、指定されたパーティションが存在しない場合に、ファブリック エラー FabricErrorCode.PartitionNotFound - です。</span><span class="sxs-lookup"><span data-stu-id="f599e-447">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumLossMode, TimeSpan quorumLossDuration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumLossMode, valuetype System.TimeSpan quorumLossDuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeQuorumLossAsync(System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.InvokeQuorumLossAsync : System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;" Usage="testManagementClient.InvokeQuorumLossAsync (partitionSelector, quorumLossMode, quorumLossDuration)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionQuorumLossAsync instead.  StartPartitionQuorumLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumLossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumLossDuration" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="f599e-448">クォーラム損失に起動されるパーティションです。</span><span class="sxs-lookup"><span data-stu-id="f599e-448">Partition which the quorum loss will be invoked.</span></span> <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumLossMode"><span data-ttu-id="f599e-449">PartialQuorumLoss または FullQuorumLoss します。</span><span class="sxs-lookup"><span data-stu-id="f599e-449">PartialQuorumLoss or FullQuorumLoss.</span></span></param>
        <param name="quorumLossDuration"><span data-ttu-id="f599e-450">クォーラム損失にパーティションを保持する時間の長さ。</span><span class="sxs-lookup"><span data-stu-id="f599e-450">Amount of time for which the partition will be kept in quorum loss.</span></span></param>
        <summary><span data-ttu-id="f599e-451">特定のステートフル サービス パーティションをクォーラム損失状態にします。</span><span class="sxs-lookup"><span data-stu-id="f599e-451">Induces quorum loss for a given stateful service partition.</span></span> </summary>
        <returns><span data-ttu-id="f599e-452">InvokeQuorumLossResult<see cref="T:System.Fabric.Result.InvokeQuorumLossResult" /></span><span class="sxs-lookup"><span data-stu-id="f599e-452">InvokeQuorumLossResult <see cref="T:System.Fabric.Result.InvokeQuorumLossResult" /></span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-453">FullQuorumLoss - ターゲット パーティションのすべてのレプリカを停止したりされます。</span><span class="sxs-lookup"><span data-stu-id="f599e-453">FullQuorumLoss - All replicas for the target partition will be downed.</span></span>
            <span data-ttu-id="f599e-454">PartialQuorumLoss - ターゲット パーティションのレプリカのクォーラムを停止したり、.</span><span class="sxs-lookup"><span data-stu-id="f599e-454">PartialQuorumLoss - A quorum of replicas for the target partition will be downed..</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-455">quorumLossMode では、クォーラムの損失が発生するために障害がレプリカの数を示します。</span><span class="sxs-lookup"><span data-stu-id="f599e-455">quorumLossMode indicates the number of replicas that will be faulted in order to cause quorum loss.</span></span> <span data-ttu-id="f599e-456">パーティションは、quorumLossDuration のクォーラム損失に残ります。</span><span class="sxs-lookup"><span data-stu-id="f599e-456">The partition will remain in quorum loss for quorumLossDuration.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-457">この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-457">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-458">ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。</span><span class="sxs-lookup"><span data-stu-id="f599e-458">Calling this API with a system service as the target is not advised.</span></span>                 
            </para>
          <para>
            <span data-ttu-id="f599e-459">重要な注意事項: この API は、実行中に中断できないする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-459">Important note:  this API should not be aborted while running.</span></span>  <span data-ttu-id="f599e-460">実行中に、この API を中止する可能性があります残した状態です。</span><span class="sxs-lookup"><span data-stu-id="f599e-460">Aborting this API while it is running may leave state behind.</span></span>  
            <span data-ttu-id="f599e-461">この API は、実行中に中止されましたが場合に、残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-461">If this API is aborted while running, CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-462">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-462">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="f599e-463">非同期操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="f599e-463">Async operation is canceled.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"> <span data-ttu-id="f599e-464">指定されたパーティションは、ステートフルな永続化サービスの一部ではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-464">Partition specified is not a part of a stateful Persisted Service.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumLossMode, TimeSpan quorumLossDuration, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumLossMode, valuetype System.TimeSpan quorumLossDuration, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeQuorumLossAsync(System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeQuorumLossAsync : System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;" Usage="testManagementClient.InvokeQuorumLossAsync (partitionSelector, quorumLossMode, quorumLossDuration, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionQuorumLossAsync instead.  StartPartitionQuorumLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumLossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumLossDuration" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="f599e-465">クォーラム損失に起動されるパーティションです。</span><span class="sxs-lookup"><span data-stu-id="f599e-465">Partition which the quorum loss will be invoked.</span></span> <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumLossMode"><span data-ttu-id="f599e-466">PartialQuorumLoss または FullQuorumLoss します。</span><span class="sxs-lookup"><span data-stu-id="f599e-466">PartialQuorumLoss or FullQuorumLoss.</span></span></param>
        <param name="quorumLossDuration"><span data-ttu-id="f599e-467">クォーラム損失にパーティションを保持する時間の長さ。</span><span class="sxs-lookup"><span data-stu-id="f599e-467">Amount of time for which the partition will be kept in quorum loss.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-468">操作のキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f599e-468">The cancellation token for the operation.</span></span></param>
        <summary><span data-ttu-id="f599e-469">特定のステートフル サービス パーティションをクォーラム損失状態にします。</span><span class="sxs-lookup"><span data-stu-id="f599e-469">Induces quorum loss for a given stateful service partition.</span></span> </summary>
        <returns><span data-ttu-id="f599e-470">InvokeQuorumLossResult<see cref="T:System.Fabric.Result.InvokeQuorumLossResult" /></span><span class="sxs-lookup"><span data-stu-id="f599e-470">InvokeQuorumLossResult <see cref="T:System.Fabric.Result.InvokeQuorumLossResult" /></span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-471">FullQuorumLoss - ターゲット パーティションのすべてのレプリカを停止したりされます。</span><span class="sxs-lookup"><span data-stu-id="f599e-471">FullQuorumLoss - All replicas for the target partition will be downed.</span></span>
            <span data-ttu-id="f599e-472">PartialQuorumLoss - ターゲット パーティションのレプリカのクォーラムを停止したり、.</span><span class="sxs-lookup"><span data-stu-id="f599e-472">PartialQuorumLoss - A quorum of replicas for the target partition will be downed..</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-473">quorumLossMode では、クォーラムの損失が発生するために障害がレプリカの数を示します。</span><span class="sxs-lookup"><span data-stu-id="f599e-473">quorumLossMode indicates the number of replicas that will be faulted in order to cause quorum loss.</span></span> <span data-ttu-id="f599e-474">パーティションは、quorumLossDuration のクォーラム損失に残ります。</span><span class="sxs-lookup"><span data-stu-id="f599e-474">The partition will remain in quorum loss for quorumLossDuration.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-475">この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-475">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-476">ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。</span><span class="sxs-lookup"><span data-stu-id="f599e-476">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-477">重要な注意事項: この API は、実行中に中断できないする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-477">Important note:  this API should not be aborted while running.</span></span>  <span data-ttu-id="f599e-478">実行中に、この API を中止する可能性があります残した状態です。</span><span class="sxs-lookup"><span data-stu-id="f599e-478">Aborting this API while it is running may leave state behind.</span></span>  
            <span data-ttu-id="f599e-479">この API は、実行中に中止されましたが場合に、残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-479">If this API is aborted while running, CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-480">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-480">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="f599e-481">非同期操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="f599e-481">Async operation is canceled.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"> <span data-ttu-id="f599e-482">指定されたパーティションは、ステートフルな永続化サービスの一部ではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-482">Partition specified is not a part of a stateful Persisted Service.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumLossMode, TimeSpan quorumLossDuration, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumLossMode, valuetype System.TimeSpan quorumLossDuration, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeQuorumLossAsync(System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.InvokeQuorumLossAsync : System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;" Usage="testManagementClient.InvokeQuorumLossAsync (partitionSelector, quorumLossMode, quorumLossDuration, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionQuorumLossAsync instead.  StartPartitionQuorumLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumLossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumLossDuration" Type="System.TimeSpan" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="f599e-483">クォーラム損失に起動されるパーティションです。</span><span class="sxs-lookup"><span data-stu-id="f599e-483">Partition which the quorum loss will be invoked.</span></span> <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumLossMode"><span data-ttu-id="f599e-484">PartialQuorumLoss または FullQuorumLoss します。</span><span class="sxs-lookup"><span data-stu-id="f599e-484">PartialQuorumLoss or FullQuorumLoss.</span></span></param>
        <param name="quorumLossDuration"><span data-ttu-id="f599e-485">クォーラム損失にパーティションを保持する時間の長さ。</span><span class="sxs-lookup"><span data-stu-id="f599e-485">Amount of time for which the partition will be kept in quorum loss.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="f599e-486">すべての操作の全体的なタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="f599e-486">Overall timeout for the entire operation.</span></span></param>
        <summary><span data-ttu-id="f599e-487">特定のステートフル サービス パーティションをクォーラム損失状態にします。</span><span class="sxs-lookup"><span data-stu-id="f599e-487">Induces quorum loss for a given stateful service partition.</span></span> </summary>
        <returns><span data-ttu-id="f599e-488">InvokeQuorumLossResult<see cref="T:System.Fabric.Result.InvokeQuorumLossResult" /></span><span class="sxs-lookup"><span data-stu-id="f599e-488">InvokeQuorumLossResult <see cref="T:System.Fabric.Result.InvokeQuorumLossResult" /></span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-489">FullQuorumLoss - ターゲット パーティションのすべてのレプリカを停止したりされます。</span><span class="sxs-lookup"><span data-stu-id="f599e-489">FullQuorumLoss - All replicas for the target partition will be downed.</span></span>
            <span data-ttu-id="f599e-490">PartialQuorumLoss - ターゲット パーティションのレプリカのクォーラムを停止したり、.</span><span class="sxs-lookup"><span data-stu-id="f599e-490">PartialQuorumLoss - A quorum of replicas for the target partition will be downed..</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-491">quorumLossMode では、クォーラムの損失が発生するために障害がレプリカの数を示します。</span><span class="sxs-lookup"><span data-stu-id="f599e-491">quorumLossMode indicates the number of replicas that will be faulted in order to cause quorum loss.</span></span> <span data-ttu-id="f599e-492">パーティションは、quorumLossDuration のクォーラム損失に残ります。</span><span class="sxs-lookup"><span data-stu-id="f599e-492">The partition will remain in quorum loss for quorumLossDuration.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-493">この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-493">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-494">ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。</span><span class="sxs-lookup"><span data-stu-id="f599e-494">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-495">重要な注意事項: この API は、実行中に中断できないする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-495">Important note:  this API should not be aborted while running.</span></span>  <span data-ttu-id="f599e-496">実行中に、この API を中止する可能性があります残した状態です。</span><span class="sxs-lookup"><span data-stu-id="f599e-496">Aborting this API while it is running may leave state behind.</span></span>  
            <span data-ttu-id="f599e-497">この API は、実行中に中止されましたが場合に、残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-497">If this API is aborted while running, CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-498">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-498">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="f599e-499">非同期操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="f599e-499">Async operation is canceled.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"> <span data-ttu-id="f599e-500">指定されたパーティションは、ステートフルな永続化サービスの一部ではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-500">Partition specified is not a part of a stateful Persisted Service.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumlossMode, TimeSpan quorumlossDuration, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumlossMode, valuetype System.TimeSpan quorumlossDuration, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeQuorumLossAsync(System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeQuorumLossAsync : System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;" Usage="testManagementClient.InvokeQuorumLossAsync (partitionSelector, quorumlossMode, quorumlossDuration, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionQuorumLossAsync instead.  StartPartitionQuorumLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumlossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumlossDuration" Type="System.TimeSpan" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="f599e-501">クォーラム損失に起動されるパーティションです。</span><span class="sxs-lookup"><span data-stu-id="f599e-501">Partition which the quorum loss will be invoked.</span></span> <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumlossMode"><span data-ttu-id="f599e-502">PartialQuorumLoss または FullQuorumLoss します。</span><span class="sxs-lookup"><span data-stu-id="f599e-502">PartialQuorumLoss or FullQuorumLoss.</span></span></param>
        <param name="quorumlossDuration"><span data-ttu-id="f599e-503">クォーラム損失にパーティションを保持する時間の長さ。</span><span class="sxs-lookup"><span data-stu-id="f599e-503">Amount of time for which the partition will be kept in quorum loss.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="f599e-504">すべての操作の全体的なタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="f599e-504">Overall timeout for the entire operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-505">操作のキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f599e-505">The cancellation token for the operation.</span></span></param>
        <summary><span data-ttu-id="f599e-506">特定のステートフル サービス パーティションをクォーラム損失状態にします。</span><span class="sxs-lookup"><span data-stu-id="f599e-506">Induces quorum loss for a given stateful service partition.</span></span> </summary>
        <returns><span data-ttu-id="f599e-507">InvokeQuorumLossResult<see cref="T:System.Fabric.Result.InvokeQuorumLossResult" /></span><span class="sxs-lookup"><span data-stu-id="f599e-507">InvokeQuorumLossResult <see cref="T:System.Fabric.Result.InvokeQuorumLossResult" /></span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-508">FullQuorumLoss - ターゲット パーティションのすべてのレプリカを停止したりされます。</span><span class="sxs-lookup"><span data-stu-id="f599e-508">FullQuorumLoss - All replicas for the target partition will be downed.</span></span>
            <span data-ttu-id="f599e-509">PartialQuorumLoss - ターゲット パーティションのレプリカのクォーラムを停止したり、.</span><span class="sxs-lookup"><span data-stu-id="f599e-509">PartialQuorumLoss - A quorum of replicas for the target partition will be downed..</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-510">quorumLossMode では、クォーラムの損失が発生するために障害がレプリカの数を示します。</span><span class="sxs-lookup"><span data-stu-id="f599e-510">quorumLossMode indicates the number of replicas that will be faulted in order to cause quorum loss.</span></span> <span data-ttu-id="f599e-511">パーティションは、quorumLossDuration のクォーラム損失に残ります。</span><span class="sxs-lookup"><span data-stu-id="f599e-511">The partition will remain in quorum loss for quorumLossDuration.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-512">この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-512">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-513">ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。</span><span class="sxs-lookup"><span data-stu-id="f599e-513">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-514">重要な注意事項: この API は、実行中に中断できないする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-514">Important note:  this API should not be aborted while running.</span></span>  <span data-ttu-id="f599e-515">実行中に、この API を中止する可能性があります残した状態です。</span><span class="sxs-lookup"><span data-stu-id="f599e-515">Aborting this API while it is running may leave state behind.</span></span>  
            <span data-ttu-id="f599e-516">この API は、実行中に中止されましたが場合に、残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-516">If this API is aborted while running, CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-517">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-517">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="f599e-518">非同期操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="f599e-518">Async operation is canceled.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"> <span data-ttu-id="f599e-519">指定されたパーティションは、ステートフルな永続化サービスの一部ではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-519">Partition specified is not a part of a stateful Persisted Service.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.RestartPartitionAsync(System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartPartitionAsync : System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;" Usage="testManagementClient.RestartPartitionAsync (partitionSelector, restartPartitionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionRestartAsync instead.  StartPartitionRestartAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">
          <span data-ttu-id="f599e-520"><see cref="T:System.Fabric.PartitionSelector" />再起動する必要があるパーティションを指定します。</span><span class="sxs-lookup"><span data-stu-id="f599e-520"><see cref="T:System.Fabric.PartitionSelector" /> that specifies the partition which needs to be restarted.</span></span></param>
        <param name="restartPartitionMode"><span data-ttu-id="f599e-521"><see cref="T:System.Fabric.RestartPartitionMode" /> AllReplicasOrInstances できるまたは OnlyActiveSecondaries が再起動するレプリカが選択されているに基づいて。</span><span class="sxs-lookup"><span data-stu-id="f599e-521">The <see cref="T:System.Fabric.RestartPartitionMode" /> which can be AllReplicasOrInstances or OnlyActiveSecondaries based on which the replicas to be restarted are selected.</span></span></param>
        <summary>
            <span data-ttu-id="f599e-522">この API は、(すべてのレプリカがダウンしている同時ににより)、同時に、パーティションのレプリカの一部またはすべてを再起動によって、<see cref="T:System.Fabric.RestartPartitionMode" />です。</span><span class="sxs-lookup"><span data-stu-id="f599e-522">This API will restart some or all the replicas of a partition at the same time (ensures all the replicas are down concurrently) depending on the <see cref="T:System.Fabric.RestartPartitionMode" />.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-523">RestartPartitionResult が実際選択されたパーティションに関する情報を得られます。</span><span class="sxs-lookup"><span data-stu-id="f599e-523">RestartPartitionResult which gives information about the actual selected partition.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-524">この API は、完全または部分的な再起動後に、パーティションの復元時間をテストし、テスト フェールオーバーに便利です。</span><span class="sxs-lookup"><span data-stu-id="f599e-524">This API is useful to test the recovery time of a partition after a full or partial restart and also to test failover.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-525">この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-525">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-526">重要な注意事項: この API は、実行中に中断できないする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-526">Important note:  this API should not be aborted while running.</span></span>  <span data-ttu-id="f599e-527">実行中に、この API を中止する可能性があります残した状態です。</span><span class="sxs-lookup"><span data-stu-id="f599e-527">Aborting this API while it is running may leave state behind.</span></span>  
            <span data-ttu-id="f599e-528">この API は、実行中に中止されましたが場合に、残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-528">If this API is aborted while running, CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-529">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-529">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-530">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="f599e-530">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="f599e-531">ステートレスなサービスに属しているパーティションに対して、API が呼び出されたかどうか<see cref="T:System.Fabric.RestartPartitionMode" />OnlyActiveSecondaries に設定します。</span><span class="sxs-lookup"><span data-stu-id="f599e-531">If the API is called for a partition belonging to a stateless service with <see cref="T:System.Fabric.RestartPartitionMode" /> set to OnlyActiveSecondaries.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="f599e-532">これらは、選択されている、指定されたパーティションが存在しない場合に、ファブリック エラー FabricErrorCode.PartitionNotFound - です。</span><span class="sxs-lookup"><span data-stu-id="f599e-532">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.RestartPartitionAsync(System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartPartitionAsync : System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;" Usage="testManagementClient.RestartPartitionAsync (partitionSelector, restartPartitionMode, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionRestartAsync instead.  StartPartitionRestartAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">
          <span data-ttu-id="f599e-533"><see cref="T:System.Fabric.PartitionSelector" />再起動する必要があるパーティションを指定します。</span><span class="sxs-lookup"><span data-stu-id="f599e-533"><see cref="T:System.Fabric.PartitionSelector" /> that specifies the partition which needs to be restarted</span></span></param>
        <param name="restartPartitionMode"><span data-ttu-id="f599e-534"><see cref="T:System.Fabric.RestartPartitionMode" /> AllReplicasOrInstances できるまたは OnlyActiveSecondaries が再起動するレプリカが選択されているに基づいて。</span><span class="sxs-lookup"><span data-stu-id="f599e-534">The <see cref="T:System.Fabric.RestartPartitionMode" /> which can be AllReplicasOrInstances or OnlyActiveSecondaries based on which the replicas to be restarted are selected.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-535">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-535">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-536">この API は、(すべてのレプリカがダウンしている同時ににより)、同時に、パーティションのレプリカの一部またはすべてを再起動によって、<see cref="T:System.Fabric.RestartPartitionMode" />です。</span><span class="sxs-lookup"><span data-stu-id="f599e-536">This API will restart some or all the replicas of a partition at the same time (ensures all the replicas are down concurrently) depending on the <see cref="T:System.Fabric.RestartPartitionMode" />.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-537">RestartPartitionResult が実際選択されたパーティションに関する情報を得られます。</span><span class="sxs-lookup"><span data-stu-id="f599e-537">RestartPartitionResult which gives information about the actual selected partition</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-538">この API は、完全または部分的な再起動後に、パーティションの復元時間をテストし、テスト フェールオーバーに便利です。</span><span class="sxs-lookup"><span data-stu-id="f599e-538">This API is useful to test the recovery time of a partition after a full or partial restart and also to test failover.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-539">この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-539">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-540">重要な注意事項: この API は、実行中に中断できないする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-540">Important note:  this API should not be aborted while running.</span></span>  <span data-ttu-id="f599e-541">実行中に、この API を中止する可能性があります残した状態です。</span><span class="sxs-lookup"><span data-stu-id="f599e-541">Aborting this API while it is running may leave state behind.</span></span>  
            <span data-ttu-id="f599e-542">この API は、実行中に中止されましたが場合に、残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-542">If this API is aborted while running, CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-543">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-543">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-544">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="f599e-544">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="f599e-545">ステートレスなサービスに属しているパーティションに対して、API が呼び出されたかどうか<see cref="T:System.Fabric.RestartPartitionMode" />OnlyActiveSecondaries に設定します。</span><span class="sxs-lookup"><span data-stu-id="f599e-545">If the API is called for a partition belonging to a stateless service with <see cref="T:System.Fabric.RestartPartitionMode" /> set to OnlyActiveSecondaries.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="f599e-546">選択されている、指定されたパーティションが存在しない場合、これらは、ファブリック エラー FabricErrorCode.PartitionNotFound-</span><span class="sxs-lookup"><span data-stu-id="f599e-546">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.RestartPartitionAsync(System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RestartPartitionAsync : System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;" Usage="testManagementClient.RestartPartitionAsync (partitionSelector, restartPartitionMode, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionRestartAsync instead.  StartPartitionRestartAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">
          <span data-ttu-id="f599e-547"><see cref="T:System.Fabric.PartitionSelector" />再起動する必要があるパーティションを指定します。</span><span class="sxs-lookup"><span data-stu-id="f599e-547"><see cref="T:System.Fabric.PartitionSelector" /> that specifies the partition which needs to be restarted.</span></span></param>
        <param name="restartPartitionMode"><span data-ttu-id="f599e-548"><see cref="T:System.Fabric.RestartPartitionMode" /> AllReplicasOrInstances できるまたは OnlyActiveSecondaries が再起動するレプリカが選択されているに基づいて。</span><span class="sxs-lookup"><span data-stu-id="f599e-548">The <see cref="T:System.Fabric.RestartPartitionMode" /> which can be AllReplicasOrInstances or OnlyActiveSecondaries based on which the replicas to be restarted are selected.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="f599e-549">操作の全体的なタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="f599e-549">The overall timeout for the operation.</span></span></param>
        <summary>
            <span data-ttu-id="f599e-550">この API は、(すべてのレプリカがダウンしている同時ににより)、同時に、パーティションのレプリカの一部またはすべてを再起動によって、<see cref="T:System.Fabric.RestartPartitionMode" />です。</span><span class="sxs-lookup"><span data-stu-id="f599e-550">This API will restart some or all the replicas of a partition at the same time (ensures all the replicas are down concurrently) depending on the <see cref="T:System.Fabric.RestartPartitionMode" />.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-551">RestartPartitionResult が実際選択されたパーティションに関する情報を得られます。</span><span class="sxs-lookup"><span data-stu-id="f599e-551">RestartPartitionResult which gives information about the actual selected partition.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-552">この API は、完全または部分的な再起動後に、パーティションの復元時間をテストし、テスト フェールオーバーに便利です。</span><span class="sxs-lookup"><span data-stu-id="f599e-552">This API is useful to test the recovery time of a partition after a full or partial restart and also to test failover.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-553">この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-553">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-554">重要な注意事項: この API は、実行中に中断できないする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-554">Important note:  this API should not be aborted while running.</span></span>  <span data-ttu-id="f599e-555">実行中に、この API を中止する可能性があります残した状態です。</span><span class="sxs-lookup"><span data-stu-id="f599e-555">Aborting this API while it is running may leave state behind.</span></span>  
            <span data-ttu-id="f599e-556">この API は、実行中に中止されましたが場合に、残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-556">If this API is aborted while running, CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-557">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-557">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-558">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="f599e-558">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="f599e-559">ステートレスなサービスに属しているパーティションに対して、API が呼び出されたかどうか<see cref="T:System.Fabric.RestartPartitionMode" />OnlyActiveSecondaries に設定します。</span><span class="sxs-lookup"><span data-stu-id="f599e-559">If the API is called for a partition belonging to a stateless service with <see cref="T:System.Fabric.RestartPartitionMode" /> set to OnlyActiveSecondaries.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="f599e-560">選択されている、指定されたパーティションが存在しない場合、これらは、ファブリック エラー FabricErrorCode.PartitionNotFound-</span><span class="sxs-lookup"><span data-stu-id="f599e-560">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.RestartPartitionAsync(System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartPartitionAsync : System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;" Usage="testManagementClient.RestartPartitionAsync (partitionSelector, restartPartitionMode, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionRestartAsync instead.  StartPartitionRestartAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">
          <span data-ttu-id="f599e-561"><see cref="T:System.Fabric.PartitionSelector" />再起動する必要があるパーティションを指定します。</span><span class="sxs-lookup"><span data-stu-id="f599e-561"><see cref="T:System.Fabric.PartitionSelector" /> that specifies the partition which needs to be restarted.</span></span></param>
        <param name="restartPartitionMode"><span data-ttu-id="f599e-562"><see cref="T:System.Fabric.RestartPartitionMode" /> AllReplicasOrInstances できるまたは OnlyActiveSecondaries が再起動するレプリカが選択されているに基づいて。</span><span class="sxs-lookup"><span data-stu-id="f599e-562">The <see cref="T:System.Fabric.RestartPartitionMode" /> which can be AllReplicasOrInstances or OnlyActiveSecondaries based on which the replicas to be restarted are selected.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="f599e-563">操作の全体的なタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="f599e-563">The overall timeout for the operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-564">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-564">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-565">この API は、(すべてのレプリカがダウンしている同時ににより)、同時に、パーティションのレプリカの一部またはすべてを再起動によって、<see cref="T:System.Fabric.RestartPartitionMode" />です。</span><span class="sxs-lookup"><span data-stu-id="f599e-565">This API will restart some or all the replicas of a partition at the same time (ensures all the replicas are down concurrently) depending on the <see cref="T:System.Fabric.RestartPartitionMode" />.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-566">RestartPartitionResult が実際選択されたパーティションに関する情報を得られます。</span><span class="sxs-lookup"><span data-stu-id="f599e-566">RestartPartitionResult which gives information about the actual selected partition.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-567">この API は、完全または部分的な再起動後に、パーティションの復元時間をテストし、テスト フェールオーバーに便利です。</span><span class="sxs-lookup"><span data-stu-id="f599e-567">This API is useful to test the recovery time of a partition after a full or partial restart and also to test failover.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-568">この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-568">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-569">重要な注意事項: この API は、実行中に中断できないする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-569">Important note:  this API should not be aborted while running.</span></span>  <span data-ttu-id="f599e-570">実行中に、この API を中止する可能性があります残した状態です。</span><span class="sxs-lookup"><span data-stu-id="f599e-570">Aborting this API while it is running may leave state behind.</span></span>  
            <span data-ttu-id="f599e-571">この API は、実行中に中止されましたが場合に、残る可能性が状態を削除する CleanTestStateAsync() を呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-571">If this API is aborted while running, CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-572">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-572">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-573">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="f599e-573">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="f599e-574">ステートレスなサービスに属しているパーティションに対して、API が呼び出されたかどうか<see cref="T:System.Fabric.RestartPartitionMode" />OnlyActiveSecondaries に設定します。</span><span class="sxs-lookup"><span data-stu-id="f599e-574">If the API is called for a partition belonging to a stateless service with <see cref="T:System.Fabric.RestartPartitionMode" /> set to OnlyActiveSecondaries.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="f599e-575">選択されている、指定されたパーティションが存在しない場合、これらは、ファブリック エラー FabricErrorCode.PartitionNotFound-</span><span class="sxs-lookup"><span data-stu-id="f599e-575">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartChaosAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartChaosAsync (System.Fabric.Chaos.DataStructures.ChaosParameters chaosParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartChaosAsync(class System.Fabric.Chaos.DataStructures.ChaosParameters chaosParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartChaosAsync(System.Fabric.Chaos.DataStructures.ChaosParameters)" />
      <MemberSignature Language="F#" Value="member this.StartChaosAsync : System.Fabric.Chaos.DataStructures.ChaosParameters -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartChaosAsync chaosParameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="chaosParameters" Type="System.Fabric.Chaos.DataStructures.ChaosParameters" />
      </Parameters>
      <Docs>
        <param name="chaosParameters">
          <span data-ttu-id="f599e-576"><see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" />Chaos; を制御するためのさまざまなパラメーターが含まれていますなど、実行時間、同時実行 fautls などの最大数。</span><span class="sxs-lookup"><span data-stu-id="f599e-576"><see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" /> contains various parameters for controlling Chaos; e.g., time to run, maximum number of concurrent fautls, etc.</span></span> </param>
        <summary>
            <span data-ttu-id="f599e-577">この API は、指定されたパラメーター値を持つ Chaos を始めます。</span><span class="sxs-lookup"><span data-stu-id="f599e-577">This API will start Chaos with the supplied parameter values.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-578">タスク。</span><span class="sxs-lookup"><span data-stu-id="f599e-578">A task.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-579">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-579">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-580">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="f599e-580">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricChaosAlreadyRunningException"><span data-ttu-id="f599e-581">クラスターで混乱が既に実行されているときに、StartChaos API が呼び出されたときに、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="f599e-581">This exception is thrown when StartChaos API is invoked while Chaos is already running in the cluster.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartChaosAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartChaosAsync (System.Fabric.Chaos.DataStructures.ChaosParameters chaosParameters, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartChaosAsync(class System.Fabric.Chaos.DataStructures.ChaosParameters chaosParameters, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartChaosAsync(System.Fabric.Chaos.DataStructures.ChaosParameters,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartChaosAsync : System.Fabric.Chaos.DataStructures.ChaosParameters * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartChaosAsync (chaosParameters, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="chaosParameters" Type="System.Fabric.Chaos.DataStructures.ChaosParameters" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="chaosParameters"> <span data-ttu-id="f599e-582">Chaos; を制御するためのさまざまなパラメーターが含まれていますなど、実行時間など、同時実行エラーの最大数。</span><span class="sxs-lookup"><span data-stu-id="f599e-582">Contains various parameters for controlling Chaos; e.g., time to run, maximum number of concurrent faults, etc.</span></span></param>
        <param name="operationTimeout"> <span data-ttu-id="f599e-583">操作の全体的なタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="f599e-583">The overall timeout for the operation.</span></span></param>
        <param name="cancellationToken"> <span data-ttu-id="f599e-584">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f599e-584">Cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="f599e-585">この API は、指定されたパラメーター値を持つ Chaos を始めます。</span><span class="sxs-lookup"><span data-stu-id="f599e-585">This API will start Chaos with the supplied parameter values.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-586">タスク。</span><span class="sxs-lookup"><span data-stu-id="f599e-586">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-587">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-587">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-588">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-588">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-589">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="f599e-589">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricChaosAlreadyRunningException"><span data-ttu-id="f599e-590">クラスターで混乱が既に実行されているときに、StartChaos API が呼び出されたときに、この例外がスローされます。</span><span class="sxs-lookup"><span data-stu-id="f599e-590">This exception is thrown when StartChaos API is invoked while Chaos is already running in the cluster.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartNodeTransitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartNodeTransitionAsync (System.Fabric.Description.NodeTransitionDescription description, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartNodeTransitionAsync(class System.Fabric.Description.NodeTransitionDescription description, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartNodeTransitionAsync(System.Fabric.Description.NodeTransitionDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function StartNodeTransitionAsync (description As NodeTransitionDescription, operationTimeout As TimeSpan, token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="member this.StartNodeTransitionAsync : System.Fabric.Description.NodeTransitionDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartNodeTransitionAsync (description, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.NodeTransitionDescription" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="f599e-591">実行するノードの移行の種類を説明するオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f599e-591">An object which describes what type of node transition to perform.</span></span>  <span data-ttu-id="f599e-592">移行を開始または停止するノードを指定できます。</span><span class="sxs-lookup"><span data-stu-id="f599e-592">The transition can be to start or stop a node.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="f599e-593">この API 呼び出しのタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="f599e-593">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="f599e-594">CancellationToken</span><span class="sxs-lookup"><span data-stu-id="f599e-594">The cancellationToken</span></span></param>
        <summary>
            <span data-ttu-id="f599e-595">クラスター ノードを開始または停止します。</span><span class="sxs-lookup"><span data-stu-id="f599e-595">Starts or stops a cluster node.</span></span>  <span data-ttu-id="f599e-596">クラスター ノードはプロセスで、OS インスタンスそのものではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-596">A cluster node is a process, not the OS instance itself.</span></span>  <span data-ttu-id="f599e-597">ノードを開始するには、description パラメーターに NodeStartDescription の型のオブジェクトに渡します。</span><span class="sxs-lookup"><span data-stu-id="f599e-597">To start a node, pass in an object of type NodeStartDescription into the description parameter.</span></span>  <span data-ttu-id="f599e-598">ノードを停止するには、型 NodeStopDescription のオブジェクトを渡します。</span><span class="sxs-lookup"><span data-stu-id="f599e-598">To stop a node, pass in an object of type NodeStopDescription.</span></span>  <span data-ttu-id="f599e-599">この API が返されると、操作の進行状況を取得する GetNodeTransitionProgressAsync() を呼び出します。</span><span class="sxs-lookup"><span data-stu-id="f599e-599">After this API returns, call GetNodeTransitionProgressAsync() to get progress on the operation.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-600">タスク</span><span class="sxs-lookup"><span data-stu-id="f599e-600">A task</span></span></returns>
        <remarks><span data-ttu-id="f599e-601">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-601">The FaultAnalysisService must be enabled to use this API.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="f599e-602"><see cref="P:System.Fabric.FabricException.ErrorCode" />プロパティには、その理由を示します。</span><span class="sxs-lookup"><span data-stu-id="f599e-602">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>        
              <span data-ttu-id="f599e-603">ErrorCode が InstanceIdMismatch の場合は、指定されたノード インスタンスは停止したノードのインスタンスを一致しません。</span><span class="sxs-lookup"><span data-stu-id="f599e-603">If the errorCode is InstanceIdMismatch, the nodeInstance provided does not match the instance of the node that was stopped.</span></span>      
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-604">操作がタイムアウトしたとき。</span><span class="sxs-lookup"><span data-stu-id="f599e-604">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-605">値は null の引数が渡されました。</span><span class="sxs-lookup"><span data-stu-id="f599e-605">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionDataLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionDataLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionDataLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.DataLossMode)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionDataLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.DataLossMode -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionDataLossAsync (operationId, partitionSelector, dataLossMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
      </Parameters>
      <Docs>
        <param name="operationId"> <span data-ttu-id="f599e-606">この API の呼び出しを識別する GUIDこれは、対応する GetProgress API に渡されます。</span><span class="sxs-lookup"><span data-stu-id="f599e-606">A GUID that identifies a call of this API; this is passed into the corresponding GetProgress API.</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="f599e-607"><see cref="T:System.Fabric.PartitionSelector" />するパーティションを指定するデータの損失は発生する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-607">The <see cref="T:System.Fabric.PartitionSelector" /> to specify which partition data loss needs to be induced.</span></span></param>
        <param name="dataLossMode"><span data-ttu-id="f599e-608">指定します、<see cref="T:System.Fabric.DataLossMode" />データの損失を発生させることのオプションなどです。</span><span class="sxs-lookup"><span data-stu-id="f599e-608">Specifies the <see cref="T:System.Fabric.DataLossMode" /> i.e. the options for inducing data loss.</span></span></param>
        <summary>
            <span data-ttu-id="f599e-609">この API は、指定されたパーティションのデータ損失を強制的に実行します。</span><span class="sxs-lookup"><span data-stu-id="f599e-609">This API will induce data loss for the specified partition.</span></span> <span data-ttu-id="f599e-610">パーティションの OnDataLoss API への呼び出しがトリガーされます。</span><span class="sxs-lookup"><span data-stu-id="f599e-610">It will trigger a call to the OnDataLoss API of the partition.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-611">タスク。</span><span class="sxs-lookup"><span data-stu-id="f599e-611">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-612">指定した実際のデータ損失が異なります<see cref="T:System.Fabric.DataLossMode" />です。</span><span class="sxs-lookup"><span data-stu-id="f599e-612">Actual data loss will depend on the specified <see cref="T:System.Fabric.DataLossMode" />.</span></span>
            <span data-ttu-id="f599e-613">PartialDataLoss - レプリカのクォーラムだけが削除されたと OnDataLoss はパーティションのトリガーしますが、実際のデータが失われるは、インフライトのレプリケーションの存在によって異なります。</span><span class="sxs-lookup"><span data-stu-id="f599e-613">PartialDataLoss - Only a quorum of replicas are removed and OnDataLoss is triggered for the partition but actual data loss depends on presence of in-flight replication.</span></span>
            <span data-ttu-id="f599e-614">FullDataLoss - すべてのレプリカは、すべてのデータが失われるため削除し、OnDataLoss がトリガーされます。</span><span class="sxs-lookup"><span data-stu-id="f599e-614">FullDataLoss - All replicas are removed hence all data is lost and OnDataLoss is triggered.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-615">この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-615">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-616">ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。</span><span class="sxs-lookup"><span data-stu-id="f599e-616">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-617">注: この API が呼び出された後に取り消すことができません。</span><span class="sxs-lookup"><span data-stu-id="f599e-617">Note:  Once this API has been called, it cannot be reversed.</span></span> <span data-ttu-id="f599e-618">CancelTestCommandAsync() を呼び出して、のみの実行を停止および内部システム状態をクリーンアップします。</span><span class="sxs-lookup"><span data-stu-id="f599e-618">Calling CancelTestCommandAsync() will only stop execution and clean up internal system state.</span></span>
            <span data-ttu-id="f599e-619">コマンドはデータの損失を十分に離れた進めた場合データは復元されません。</span><span class="sxs-lookup"><span data-stu-id="f599e-619">It will not restore data if the command has progressed far enough to cause data loss.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-620">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-620">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-621">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-621">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-622">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="f599e-622">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="f599e-623">場合は、API は、ステートレスなサービスに属しているパーティションに対して呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="f599e-623">If the API is called for a partition belonging to a stateless service.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="f599e-624">これらは、ファブリック エラーです。</span><span class="sxs-lookup"><span data-stu-id="f599e-624">These are the fabric failures.</span></span>
            <span data-ttu-id="f599e-625">FabricErrorCode.PartitionNotFound - 選択した指定したパーティションが存在しない場合。</span><span class="sxs-lookup"><span data-stu-id="f599e-625">FabricErrorCode.PartitionNotFound - If the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionDataLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionDataLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionDataLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.DataLossMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionDataLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.DataLossMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionDataLossAsync (operationId, partitionSelector, dataLossMode, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"> <span data-ttu-id="f599e-626">この API の呼び出しを識別する GUIDこれは、対応する GetProgress API に渡される</span><span class="sxs-lookup"><span data-stu-id="f599e-626">A GUID that identifies a call of this API; this is passed into the corresponding GetProgress API</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="f599e-627"><see cref="T:System.Fabric.PartitionSelector" />するパーティションを指定するデータの損失に起因する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-627">The <see cref="T:System.Fabric.PartitionSelector" /> to specify which partition data loss needs to be induced for.</span></span></param>
        <param name="dataLossMode"><span data-ttu-id="f599e-628">指定します、<see cref="T:System.Fabric.DataLossMode" />データの損失を発生させることのオプションなどです。</span><span class="sxs-lookup"><span data-stu-id="f599e-628">Specifies the <see cref="T:System.Fabric.DataLossMode" /> i.e. the options for inducing data loss.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-629">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-629">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-630">この API は、指定されたパーティションのデータ損失を強制的に実行します。</span><span class="sxs-lookup"><span data-stu-id="f599e-630">This API will induce data loss for the specified partition.</span></span> <span data-ttu-id="f599e-631">パーティションの OnDataLoss API への呼び出しがトリガーされます。</span><span class="sxs-lookup"><span data-stu-id="f599e-631">It will trigger a call to the OnDataLoss API of the partition.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-632">タスク。</span><span class="sxs-lookup"><span data-stu-id="f599e-632">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-633">指定した実際のデータ損失が異なります<see cref="T:System.Fabric.DataLossMode" />PartialDataLoss - PartialDataLoss - クォーラムのみのレプリカを削除し、パーティションの OnDataLoss がトリガーされますが実際のデータ損失が転送レプリケーションの存在に依存します。</span><span class="sxs-lookup"><span data-stu-id="f599e-633">Actual data loss will depend on the specified <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - Only a quorum of replicas are removed and OnDataLoss is triggered for the partition but actual data loss depends on presence of inflight replication.</span></span>
            <span data-ttu-id="f599e-634">FullDataLoss - すべてのレプリカは、すべてのデータが失われるため削除し、OnDataLoss がトリガーされます。</span><span class="sxs-lookup"><span data-stu-id="f599e-634">FullDataLoss - All replicas are removed hence all data is lost and OnDataLoss is triggered.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-635">この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-635">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-636">ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。</span><span class="sxs-lookup"><span data-stu-id="f599e-636">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-637">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-637">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-638">注: この API が呼び出された後に取り消すことができません。</span><span class="sxs-lookup"><span data-stu-id="f599e-638">Note:  Once this API has been called, it cannot be reversed.</span></span>  <span data-ttu-id="f599e-639">CancelTestCommandAsync() を呼び出して、のみの実行を停止および内部システム状態をクリーンアップします。</span><span class="sxs-lookup"><span data-stu-id="f599e-639">Calling CancelTestCommandAsync() will only stop execution and clean up internal system state.</span></span>  
            <span data-ttu-id="f599e-640">コマンドはデータの損失を十分に離れた進めた場合データは復元されません。</span><span class="sxs-lookup"><span data-stu-id="f599e-640">It will not restore data if the command has progressed far enough to cause data loss.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-641">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-641">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-642">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="f599e-642">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="f599e-643">場合は、API は、ステートレスなサービスに属しているパーティションに対して呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="f599e-643">If the API is called for a partition belonging to a stateless service.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="f599e-644">これらは、選択されている、指定されたパーティションが存在しない場合に、ファブリック エラー FabricErrorCode.PartitionNotFound - です。</span><span class="sxs-lookup"><span data-stu-id="f599e-644">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionDataLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionDataLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionDataLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.DataLossMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionDataLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.DataLossMode * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionDataLossAsync (operationId, partitionSelector, dataLossMode, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId"> <span data-ttu-id="f599e-645">この API の呼び出しを識別する GUIDこれは、対応する GetProgress API に渡される</span><span class="sxs-lookup"><span data-stu-id="f599e-645">A GUID that identifies a call of this API; this is passed into the corresponding GetProgress API</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="f599e-646"><see cref="T:System.Fabric.PartitionSelector" />するパーティションを指定するデータの損失に起因する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-646">The <see cref="T:System.Fabric.PartitionSelector" /> to specify which partition data loss needs to be induced for.</span></span></param>
        <param name="dataLossMode"><span data-ttu-id="f599e-647">指定します、<see cref="T:System.Fabric.DataLossMode" />データの損失を発生させることのオプションなどです。</span><span class="sxs-lookup"><span data-stu-id="f599e-647">Specifies the <see cref="T:System.Fabric.DataLossMode" /> i.e. the options for inducing data loss.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="f599e-648">操作の全体的なタイムアウト</span><span class="sxs-lookup"><span data-stu-id="f599e-648">The overall timeout for the operation</span></span></param>
        <summary>
            <span data-ttu-id="f599e-649">この API は、指定されたパーティションのデータ損失を強制的に実行します。</span><span class="sxs-lookup"><span data-stu-id="f599e-649">This API will induce data loss for the specified partition.</span></span> <span data-ttu-id="f599e-650">パーティションの OnDataLoss API への呼び出しがトリガーされます。</span><span class="sxs-lookup"><span data-stu-id="f599e-650">It will trigger a call to the OnDataLoss API of the partition.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-651">タスク。</span><span class="sxs-lookup"><span data-stu-id="f599e-651">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-652">指定した実際のデータ損失が異なります<see cref="T:System.Fabric.DataLossMode" />PartialDataLoss - PartialDataLoss - クォーラムのみのレプリカを削除し、パーティションの OnDataLoss がトリガーされますが実際のデータ損失がインフライトのレプリケーションの存在に依存します。</span><span class="sxs-lookup"><span data-stu-id="f599e-652">Actual data loss will depend on the specified <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - Only a quorum of replicas are removed and OnDataLoss is triggered for the partition but actual data loss depends on presence of in-flight replication.</span></span>
            <span data-ttu-id="f599e-653">FullDataLoss - すべてのレプリカは、すべてのデータが失われるため削除し、OnDataLoss がトリガーされます。</span><span class="sxs-lookup"><span data-stu-id="f599e-653">FullDataLoss - All replicas are removed hence all data is lost and OnDataLoss is triggered.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-654">この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-654">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-655">ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。</span><span class="sxs-lookup"><span data-stu-id="f599e-655">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-656">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-656">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-657">注: この API が呼び出された後に取り消すことができません。</span><span class="sxs-lookup"><span data-stu-id="f599e-657">Note:  Once this API has been called, it cannot be reversed.</span></span>  <span data-ttu-id="f599e-658">CancelTestCommandAsync() を呼び出して、のみの実行を停止および内部システム状態をクリーンアップします。</span><span class="sxs-lookup"><span data-stu-id="f599e-658">Calling CancelTestCommandAsync() will only stop execution and clean up internal system state.</span></span>  
            <span data-ttu-id="f599e-659">コマンドはデータの損失を十分に離れた進めた場合データは復元されません。</span><span class="sxs-lookup"><span data-stu-id="f599e-659">It will not restore data if the command has progressed far enough to cause data loss.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-660">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-660">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-661">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="f599e-661">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="f599e-662">場合は、API は、ステートレスなサービスに属しているパーティションに対して呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="f599e-662">If the API is called for a partition belonging to a stateless service.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="f599e-663">これらは、選択されている、指定されたパーティションが存在しない場合に、ファブリック エラー FabricErrorCode.PartitionNotFound - です。</span><span class="sxs-lookup"><span data-stu-id="f599e-663">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionDataLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionDataLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionDataLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.DataLossMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionDataLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.DataLossMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionDataLossAsync (operationId, partitionSelector, dataLossMode, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"> <span data-ttu-id="f599e-664">この API の呼び出しを識別する GUIDこれは、対応する GetProgress API に渡される</span><span class="sxs-lookup"><span data-stu-id="f599e-664">A GUID that identifies a call of this API; this is passed into the corresponding GetProgress API</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="f599e-665"><see cref="T:System.Fabric.PartitionSelector" />するパーティションを指定するデータの損失に起因する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-665">The <see cref="T:System.Fabric.PartitionSelector" /> to specify which partition data loss needs to be induced for.</span></span></param>
        <param name="dataLossMode"><span data-ttu-id="f599e-666">指定します、<see cref="T:System.Fabric.DataLossMode" />データの損失を発生させることのオプションなどです。</span><span class="sxs-lookup"><span data-stu-id="f599e-666">Specifies the <see cref="T:System.Fabric.DataLossMode" /> i.e. the options for inducing data loss.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="f599e-667">操作の全体的なタイムアウト</span><span class="sxs-lookup"><span data-stu-id="f599e-667">The overall timeout for the operation</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-668">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-668">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-669">この API は、指定されたパーティションのデータ損失を強制的に実行します。</span><span class="sxs-lookup"><span data-stu-id="f599e-669">This API will induce data loss for the specified partition.</span></span> <span data-ttu-id="f599e-670">パーティションの OnDataLoss API への呼び出しがトリガーされます。</span><span class="sxs-lookup"><span data-stu-id="f599e-670">It will trigger a call to the OnDataLoss API of the partition.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-671">タスク。</span><span class="sxs-lookup"><span data-stu-id="f599e-671">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-672">指定した実際のデータ損失が異なります<see cref="T:System.Fabric.DataLossMode" />PartialDataLoss - PartialDataLoss - クォーラムのみのレプリカを削除し、パーティションの OnDataLoss がトリガーされますが実際のデータ損失がインフライトのレプリケーションの存在に依存します。</span><span class="sxs-lookup"><span data-stu-id="f599e-672">Actual data loss will depend on the specified <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - Only a quorum of replicas are removed and OnDataLoss is triggered for the partition but actual data loss depends on presence of in-flight replication.</span></span>
            <span data-ttu-id="f599e-673">FullDataLoss - すべてのレプリカは、すべてのデータが失われるため削除し、OnDataLoss がトリガーされます。</span><span class="sxs-lookup"><span data-stu-id="f599e-673">FullDataLoss - All replicas are removed hence all data is lost and OnDataLoss is triggered.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-674">この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-674">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-675">ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。</span><span class="sxs-lookup"><span data-stu-id="f599e-675">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-676">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-676">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-677">注: この API が呼び出された後に取り消すことができません。</span><span class="sxs-lookup"><span data-stu-id="f599e-677">Note:  Once this API has been called, it cannot be reversed.</span></span>  <span data-ttu-id="f599e-678">CancelTestCommandAsync() を呼び出して、のみの実行を停止および内部システム状態をクリーンアップします。</span><span class="sxs-lookup"><span data-stu-id="f599e-678">Calling CancelTestCommandAsync() will only stop execution and clean up internal system state.</span></span>
            <span data-ttu-id="f599e-679">コマンドはデータの損失を十分に離れた進めた場合データは復元されません。</span><span class="sxs-lookup"><span data-stu-id="f599e-679">It will not restore data if the command has progressed far enough to cause data loss.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-680">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-680">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-681">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="f599e-681">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="f599e-682">場合は、API は、ステートレスなサービスに属しているパーティションに対して呼び出されます。</span><span class="sxs-lookup"><span data-stu-id="f599e-682">If the API is called for a partition belonging to a stateless service.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="f599e-683">これらは、選択されている、指定されたパーティションが存在しない場合に、ファブリック エラー FabricErrorCode.PartitionNotFound - です。</span><span class="sxs-lookup"><span data-stu-id="f599e-683">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionQuorumLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumLossMode, TimeSpan quorumLossDuration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionQuorumLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumLossMode, valuetype System.TimeSpan quorumLossDuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionQuorumLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionQuorumLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionQuorumLossAsync (operationId, partitionSelector, quorumLossMode, quorumLossDuration)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumLossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumLossDuration" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId"> <span data-ttu-id="f599e-684">ユーザー指定の識別子です。</span><span class="sxs-lookup"><span data-stu-id="f599e-684">A user-provided identifier.</span></span>  <span data-ttu-id="f599e-685">この識別子は、対応する GetProgress API に渡すこともできます。</span><span class="sxs-lookup"><span data-stu-id="f599e-685">This identifier can also be passed into the corresponding GetProgress API</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="f599e-686">クォーラム損失に起動されるパーティションです。</span><span class="sxs-lookup"><span data-stu-id="f599e-686">Partition which the quorum loss will be invoked.</span></span> <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumLossMode"><span data-ttu-id="f599e-687">PartialQuorumLoss または FullQuorumLoss します。</span><span class="sxs-lookup"><span data-stu-id="f599e-687">PartialQuorumLoss or FullQuorumLoss.</span></span></param>
        <param name="quorumLossDuration"><span data-ttu-id="f599e-688">クォーラム損失にパーティションを保持する時間の長さ。</span><span class="sxs-lookup"><span data-stu-id="f599e-688">Amount of time for which the partition will be kept in quorum loss.</span></span></param>
        <summary><span data-ttu-id="f599e-689">特定のステートフル サービス パーティションをクォーラム損失状態にします。</span><span class="sxs-lookup"><span data-stu-id="f599e-689">Induces quorum loss for a given stateful service partition.</span></span> </summary>
        <returns><span data-ttu-id="f599e-690">タスク。</span><span class="sxs-lookup"><span data-stu-id="f599e-690">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-691">FullQuorumLoss - ターゲット パーティションのすべてのレプリカを停止したりされます。</span><span class="sxs-lookup"><span data-stu-id="f599e-691">FullQuorumLoss - All replicas for the target partition will be downed.</span></span>
            <span data-ttu-id="f599e-692">PartialQuorumLoss - ターゲット パーティションのレプリカのクォーラムを停止したり、.</span><span class="sxs-lookup"><span data-stu-id="f599e-692">PartialQuorumLoss - A quorum of replicas for the target partition will be downed..</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-693">quorumLossMode では、クォーラムの損失が発生するために障害がレプリカの数を示します。</span><span class="sxs-lookup"><span data-stu-id="f599e-693">quorumLossMode indicates the number of replicas that will be faulted in order to cause quorum loss.</span></span> <span data-ttu-id="f599e-694">パーティションは、quorumLossDuration のクォーラム損失に残ります。</span><span class="sxs-lookup"><span data-stu-id="f599e-694">The partition will remain in quorum loss for quorumLossDuration.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-695">この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-695">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-696">ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。</span><span class="sxs-lookup"><span data-stu-id="f599e-696">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-697">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-697">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-698">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-698">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="f599e-699">非同期操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="f599e-699">Async operation is canceled.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"> <span data-ttu-id="f599e-700">指定されたパーティションは、ステートフルな永続化サービスの一部ではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-700">Partition specified is not a part of a stateful Persisted Service.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionQuorumLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumLossMode, TimeSpan quorumLossDuration, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionQuorumLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumLossMode, valuetype System.TimeSpan quorumLossDuration, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionQuorumLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionQuorumLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionQuorumLossAsync (operationId, partitionSelector, quorumLossMode, quorumLossDuration, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumLossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumLossDuration" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"> <span data-ttu-id="f599e-701">ユーザー指定の識別子です。</span><span class="sxs-lookup"><span data-stu-id="f599e-701">A user-provided identifier.</span></span>  <span data-ttu-id="f599e-702">この識別子は、対応する GetProgress API に渡すこともできます。</span><span class="sxs-lookup"><span data-stu-id="f599e-702">This identifier can also be passed into the corresponding GetProgress API</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="f599e-703">クォーラム損失に起動されるパーティションです。</span><span class="sxs-lookup"><span data-stu-id="f599e-703">Partition which the quorum loss will be invoked.</span></span> <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumLossMode"><span data-ttu-id="f599e-704">PartialQuorumLoss または FullQuorumLoss します。</span><span class="sxs-lookup"><span data-stu-id="f599e-704">PartialQuorumLoss or FullQuorumLoss.</span></span></param>
        <param name="quorumLossDuration"><span data-ttu-id="f599e-705">クォーラム損失にパーティションを保持する時間の長さ。</span><span class="sxs-lookup"><span data-stu-id="f599e-705">Amount of time for which the partition will be kept in quorum loss.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-706">操作のキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f599e-706">The cancellation token for the operation.</span></span></param>
        <summary><span data-ttu-id="f599e-707">特定のステートフル サービス パーティションをクォーラム損失状態にします。</span><span class="sxs-lookup"><span data-stu-id="f599e-707">Induces quorum loss for a given stateful service partition.</span></span> </summary>
        <returns><span data-ttu-id="f599e-708">タスク。</span><span class="sxs-lookup"><span data-stu-id="f599e-708">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-709">FullQuorumLoss - ターゲット パーティションのすべてのレプリカを停止したりされます。</span><span class="sxs-lookup"><span data-stu-id="f599e-709">FullQuorumLoss - All replicas for the target partition will be downed.</span></span>
            <span data-ttu-id="f599e-710">PartialQuorumLoss - ターゲット パーティションのレプリカのクォーラムを停止したり、.</span><span class="sxs-lookup"><span data-stu-id="f599e-710">PartialQuorumLoss - A quorum of replicas for the target partition will be downed..</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-711">quorumLossMode では、クォーラムの損失が発生するために障害がレプリカの数を示します。</span><span class="sxs-lookup"><span data-stu-id="f599e-711">quorumLossMode indicates the number of replicas that will be faulted in order to cause quorum loss.</span></span> <span data-ttu-id="f599e-712">パーティションは、quorumLossDuration のクォーラム損失に残ります。</span><span class="sxs-lookup"><span data-stu-id="f599e-712">The partition will remain in quorum loss for quorumLossDuration.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-713">この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-713">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-714">ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。</span><span class="sxs-lookup"><span data-stu-id="f599e-714">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-715">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-715">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-716">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-716">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="f599e-717">非同期操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="f599e-717">Async operation is canceled.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"> <span data-ttu-id="f599e-718">指定されたパーティションは、ステートフルな永続化サービスの一部ではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-718">Partition specified is not a part of a stateful Persisted Service.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionQuorumLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumLossMode, TimeSpan quorumLossDuration, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionQuorumLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumLossMode, valuetype System.TimeSpan quorumLossDuration, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionQuorumLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionQuorumLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionQuorumLossAsync (operationId, partitionSelector, quorumLossMode, quorumLossDuration, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumLossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumLossDuration" Type="System.TimeSpan" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId"> <span data-ttu-id="f599e-719">ユーザー指定の識別子です。</span><span class="sxs-lookup"><span data-stu-id="f599e-719">A user-provided identifier.</span></span>  <span data-ttu-id="f599e-720">この識別子は、対応する GetProgress API に渡すこともできます。</span><span class="sxs-lookup"><span data-stu-id="f599e-720">This identifier can also be passed into the corresponding GetProgress API</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="f599e-721">クォーラム損失に起動されるパーティションです。</span><span class="sxs-lookup"><span data-stu-id="f599e-721">Partition which the quorum loss will be invoked.</span></span> <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumLossMode"><span data-ttu-id="f599e-722">PartialQuorumLoss または FullQuorumLoss します。</span><span class="sxs-lookup"><span data-stu-id="f599e-722">PartialQuorumLoss or FullQuorumLoss.</span></span></param>
        <param name="quorumLossDuration"><span data-ttu-id="f599e-723">クォーラム損失にパーティションを保持する時間の長さ。</span><span class="sxs-lookup"><span data-stu-id="f599e-723">Amount of time for which the partition will be kept in quorum loss.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="f599e-724">すべての操作の全体的なタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="f599e-724">Overall timeout for the entire operation.</span></span></param>
        <summary><span data-ttu-id="f599e-725">特定のステートフル サービス パーティションをクォーラム損失状態にします。</span><span class="sxs-lookup"><span data-stu-id="f599e-725">Induces quorum loss for a given stateful service partition.</span></span> </summary>
        <returns><span data-ttu-id="f599e-726">タスク。</span><span class="sxs-lookup"><span data-stu-id="f599e-726">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-727">FullQuorumLoss - ターゲット パーティションのすべてのレプリカを停止したりされます。</span><span class="sxs-lookup"><span data-stu-id="f599e-727">FullQuorumLoss - All replicas for the target partition will be downed.</span></span>
            <span data-ttu-id="f599e-728">PartialQuorumLoss - ターゲット パーティションのレプリカのクォーラムを停止したり、.</span><span class="sxs-lookup"><span data-stu-id="f599e-728">PartialQuorumLoss - A quorum of replicas for the target partition will be downed..</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-729">quorumLossMode では、クォーラムの損失が発生するために障害がレプリカの数を示します。</span><span class="sxs-lookup"><span data-stu-id="f599e-729">quorumLossMode indicates the number of replicas that will be faulted in order to cause quorum loss.</span></span> <span data-ttu-id="f599e-730">パーティションは、quorumLossDuration のクォーラム損失に残ります。</span><span class="sxs-lookup"><span data-stu-id="f599e-730">The partition will remain in quorum loss for quorumLossDuration.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-731">この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-731">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-732">ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。</span><span class="sxs-lookup"><span data-stu-id="f599e-732">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-733">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-733">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-734">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-734">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="f599e-735">非同期操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="f599e-735">Async operation is canceled.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"> <span data-ttu-id="f599e-736">指定されたパーティションは、ステートフルな永続化サービスの一部ではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-736">Partition specified is not a part of a stateful Persisted Service.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionQuorumLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumlossMode, TimeSpan quorumlossDuration, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionQuorumLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumlossMode, valuetype System.TimeSpan quorumlossDuration, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionQuorumLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionQuorumLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionQuorumLossAsync (operationId, partitionSelector, quorumlossMode, quorumlossDuration, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumlossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumlossDuration" Type="System.TimeSpan" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"> <span data-ttu-id="f599e-737">ユーザー指定の識別子です。</span><span class="sxs-lookup"><span data-stu-id="f599e-737">A user-provided identifier.</span></span>  <span data-ttu-id="f599e-738">この識別子は、対応する GetProgress API に渡すこともできます。</span><span class="sxs-lookup"><span data-stu-id="f599e-738">This identifier can also be passed into the corresponding GetProgress API</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="f599e-739">クォーラム損失に起動されるパーティションです。</span><span class="sxs-lookup"><span data-stu-id="f599e-739">Partition which the quorum loss will be invoked.</span></span> <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumlossMode"><span data-ttu-id="f599e-740">PartialQuorumLoss または FullQuorumLoss します。</span><span class="sxs-lookup"><span data-stu-id="f599e-740">PartialQuorumLoss or FullQuorumLoss.</span></span></param>
        <param name="quorumlossDuration"><span data-ttu-id="f599e-741">クォーラム損失にパーティションを保持する時間の長さ。</span><span class="sxs-lookup"><span data-stu-id="f599e-741">Amount of time for which the partition will be kept in quorum loss.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="f599e-742">すべての操作の全体的なタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="f599e-742">Overall timeout for the entire operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-743">操作のキャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="f599e-743">The cancellation token for the operation.</span></span></param>
        <summary><span data-ttu-id="f599e-744">特定のステートフル サービス パーティションをクォーラム損失状態にします。</span><span class="sxs-lookup"><span data-stu-id="f599e-744">Induces quorum loss for a given stateful service partition.</span></span> </summary>
        <returns><span data-ttu-id="f599e-745">タスク。</span><span class="sxs-lookup"><span data-stu-id="f599e-745">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-746">FullQuorumLoss - ターゲット パーティションのすべてのレプリカを停止したりされます。</span><span class="sxs-lookup"><span data-stu-id="f599e-746">FullQuorumLoss - All replicas for the target partition will be downed.</span></span>
            <span data-ttu-id="f599e-747">PartialQuorumLoss - ターゲット パーティションのレプリカのクォーラムを停止したり、.</span><span class="sxs-lookup"><span data-stu-id="f599e-747">PartialQuorumLoss - A quorum of replicas for the target partition will be downed..</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-748">quorumLossMode では、クォーラムの損失が発生するために障害がレプリカの数を示します。</span><span class="sxs-lookup"><span data-stu-id="f599e-748">quorumLossMode indicates the number of replicas that will be faulted in order to cause quorum loss.</span></span> <span data-ttu-id="f599e-749">パーティションは、quorumLossDuration のクォーラム損失に残ります。</span><span class="sxs-lookup"><span data-stu-id="f599e-749">The partition will remain in quorum loss for quorumLossDuration.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-750">この API は、ターゲットとして、ステートフルなサービスでのみ呼び出す必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-750">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-751">ターゲットとしてのシステム サービスとこの API を呼び出すことはお勧めしません。</span><span class="sxs-lookup"><span data-stu-id="f599e-751">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-752">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-752">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-753">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-753">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="f599e-754">非同期操作が取り消されました。</span><span class="sxs-lookup"><span data-stu-id="f599e-754">Async operation is canceled.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"> <span data-ttu-id="f599e-755">指定されたパーティションは、ステートフルな永続化サービスの一部ではありません。</span><span class="sxs-lookup"><span data-stu-id="f599e-755">Partition specified is not a part of a stateful Persisted Service.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionRestartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionRestartAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionRestartAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionRestartAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionRestartAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionRestartAsync (operationId, partitionSelector, restartPartitionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
      </Parameters>
      <Docs>
        <param name="operationId"> <span data-ttu-id="f599e-756">この API の呼び出しを識別する GUIDこれは、対応する GetProgress API に渡される</span><span class="sxs-lookup"><span data-stu-id="f599e-756">A GUID that identifies a call of this API; this is passed into the corresponding GetProgress API</span></span></param>
        <param name="partitionSelector">
          <span data-ttu-id="f599e-757"><see cref="T:System.Fabric.PartitionSelector" />再起動する必要があるパーティションを指定します。</span><span class="sxs-lookup"><span data-stu-id="f599e-757"><see cref="T:System.Fabric.PartitionSelector" /> that specifies the partition which needs to be restarted.</span></span></param>
        <param name="restartPartitionMode"><span data-ttu-id="f599e-758"><see cref="T:System.Fabric.RestartPartitionMode" /> AllReplicasOrInstances できるまたは OnlyActiveSecondaries が再起動するレプリカが選択されているに基づいて。</span><span class="sxs-lookup"><span data-stu-id="f599e-758">The <see cref="T:System.Fabric.RestartPartitionMode" /> which can be AllReplicasOrInstances or OnlyActiveSecondaries based on which the replicas to be restarted are selected.</span></span></param>
        <summary>
            <span data-ttu-id="f599e-759">この API は、(すべてのレプリカがダウンしている同時ににより)、同時に、パーティションのレプリカの一部またはすべてを再起動によって、<see cref="T:System.Fabric.RestartPartitionMode" />です。</span><span class="sxs-lookup"><span data-stu-id="f599e-759">This API will restart some or all the replicas of a partition at the same time (ensures all the replicas are down concurrently) depending on the <see cref="T:System.Fabric.RestartPartitionMode" />.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-760">タスク。</span><span class="sxs-lookup"><span data-stu-id="f599e-760">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-761">この API は、完全または部分的な再起動後に、パーティションの復元時間をテストし、テスト フェールオーバーに便利です。</span><span class="sxs-lookup"><span data-stu-id="f599e-761">This API is useful to test the recovery time of a partition after a full or partial restart and also to test failover.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-762">この API は、ステートフルなとステートレス サービスの両方で呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="f599e-762">This API may be called on both stateful and stateless services.</span></span>  
            <span data-ttu-id="f599e-763">呼び出しの場合は、ステートレスなサービスで、RestartPartitionMode は RestartPartitionMode.AllReplicasOrInstances をする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-763">If the call is on a stateless service, RestartPartitionMode must be RestartPartitionMode.AllReplicasOrInstances.</span></span>  <span data-ttu-id="f599e-764">その他のモードになります ArgumentException、返された結果オブジェクトの内部 GetPartitionRestartProgressAsync() が呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="f599e-764">Other modes will result in ArgumentException inside the returned Result object when GetPartitionRestartProgressAsync() is called.</span></span>  <span data-ttu-id="f599e-765">GetPartitionRestartProgressAsync() を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f599e-765">See GetPartitionRestartProgressAsync().</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-766">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-766">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-767">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-767">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-768">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="f599e-768">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="f599e-769">入力が無効でした。</span><span class="sxs-lookup"><span data-stu-id="f599e-769">The input was invalid.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="f599e-770">これらは、選択されている、指定されたパーティションが存在しない場合に、ファブリック エラー FabricErrorCode.PartitionNotFound - です。</span><span class="sxs-lookup"><span data-stu-id="f599e-770">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionRestartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionRestartAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionRestartAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionRestartAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionRestartAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionRestartAsync (operationId, partitionSelector, restartPartitionMode, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"> <span data-ttu-id="f599e-771">この API の呼び出しを識別する GUIDこれは、対応する GetProgress API に渡される</span><span class="sxs-lookup"><span data-stu-id="f599e-771">A GUID that identifies a call of this API; this is passed into the corresponding GetProgress API</span></span></param>
        <param name="partitionSelector">
          <span data-ttu-id="f599e-772"><see cref="T:System.Fabric.PartitionSelector" />再起動する必要があるパーティションを指定します。</span><span class="sxs-lookup"><span data-stu-id="f599e-772"><see cref="T:System.Fabric.PartitionSelector" /> that specifies the partition which needs to be restarted</span></span></param>
        <param name="restartPartitionMode"><span data-ttu-id="f599e-773"><see cref="T:System.Fabric.RestartPartitionMode" /> AllReplicasOrInstances できるまたは OnlyActiveSecondaries が再起動するレプリカが選択されているに基づいて。</span><span class="sxs-lookup"><span data-stu-id="f599e-773">The <see cref="T:System.Fabric.RestartPartitionMode" /> which can be AllReplicasOrInstances or OnlyActiveSecondaries based on which the replicas to be restarted are selected.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-774">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-774">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-775">この API は、(すべてのレプリカがダウンしている同時ににより)、同時に、パーティションのレプリカの一部またはすべてを再起動によって、<see cref="T:System.Fabric.RestartPartitionMode" />です。</span><span class="sxs-lookup"><span data-stu-id="f599e-775">This API will restart some or all the replicas of a partition at the same time (ensures all the replicas are down concurrently) depending on the <see cref="T:System.Fabric.RestartPartitionMode" />.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-776">タスク。</span><span class="sxs-lookup"><span data-stu-id="f599e-776">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-777">この API は、完全または部分的な再起動後に、パーティションの復元時間をテストし、テスト フェールオーバーに便利です。</span><span class="sxs-lookup"><span data-stu-id="f599e-777">This API is useful to test the recovery time of a partition after a full or partial restart and also to test failover.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-778">この API は、ステートフルなとステートレス サービスの両方で呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="f599e-778">This API may be called on both stateful and stateless services.</span></span>  
            <span data-ttu-id="f599e-779">呼び出しの場合は、ステートレスなサービスで、RestartPartitionMode は RestartPartitionMode.AllReplicasOrInstances をする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-779">If the call is on a stateless service, RestartPartitionMode must be RestartPartitionMode.AllReplicasOrInstances.</span></span>  <span data-ttu-id="f599e-780">その他のモードになります ArgumentException、返された結果オブジェクトの内部 GetPartitionRestartProgressAsync() が呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="f599e-780">Other modes will result in ArgumentException inside the returned Result object when GetPartitionRestartProgressAsync() is called.</span></span>  <span data-ttu-id="f599e-781">GetPartitionRestartProgressAsync() を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f599e-781">See GetPartitionRestartProgressAsync().</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-782">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-782">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-783">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="f599e-783">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="f599e-784">入力が無効でした。</span><span class="sxs-lookup"><span data-stu-id="f599e-784">The input was invalid.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="f599e-785">選択されている、指定されたパーティションが存在しない場合、これらは、ファブリック エラー FabricErrorCode.PartitionNotFound-</span><span class="sxs-lookup"><span data-stu-id="f599e-785">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionRestartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionRestartAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionRestartAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionRestartAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionRestartAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionRestartAsync (operationId, partitionSelector, restartPartitionMode, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId"> <span data-ttu-id="f599e-786">この API の呼び出しを識別する GUIDこれは、対応する GetProgress API に渡される</span><span class="sxs-lookup"><span data-stu-id="f599e-786">A GUID that identifies a call of this API; this is passed into the corresponding GetProgress API</span></span></param>
        <param name="partitionSelector">
          <span data-ttu-id="f599e-787"><see cref="T:System.Fabric.PartitionSelector" />再起動する必要があるパーティションを指定します。</span><span class="sxs-lookup"><span data-stu-id="f599e-787"><see cref="T:System.Fabric.PartitionSelector" /> that specifies the partition which needs to be restarted.</span></span></param>
        <param name="restartPartitionMode"><span data-ttu-id="f599e-788"><see cref="T:System.Fabric.RestartPartitionMode" /> AllReplicasOrInstances できるまたは OnlyActiveSecondaries が再起動するレプリカが選択されているに基づいて。</span><span class="sxs-lookup"><span data-stu-id="f599e-788">The <see cref="T:System.Fabric.RestartPartitionMode" /> which can be AllReplicasOrInstances or OnlyActiveSecondaries based on which the replicas to be restarted are selected.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="f599e-789">操作の全体的なタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="f599e-789">The overall timeout for the operation.</span></span></param>
        <summary>
            <span data-ttu-id="f599e-790">この API は、(すべてのレプリカがダウンしている同時ににより)、同時に、パーティションのレプリカの一部またはすべてを再起動によって、<see cref="T:System.Fabric.RestartPartitionMode" />です。</span><span class="sxs-lookup"><span data-stu-id="f599e-790">This API will restart some or all the replicas of a partition at the same time (ensures all the replicas are down concurrently) depending on the <see cref="T:System.Fabric.RestartPartitionMode" />.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-791">タスク。</span><span class="sxs-lookup"><span data-stu-id="f599e-791">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-792">この API は、完全または部分的な再起動後に、パーティションの復元時間をテストし、テスト フェールオーバーに便利です。</span><span class="sxs-lookup"><span data-stu-id="f599e-792">This API is useful to test the recovery time of a partition after a full or partial restart and also to test failover.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-793">この API は、ステートフルなとステートレス サービスの両方で呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="f599e-793">This API may be called on both stateful and stateless services.</span></span>  
            <span data-ttu-id="f599e-794">呼び出しの場合は、ステートレスなサービスで、RestartPartitionMode は RestartPartitionMode.AllReplicasOrInstances をする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-794">If the call is on a stateless service, RestartPartitionMode must be RestartPartitionMode.AllReplicasOrInstances.</span></span>  <span data-ttu-id="f599e-795">その他のモードになります ArgumentException、返された結果オブジェクトの内部 GetPartitionRestartProgressAsync() が呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="f599e-795">Other modes will result in ArgumentException inside the returned Result object when GetPartitionRestartProgressAsync() is called.</span></span>  <span data-ttu-id="f599e-796">GetPartitionRestartProgressAsync() を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f599e-796">See GetPartitionRestartProgressAsync().</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-797">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-797">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-798">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-798">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-799">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="f599e-799">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="f599e-800">入力が無効でした。</span><span class="sxs-lookup"><span data-stu-id="f599e-800">The input was invalid.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="f599e-801">選択されている、指定されたパーティションが存在しない場合、これらは、ファブリック エラー FabricErrorCode.PartitionNotFound-</span><span class="sxs-lookup"><span data-stu-id="f599e-801">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionRestartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionRestartAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionRestartAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionRestartAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionRestartAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionRestartAsync (operationId, partitionSelector, restartPartitionMode, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"> <span data-ttu-id="f599e-802">この API の呼び出しを識別する GUIDこれは、対応する GetProgress API に渡される</span><span class="sxs-lookup"><span data-stu-id="f599e-802">A GUID that identifies a call of this API; this is passed into the corresponding GetProgress API</span></span></param>
        <param name="partitionSelector">
          <span data-ttu-id="f599e-803"><see cref="T:System.Fabric.PartitionSelector" />再起動する必要があるパーティションを指定します。</span><span class="sxs-lookup"><span data-stu-id="f599e-803"><see cref="T:System.Fabric.PartitionSelector" /> that specifies the partition which needs to be restarted.</span></span></param>
        <param name="restartPartitionMode"><span data-ttu-id="f599e-804"><see cref="T:System.Fabric.RestartPartitionMode" /> AllReplicasOrInstances できるまたは OnlyActiveSecondaries が再起動するレプリカが選択されているに基づいて。</span><span class="sxs-lookup"><span data-stu-id="f599e-804">The <see cref="T:System.Fabric.RestartPartitionMode" /> which can be AllReplicasOrInstances or OnlyActiveSecondaries based on which the replicas to be restarted are selected.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="f599e-805">操作の全体的なタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="f599e-805">The overall timeout for the operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f599e-806">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-806">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-807">この API は、(すべてのレプリカがダウンしている同時ににより)、同時に、パーティションのレプリカの一部またはすべてを再起動によって、<see cref="T:System.Fabric.RestartPartitionMode" />です。</span><span class="sxs-lookup"><span data-stu-id="f599e-807">This API will restart some or all the replicas of a partition at the same time (ensures all the replicas are down concurrently) depending on the <see cref="T:System.Fabric.RestartPartitionMode" />.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-808">タスク。</span><span class="sxs-lookup"><span data-stu-id="f599e-808">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-809">この API は、完全または部分的な再起動後に、パーティションの復元時間をテストし、テスト フェールオーバーに便利です。</span><span class="sxs-lookup"><span data-stu-id="f599e-809">This API is useful to test the recovery time of a partition after a full or partial restart and also to test failover.</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-810">この API は、ステートフルなとステートレス サービスの両方で呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="f599e-810">This API may be called on both stateful and stateless services.</span></span>  
            <span data-ttu-id="f599e-811">呼び出しの場合は、ステートレスなサービスで、RestartPartitionMode は RestartPartitionMode.AllReplicasOrInstances をする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-811">If the call is on a stateless service, RestartPartitionMode must be RestartPartitionMode.AllReplicasOrInstances.</span></span>  <span data-ttu-id="f599e-812">その他のモードになります ArgumentException、返された結果オブジェクトの内部 GetPartitionRestartProgressAsync() が呼び出されるとします。</span><span class="sxs-lookup"><span data-stu-id="f599e-812">Other modes will result in ArgumentException inside the returned Result object when GetPartitionRestartProgressAsync() is called.</span></span>  <span data-ttu-id="f599e-813">GetPartitionRestartProgressAsync() を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f599e-813">See GetPartitionRestartProgressAsync().</span></span>
            </para>
          <para>
            <span data-ttu-id="f599e-814">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-814">The FaultAnalysisService must be enabled to use this API.</span></span>             
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-815">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-815">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-816">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="f599e-816">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="f599e-817">入力が無効でした。</span><span class="sxs-lookup"><span data-stu-id="f599e-817">The input was invalid.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="f599e-818">選択されている、指定されたパーティションが存在しない場合、これらは、ファブリック エラー FabricErrorCode.PartitionNotFound-</span><span class="sxs-lookup"><span data-stu-id="f599e-818">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StopChaosAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StopChaosAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StopChaosAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StopChaosAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function StopChaosAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.StopChaosAsync : unit -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StopChaosAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f599e-819">この API は、混乱を停止します。</span><span class="sxs-lookup"><span data-stu-id="f599e-819">This API will stop Chaos.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-820">タスク。</span><span class="sxs-lookup"><span data-stu-id="f599e-820">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-821">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-821">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="StopChaosAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StopChaosAsync (TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StopChaosAsync(valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StopChaosAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StopChaosAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StopChaosAsync (operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationTimeout"> <span data-ttu-id="f599e-822">操作の全体的なタイムアウト。</span><span class="sxs-lookup"><span data-stu-id="f599e-822">The overall timeout for the operation.</span></span></param>
        <param name="cancellationToken"> <span data-ttu-id="f599e-823">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-823">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-824">この API は、混乱を停止します。</span><span class="sxs-lookup"><span data-stu-id="f599e-824">This API will stop Chaos.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-825">タスク。</span><span class="sxs-lookup"><span data-stu-id="f599e-825">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="f599e-826">この API を使用して、FaultAnalysisService を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f599e-826">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-827">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-827">Action took more than its allocated time.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ValidateApplicationAsync (Uri applicationName, TimeSpan maximumStabilizationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ValidateApplicationAsync(class System.Uri applicationName, valuetype System.TimeSpan maximumStabilizationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.ValidateApplicationAsync(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateApplicationAsync (applicationName As Uri, maximumStabilizationTimeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="member this.ValidateApplicationAsync : Uri * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.ValidateApplicationAsync (applicationName, maximumStabilizationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="maximumStabilizationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="applicationName"><span data-ttu-id="f599e-828">検証に使用するサービスを提供する必要があるアプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="f599e-828">Name of the application whose services need to be validated.</span></span></param>
        <param name="maximumStabilizationTimeout"><span data-ttu-id="f599e-829">他の失敗が安定してサービスの操作を待機する時間の最大量。</span><span class="sxs-lookup"><span data-stu-id="f599e-829">Max amount of time to wait for the services to stabilize else fail the operation.</span></span></param>
        <summary>
            <span data-ttu-id="f599e-830">この API は、可用性と指定したアプリケーションのすべてのサービスの正常性を検証します。</span><span class="sxs-lookup"><span data-stu-id="f599e-830">This API will validate the availability and health of all services in the specified application.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-831">タスク</span><span class="sxs-lookup"><span data-stu-id="f599e-831">Task</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-832">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-832">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-833">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="f599e-833">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricValidationException"><span data-ttu-id="f599e-834">場合は任意のサービスは、指定されたタイムアウト内では安定されません。</span><span class="sxs-lookup"><span data-stu-id="f599e-834">If any service does not stabilize within the specified timeout.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ValidateApplicationAsync (Uri applicationName, TimeSpan maximumStabilizationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ValidateApplicationAsync(class System.Uri applicationName, valuetype System.TimeSpan maximumStabilizationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.ValidateApplicationAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateApplicationAsync (applicationName As Uri, maximumStabilizationTimeout As TimeSpan, token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="member this.ValidateApplicationAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.ValidateApplicationAsync (applicationName, maximumStabilizationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="maximumStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName"><span data-ttu-id="f599e-835">検証に使用するサービスを提供する必要があるアプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="f599e-835">Name of the application whose services need to be validated.</span></span></param>
        <param name="maximumStabilizationTimeout"><span data-ttu-id="f599e-836">他の失敗が安定してサービスの操作を待機する時間の最大量。</span><span class="sxs-lookup"><span data-stu-id="f599e-836">Max amount of time to wait for the services to stabilize else fail the operation.</span></span></param>
        <param name="token"><span data-ttu-id="f599e-837">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-837">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-838">この API は、可用性と指定したアプリケーションのすべてのサービスの正常性を検証します。</span><span class="sxs-lookup"><span data-stu-id="f599e-838">This API will validate the availability and health of all services in the specified application.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-839">タスク</span><span class="sxs-lookup"><span data-stu-id="f599e-839">Task</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-840">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-840">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-841">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="f599e-841">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricValidationException"><span data-ttu-id="f599e-842">場合は任意のサービスは、指定されたタイムアウト内では安定されません。</span><span class="sxs-lookup"><span data-stu-id="f599e-842">If any service does not stabilize within the specified timeout.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ValidateApplicationAsync (Uri applicationName, TimeSpan maximumStabilizationTimeout, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ValidateApplicationAsync(class System.Uri applicationName, valuetype System.TimeSpan maximumStabilizationTimeout, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.ValidateApplicationAsync(System.Uri,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateApplicationAsync (applicationName As Uri, maximumStabilizationTimeout As TimeSpan, operationTimeout As TimeSpan, token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="member this.ValidateApplicationAsync : Uri * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.ValidateApplicationAsync (applicationName, maximumStabilizationTimeout, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="maximumStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName"><span data-ttu-id="f599e-843">検証に使用するサービスを提供する必要があるアプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="f599e-843">Name of the application whose services need to be validated.</span></span></param>
        <param name="maximumStabilizationTimeout"><span data-ttu-id="f599e-844">他の失敗が安定してサービスの操作を待機する時間の最大量。</span><span class="sxs-lookup"><span data-stu-id="f599e-844">Max amount of time to wait for the services to stabilize else fail the operation.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="f599e-845">操作が他のフェールオーバーを完了するため、操作を待機する時間の長さ。</span><span class="sxs-lookup"><span data-stu-id="f599e-845">Amount of time to wait for an operation to complete else fail the operation.</span></span></param>
        <param name="token"><span data-ttu-id="f599e-846">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-846">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-847">この API は、可用性と指定したアプリケーションのすべてのサービスの正常性を検証します。</span><span class="sxs-lookup"><span data-stu-id="f599e-847">This API will validate the availability and health of all services in the specified application.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-848">タスク</span><span class="sxs-lookup"><span data-stu-id="f599e-848">Task</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-849">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-849">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-850">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="f599e-850">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricValidationException"><span data-ttu-id="f599e-851">場合は任意のサービスは、指定されたタイムアウト内では安定されません。</span><span class="sxs-lookup"><span data-stu-id="f599e-851">If any service does not stabilize within the specified timeout.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ValidateServiceAsync (Uri serviceName, TimeSpan maximumStabilizationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ValidateServiceAsync(class System.Uri serviceName, valuetype System.TimeSpan maximumStabilizationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.ValidateServiceAsync(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateServiceAsync (serviceName As Uri, maximumStabilizationTimeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="member this.ValidateServiceAsync : Uri * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.ValidateServiceAsync (serviceName, maximumStabilizationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="maximumStabilizationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serviceName"><span data-ttu-id="f599e-852">検証に使用する必要があるサービスの名前。</span><span class="sxs-lookup"><span data-stu-id="f599e-852">Name of the service that needs to be validated.</span></span></param>
        <param name="maximumStabilizationTimeout"><span data-ttu-id="f599e-853">他の失敗が安定してサービスの操作を待機する時間の最大量。</span><span class="sxs-lookup"><span data-stu-id="f599e-853">Max amount of time to wait for the service to stabilize else fail the operation.</span></span></param>
        <summary>
            <span data-ttu-id="f599e-854">この API は、可用性と指定されたサービスの正常性を検証します。</span><span class="sxs-lookup"><span data-stu-id="f599e-854">This API will validate the availability and health of the specified service.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-855">タスク</span><span class="sxs-lookup"><span data-stu-id="f599e-855">Task</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-856">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-856">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-857">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="f599e-857">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricValidationException"><span data-ttu-id="f599e-858">場合は任意のサービスは、指定されたタイムアウト内では安定されません。</span><span class="sxs-lookup"><span data-stu-id="f599e-858">If any service does not stabilize within the specified timeout.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ValidateServiceAsync (Uri serviceName, TimeSpan maximumStabilizationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ValidateServiceAsync(class System.Uri serviceName, valuetype System.TimeSpan maximumStabilizationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.ValidateServiceAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateServiceAsync (serviceName As Uri, maximumStabilizationTimeout As TimeSpan, token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="member this.ValidateServiceAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.ValidateServiceAsync (serviceName, maximumStabilizationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="maximumStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName"><span data-ttu-id="f599e-859">検証に使用する必要があるサービスの名前。</span><span class="sxs-lookup"><span data-stu-id="f599e-859">Name of the service that needs to be validated.</span></span></param>
        <param name="maximumStabilizationTimeout"><span data-ttu-id="f599e-860">他の失敗が安定してサービスの操作を待機する時間の最大量。</span><span class="sxs-lookup"><span data-stu-id="f599e-860">Max amount of time to wait for the service to stabilize else fail the operation.</span></span></param>
        <param name="token"><span data-ttu-id="f599e-861">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-861">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-862">この API は、可用性と指定されたサービスの正常性を検証します。</span><span class="sxs-lookup"><span data-stu-id="f599e-862">This API will validate the availability and health of the specified service.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-863">タスク</span><span class="sxs-lookup"><span data-stu-id="f599e-863">Task</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-864">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-864">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-865">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="f599e-865">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricValidationException"><span data-ttu-id="f599e-866">場合は任意のサービスは、指定されたタイムアウト内では安定されません。</span><span class="sxs-lookup"><span data-stu-id="f599e-866">If any service does not stabilize within the specified timeout.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ValidateServiceAsync (Uri serviceName, TimeSpan maximumStabilizationTimeout, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ValidateServiceAsync(class System.Uri serviceName, valuetype System.TimeSpan maximumStabilizationTimeout, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.ValidateServiceAsync(System.Uri,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateServiceAsync (serviceName As Uri, maximumStabilizationTimeout As TimeSpan, operationTimeout As TimeSpan, token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="member this.ValidateServiceAsync : Uri * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.ValidateServiceAsync (serviceName, maximumStabilizationTimeout, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="maximumStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName"><span data-ttu-id="f599e-867">検証に使用する必要があるサービスの名前。</span><span class="sxs-lookup"><span data-stu-id="f599e-867">Name of the service that needs to be validated.</span></span></param>
        <param name="maximumStabilizationTimeout"><span data-ttu-id="f599e-868">他の失敗が安定してサービスの操作を待機する時間の最大量。</span><span class="sxs-lookup"><span data-stu-id="f599e-868">Max amount of time to wait for the service to stabilize else fail the operation.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="f599e-869">操作が他のフェールオーバーを完了するため、操作を待機する時間の長さ。</span><span class="sxs-lookup"><span data-stu-id="f599e-869">Amount of time to wait for an operation to complete else fail the operation.</span></span></param>
        <param name="token"><span data-ttu-id="f599e-870">キャンセル トークン</span><span class="sxs-lookup"><span data-stu-id="f599e-870">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f599e-871">この API は、可用性と指定されたサービスの正常性を検証します。</span><span class="sxs-lookup"><span data-stu-id="f599e-871">This API will validate the availability and health of the specified service.</span></span>
            </summary>
        <returns><span data-ttu-id="f599e-872">タスク</span><span class="sxs-lookup"><span data-stu-id="f599e-872">Task</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="f599e-873">アクションにかかった、割り当てられた時間を超える。</span><span class="sxs-lookup"><span data-stu-id="f599e-873">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="f599e-874">必須の引数のいずれかが null です。</span><span class="sxs-lookup"><span data-stu-id="f599e-874">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricValidationException"><span data-ttu-id="f599e-875">場合は任意のサービスは、指定されたタイムアウト内では安定されません。</span><span class="sxs-lookup"><span data-stu-id="f599e-875">If any service does not stabilize within the specified timeout.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>