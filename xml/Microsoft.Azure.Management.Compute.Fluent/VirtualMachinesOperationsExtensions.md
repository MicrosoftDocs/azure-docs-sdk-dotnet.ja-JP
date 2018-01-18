<Type Name="VirtualMachinesOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualMachinesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualMachinesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualMachinesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualMachinesOperationsExtensions = class" />
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
            <span data-ttu-id="d5706-101">VirtualMachinesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="d5706-101">Extension methods for VirtualMachinesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCaptureAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineCaptureResultInner&gt; BeginCaptureAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineCaptureParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineCaptureResultInner&gt; BeginCaptureAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineCaptureParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.BeginCaptureAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineCaptureParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCaptureAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineCaptureParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineCaptureResultInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.BeginCaptureAsync (operations, resourceGroupName, vmName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;BeginCaptureAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineCaptureResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineCaptureParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d5706-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d5706-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d5706-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-103">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="d5706-104">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-104">The name of the virtual machine.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d5706-105">パラメーターは、仮想マシンのキャプチャ操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="d5706-105">Parameters supplied to the Capture Virtual Machine operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d5706-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d5706-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d5706-107">VM の仮想ハード_ディスクをコピーして、VM をキャプチャし、類似した Vm の作成に使用できるテンプレートを出力します。</span><span class="sxs-lookup"><span data-stu-id="d5706-107">Captures the VM by copying virtual hard disks of the VM and outputs a template that can be used to create similar VMs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginConvertToManagedDisksAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginConvertToManagedDisksAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginConvertToManagedDisksAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.BeginConvertToManagedDisksAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginConvertToManagedDisksAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.BeginConvertToManagedDisksAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;BeginConvertToManagedDisksAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d5706-108">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d5706-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d5706-109">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-109">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="d5706-110">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-110">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d5706-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d5706-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d5706-112">仮想マシンのディスクを blob に基づくから管理されるディスクに変換します。</span><span class="sxs-lookup"><span data-stu-id="d5706-112">Converts virtual machine disks from blob-based to managed disks.</span></span> <span data-ttu-id="d5706-113">仮想マシンがあります停止-割り当て解除されたこの操作を呼び出す前にします。</span><span class="sxs-lookup"><span data-stu-id="d5706-113">Virtual machine must be stop-deallocated before invoking this operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, vmName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d5706-114">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d5706-114">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d5706-115">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-115">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="d5706-116">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-116">The name of the virtual machine.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d5706-117">パラメーターは、仮想マシンの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="d5706-117">Parameters supplied to the Create Virtual Machine operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d5706-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d5706-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d5706-119">作成または仮想マシンを更新する操作です。</span><span class="sxs-lookup"><span data-stu-id="d5706-119">The operation to create or update a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeallocateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeallocateAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeallocateAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.BeginDeallocateAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeallocateAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.BeginDeallocateAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;BeginDeallocateAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d5706-120">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d5706-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d5706-121">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-121">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="d5706-122">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-122">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d5706-123">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d5706-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d5706-124">仮想マシンをシャット ダウンし、コンピューティング リソースを解放します。</span><span class="sxs-lookup"><span data-stu-id="d5706-124">Shuts down the virtual machine and releases the compute resources.</span></span> <span data-ttu-id="d5706-125">このバーチャル マシンを使用するコンピューティング リソースには課金されません。</span><span class="sxs-lookup"><span data-stu-id="d5706-125">You are not billed for the compute resources that this virtual machine uses.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d5706-126">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d5706-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d5706-127">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-127">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="d5706-128">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-128">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d5706-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d5706-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d5706-130">仮想マシンを削除する操作です。</span><span class="sxs-lookup"><span data-stu-id="d5706-130">The operation to delete a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPerformMaintenanceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginPerformMaintenanceAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginPerformMaintenanceAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.BeginPerformMaintenanceAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginPerformMaintenanceAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.BeginPerformMaintenanceAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;BeginPerformMaintenanceAsync&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="vmName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPowerOffAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginPowerOffAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginPowerOffAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.BeginPowerOffAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginPowerOffAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.BeginPowerOffAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;BeginPowerOffAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d5706-131">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d5706-131">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d5706-132">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-132">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="d5706-133">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-133">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d5706-134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d5706-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d5706-135">仮想マシンの電源をオフ (停止) する操作です。</span><span class="sxs-lookup"><span data-stu-id="d5706-135">The operation to power off (stop) a virtual machine.</span></span> <span data-ttu-id="d5706-136">同じプロビジョニングされているリソースを持つ仮想マシンを再起動することができます。</span><span class="sxs-lookup"><span data-stu-id="d5706-136">The virtual machine can be restarted with the same provisioned resources.</span></span> <span data-ttu-id="d5706-137">また、この仮想マシンの引き続き課金されます。</span><span class="sxs-lookup"><span data-stu-id="d5706-137">You are still charged for this virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRedeployAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginRedeployAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginRedeployAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.BeginRedeployAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRedeployAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.BeginRedeployAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;BeginRedeployAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d5706-138">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d5706-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d5706-139">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-139">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="d5706-140">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-140">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d5706-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d5706-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d5706-142">仮想マシンを再デプロイ操作です。</span><span class="sxs-lookup"><span data-stu-id="d5706-142">The operation to redeploy a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRestartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginRestartAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginRestartAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.BeginRestartAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRestartAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.BeginRestartAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;BeginRestartAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d5706-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d5706-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d5706-144">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-144">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="d5706-145">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-145">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d5706-146">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d5706-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d5706-147">仮想マシンを再起動する操作です。</span><span class="sxs-lookup"><span data-stu-id="d5706-147">The operation to restart a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRunCommandAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.RunCommandResultInner&gt; BeginRunCommandAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Fluent.Models.RunCommandInputInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.RunCommandResultInner&gt; BeginRunCommandAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Fluent.Models.RunCommandInputInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.BeginRunCommandAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.RunCommandInputInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRunCommandAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.RunCommandInputInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.RunCommandResultInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.BeginRunCommandAsync (operations, resourceGroupName, vmName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;BeginRunCommandAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.RunCommandResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Fluent.Models.RunCommandInputInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="vmName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginStartAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; BeginStartAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.BeginStartAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStartAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.BeginStartAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;BeginStartAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d5706-148">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d5706-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d5706-149">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-149">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="d5706-150">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-150">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d5706-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d5706-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d5706-152">バーチャル マシンを起動する操作です。</span><span class="sxs-lookup"><span data-stu-id="d5706-152">The operation to start a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CaptureAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineCaptureResultInner&gt; CaptureAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineCaptureParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineCaptureResultInner&gt; CaptureAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineCaptureParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.CaptureAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineCaptureParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CaptureAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineCaptureParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineCaptureResultInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.CaptureAsync (operations, resourceGroupName, vmName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;CaptureAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineCaptureResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineCaptureParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d5706-153">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d5706-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d5706-154">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-154">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="d5706-155">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-155">The name of the virtual machine.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d5706-156">パラメーターは、仮想マシンのキャプチャ操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="d5706-156">Parameters supplied to the Capture Virtual Machine operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d5706-157">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d5706-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d5706-158">VM の仮想ハード_ディスクをコピーして、VM をキャプチャし、類似した Vm の作成に使用できるテンプレートを出力します。</span><span class="sxs-lookup"><span data-stu-id="d5706-158">Captures the VM by copying virtual hard disks of the VM and outputs a template that can be used to create similar VMs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConvertToManagedDisksAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; ConvertToManagedDisksAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; ConvertToManagedDisksAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.ConvertToManagedDisksAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ConvertToManagedDisksAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.ConvertToManagedDisksAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;ConvertToManagedDisksAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d5706-159">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d5706-159">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d5706-160">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-160">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="d5706-161">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-161">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d5706-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d5706-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d5706-163">仮想マシンのディスクを blob に基づくから管理されるディスクに変換します。</span><span class="sxs-lookup"><span data-stu-id="d5706-163">Converts virtual machine disks from blob-based to managed disks.</span></span> <span data-ttu-id="d5706-164">仮想マシンがあります停止-割り当て解除されたこの操作を呼び出す前にします。</span><span class="sxs-lookup"><span data-stu-id="d5706-164">Virtual machine must be stop-deallocated before invoking this operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, vmName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d5706-165">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d5706-165">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d5706-166">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-166">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="d5706-167">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-167">The name of the virtual machine.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d5706-168">パラメーターは、仮想マシンの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="d5706-168">Parameters supplied to the Create Virtual Machine operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d5706-169">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d5706-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d5706-170">作成または仮想マシンを更新する操作です。</span><span class="sxs-lookup"><span data-stu-id="d5706-170">The operation to create or update a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeallocateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeallocateAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeallocateAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.DeallocateAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeallocateAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.DeallocateAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;DeallocateAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d5706-171">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d5706-171">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d5706-172">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-172">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="d5706-173">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-173">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d5706-174">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d5706-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d5706-175">仮想マシンをシャット ダウンし、コンピューティング リソースを解放します。</span><span class="sxs-lookup"><span data-stu-id="d5706-175">Shuts down the virtual machine and releases the compute resources.</span></span> <span data-ttu-id="d5706-176">このバーチャル マシンを使用するコンピューティング リソースには課金されません。</span><span class="sxs-lookup"><span data-stu-id="d5706-176">You are not billed for the compute resources that this virtual machine uses.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeleteAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; DeleteAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.DeleteAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d5706-177">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d5706-177">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d5706-178">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-178">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="d5706-179">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-179">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d5706-180">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d5706-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d5706-181">仮想マシンを削除する操作です。</span><span class="sxs-lookup"><span data-stu-id="d5706-181">The operation to delete a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeneralizeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; GeneralizeAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; GeneralizeAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.GeneralizeAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GeneralizeAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.GeneralizeAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;GeneralizeAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d5706-182">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d5706-182">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d5706-183">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-183">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="d5706-184">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-184">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d5706-185">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d5706-185">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d5706-186">一般化された仮想マシンの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="d5706-186">Sets the state of the virtual machine to generalized.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt; GetAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewTypes&gt; expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt; GetAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewTypes&gt; expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.String,System.Nullable{Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewTypes},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * string * Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewTypes&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.GetAsync (operations, resourceGroupName, vmName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="expand" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.InstanceViewTypes&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d5706-187">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d5706-187">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d5706-188">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-188">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="d5706-189">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-189">The name of the virtual machine.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="d5706-190">操作に適用する展開式です。</span><span class="sxs-lookup"><span data-stu-id="d5706-190">The expand expression to apply on the operation.</span></span> <span data-ttu-id="d5706-191">使用可能な値が含まれます: 'instanceView'</span><span class="sxs-lookup"><span data-stu-id="d5706-191">Possible values include: 'instanceView'</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d5706-192">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d5706-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d5706-193">モデル ビューまたはバーチャル マシンのインスタンス ビューに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="d5706-193">Retrieves information about the model view or the instance view of a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceViewAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView&gt; InstanceViewAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView&gt; InstanceViewAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.InstanceViewAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member InstanceViewAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.InstanceViewAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;InstanceViewAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="vmName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;ListAllAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d5706-194">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d5706-194">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d5706-195">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d5706-195">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d5706-196">すべての指定されたサブスクリプションの仮想マシンの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="d5706-196">Lists all of the virtual machines in the specified subscription.</span></span> <span data-ttu-id="d5706-197">応答で nextLink プロパティを使用すると、仮想マシンの次のページを取得できます。</span><span class="sxs-lookup"><span data-stu-id="d5706-197">Use the nextLink property in the response to get the next page of virtual machines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;ListAllNextAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d5706-198">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d5706-198">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="d5706-199">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="d5706-199">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d5706-200">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d5706-200">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d5706-201">すべての指定されたサブスクリプションの仮想マシンの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="d5706-201">Lists all of the virtual machines in the specified subscription.</span></span> <span data-ttu-id="d5706-202">応答で nextLink プロパティを使用すると、仮想マシンの次のページを取得できます。</span><span class="sxs-lookup"><span data-stu-id="d5706-202">Use the nextLink property in the response to get the next page of virtual machines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;ListAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d5706-203">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d5706-203">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d5706-204">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-204">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d5706-205">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d5706-205">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d5706-206">指定されたリソース グループの仮想マシンのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="d5706-206">Lists all of the virtual machines in the specified resource group.</span></span> <span data-ttu-id="d5706-207">応答で nextLink プロパティを使用すると、仮想マシンの次のページを取得できます。</span><span class="sxs-lookup"><span data-stu-id="d5706-207">Use the nextLink property in the response to get the next page of virtual machines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableSizesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize&gt;&gt; ListAvailableSizesAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize&gt;&gt; ListAvailableSizesAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.ListAvailableSizesAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAvailableSizesAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.ListAvailableSizesAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;ListAvailableSizesAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSize&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d5706-208">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d5706-208">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d5706-209">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-209">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="d5706-210">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-210">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d5706-211">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d5706-211">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d5706-212">指定された仮想マシンのサイズ変更するすべての利用可能な仮想マシンのサイズを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="d5706-212">Lists all available virtual machine sizes to which the specified virtual machine can be resized.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;ListNextAsync&gt;d__28))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d5706-213">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d5706-213">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="d5706-214">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="d5706-214">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d5706-215">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d5706-215">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d5706-216">指定されたリソース グループの仮想マシンのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="d5706-216">Lists all of the virtual machines in the specified resource group.</span></span> <span data-ttu-id="d5706-217">応答で nextLink プロパティを使用すると、仮想マシンの次のページを取得できます。</span><span class="sxs-lookup"><span data-stu-id="d5706-217">Use the nextLink property in the response to get the next page of virtual machines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PerformMaintenanceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; PerformMaintenanceAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; PerformMaintenanceAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.PerformMaintenanceAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PerformMaintenanceAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.PerformMaintenanceAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;PerformMaintenanceAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="vmName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PowerOffAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; PowerOffAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; PowerOffAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.PowerOffAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PowerOffAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.PowerOffAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;PowerOffAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d5706-218">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d5706-218">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d5706-219">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-219">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="d5706-220">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-220">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d5706-221">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d5706-221">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d5706-222">仮想マシンの電源をオフ (停止) する操作です。</span><span class="sxs-lookup"><span data-stu-id="d5706-222">The operation to power off (stop) a virtual machine.</span></span> <span data-ttu-id="d5706-223">同じプロビジョニングされているリソースを持つ仮想マシンを再起動することができます。</span><span class="sxs-lookup"><span data-stu-id="d5706-223">The virtual machine can be restarted with the same provisioned resources.</span></span> <span data-ttu-id="d5706-224">また、この仮想マシンの引き続き課金されます。</span><span class="sxs-lookup"><span data-stu-id="d5706-224">You are still charged for this virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedeployAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; RedeployAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; RedeployAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.RedeployAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RedeployAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.RedeployAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;RedeployAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d5706-225">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d5706-225">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d5706-226">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-226">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="d5706-227">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-227">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d5706-228">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d5706-228">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d5706-229">仮想マシンを再デプロイ操作です。</span><span class="sxs-lookup"><span data-stu-id="d5706-229">The operation to redeploy a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; RestartAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; RestartAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.RestartAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RestartAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.RestartAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;RestartAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d5706-230">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d5706-230">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d5706-231">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-231">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="d5706-232">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-232">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d5706-233">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d5706-233">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d5706-234">仮想マシンを再起動する操作です。</span><span class="sxs-lookup"><span data-stu-id="d5706-234">The operation to restart a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunCommandAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.RunCommandResultInner&gt; RunCommandAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Fluent.Models.RunCommandInputInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.RunCommandResultInner&gt; RunCommandAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Fluent.Models.RunCommandInputInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.RunCommandAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.RunCommandInputInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RunCommandAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Fluent.Models.RunCommandInputInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.RunCommandResultInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.RunCommandAsync (operations, resourceGroupName, vmName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;RunCommandAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.RunCommandResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Fluent.Models.RunCommandInputInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="vmName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; StartAsync (this Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt; StartAsync(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.StartAsync(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StartAsync : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions.StartAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.Fluent.VirtualMachinesOperationsExtensions/&lt;StartAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d5706-235">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="d5706-235">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d5706-236">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-236">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="d5706-237">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="d5706-237">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d5706-238">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d5706-238">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d5706-239">バーチャル マシンを起動する操作です。</span><span class="sxs-lookup"><span data-stu-id="d5706-239">The operation to start a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>