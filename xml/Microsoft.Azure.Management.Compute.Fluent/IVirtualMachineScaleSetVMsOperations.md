<Type Name="IVirtualMachineScaleSetVMsOperations" FullName="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineScaleSetVMsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineScaleSetVMsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineScaleSetVMsOperations" />
  <TypeSignature Language="F#" Value="type IVirtualMachineScaleSetVMsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c26ac-101">VirtualMachineScaleSetVMsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="c26ac-101">VirtualMachineScaleSetVMsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginDeallocateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; BeginDeallocateWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, string instanceId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; BeginDeallocateWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, string instanceId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations.BeginDeallocateWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeallocateWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;" Usage="iVirtualMachineScaleSetVMsOperations.BeginDeallocateWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c26ac-102">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-102">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="c26ac-103">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-103">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="c26ac-104">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="c26ac-104">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c26ac-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26ac-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26ac-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26ac-107">VM スケール セット内の特定の仮想マシンの割り当てを解除します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-107">Deallocates a specific virtual machine in a VM scale set.</span></span> <span data-ttu-id="c26ac-108">仮想マシンをシャット ダウンし、使用するコンピューティング リソースを解放します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-108">Shuts down the virtual machine and releases the compute resources it uses.</span></span> <span data-ttu-id="c26ac-109">料金はかかりませんこのバーチャル マシンのコンピューティング リソースの割り当てが解除されるとします。</span><span class="sxs-lookup"><span data-stu-id="c26ac-109">You are not billed for the compute resources of this virtual machine once it is deallocated.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c26ac-110">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c26ac-111">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-111">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c26ac-112">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-112">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, string instanceId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, string instanceId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;" Usage="iVirtualMachineScaleSetVMsOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c26ac-113">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-113">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="c26ac-114">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-114">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="c26ac-115">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="c26ac-115">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c26ac-116">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-116">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26ac-117">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26ac-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26ac-118">VM スケール セットから仮想マシンを削除します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-118">Deletes a virtual machine from a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c26ac-119">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-119">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c26ac-120">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-120">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c26ac-121">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginPowerOffWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; BeginPowerOffWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, string instanceId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; BeginPowerOffWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, string instanceId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations.BeginPowerOffWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginPowerOffWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;" Usage="iVirtualMachineScaleSetVMsOperations.BeginPowerOffWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c26ac-122">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-122">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="c26ac-123">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-123">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="c26ac-124">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="c26ac-124">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c26ac-125">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-125">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26ac-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26ac-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26ac-127">(停止) 仮想マシンに VM スケール セットの電源を切ります。</span><span class="sxs-lookup"><span data-stu-id="c26ac-127">Power off (stop) a virtual machine in a VM scale set.</span></span> <span data-ttu-id="c26ac-128">リソースがまだアタッチされているリソースには料金が取得することに注意してください。</span><span class="sxs-lookup"><span data-stu-id="c26ac-128">Note that resources are still attached and you are getting charged for the resources.</span></span> <span data-ttu-id="c26ac-129">代わりに、使用は、リソースを解放し、課金されないようにするの割り当てを解除します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-129">Instead, use deallocate to release resources and avoid charges.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c26ac-130">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-130">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c26ac-131">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-131">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c26ac-132">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-132">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginReimageAllWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; BeginReimageAllWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, string instanceId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; BeginReimageAllWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, string instanceId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations.BeginReimageAllWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginReimageAllWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;" Usage="iVirtualMachineScaleSetVMsOperations.BeginReimageAllWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c26ac-133">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-133">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="c26ac-134">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-134">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="c26ac-135">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="c26ac-135">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c26ac-136">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-136">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26ac-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26ac-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26ac-138">使用すると、イメージを再作成 (データ ディスクを含む) すべてのディスク、仮想マシン スケール セットのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="c26ac-138">Allows you to re-image all the disks ( including data disks ) in the a virtual machine scale set instance.</span></span> <span data-ttu-id="c26ac-139">この操作は、管理対象ディスクに対してのみサポートされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-139">This operation is only supported for managed disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c26ac-140">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-140">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c26ac-141">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-141">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c26ac-142">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-142">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginReimageWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; BeginReimageWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, string instanceId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; BeginReimageWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, string instanceId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations.BeginReimageWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginReimageWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;" Usage="iVirtualMachineScaleSetVMsOperations.BeginReimageWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c26ac-143">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-143">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="c26ac-144">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-144">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="c26ac-145">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="c26ac-145">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c26ac-146">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-146">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26ac-147">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26ac-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26ac-148">(オペレーティング システムのアップグレード) reimages VM スケール内の特定の仮想マシンを設定します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-148">Reimages (upgrade the operating system) a specific virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c26ac-149">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-149">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c26ac-150">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-150">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c26ac-151">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-151">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginRestartWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; BeginRestartWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, string instanceId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; BeginRestartWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, string instanceId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations.BeginRestartWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginRestartWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;" Usage="iVirtualMachineScaleSetVMsOperations.BeginRestartWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c26ac-152">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-152">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="c26ac-153">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-153">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="c26ac-154">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="c26ac-154">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c26ac-155">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-155">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26ac-156">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26ac-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26ac-157">VM スケール セット内の仮想マシンを再起動します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-157">Restarts a virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c26ac-158">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-158">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c26ac-159">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-159">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c26ac-160">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-160">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginStartWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; BeginStartWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, string instanceId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; BeginStartWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, string instanceId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations.BeginStartWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginStartWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;" Usage="iVirtualMachineScaleSetVMsOperations.BeginStartWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c26ac-161">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-161">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="c26ac-162">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-162">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="c26ac-163">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="c26ac-163">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c26ac-164">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-164">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26ac-165">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26ac-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26ac-166">VM スケール セット内の仮想マシンを起動します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-166">Starts a virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c26ac-167">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-167">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c26ac-168">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-168">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c26ac-169">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-169">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeallocateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; DeallocateWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, string instanceId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; DeallocateWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, string instanceId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations.DeallocateWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeallocateWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;" Usage="iVirtualMachineScaleSetVMsOperations.DeallocateWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c26ac-170">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-170">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="c26ac-171">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-171">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="c26ac-172">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="c26ac-172">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c26ac-173">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-173">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26ac-174">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26ac-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26ac-175">VM スケール セット内の特定の仮想マシンの割り当てを解除します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-175">Deallocates a specific virtual machine in a VM scale set.</span></span> <span data-ttu-id="c26ac-176">仮想マシンをシャット ダウンし、使用するコンピューティング リソースを解放します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-176">Shuts down the virtual machine and releases the compute resources it uses.</span></span> <span data-ttu-id="c26ac-177">料金はかかりませんこのバーチャル マシンのコンピューティング リソースの割り当てが解除されるとします。</span><span class="sxs-lookup"><span data-stu-id="c26ac-177">You are not billed for the compute resources of this virtual machine once it is deallocated.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c26ac-178">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-178">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c26ac-179">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-179">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c26ac-180">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-180">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, string instanceId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, string instanceId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;" Usage="iVirtualMachineScaleSetVMsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c26ac-181">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-181">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="c26ac-182">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-182">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="c26ac-183">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="c26ac-183">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c26ac-184">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-184">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26ac-185">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26ac-185">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26ac-186">VM スケール セットから仮想マシンを削除します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-186">Deletes a virtual machine from a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c26ac-187">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-187">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c26ac-188">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-188">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c26ac-189">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-189">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetInstanceViewWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInstanceViewInner&gt;&gt; GetInstanceViewWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, string instanceId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInstanceViewInner&gt;&gt; GetInstanceViewWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, string instanceId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations.GetInstanceViewWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetInstanceViewWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInstanceViewInner&gt;&gt;" Usage="iVirtualMachineScaleSetVMsOperations.GetInstanceViewWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInstanceViewInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c26ac-190">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-190">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="c26ac-191">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-191">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="c26ac-192">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="c26ac-192">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c26ac-193">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-193">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26ac-194">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26ac-194">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26ac-195">VM スケール セットから仮想マシンの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-195">Gets the status of a virtual machine from a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c26ac-196">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-196">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c26ac-197">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-197">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c26ac-198">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-198">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, string instanceId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, string instanceId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt;" Usage="iVirtualMachineScaleSetVMsOperations.GetWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c26ac-199">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-199">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="c26ac-200">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-200">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="c26ac-201">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="c26ac-201">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c26ac-202">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-202">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26ac-203">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26ac-203">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26ac-204">VM スケール セットから仮想マシンを取得します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-204">Gets a virtual machine from a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c26ac-205">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-205">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c26ac-206">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-206">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c26ac-207">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-207">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt;&gt;" Usage="iVirtualMachineScaleSetVMsOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="c26ac-208">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="c26ac-208">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c26ac-209">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-209">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26ac-210">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26ac-210">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26ac-211">VM スケール セットのすべての仮想マシンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-211">Gets a list of all virtual machines in a VM scale sets.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c26ac-212">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-212">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c26ac-213">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-213">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c26ac-214">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-214">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt;&gt; ListWithHttpMessagesAsync (string resourceGroupName, string virtualMachineScaleSetName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt; odataQuery = null, string select = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt;&gt; ListWithHttpMessagesAsync(string resourceGroupName, string virtualMachineScaleSetName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt; odataQuery, string select, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations.ListWithHttpMessagesAsync(System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner},System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt; * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt;&gt;" Usage="iVirtualMachineScaleSetVMsOperations.ListWithHttpMessagesAsync (resourceGroupName, virtualMachineScaleSetName, odataQuery, select, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c26ac-215">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-215">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="c26ac-216">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-216">The name of the VM scale set.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="c26ac-217">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="c26ac-217">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="c26ac-218">リストのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="c26ac-218">The list parameters.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c26ac-219">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-219">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26ac-220">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26ac-220">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26ac-221">VM スケール セットのすべての仮想マシンの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-221">Gets a list of all virtual machines in a VM scale sets.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c26ac-222">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-222">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c26ac-223">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-223">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c26ac-224">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-224">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PowerOffWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; PowerOffWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, string instanceId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; PowerOffWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, string instanceId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations.PowerOffWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PowerOffWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;" Usage="iVirtualMachineScaleSetVMsOperations.PowerOffWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c26ac-225">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-225">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="c26ac-226">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-226">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="c26ac-227">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="c26ac-227">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c26ac-228">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-228">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26ac-229">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26ac-229">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26ac-230">(停止) 仮想マシンに VM スケール セットの電源を切ります。</span><span class="sxs-lookup"><span data-stu-id="c26ac-230">Power off (stop) a virtual machine in a VM scale set.</span></span> <span data-ttu-id="c26ac-231">リソースがまだアタッチされているリソースには料金が取得することに注意してください。</span><span class="sxs-lookup"><span data-stu-id="c26ac-231">Note that resources are still attached and you are getting charged for the resources.</span></span> <span data-ttu-id="c26ac-232">代わりに、使用は、リソースを解放し、課金されないようにするの割り当てを解除します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-232">Instead, use deallocate to release resources and avoid charges.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c26ac-233">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-233">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c26ac-234">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-234">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c26ac-235">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-235">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ReimageAllWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; ReimageAllWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, string instanceId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; ReimageAllWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, string instanceId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations.ReimageAllWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReimageAllWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;" Usage="iVirtualMachineScaleSetVMsOperations.ReimageAllWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c26ac-236">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-236">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="c26ac-237">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-237">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="c26ac-238">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="c26ac-238">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c26ac-239">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-239">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26ac-240">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26ac-240">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26ac-241">使用すると、イメージを再作成 (データ ディスクを含む) すべてのディスク、仮想マシン スケール セットのインスタンス。</span><span class="sxs-lookup"><span data-stu-id="c26ac-241">Allows you to re-image all the disks ( including data disks ) in the a virtual machine scale set instance.</span></span> <span data-ttu-id="c26ac-242">この操作は、管理対象ディスクに対してのみサポートされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-242">This operation is only supported for managed disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c26ac-243">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-243">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c26ac-244">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-244">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c26ac-245">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-245">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ReimageWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; ReimageWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, string instanceId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; ReimageWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, string instanceId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations.ReimageWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReimageWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;" Usage="iVirtualMachineScaleSetVMsOperations.ReimageWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c26ac-246">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-246">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="c26ac-247">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-247">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="c26ac-248">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="c26ac-248">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c26ac-249">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-249">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26ac-250">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26ac-250">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26ac-251">(オペレーティング システムのアップグレード) reimages VM スケール内の特定の仮想マシンを設定します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-251">Reimages (upgrade the operating system) a specific virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c26ac-252">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-252">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c26ac-253">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-253">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c26ac-254">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-254">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RestartWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; RestartWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, string instanceId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; RestartWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, string instanceId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations.RestartWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestartWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;" Usage="iVirtualMachineScaleSetVMsOperations.RestartWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c26ac-255">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-255">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="c26ac-256">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-256">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="c26ac-257">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="c26ac-257">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c26ac-258">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-258">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26ac-259">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26ac-259">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26ac-260">VM スケール セット内の仮想マシンを再起動します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-260">Restarts a virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c26ac-261">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-261">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c26ac-262">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-262">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c26ac-263">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-263">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="StartWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; StartWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, string instanceId, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt; StartWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, string instanceId, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations.StartWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StartWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;" Usage="iVirtualMachineScaleSetVMsOperations.StartWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceId, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.OperationStatusResponseInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c26ac-264">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-264">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="c26ac-265">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="c26ac-265">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceId">
            <span data-ttu-id="c26ac-266">仮想マシンのインスタンス ID。</span><span class="sxs-lookup"><span data-stu-id="c26ac-266">The instance ID of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c26ac-267">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-267">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c26ac-268">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c26ac-268">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c26ac-269">VM スケール セット内の仮想マシンを起動します。</span><span class="sxs-lookup"><span data-stu-id="c26ac-269">Starts a virtual machine in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c26ac-270">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-270">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c26ac-271">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-271">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c26ac-272">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c26ac-272">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>