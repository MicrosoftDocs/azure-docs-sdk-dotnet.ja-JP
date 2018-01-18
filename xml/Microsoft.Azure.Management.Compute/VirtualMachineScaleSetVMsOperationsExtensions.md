<Type Name="VirtualMachineScaleSetVMsOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualMachineScaleSetVMsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualMachineScaleSetVMsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualMachineScaleSetVMsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualMachineScaleSetVMsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="200fb-101">VirtualMachineScaleSetVMsOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="200fb-101">Extension methods for VirtualMachineScaleSetVMsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginDeallocate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDeallocate (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDeallocate(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginDeallocate(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDeallocate (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginDeallocate : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginDeallocate (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-103">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-104">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-104">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-105">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-105">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-106">VM スケール セット内の特定の仮想マシンの割り当てを解除します。</span><span class="sxs-lookup"><span data-stu-id="200fb-106">Deallocates a specific virtual machine in a VM scale set.</span></span> <span data-ttu-id="200fb-107">仮想マシンをシャット ダウンし、使用するコンピューティング リソースを解放します。</span><span class="sxs-lookup"><span data-stu-id="200fb-107">Shuts down the virtual machine and releases the compute resources it uses.</span></span> <span data-ttu-id="200fb-108">料金はかかりませんこのバーチャル マシンのコンピューティング リソースの割り当てが解除されるとします。</span><span class="sxs-lookup"><span data-stu-id="200fb-108">You are not billed for the compute resources of this virtual machine once it is deallocated.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeallocateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeallocateAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeallocateAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginDeallocateAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeallocateAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginDeallocateAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginDeallocateAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-109">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-110">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-110">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-111">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-111">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-112">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-112">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="200fb-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="200fb-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-114">VM スケール セット内の特定の仮想マシンの割り当てを解除します。</span><span class="sxs-lookup"><span data-stu-id="200fb-114">Deallocates a specific virtual machine in a VM scale set.</span></span> <span data-ttu-id="200fb-115">仮想マシンをシャット ダウンし、使用するコンピューティング リソースを解放します。</span><span class="sxs-lookup"><span data-stu-id="200fb-115">Shuts down the virtual machine and releases the compute resources it uses.</span></span> <span data-ttu-id="200fb-116">料金はかかりませんこのバーチャル マシンのコンピューティング リソースの割り当てが解除されるとします。</span><span class="sxs-lookup"><span data-stu-id="200fb-116">You are not billed for the compute resources of this virtual machine once it is deallocated.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDelete (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDelete(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginDelete (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-117">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-118">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-118">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-119">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-119">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-120">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-120">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-121">VM スケール セットから仮想マシンを削除します。</span><span class="sxs-lookup"><span data-stu-id="200fb-121">Deletes a virtual machine from a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-122">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-123">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-123">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-124">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-124">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-125">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-125">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="200fb-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="200fb-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-127">VM スケール セットから仮想マシンを削除します。</span><span class="sxs-lookup"><span data-stu-id="200fb-127">Deletes a virtual machine from a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPowerOff">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginPowerOff (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginPowerOff(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginPowerOff(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginPowerOff (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginPowerOff : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginPowerOff (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-128">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-129">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-129">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-130">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-130">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-131">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-131">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-132">(停止) 仮想マシンに VM スケール セットの電源を切ります。</span><span class="sxs-lookup"><span data-stu-id="200fb-132">Power off (stop) a virtual machine in a VM scale set.</span></span> <span data-ttu-id="200fb-133">リソースがまだアタッチされているリソースには料金が取得することに注意してください。</span><span class="sxs-lookup"><span data-stu-id="200fb-133">Note that resources are still attached and you are getting charged for the resources.</span></span> <span data-ttu-id="200fb-134">代わりに、使用は、リソースを解放し、課金されないようにするの割り当てを解除します。</span><span class="sxs-lookup"><span data-stu-id="200fb-134">Instead, use deallocate to release resources and avoid charges.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPowerOffAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginPowerOffAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginPowerOffAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginPowerOffAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginPowerOffAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginPowerOffAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginPowerOffAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-135">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-135">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-136">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-136">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-137">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-137">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-138">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-138">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="200fb-139">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="200fb-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-140">(停止) 仮想マシンに VM スケール セットの電源を切ります。</span><span class="sxs-lookup"><span data-stu-id="200fb-140">Power off (stop) a virtual machine in a VM scale set.</span></span> <span data-ttu-id="200fb-141">リソースがまだアタッチされているリソースには料金が取得することに注意してください。</span><span class="sxs-lookup"><span data-stu-id="200fb-141">Note that resources are still attached and you are getting charged for the resources.</span></span> <span data-ttu-id="200fb-142">代わりに、使用は、リソースを解放し、課金されないようにするの割り当てを解除します。</span><span class="sxs-lookup"><span data-stu-id="200fb-142">Instead, use deallocate to release resources and avoid charges.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginReimage">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginReimage (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginReimage(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginReimage(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginReimage (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginReimage : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginReimage (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-143">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-144">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-144">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-145">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-145">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-146">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-146">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-147">(オペレーティング システムのアップグレード) reimages VM スケール内の特定の仮想マシンを設定します。</span><span class="sxs-lookup"><span data-stu-id="200fb-147">Reimages (upgrade the operating system) a specific virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginReimageAll">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginReimageAll (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginReimageAll(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginReimageAll(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginReimageAll (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginReimageAll : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginReimageAll (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-148">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-149">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-149">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-150">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-150">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-151">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-151">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-152">使用すると、イメージを再作成 (データ ディスクを含む) すべてのディスクは、VM スケール セットのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="200fb-152">Allows you to re-image all the disks ( including data disks ) in the a VM scale set instance.</span></span> <span data-ttu-id="200fb-153">この操作は、管理対象ディスクに対してのみサポートされます。</span><span class="sxs-lookup"><span data-stu-id="200fb-153">This operation is only supported for managed disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginReimageAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginReimageAllAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginReimageAllAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginReimageAllAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginReimageAllAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginReimageAllAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginReimageAllAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-154">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-154">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-155">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-155">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-156">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-156">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-157">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-157">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="200fb-158">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="200fb-158">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-159">使用すると、イメージを再作成 (データ ディスクを含む) すべてのディスクは、VM スケール セットのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="200fb-159">Allows you to re-image all the disks ( including data disks ) in the a VM scale set instance.</span></span> <span data-ttu-id="200fb-160">この操作は、管理対象ディスクに対してのみサポートされます。</span><span class="sxs-lookup"><span data-stu-id="200fb-160">This operation is only supported for managed disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginReimageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginReimageAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginReimageAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginReimageAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginReimageAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginReimageAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginReimageAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-161">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-161">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-162">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-162">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-163">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-163">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-164">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-164">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="200fb-165">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="200fb-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-166">(オペレーティング システムのアップグレード) reimages VM スケール内の特定の仮想マシンを設定します。</span><span class="sxs-lookup"><span data-stu-id="200fb-166">Reimages (upgrade the operating system) a specific virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRestart">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginRestart (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginRestart(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginRestart(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginRestart (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginRestart : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginRestart (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-167">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-167">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-168">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-168">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-169">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-169">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-170">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-170">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-171">VM スケール セット内の仮想マシンを再起動します。</span><span class="sxs-lookup"><span data-stu-id="200fb-171">Restarts a virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRestartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginRestartAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginRestartAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginRestartAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRestartAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginRestartAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginRestartAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-172">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-172">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-173">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-173">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-174">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-174">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-175">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-175">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="200fb-176">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="200fb-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-177">VM スケール セット内の仮想マシンを再起動します。</span><span class="sxs-lookup"><span data-stu-id="200fb-177">Restarts a virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStart">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginStart (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginStart(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginStart(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginStart (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginStart : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginStart (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-178">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-178">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-179">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-179">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-180">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-180">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-181">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-181">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-182">VM スケール セット内の仮想マシンを起動します。</span><span class="sxs-lookup"><span data-stu-id="200fb-182">Starts a virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginStartAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginStartAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginStartAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStartAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.BeginStartAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;BeginStartAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-183">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-183">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-184">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-184">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-185">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-185">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-186">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-186">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="200fb-187">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="200fb-187">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-188">VM スケール セット内の仮想マシンを起動します。</span><span class="sxs-lookup"><span data-stu-id="200fb-188">Starts a virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Deallocate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Deallocate (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Deallocate(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.Deallocate(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Deallocate (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Deallocate : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.Deallocate (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-189">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-189">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-190">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-190">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-191">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-191">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-192">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-192">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-193">VM スケール セット内の特定の仮想マシンの割り当てを解除します。</span><span class="sxs-lookup"><span data-stu-id="200fb-193">Deallocates a specific virtual machine in a VM scale set.</span></span> <span data-ttu-id="200fb-194">仮想マシンをシャット ダウンし、使用するコンピューティング リソースを解放します。</span><span class="sxs-lookup"><span data-stu-id="200fb-194">Shuts down the virtual machine and releases the compute resources it uses.</span></span> <span data-ttu-id="200fb-195">料金はかかりませんこのバーチャル マシンのコンピューティング リソースの割り当てが解除されるとします。</span><span class="sxs-lookup"><span data-stu-id="200fb-195">You are not billed for the compute resources of this virtual machine once it is deallocated.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeallocateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeallocateAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeallocateAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.DeallocateAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeallocateAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.DeallocateAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;DeallocateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-196">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-196">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-197">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-197">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-198">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-198">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-199">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-199">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="200fb-200">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="200fb-200">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-201">VM スケール セット内の特定の仮想マシンの割り当てを解除します。</span><span class="sxs-lookup"><span data-stu-id="200fb-201">Deallocates a specific virtual machine in a VM scale set.</span></span> <span data-ttu-id="200fb-202">仮想マシンをシャット ダウンし、使用するコンピューティング リソースを解放します。</span><span class="sxs-lookup"><span data-stu-id="200fb-202">Shuts down the virtual machine and releases the compute resources it uses.</span></span> <span data-ttu-id="200fb-203">料金はかかりませんこのバーチャル マシンのコンピューティング リソースの割り当てが解除されるとします。</span><span class="sxs-lookup"><span data-stu-id="200fb-203">You are not billed for the compute resources of this virtual machine once it is deallocated.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Delete (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Delete(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.Delete(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.Delete (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-204">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-204">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-205">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-205">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-206">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-206">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-207">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-207">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-208">VM スケール セットから仮想マシンを削除します。</span><span class="sxs-lookup"><span data-stu-id="200fb-208">Deletes a virtual machine from a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.DeleteAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-209">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-209">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-210">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-210">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-211">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-211">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-212">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-212">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="200fb-213">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="200fb-213">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-214">VM スケール セットから仮想マシンを削除します。</span><span class="sxs-lookup"><span data-stu-id="200fb-214">Deletes a virtual machine from a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM Get (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM Get(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.Get(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As VirtualMachineScaleSetVM" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.Get (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-215">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-215">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-216">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-216">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-217">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-217">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-218">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-218">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-219">VM スケール セットから仮想マシンを取得します。</span><span class="sxs-lookup"><span data-stu-id="200fb-219">Gets a virtual machine from a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt; GetAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt; GetAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.GetAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-220">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-220">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-221">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-221">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-222">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-222">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-223">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-223">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="200fb-224">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="200fb-224">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-225">VM スケール セットから仮想マシンを取得します。</span><span class="sxs-lookup"><span data-stu-id="200fb-225">Gets a virtual machine from a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetInstanceView">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView GetInstanceView (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView GetInstanceView(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.GetInstanceView(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetInstanceView (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As VirtualMachineScaleSetVMInstanceView" />
      <MemberSignature Language="F#" Value="static member GetInstanceView : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.GetInstanceView (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-226">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-226">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-227">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-227">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-228">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-228">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-229">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-229">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-230">VM スケール セットから仮想マシンの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="200fb-230">Gets the status of a virtual machine from a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetInstanceViewAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView&gt; GetInstanceViewAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView&gt; GetInstanceViewAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.GetInstanceViewAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetInstanceViewAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.GetInstanceViewAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;GetInstanceViewAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVMInstanceView&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-231">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-231">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-232">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-232">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-233">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-233">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-234">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-234">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="200fb-235">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="200fb-235">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-236">VM スケール セットから仮想マシンの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="200fb-236">Gets the status of a virtual machine from a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt; List (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string virtualMachineScaleSetName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt; odataQuery = null, string select = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt; List(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string virtualMachineScaleSetName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt; odataQuery, string select) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.List(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, virtualMachineScaleSetName As String, Optional odataQuery As ODataQuery(Of VirtualMachineScaleSetVM) = null, Optional select As String = null) As IPage(Of VirtualMachineScaleSetVM)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt; * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.List (operations, resourceGroupName, virtualMachineScaleSetName, odataQuery, select)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;" />
        <Parameter Name="select" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-237">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-237">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-238">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-238">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="200fb-239">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-239">The name of the VM scale set.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="200fb-240">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="200fb-240">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="200fb-241">リストのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="200fb-241">The list parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-242">VM スケール セットのすべての仮想マシンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="200fb-242">Gets a list of all virtual machines in a VM scale sets.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string virtualMachineScaleSetName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt; odataQuery = null, string select = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string virtualMachineScaleSetName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt; odataQuery, string select, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.ListAsync (operations, resourceGroupName, virtualMachineScaleSetName, odataQuery, select, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;ListAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-243">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-243">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-244">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-244">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="200fb-245">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-245">The name of the VM scale set.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="200fb-246">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="200fb-246">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="200fb-247">リストのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="200fb-247">The list parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="200fb-248">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="200fb-248">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-249">VM スケール セットのすべての仮想マシンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="200fb-249">Gets a list of all virtual machines in a VM scale sets.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt; ListNext (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt; ListNext(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.ListNext(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IVirtualMachineScaleSetVMsOperations, nextPageLink As String) As IPage(Of VirtualMachineScaleSetVM)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-250">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-250">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="200fb-251">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="200fb-251">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-252">VM スケール セットのすべての仮想マシンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="200fb-252">Gets a list of all virtual machines in a VM scale sets.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;ListNextAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetVM&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-253">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-253">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="200fb-254">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="200fb-254">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="200fb-255">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="200fb-255">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-256">VM スケール セットのすべての仮想マシンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="200fb-256">Gets a list of all virtual machines in a VM scale sets.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PowerOff">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse PowerOff (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse PowerOff(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.PowerOff(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PowerOff (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member PowerOff : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.PowerOff (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-257">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-257">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-258">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-258">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-259">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-259">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-260">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-260">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-261">(停止) 仮想マシンに VM スケール セットの電源を切ります。</span><span class="sxs-lookup"><span data-stu-id="200fb-261">Power off (stop) a virtual machine in a VM scale set.</span></span> <span data-ttu-id="200fb-262">リソースがまだアタッチされているリソースには料金が取得することに注意してください。</span><span class="sxs-lookup"><span data-stu-id="200fb-262">Note that resources are still attached and you are getting charged for the resources.</span></span> <span data-ttu-id="200fb-263">代わりに、使用は、リソースを解放し、課金されないようにするの割り当てを解除します。</span><span class="sxs-lookup"><span data-stu-id="200fb-263">Instead, use deallocate to release resources and avoid charges.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PowerOffAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; PowerOffAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; PowerOffAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.PowerOffAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PowerOffAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.PowerOffAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;PowerOffAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-264">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-264">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-265">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-265">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-266">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-266">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-267">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-267">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="200fb-268">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="200fb-268">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-269">(停止) 仮想マシンに VM スケール セットの電源を切ります。</span><span class="sxs-lookup"><span data-stu-id="200fb-269">Power off (stop) a virtual machine in a VM scale set.</span></span> <span data-ttu-id="200fb-270">リソースがまだアタッチされているリソースには料金が取得することに注意してください。</span><span class="sxs-lookup"><span data-stu-id="200fb-270">Note that resources are still attached and you are getting charged for the resources.</span></span> <span data-ttu-id="200fb-271">代わりに、使用は、リソースを解放し、課金されないようにするの割り当てを解除します。</span><span class="sxs-lookup"><span data-stu-id="200fb-271">Instead, use deallocate to release resources and avoid charges.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reimage">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Reimage (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Reimage(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.Reimage(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Reimage (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Reimage : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.Reimage (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-272">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-272">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-273">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-273">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-274">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-274">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-275">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-275">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-276">(オペレーティング システムのアップグレード) reimages VM スケール内の特定の仮想マシンを設定します。</span><span class="sxs-lookup"><span data-stu-id="200fb-276">Reimages (upgrade the operating system) a specific virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReimageAll">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse ReimageAll (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse ReimageAll(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.ReimageAll(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ReimageAll (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member ReimageAll : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.ReimageAll (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-277">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-277">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-278">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-278">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-279">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-279">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-280">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-280">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-281">使用すると、イメージを再作成 (データ ディスクを含む) すべてのディスクは、VM スケール セットのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="200fb-281">Allows you to re-image all the disks ( including data disks ) in the a VM scale set instance.</span></span> <span data-ttu-id="200fb-282">この操作は、管理対象ディスクに対してのみサポートされます。</span><span class="sxs-lookup"><span data-stu-id="200fb-282">This operation is only supported for managed disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReimageAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; ReimageAllAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; ReimageAllAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.ReimageAllAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ReimageAllAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.ReimageAllAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;ReimageAllAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-283">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-283">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-284">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-284">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-285">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-285">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-286">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-286">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="200fb-287">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="200fb-287">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-288">使用すると、イメージを再作成 (データ ディスクを含む) すべてのディスクは、VM スケール セットのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="200fb-288">Allows you to re-image all the disks ( including data disks ) in the a VM scale set instance.</span></span> <span data-ttu-id="200fb-289">この操作は、管理対象ディスクに対してのみサポートされます。</span><span class="sxs-lookup"><span data-stu-id="200fb-289">This operation is only supported for managed disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReimageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; ReimageAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; ReimageAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.ReimageAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ReimageAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.ReimageAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;ReimageAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-290">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-290">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-291">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-291">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-292">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-292">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-293">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-293">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="200fb-294">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="200fb-294">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-295">(オペレーティング システムのアップグレード) reimages VM スケール内の特定の仮想マシンを設定します。</span><span class="sxs-lookup"><span data-stu-id="200fb-295">Reimages (upgrade the operating system) a specific virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Restart">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Restart (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Restart(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.Restart(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Restart (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Restart : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.Restart (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-296">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-296">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-297">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-297">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-298">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-298">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-299">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-299">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-300">VM スケール セット内の仮想マシンを再起動します。</span><span class="sxs-lookup"><span data-stu-id="200fb-300">Restarts a virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; RestartAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; RestartAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.RestartAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RestartAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.RestartAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;RestartAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-301">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-301">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-302">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-302">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-303">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-303">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-304">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-304">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="200fb-305">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="200fb-305">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-306">VM スケール セット内の仮想マシンを再起動します。</span><span class="sxs-lookup"><span data-stu-id="200fb-306">Restarts a virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Start (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Start(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.Start(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Start (operations As IVirtualMachineScaleSetVMsOperations, resourceGroupName As String, vmScaleSetName As String, instanceId As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Start : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.Start (operations, resourceGroupName, vmScaleSetName, instanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-307">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-307">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-308">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-308">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-309">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-309">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-310">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-310">The instance ID of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-311">VM スケール セット内の仮想マシンを起動します。</span><span class="sxs-lookup"><span data-stu-id="200fb-311">Starts a virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; StartAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; StartAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations operations, string resourceGroupName, string vmScaleSetName, string instanceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.StartAsync(Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StartAsync : Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions.StartAsync (operations, resourceGroupName, vmScaleSetName, instanceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineScaleSetVMsOperationsExtensions/&lt;StartAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetVMsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="200fb-312">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="200fb-312">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="200fb-313">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-313">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="200fb-314">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="200fb-314">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="200fb-315">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="200fb-315">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="200fb-316">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="200fb-316">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="200fb-317">VM スケール セット内の仮想マシンを起動します。</span><span class="sxs-lookup"><span data-stu-id="200fb-317">Starts a virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>