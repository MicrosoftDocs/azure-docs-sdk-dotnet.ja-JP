<Type Name="IVirtualMachineScaleSetsOperations" FullName="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineScaleSetsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineScaleSetsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineScaleSetsOperations" />
  <TypeSignature Language="F#" Value="type IVirtualMachineScaleSetsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a0311-101">VirtualMachineScaleSetsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="a0311-101">VirtualMachineScaleSetsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a0311-102">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-102">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="a0311-103">作成または更新する VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-103">The name of the VM scale set to create or update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a0311-104">小数点以下桁数は、オブジェクトを設定します。</span><span class="sxs-lookup"><span data-stu-id="a0311-104">The scale set object.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-107">作成または、VM スケール セットを更新します。</span><span class="sxs-lookup"><span data-stu-id="a0311-107">Create or update a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-108">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-109">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-109">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeallocateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginDeallocateWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginDeallocateWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.BeginDeallocateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeallocateWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.BeginDeallocateWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceIds, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a0311-111">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-111">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="a0311-112">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-112">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceIds">
            <span data-ttu-id="a0311-113">仮想マシン スケール セットのインスタンス id。</span><span class="sxs-lookup"><span data-stu-id="a0311-113">The virtual machine scale set instance ids.</span></span> <span data-ttu-id="a0311-114">仮想マシン スケール セットのインスタンス id を省略すると、仮想マシン スケール セット内のすべてのバーチャル マシンで実行される操作が発生します。</span><span class="sxs-lookup"><span data-stu-id="a0311-114">Omitting the virtual machine scale set instance ids will result in the operation being performed on all virtual machines in the virtual machine scale set.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-115">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-115">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-117">VM スケール セット内の特定の仮想マシンの割り当てを解除します。</span><span class="sxs-lookup"><span data-stu-id="a0311-117">Deallocates specific virtual machines in a VM scale set.</span></span> <span data-ttu-id="a0311-118">仮想マシンをシャット ダウンし、コンピューティング リソースを解放します。</span><span class="sxs-lookup"><span data-stu-id="a0311-118">Shuts down the virtual machines and releases the compute resources.</span></span> <span data-ttu-id="a0311-119">この仮想マシン スケール セットの割り当てを解除するコンピューティング リソースの料金はかかりません。</span><span class="sxs-lookup"><span data-stu-id="a0311-119">You are not billed for the compute resources that this virtual machine scale set deallocates.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-121">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-121">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-122">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-122">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteInstancesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginDeleteInstancesWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginDeleteInstancesWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.BeginDeleteInstancesWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteInstancesWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.BeginDeleteInstancesWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceIds, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a0311-123">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-123">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="a0311-124">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-124">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceIds">
            <span data-ttu-id="a0311-125">仮想マシン スケール セットのインスタンス id。</span><span class="sxs-lookup"><span data-stu-id="a0311-125">The virtual machine scale set instance ids.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-126">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-126">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-128">VM スケール セット内の仮想マシンを削除します。</span><span class="sxs-lookup"><span data-stu-id="a0311-128">Deletes virtual machines in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-129">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-129">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-130">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-130">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-131">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-131">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a0311-132">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-132">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="a0311-133">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-133">The name of the VM scale set.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-134">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-134">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-136">VM スケール セットを削除します。</span><span class="sxs-lookup"><span data-stu-id="a0311-136">Deletes a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-137">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-137">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-138">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-138">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-139">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-139">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginPowerOffWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginPowerOffWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginPowerOffWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.BeginPowerOffWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginPowerOffWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.BeginPowerOffWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceIds, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a0311-140">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-140">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="a0311-141">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-141">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceIds">
            <span data-ttu-id="a0311-142">仮想マシン スケール セットのインスタンス id。</span><span class="sxs-lookup"><span data-stu-id="a0311-142">The virtual machine scale set instance ids.</span></span> <span data-ttu-id="a0311-143">仮想マシン スケール セットのインスタンス id を省略すると、仮想マシン スケール セット内のすべてのバーチャル マシンで実行される操作が発生します。</span><span class="sxs-lookup"><span data-stu-id="a0311-143">Omitting the virtual machine scale set instance ids will result in the operation being performed on all virtual machines in the virtual machine scale set.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-144">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-144">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-145">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-146">電源をオフ (停止) VM スケール セット内の 1 つまたは複数の仮想マシン。</span><span class="sxs-lookup"><span data-stu-id="a0311-146">Power off (stop) one or more virtual machines in a VM scale set.</span></span>
            <span data-ttu-id="a0311-147">リソースがまだアタッチされているリソースには料金が取得することに注意してください。</span><span class="sxs-lookup"><span data-stu-id="a0311-147">Note that resources are still attached and you are getting charged for the resources.</span></span> <span data-ttu-id="a0311-148">代わりに、使用は、リソースを解放し、課金されないようにするの割り当てを解除します。</span><span class="sxs-lookup"><span data-stu-id="a0311-148">Instead, use deallocate to release resources and avoid charges.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-149">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-149">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-150">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-150">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-151">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-151">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginReimageAllWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginReimageAllWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginReimageAllWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.BeginReimageAllWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginReimageAllWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.BeginReimageAllWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceIds, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a0311-152">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-152">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="a0311-153">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-153">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceIds">
            <span data-ttu-id="a0311-154">仮想マシン スケール セットのインスタンス id。</span><span class="sxs-lookup"><span data-stu-id="a0311-154">The virtual machine scale set instance ids.</span></span> <span data-ttu-id="a0311-155">仮想マシン スケール セットのインスタンス id を省略すると、仮想マシン スケール セット内のすべてのバーチャル マシンで実行される操作が発生します。</span><span class="sxs-lookup"><span data-stu-id="a0311-155">Omitting the virtual machine scale set instance ids will result in the operation being performed on all virtual machines in the virtual machine scale set.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-156">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-156">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-157">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-158">VM スケール セット内の仮想マシンでは、(データ ディスクを含む) すべてのディスクを個です。</span><span class="sxs-lookup"><span data-stu-id="a0311-158">Reimages all the disks ( including data disks ) in the virtual machines in a VM scale set.</span></span> <span data-ttu-id="a0311-159">この操作は、管理対象ディスクに対してのみサポートされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-159">This operation is only supported for managed disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-160">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-160">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-161">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-161">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-162">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-162">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginReimageWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginReimageWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginReimageWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.BeginReimageWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginReimageWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.BeginReimageWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceIds, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a0311-163">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-163">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="a0311-164">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-164">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceIds">
            <span data-ttu-id="a0311-165">仮想マシン スケール セットのインスタンス id。</span><span class="sxs-lookup"><span data-stu-id="a0311-165">The virtual machine scale set instance ids.</span></span> <span data-ttu-id="a0311-166">仮想マシン スケール セットのインスタンス id を省略すると、仮想マシン スケール セット内のすべてのバーチャル マシンで実行される操作が発生します。</span><span class="sxs-lookup"><span data-stu-id="a0311-166">Omitting the virtual machine scale set instance ids will result in the operation being performed on all virtual machines in the virtual machine scale set.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-167">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-167">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-168">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-169">(オペレーティング システムのアップグレード) reimages VM スケールに 1 つまたは複数の仮想マシンを設定します。</span><span class="sxs-lookup"><span data-stu-id="a0311-169">Reimages (upgrade the operating system) one or more virtual machines in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-170">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-170">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-171">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-171">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-172">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-172">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginRestartWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginRestartWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginRestartWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.BeginRestartWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginRestartWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.BeginRestartWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceIds, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a0311-173">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-173">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="a0311-174">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-174">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceIds">
            <span data-ttu-id="a0311-175">仮想マシン スケール セットのインスタンス id。</span><span class="sxs-lookup"><span data-stu-id="a0311-175">The virtual machine scale set instance ids.</span></span> <span data-ttu-id="a0311-176">仮想マシン スケール セットのインスタンス id を省略すると、仮想マシン スケール セット内のすべてのバーチャル マシンで実行される操作が発生します。</span><span class="sxs-lookup"><span data-stu-id="a0311-176">Omitting the virtual machine scale set instance ids will result in the operation being performed on all virtual machines in the virtual machine scale set.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-177">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-177">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-178">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-178">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-179">VM スケール セット内の 1 つまたは複数の仮想マシンを再起動します。</span><span class="sxs-lookup"><span data-stu-id="a0311-179">Restarts one or more virtual machines in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-180">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-180">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-181">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-181">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-182">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-182">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginStartWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginStartWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginStartWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.BeginStartWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginStartWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.BeginStartWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceIds, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a0311-183">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-183">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="a0311-184">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-184">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceIds">
            <span data-ttu-id="a0311-185">仮想マシン スケール セットのインスタンス id。</span><span class="sxs-lookup"><span data-stu-id="a0311-185">The virtual machine scale set instance ids.</span></span> <span data-ttu-id="a0311-186">仮想マシン スケール セットのインスタンス id を省略すると、仮想マシン スケール セット内のすべてのバーチャル マシンで実行される操作が発生します。</span><span class="sxs-lookup"><span data-stu-id="a0311-186">Omitting the virtual machine scale set instance ids will result in the operation being performed on all virtual machines in the virtual machine scale set.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-187">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-187">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-188">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-189">VM スケール セット内の 1 つまたは複数の仮想マシンを起動します。</span><span class="sxs-lookup"><span data-stu-id="a0311-189">Starts one or more virtual machines in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-190">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-190">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-191">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-191">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-192">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-192">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateInstancesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginUpdateInstancesWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginUpdateInstancesWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.BeginUpdateInstancesWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateInstancesWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.BeginUpdateInstancesWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceIds, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a0311-193">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-193">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="a0311-194">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-194">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceIds">
            <span data-ttu-id="a0311-195">仮想マシン スケール セットのインスタンス id。</span><span class="sxs-lookup"><span data-stu-id="a0311-195">The virtual machine scale set instance ids.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-196">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-196">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-197">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-197">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-198">VM スケールで最新の SKU に 1 つまたは複数の仮想マシンの設定のアップグレードは、モデルを設定します。</span><span class="sxs-lookup"><span data-stu-id="a0311-198">Upgrades one or more virtual machines to the latest SKU set in the VM scale set model.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-199">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-199">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-200">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-200">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-201">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-201">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt; BeginUpdateWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt; BeginUpdateWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.BeginUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.BeginUpdateWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a0311-202">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-202">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="a0311-203">作成または更新する VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-203">The name of the VM scale set to create or update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a0311-204">小数点以下桁数は、オブジェクトを設定します。</span><span class="sxs-lookup"><span data-stu-id="a0311-204">The scale set object.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-205">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-205">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-206">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-206">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-207">VM スケール セットを更新します。</span><span class="sxs-lookup"><span data-stu-id="a0311-207">Update a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-208">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-208">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-209">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-209">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-210">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-210">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a0311-211">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-211">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="a0311-212">作成または更新する VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-212">The name of the VM scale set to create or update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a0311-213">小数点以下桁数は、オブジェクトを設定します。</span><span class="sxs-lookup"><span data-stu-id="a0311-213">The scale set object.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-214">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-214">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-215">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-215">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-216">作成または、VM スケール セットを更新します。</span><span class="sxs-lookup"><span data-stu-id="a0311-216">Create or update a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-217">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-217">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-218">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-218">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-219">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-219">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeallocateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; DeallocateWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; DeallocateWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.DeallocateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeallocateWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.DeallocateWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceIds, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a0311-220">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-220">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="a0311-221">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-221">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceIds">
            <span data-ttu-id="a0311-222">仮想マシン スケール セットのインスタンス id。</span><span class="sxs-lookup"><span data-stu-id="a0311-222">The virtual machine scale set instance ids.</span></span> <span data-ttu-id="a0311-223">仮想マシン スケール セットのインスタンス id を省略すると、仮想マシン スケール セット内のすべてのバーチャル マシンで実行される操作が発生します。</span><span class="sxs-lookup"><span data-stu-id="a0311-223">Omitting the virtual machine scale set instance ids will result in the operation being performed on all virtual machines in the virtual machine scale set.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-224">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-224">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-225">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-225">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-226">VM スケール セット内の特定の仮想マシンの割り当てを解除します。</span><span class="sxs-lookup"><span data-stu-id="a0311-226">Deallocates specific virtual machines in a VM scale set.</span></span> <span data-ttu-id="a0311-227">仮想マシンをシャット ダウンし、コンピューティング リソースを解放します。</span><span class="sxs-lookup"><span data-stu-id="a0311-227">Shuts down the virtual machines and releases the compute resources.</span></span> <span data-ttu-id="a0311-228">この仮想マシン スケール セットの割り当てを解除するコンピューティング リソースの料金はかかりません。</span><span class="sxs-lookup"><span data-stu-id="a0311-228">You are not billed for the compute resources that this virtual machine scale set deallocates.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-229">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-229">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-230">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-230">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-231">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-231">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteInstancesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; DeleteInstancesWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; DeleteInstancesWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.DeleteInstancesWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteInstancesWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.DeleteInstancesWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceIds, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a0311-232">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-232">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="a0311-233">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-233">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceIds">
            <span data-ttu-id="a0311-234">仮想マシン スケール セットのインスタンス id。</span><span class="sxs-lookup"><span data-stu-id="a0311-234">The virtual machine scale set instance ids.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-235">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-235">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-236">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-236">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-237">VM スケール セット内の仮想マシンを削除します。</span><span class="sxs-lookup"><span data-stu-id="a0311-237">Deletes virtual machines in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-238">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-238">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-239">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-239">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-240">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-240">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a0311-241">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-241">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="a0311-242">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-242">The name of the VM scale set.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-243">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-243">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-244">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-244">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-245">VM スケール セットを削除します。</span><span class="sxs-lookup"><span data-stu-id="a0311-245">Deletes a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-246">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-246">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-247">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-247">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-248">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-248">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetInstanceViewWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetInstanceView&gt;&gt; GetInstanceViewWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetInstanceView&gt;&gt; GetInstanceViewWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.GetInstanceViewWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetInstanceViewWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetInstanceView&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.GetInstanceViewWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetInstanceView&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a0311-249">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-249">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="a0311-250">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-250">The name of the VM scale set.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-251">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-251">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-252">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-252">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-253">状態の VM スケール セットのインスタンスを取得します。</span><span class="sxs-lookup"><span data-stu-id="a0311-253">Gets the status of a VM scale set instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-254">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-254">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-255">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-255">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-256">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-256">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.GetWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a0311-257">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-257">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="a0311-258">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-258">The name of the VM scale set.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-259">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-259">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-260">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-260">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-261">仮想マシン スケール セットに関する情報を表示します。</span><span class="sxs-lookup"><span data-stu-id="a0311-261">Display information about a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-262">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-262">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-263">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-263">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-264">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-264">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt;&gt; ListAllNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt;&gt; ListAllNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.ListAllNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAllNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.ListAllNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="a0311-265">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="a0311-265">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-266">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-266">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-267">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-267">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-268">関連付けられているリソース グループに関係なく、サブスクリプション内のすべての VM スケール セットの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="a0311-268">Gets a list of all VM Scale Sets in the subscription, regardless of the associated resource group.</span></span> <span data-ttu-id="a0311-269">応答で nextLink プロパティを使用して、VM スケール セットの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="a0311-269">Use nextLink property in the response to get the next page of VM Scale Sets.</span></span> <span data-ttu-id="a0311-270">NextLink が null のすべての VM スケール セットをフェッチするまで、この操作を行います。</span><span class="sxs-lookup"><span data-stu-id="a0311-270">Do this till nextLink is null to fetch all the VM Scale Sets.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-271">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-271">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-272">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-272">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-273">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-273">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAllWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt;&gt; ListAllWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt;&gt; ListAllWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.ListAllWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAllWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.ListAllWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="a0311-274">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-274">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-275">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-275">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-276">関連付けられているリソース グループに関係なく、サブスクリプション内のすべての VM スケール セットの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="a0311-276">Gets a list of all VM Scale Sets in the subscription, regardless of the associated resource group.</span></span> <span data-ttu-id="a0311-277">応答で nextLink プロパティを使用して、VM スケール セットの次のページを取得します。</span><span class="sxs-lookup"><span data-stu-id="a0311-277">Use nextLink property in the response to get the next page of VM Scale Sets.</span></span> <span data-ttu-id="a0311-278">NextLink が null のすべての VM スケール セットをフェッチするまで、この操作を行います。</span><span class="sxs-lookup"><span data-stu-id="a0311-278">Do this till nextLink is null to fetch all the VM Scale Sets.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-279">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-279">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-280">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-280">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-281">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-281">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="a0311-282">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="a0311-282">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-283">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-283">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-284">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-284">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-285">リソース グループに属するすべての VM スケールの一覧のセットを取得します。</span><span class="sxs-lookup"><span data-stu-id="a0311-285">Gets a list of all VM scale sets under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-286">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-286">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-287">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-287">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-288">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-288">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListSkusNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSku&gt;&gt;&gt; ListSkusNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSku&gt;&gt;&gt; ListSkusNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.ListSkusNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSkusNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSku&gt;&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.ListSkusNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSku&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="a0311-289">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="a0311-289">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-290">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-290">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-291">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-291">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-292">各 SKU に対して許可される最小値と最大の VM インスタンスを含む、VM スケール セットの使用可能な Sku の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="a0311-292">Gets a list of SKUs available for your VM scale set, including the minimum and maximum VM instances allowed for each SKU.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-293">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-293">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-294">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-294">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-295">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-295">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListSkusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSku&gt;&gt;&gt; ListSkusWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSku&gt;&gt;&gt; ListSkusWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.ListSkusWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSkusWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSku&gt;&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.ListSkusWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetSku&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a0311-296">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-296">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="a0311-297">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-297">The name of the VM scale set.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-298">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-298">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-299">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-299">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-300">各 SKU に対して許可される最小値と最大の VM インスタンスを含む、VM スケール セットの使用可能な Sku の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="a0311-300">Gets a list of SKUs available for your VM scale set, including the minimum and maximum VM instances allowed for each SKU.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-301">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-301">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-302">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-302">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-303">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-303">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt;&gt; ListWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt;&gt; ListWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.ListWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.ListWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a0311-304">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-304">The name of the resource group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-305">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-305">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-306">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-306">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-307">リソース グループに属するすべての VM スケールの一覧のセットを取得します。</span><span class="sxs-lookup"><span data-stu-id="a0311-307">Gets a list of all VM scale sets under a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-308">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-308">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-309">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-309">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-310">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-310">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PowerOffWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; PowerOffWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; PowerOffWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.PowerOffWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PowerOffWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.PowerOffWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceIds, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a0311-311">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-311">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="a0311-312">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-312">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceIds">
            <span data-ttu-id="a0311-313">仮想マシン スケール セットのインスタンス id。</span><span class="sxs-lookup"><span data-stu-id="a0311-313">The virtual machine scale set instance ids.</span></span> <span data-ttu-id="a0311-314">仮想マシン スケール セットのインスタンス id を省略すると、仮想マシン スケール セット内のすべてのバーチャル マシンで実行される操作が発生します。</span><span class="sxs-lookup"><span data-stu-id="a0311-314">Omitting the virtual machine scale set instance ids will result in the operation being performed on all virtual machines in the virtual machine scale set.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-315">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-315">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-316">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-316">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-317">電源をオフ (停止) VM スケール セット内の 1 つまたは複数の仮想マシン。</span><span class="sxs-lookup"><span data-stu-id="a0311-317">Power off (stop) one or more virtual machines in a VM scale set.</span></span>
            <span data-ttu-id="a0311-318">リソースがまだアタッチされているリソースには料金が取得することに注意してください。</span><span class="sxs-lookup"><span data-stu-id="a0311-318">Note that resources are still attached and you are getting charged for the resources.</span></span> <span data-ttu-id="a0311-319">代わりに、使用は、リソースを解放し、課金されないようにするの割り当てを解除します。</span><span class="sxs-lookup"><span data-stu-id="a0311-319">Instead, use deallocate to release resources and avoid charges.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-320">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-320">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-321">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-321">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-322">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-322">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ReimageAllWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; ReimageAllWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; ReimageAllWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.ReimageAllWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReimageAllWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.ReimageAllWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceIds, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a0311-323">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-323">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="a0311-324">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-324">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceIds">
            <span data-ttu-id="a0311-325">仮想マシン スケール セットのインスタンス id。</span><span class="sxs-lookup"><span data-stu-id="a0311-325">The virtual machine scale set instance ids.</span></span> <span data-ttu-id="a0311-326">仮想マシン スケール セットのインスタンス id を省略すると、仮想マシン スケール セット内のすべてのバーチャル マシンで実行される操作が発生します。</span><span class="sxs-lookup"><span data-stu-id="a0311-326">Omitting the virtual machine scale set instance ids will result in the operation being performed on all virtual machines in the virtual machine scale set.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-327">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-327">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-328">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-328">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-329">VM スケール セット内の仮想マシンでは、(データ ディスクを含む) すべてのディスクを個です。</span><span class="sxs-lookup"><span data-stu-id="a0311-329">Reimages all the disks ( including data disks ) in the virtual machines in a VM scale set.</span></span> <span data-ttu-id="a0311-330">この操作は、管理対象ディスクに対してのみサポートされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-330">This operation is only supported for managed disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-331">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-331">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-332">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-332">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-333">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-333">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ReimageWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; ReimageWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; ReimageWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.ReimageWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReimageWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.ReimageWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceIds, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a0311-334">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-334">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="a0311-335">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-335">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceIds">
            <span data-ttu-id="a0311-336">仮想マシン スケール セットのインスタンス id。</span><span class="sxs-lookup"><span data-stu-id="a0311-336">The virtual machine scale set instance ids.</span></span> <span data-ttu-id="a0311-337">仮想マシン スケール セットのインスタンス id を省略すると、仮想マシン スケール セット内のすべてのバーチャル マシンで実行される操作が発生します。</span><span class="sxs-lookup"><span data-stu-id="a0311-337">Omitting the virtual machine scale set instance ids will result in the operation being performed on all virtual machines in the virtual machine scale set.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-338">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-338">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-339">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-339">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-340">(オペレーティング システムのアップグレード) reimages VM スケールに 1 つまたは複数の仮想マシンを設定します。</span><span class="sxs-lookup"><span data-stu-id="a0311-340">Reimages (upgrade the operating system) one or more virtual machines in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-341">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-341">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-342">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-342">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-343">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-343">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RestartWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; RestartWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; RestartWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.RestartWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestartWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.RestartWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceIds, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a0311-344">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-344">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="a0311-345">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-345">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceIds">
            <span data-ttu-id="a0311-346">仮想マシン スケール セットのインスタンス id。</span><span class="sxs-lookup"><span data-stu-id="a0311-346">The virtual machine scale set instance ids.</span></span> <span data-ttu-id="a0311-347">仮想マシン スケール セットのインスタンス id を省略すると、仮想マシン スケール セット内のすべてのバーチャル マシンで実行される操作が発生します。</span><span class="sxs-lookup"><span data-stu-id="a0311-347">Omitting the virtual machine scale set instance ids will result in the operation being performed on all virtual machines in the virtual machine scale set.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-348">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-348">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-349">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-349">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-350">VM スケール セット内の 1 つまたは複数の仮想マシンを再起動します。</span><span class="sxs-lookup"><span data-stu-id="a0311-350">Restarts one or more virtual machines in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-351">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-351">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-352">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-352">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-353">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-353">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="StartWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; StartWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; StartWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.StartWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StartWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.StartWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceIds, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a0311-354">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-354">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="a0311-355">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-355">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceIds">
            <span data-ttu-id="a0311-356">仮想マシン スケール セットのインスタンス id。</span><span class="sxs-lookup"><span data-stu-id="a0311-356">The virtual machine scale set instance ids.</span></span> <span data-ttu-id="a0311-357">仮想マシン スケール セットのインスタンス id を省略すると、仮想マシン スケール セット内のすべてのバーチャル マシンで実行される操作が発生します。</span><span class="sxs-lookup"><span data-stu-id="a0311-357">Omitting the virtual machine scale set instance ids will result in the operation being performed on all virtual machines in the virtual machine scale set.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-358">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-358">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-359">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-359">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-360">VM スケール セット内の 1 つまたは複数の仮想マシンを起動します。</span><span class="sxs-lookup"><span data-stu-id="a0311-360">Starts one or more virtual machines in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-361">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-361">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-362">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-362">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-363">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-363">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateInstancesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; UpdateInstancesWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, System.Collections.Generic.IList&lt;string&gt; instanceIds, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; UpdateInstancesWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.IList`1&lt;string&gt; instanceIds, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.UpdateInstancesWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateInstancesWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.UpdateInstancesWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, instanceIds, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="instanceIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a0311-364">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-364">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="a0311-365">VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-365">The name of the VM scale set.</span></span>
            </param>
        <param name="instanceIds">
            <span data-ttu-id="a0311-366">仮想マシン スケール セットのインスタンス id。</span><span class="sxs-lookup"><span data-stu-id="a0311-366">The virtual machine scale set instance ids.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-367">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-367">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-368">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-368">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-369">VM スケールで最新の SKU に 1 つまたは複数の仮想マシンの設定のアップグレードは、モデルを設定します。</span><span class="sxs-lookup"><span data-stu-id="a0311-369">Upgrades one or more virtual machines to the latest SKU set in the VM scale set model.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-370">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-370">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-371">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-371">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-372">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-372">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetsOperations.UpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt;" Usage="iVirtualMachineScaleSetsOperations.UpdateWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSet&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetUpdate" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a0311-373">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-373">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="a0311-374">作成または更新する VM スケール セットの名前。</span><span class="sxs-lookup"><span data-stu-id="a0311-374">The name of the VM scale set to create or update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a0311-375">小数点以下桁数は、オブジェクトを設定します。</span><span class="sxs-lookup"><span data-stu-id="a0311-375">The scale set object.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="a0311-376">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="a0311-376">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a0311-377">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="a0311-377">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a0311-378">VM スケール セットを更新します。</span><span class="sxs-lookup"><span data-stu-id="a0311-378">Update a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="a0311-379">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-379">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="a0311-380">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-380">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a0311-381">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="a0311-381">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>