<Type Name="VirtualMachineScaleSetVMsOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualMachineScaleSetVMsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualMachineScaleSetVMsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualMachineScaleSetVMsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetVMsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7fbf6-101">VirtualMachineScaleSetVMsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-101">Extension methods for VirtualMachineScaleSetVMsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginDeallocateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeallocateAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeallocateAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginDeallocateAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeallocateAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginDeallocateAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginDeallocateAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7fbf6-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7fbf6-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-103">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="7fbf6-104">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-104">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="7fbf6-105">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-105">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7fbf6-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7fbf6-107">VM スケール セット内の特定の仮想マシンの割り当てを解除します。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-107">Deallocates a specific virtual machine in a VM scale set.</span></span> <span data-ttu-id="7fbf6-108">仮想マシンをシャット ダウンし、使用するコンピューティング リソースを解放します。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-108">Shuts down the virtual machine and releases the compute resources it uses.</span></span> <span data-ttu-id="7fbf6-109">料金はかかりませんこのバーチャル マシンのコンピューティング リソースの割り当てが解除されるとします。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-109">You are not billed for the compute resources of this virtual machine once it is deallocated.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7fbf6-110">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-110">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7fbf6-111">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-111">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="7fbf6-112">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-112">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="7fbf6-113">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-113">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7fbf6-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7fbf6-115">VM スケール セットから仮想マシンを削除します。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-115">Deletes a virtual machine from a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPowerOffAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginPowerOffAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginPowerOffAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginPowerOffAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginPowerOffAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginPowerOffAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginPowerOffAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7fbf6-116">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-116">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7fbf6-117">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-117">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="7fbf6-118">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-118">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="7fbf6-119">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-119">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7fbf6-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7fbf6-121">(停止) 仮想マシンに VM スケール セットの電源を切ります。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-121">Power off (stop) a virtual machine in a VM scale set.</span></span> <span data-ttu-id="7fbf6-122">リソースがまだアタッチされているリソースには料金が取得することに注意してください。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-122">Note that resources are still attached and you are getting charged for the resources.</span></span> <span data-ttu-id="7fbf6-123">代わりに、使用は、リソースを解放し、課金されないようにするの割り当てを解除します。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-123">Instead, use deallocate to release resources and avoid charges.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginReimageAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginReimageAllAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginReimageAllAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginReimageAllAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginReimageAllAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginReimageAllAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginReimageAllAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7fbf6-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7fbf6-125">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-125">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="7fbf6-126">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-126">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="7fbf6-127">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-127">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7fbf6-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7fbf6-129">使用すると、イメージを再作成 (データ ディスクを含む) すべてのディスク、仮想マシン スケール セットのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-129">Allows you to re-image all the disks ( including data disks ) in the a virtual machine scale set instance.</span></span> <span data-ttu-id="7fbf6-130">この操作は、管理対象ディスクに対してのみサポートされます。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-130">This operation is only supported for managed disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginReimageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginReimageAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginReimageAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginReimageAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginReimageAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginReimageAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginReimageAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7fbf6-131">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-131">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7fbf6-132">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-132">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="7fbf6-133">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-133">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="7fbf6-134">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-134">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7fbf6-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7fbf6-136">(オペレーティング システムのアップグレード) reimages VM スケール内の特定の仮想マシンを設定します。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-136">Reimages (upgrade the operating system) a specific virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRestartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginRestartAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginRestartAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginRestartAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRestartAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginRestartAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginRestartAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7fbf6-137">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7fbf6-138">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-138">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="7fbf6-139">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-139">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="7fbf6-140">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-140">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7fbf6-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7fbf6-142">VM スケール セット内の仮想マシンを再起動します。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-142">Restarts a virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginStartAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginStartAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginStartAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStartAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.BeginStartAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginStartAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7fbf6-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7fbf6-144">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-144">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="7fbf6-145">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-145">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="7fbf6-146">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-146">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7fbf6-147">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7fbf6-148">VM スケール セット内の仮想マシンを起動します。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-148">Starts a virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeallocateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeallocateAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeallocateAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.DeallocateAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeallocateAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.DeallocateAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;DeallocateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7fbf6-149">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-149">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7fbf6-150">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-150">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="7fbf6-151">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-151">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="7fbf6-152">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-152">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7fbf6-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7fbf6-154">VM スケール セット内の特定の仮想マシンの割り当てを解除します。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-154">Deallocates a specific virtual machine in a VM scale set.</span></span> <span data-ttu-id="7fbf6-155">仮想マシンをシャット ダウンし、使用するコンピューティング リソースを解放します。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-155">Shuts down the virtual machine and releases the compute resources it uses.</span></span> <span data-ttu-id="7fbf6-156">料金はかかりませんこのバーチャル マシンのコンピューティング リソースの割り当てが解除されるとします。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-156">You are not billed for the compute resources of this virtual machine once it is deallocated.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeleteAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeleteAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.DeleteAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7fbf6-157">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-157">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7fbf6-158">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-158">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="7fbf6-159">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-159">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="7fbf6-160">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-160">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7fbf6-161">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7fbf6-162">VM スケール セットから仮想マシンを削除します。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-162">Deletes a virtual machine from a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt; GetAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt; GetAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.GetAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;GetAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7fbf6-163">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7fbf6-164">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-164">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="7fbf6-165">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-165">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="7fbf6-166">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-166">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7fbf6-167">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7fbf6-168">VM スケール セットから仮想マシンを取得します。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-168">Gets a virtual machine from a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetInstanceViewAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInstanceViewInner&gt; GetInstanceViewAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInstanceViewInner&gt; GetInstanceViewAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.GetInstanceViewAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetInstanceViewAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInstanceViewInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.GetInstanceViewAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;GetInstanceViewAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInstanceViewInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7fbf6-169">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-169">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7fbf6-170">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-170">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="7fbf6-171">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-171">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="7fbf6-172">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-172">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7fbf6-173">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-173">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7fbf6-174">VM スケール セットから仮想マシンの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-174">Gets the status of a virtual machine from a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string virtualMachineScaleSetName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt; odataQuery = null, string select = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string virtualMachineScaleSetName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt; odataQuery, string select, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.ListAsync (operations, resourceGroupName, virtualMachineScaleSetName, odataQuery, select, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;ListAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7fbf6-175">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-175">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7fbf6-176">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-176">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="7fbf6-177">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-177">The name of the VM scale set.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="7fbf6-178">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-178">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="7fbf6-179">リストのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-179">The list parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7fbf6-180">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7fbf6-181">VM スケール セットのすべての仮想マシンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-181">Gets a list of all virtual machines in a VM scale sets.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;ListNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7fbf6-182">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-182">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7fbf6-183">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-183">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7fbf6-184">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-184">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7fbf6-185">VM スケール セットのすべての仮想マシンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-185">Gets a list of all virtual machines in a VM scale sets.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PowerOffAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; PowerOffAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; PowerOffAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.PowerOffAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PowerOffAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.PowerOffAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;PowerOffAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7fbf6-186">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-186">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7fbf6-187">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-187">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="7fbf6-188">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-188">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="7fbf6-189">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-189">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7fbf6-190">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7fbf6-191">(停止) 仮想マシンに VM スケール セットの電源を切ります。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-191">Power off (stop) a virtual machine in a VM scale set.</span></span> <span data-ttu-id="7fbf6-192">リソースがまだアタッチされているリソースには料金が取得することに注意してください。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-192">Note that resources are still attached and you are getting charged for the resources.</span></span> <span data-ttu-id="7fbf6-193">代わりに、使用は、リソースを解放し、課金されないようにするの割り当てを解除します。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-193">Instead, use deallocate to release resources and avoid charges.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReimageAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; ReimageAllAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; ReimageAllAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.ReimageAllAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ReimageAllAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.ReimageAllAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;ReimageAllAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7fbf6-194">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-194">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7fbf6-195">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-195">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="7fbf6-196">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-196">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="7fbf6-197">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-197">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7fbf6-198">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-198">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7fbf6-199">使用すると、イメージを再作成 (データ ディスクを含む) すべてのディスク、仮想マシン スケール セットのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-199">Allows you to re-image all the disks ( including data disks ) in the a virtual machine scale set instance.</span></span> <span data-ttu-id="7fbf6-200">この操作は、管理対象ディスクに対してのみサポートされます。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-200">This operation is only supported for managed disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReimageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; ReimageAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; ReimageAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.ReimageAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ReimageAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.ReimageAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;ReimageAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7fbf6-201">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-201">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7fbf6-202">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-202">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="7fbf6-203">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-203">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="7fbf6-204">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-204">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7fbf6-205">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-205">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7fbf6-206">(オペレーティング システムのアップグレード) reimages VM スケール内の特定の仮想マシンを設定します。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-206">Reimages (upgrade the operating system) a specific virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; RestartAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; RestartAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.RestartAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RestartAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.RestartAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;RestartAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7fbf6-207">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-207">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7fbf6-208">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-208">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="7fbf6-209">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-209">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="7fbf6-210">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-210">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7fbf6-211">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-211">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7fbf6-212">VM スケール セット内の仮想マシンを再起動します。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-212">Restarts a virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; StartAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; StartAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.StartAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StartAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions.StartAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetVMsOperationsExtensions/&lt;StartAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7fbf6-213">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-213">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7fbf6-214">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-214">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="7fbf6-215">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-215">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="7fbf6-216">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-216">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7fbf6-217">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-217">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7fbf6-218">VM スケール セット内の仮想マシンを起動します。</span><span class="sxs-lookup"><span data-stu-id="7fbf6-218">Starts a virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>