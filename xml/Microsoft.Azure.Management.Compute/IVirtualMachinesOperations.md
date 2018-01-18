<Type Name="IVirtualMachinesOperations" FullName="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations">
  <TypeSignature Language="C#" Value="public interface IVirtualMachinesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachinesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachinesOperations" />
  <TypeSignature Language="F#" Value="type IVirtualMachinesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c3a46-101">VirtualMachinesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="c3a46-101">VirtualMachinesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCaptureWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult&gt;&gt; BeginCaptureWithHttpMessagesAsync (string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult&gt;&gt; BeginCaptureWithHttpMessagesAsync(string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.BeginCaptureWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCaptureWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult&gt;&gt;" Usage="iVirtualMachinesOperations.BeginCaptureWithHttpMessagesAsync (resourceGroupName, vmName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-102">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-102">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="c3a46-103">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-103">The name of the virtual machine.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c3a46-104">パラメーターは、仮想マシンのキャプチャ操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-104">Parameters supplied to the Capture Virtual Machine operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-107">VM の仮想ハード_ディスクをコピーして、VM をキャプチャし、類似した Vm の作成に使用できるテンプレートを出力します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-107">Captures the VM by copying virtual hard disks of the VM and outputs a template that can be used to create similar VMs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-108">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-109">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-109">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginConvertToManagedDisksWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginConvertToManagedDisksWithHttpMessagesAsync (string resourceGroupName, string vmName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginConvertToManagedDisksWithHttpMessagesAsync(string resourceGroupName, string vmName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.BeginConvertToManagedDisksWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginConvertToManagedDisksWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachinesOperations.BeginConvertToManagedDisksWithHttpMessagesAsync (resourceGroupName, vmName, customHeaders, cancellationToken)" />
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
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-111">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-111">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="c3a46-112">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-112">The name of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-113">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-113">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-114">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-115">仮想マシンのディスクを blob に基づくから管理されるディスクに変換します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-115">Converts virtual machine disks from blob-based to managed disks.</span></span>
            <span data-ttu-id="c3a46-116">仮想マシンがあります停止-割り当て解除されたこの操作を呼び出す前にします。</span><span class="sxs-lookup"><span data-stu-id="c3a46-116">Virtual machine must be stop-deallocated before invoking this operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-117">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-117">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-118">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-118">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-119">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-119">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.VirtualMachine parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.VirtualMachine parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachine,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachine * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;" Usage="iVirtualMachinesOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, vmName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachine" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-120">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-120">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="c3a46-121">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-121">The name of the virtual machine.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c3a46-122">パラメーターは、仮想マシンの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-122">Parameters supplied to the Create Virtual Machine operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-123">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-123">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-125">作成または仮想マシンを更新する操作です。</span><span class="sxs-lookup"><span data-stu-id="c3a46-125">The operation to create or update a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-126">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-126">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-127">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-127">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-128">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-128">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeallocateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginDeallocateWithHttpMessagesAsync (string resourceGroupName, string vmName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginDeallocateWithHttpMessagesAsync(string resourceGroupName, string vmName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.BeginDeallocateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeallocateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachinesOperations.BeginDeallocateWithHttpMessagesAsync (resourceGroupName, vmName, customHeaders, cancellationToken)" />
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
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-129">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-129">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="c3a46-130">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-130">The name of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-131">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-131">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-133">仮想マシンをシャット ダウンし、コンピューティング リソースを解放します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-133">Shuts down the virtual machine and releases the compute resources.</span></span>
            <span data-ttu-id="c3a46-134">このバーチャル マシンを使用するコンピューティング リソースには課金されません。</span><span class="sxs-lookup"><span data-stu-id="c3a46-134">You are not billed for the compute resources that this virtual machine uses.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-135">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-135">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-136">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-136">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-137">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-137">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string vmName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string vmName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachinesOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, vmName, customHeaders, cancellationToken)" />
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
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-138">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-138">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="c3a46-139">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-139">The name of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-140">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-140">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-141">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-142">仮想マシンを削除する操作です。</span><span class="sxs-lookup"><span data-stu-id="c3a46-142">The operation to delete a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-143">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-143">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-144">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-144">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-145">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginPerformMaintenanceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginPerformMaintenanceWithHttpMessagesAsync (string resourceGroupName, string vmName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginPerformMaintenanceWithHttpMessagesAsync(string resourceGroupName, string vmName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.BeginPerformMaintenanceWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginPerformMaintenanceWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachinesOperations.BeginPerformMaintenanceWithHttpMessagesAsync (resourceGroupName, vmName, customHeaders, cancellationToken)" />
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
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-146">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-146">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="c3a46-147">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-147">The name of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-148">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-148">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-149">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-150">仮想マシンでメンテナンスを実行する操作。</span><span class="sxs-lookup"><span data-stu-id="c3a46-150">The operation to perform maintenance on a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-151">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-151">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-152">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-152">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-153">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-153">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginPowerOffWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginPowerOffWithHttpMessagesAsync (string resourceGroupName, string vmName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginPowerOffWithHttpMessagesAsync(string resourceGroupName, string vmName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.BeginPowerOffWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginPowerOffWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachinesOperations.BeginPowerOffWithHttpMessagesAsync (resourceGroupName, vmName, customHeaders, cancellationToken)" />
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
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-154">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-154">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="c3a46-155">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-155">The name of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-156">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-156">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-157">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-158">仮想マシンの電源をオフ (停止) する操作です。</span><span class="sxs-lookup"><span data-stu-id="c3a46-158">The operation to power off (stop) a virtual machine.</span></span> <span data-ttu-id="c3a46-159">同じプロビジョニングされているリソースを持つ仮想マシンを再起動することができます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-159">The virtual machine can be restarted with the same provisioned resources.</span></span> <span data-ttu-id="c3a46-160">また、この仮想マシンの引き続き課金されます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-160">You are still charged for this virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-161">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-161">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-162">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-162">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-163">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-163">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginRedeployWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginRedeployWithHttpMessagesAsync (string resourceGroupName, string vmName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginRedeployWithHttpMessagesAsync(string resourceGroupName, string vmName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.BeginRedeployWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginRedeployWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachinesOperations.BeginRedeployWithHttpMessagesAsync (resourceGroupName, vmName, customHeaders, cancellationToken)" />
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
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-164">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-164">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="c3a46-165">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-165">The name of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-166">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-166">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-167">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-168">仮想マシンを再デプロイ操作です。</span><span class="sxs-lookup"><span data-stu-id="c3a46-168">The operation to redeploy a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-169">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-169">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-170">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-170">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-171">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-171">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginRestartWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginRestartWithHttpMessagesAsync (string resourceGroupName, string vmName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginRestartWithHttpMessagesAsync(string resourceGroupName, string vmName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.BeginRestartWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginRestartWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachinesOperations.BeginRestartWithHttpMessagesAsync (resourceGroupName, vmName, customHeaders, cancellationToken)" />
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
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-172">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-172">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="c3a46-173">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-173">The name of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-174">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-174">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-175">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-175">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-176">仮想マシンを再起動する操作です。</span><span class="sxs-lookup"><span data-stu-id="c3a46-176">The operation to restart a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-177">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-177">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-178">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-178">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-179">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-179">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginRunCommandWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.RunCommandResult&gt;&gt; BeginRunCommandWithHttpMessagesAsync (string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.RunCommandInput parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.RunCommandResult&gt;&gt; BeginRunCommandWithHttpMessagesAsync(string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.RunCommandInput parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.BeginRunCommandWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Compute.Models.RunCommandInput,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginRunCommandWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Compute.Models.RunCommandInput * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.RunCommandResult&gt;&gt;" Usage="iVirtualMachinesOperations.BeginRunCommandWithHttpMessagesAsync (resourceGroupName, vmName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.RunCommandResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.RunCommandInput" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-180">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-180">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="c3a46-181">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-181">The name of the virtual machine.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c3a46-182">Run コマンドの操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="c3a46-182">Parameters supplied to the Run command operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-183">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-183">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-184">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-184">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-185">VM 上のコマンドを実行します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-185">Run command on the VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-186">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-186">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-187">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-187">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-188">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-188">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginStartWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginStartWithHttpMessagesAsync (string resourceGroupName, string vmName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginStartWithHttpMessagesAsync(string resourceGroupName, string vmName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.BeginStartWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginStartWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachinesOperations.BeginStartWithHttpMessagesAsync (resourceGroupName, vmName, customHeaders, cancellationToken)" />
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
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-189">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-189">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="c3a46-190">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-190">The name of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-191">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-191">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-192">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-193">バーチャル マシンを起動する操作です。</span><span class="sxs-lookup"><span data-stu-id="c3a46-193">The operation to start a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-194">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-194">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-195">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-195">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-196">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-196">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CaptureWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult&gt;&gt; CaptureWithHttpMessagesAsync (string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult&gt;&gt; CaptureWithHttpMessagesAsync(string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.CaptureWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CaptureWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult&gt;&gt;" Usage="iVirtualMachinesOperations.CaptureWithHttpMessagesAsync (resourceGroupName, vmName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-197">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-197">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="c3a46-198">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-198">The name of the virtual machine.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c3a46-199">パラメーターは、仮想マシンのキャプチャ操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-199">Parameters supplied to the Capture Virtual Machine operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-200">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-200">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-201">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-201">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-202">VM の仮想ハード_ディスクをコピーして、VM をキャプチャし、類似した Vm の作成に使用できるテンプレートを出力します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-202">Captures the VM by copying virtual hard disks of the VM and outputs a template that can be used to create similar VMs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-203">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-203">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-204">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-204">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-205">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-205">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ConvertToManagedDisksWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; ConvertToManagedDisksWithHttpMessagesAsync (string resourceGroupName, string vmName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; ConvertToManagedDisksWithHttpMessagesAsync(string resourceGroupName, string vmName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.ConvertToManagedDisksWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ConvertToManagedDisksWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachinesOperations.ConvertToManagedDisksWithHttpMessagesAsync (resourceGroupName, vmName, customHeaders, cancellationToken)" />
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
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-206">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-206">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="c3a46-207">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-207">The name of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-208">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-208">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-209">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-209">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-210">仮想マシンのディスクを blob に基づくから管理されるディスクに変換します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-210">Converts virtual machine disks from blob-based to managed disks.</span></span>
            <span data-ttu-id="c3a46-211">仮想マシンがあります停止-割り当て解除されたこの操作を呼び出す前にします。</span><span class="sxs-lookup"><span data-stu-id="c3a46-211">Virtual machine must be stop-deallocated before invoking this operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-212">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-212">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-213">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-213">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-214">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-214">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.VirtualMachine parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.VirtualMachine parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachine,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachine * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;" Usage="iVirtualMachinesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, vmName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachine" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-215">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-215">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="c3a46-216">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-216">The name of the virtual machine.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c3a46-217">パラメーターは、仮想マシンの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-217">Parameters supplied to the Create Virtual Machine operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-218">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-218">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-219">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-219">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-220">作成または仮想マシンを更新する操作です。</span><span class="sxs-lookup"><span data-stu-id="c3a46-220">The operation to create or update a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-221">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-221">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-222">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-222">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-223">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-223">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeallocateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; DeallocateWithHttpMessagesAsync (string resourceGroupName, string vmName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; DeallocateWithHttpMessagesAsync(string resourceGroupName, string vmName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.DeallocateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeallocateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachinesOperations.DeallocateWithHttpMessagesAsync (resourceGroupName, vmName, customHeaders, cancellationToken)" />
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
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-224">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-224">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="c3a46-225">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-225">The name of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-226">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-226">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-227">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-227">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-228">仮想マシンをシャット ダウンし、コンピューティング リソースを解放します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-228">Shuts down the virtual machine and releases the compute resources.</span></span>
            <span data-ttu-id="c3a46-229">このバーチャル マシンを使用するコンピューティング リソースには課金されません。</span><span class="sxs-lookup"><span data-stu-id="c3a46-229">You are not billed for the compute resources that this virtual machine uses.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-230">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-230">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-231">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-231">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-232">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-232">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string vmName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string vmName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachinesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, vmName, customHeaders, cancellationToken)" />
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
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-233">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-233">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="c3a46-234">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-234">The name of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-235">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-235">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-236">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-236">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-237">仮想マシンを削除する操作です。</span><span class="sxs-lookup"><span data-stu-id="c3a46-237">The operation to delete a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-238">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-238">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-239">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-239">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-240">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-240">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GeneralizeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; GeneralizeWithHttpMessagesAsync (string resourceGroupName, string vmName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; GeneralizeWithHttpMessagesAsync(string resourceGroupName, string vmName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.GeneralizeWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GeneralizeWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachinesOperations.GeneralizeWithHttpMessagesAsync (resourceGroupName, vmName, customHeaders, cancellationToken)" />
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
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-241">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-241">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="c3a46-242">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-242">The name of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-243">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-243">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-244">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-244">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-245">一般化された仮想マシンの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-245">Sets the state of the virtual machine to generalized.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-246">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-246">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-247">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-247">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-248">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-248">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string vmName, Nullable&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewTypes&gt; expand = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string vmName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.InstanceViewTypes&gt; expand, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Nullable{Microsoft.Azure.Management.Compute.Models.InstanceViewTypes},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * Nullable&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewTypes&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;" Usage="iVirtualMachinesOperations.GetWithHttpMessagesAsync (resourceGroupName, vmName, expand, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="expand" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewTypes&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-249">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-249">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="c3a46-250">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-250">The name of the virtual machine.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="c3a46-251">操作に適用する展開式です。</span><span class="sxs-lookup"><span data-stu-id="c3a46-251">The expand expression to apply on the operation.</span></span> <span data-ttu-id="c3a46-252">使用可能な値が含まれます: 'instanceView'</span><span class="sxs-lookup"><span data-stu-id="c3a46-252">Possible values include: 'instanceView'</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-253">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-253">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-254">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-254">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-255">モデル ビューまたはバーチャル マシンのインスタンス ビューに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-255">Retrieves information about the model view or the instance view of a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-256">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-256">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-257">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-257">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-258">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-258">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="InstanceViewWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView&gt;&gt; InstanceViewWithHttpMessagesAsync (string resourceGroupName, string vmName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView&gt;&gt; InstanceViewWithHttpMessagesAsync(string resourceGroupName, string vmName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.InstanceViewWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InstanceViewWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView&gt;&gt;" Usage="iVirtualMachinesOperations.InstanceViewWithHttpMessagesAsync (resourceGroupName, vmName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-259">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-259">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="c3a46-260">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-260">The name of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-261">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-261">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-262">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-262">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-263">仮想マシンの実行時の状態に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-263">Retrieves information about the run-time state of a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-264">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-264">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-265">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-265">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-266">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-266">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;&gt; ListAllNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;&gt; ListAllNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.ListAllNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAllNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;&gt;" Usage="iVirtualMachinesOperations.ListAllNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="c3a46-267">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="c3a46-267">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-268">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-268">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-269">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-269">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-270">すべての指定されたサブスクリプションの仮想マシンの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-270">Lists all of the virtual machines in the specified subscription.</span></span>
            <span data-ttu-id="c3a46-271">応答で nextLink プロパティを使用すると、仮想マシンの次のページを取得できます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-271">Use the nextLink property in the response to get the next page of virtual machines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-272">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-272">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-273">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-273">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-274">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-274">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAllWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;&gt; ListAllWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;&gt; ListAllWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.ListAllWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAllWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;&gt;" Usage="iVirtualMachinesOperations.ListAllWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-275">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-275">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-276">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-276">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-277">すべての指定されたサブスクリプションの仮想マシンの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-277">Lists all of the virtual machines in the specified subscription.</span></span>
            <span data-ttu-id="c3a46-278">応答で nextLink プロパティを使用すると、仮想マシンの次のページを取得できます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-278">Use the nextLink property in the response to get the next page of virtual machines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-279">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-279">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-280">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-280">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-281">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-281">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableSizesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;&gt;&gt; ListAvailableSizesWithHttpMessagesAsync (string resourceGroupName, string vmName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;&gt;&gt; ListAvailableSizesWithHttpMessagesAsync(string resourceGroupName, string vmName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.ListAvailableSizesWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAvailableSizesWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;&gt;&gt;" Usage="iVirtualMachinesOperations.ListAvailableSizesWithHttpMessagesAsync (resourceGroupName, vmName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-282">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-282">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="c3a46-283">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-283">The name of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-284">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-284">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-285">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-285">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-286">指定された仮想マシンのサイズ変更するすべての利用可能な仮想マシンのサイズを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-286">Lists all available virtual machine sizes to which the specified virtual machine can be resized.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-287">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-287">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-288">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-288">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-289">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-289">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;&gt;" Usage="iVirtualMachinesOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="c3a46-290">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="c3a46-290">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-291">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-291">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-292">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-292">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-293">指定されたリソース グループの仮想マシンのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-293">Lists all of the virtual machines in the specified resource group.</span></span>
            <span data-ttu-id="c3a46-294">応答で nextLink プロパティを使用すると、仮想マシンの次のページを取得できます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-294">Use the nextLink property in the response to get the next page of virtual machines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-295">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-295">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-296">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-296">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-297">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-297">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;&gt; ListWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;&gt; ListWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.ListWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;&gt;" Usage="iVirtualMachinesOperations.ListWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-298">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-298">The name of the resource group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-299">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-299">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-300">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-300">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-301">指定されたリソース グループの仮想マシンのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-301">Lists all of the virtual machines in the specified resource group.</span></span>
            <span data-ttu-id="c3a46-302">応答で nextLink プロパティを使用すると、仮想マシンの次のページを取得できます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-302">Use the nextLink property in the response to get the next page of virtual machines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-303">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-303">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-304">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-304">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-305">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-305">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PerformMaintenanceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; PerformMaintenanceWithHttpMessagesAsync (string resourceGroupName, string vmName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; PerformMaintenanceWithHttpMessagesAsync(string resourceGroupName, string vmName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.PerformMaintenanceWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PerformMaintenanceWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachinesOperations.PerformMaintenanceWithHttpMessagesAsync (resourceGroupName, vmName, customHeaders, cancellationToken)" />
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
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-306">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-306">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="c3a46-307">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-307">The name of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-308">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-308">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-309">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-309">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-310">仮想マシンでメンテナンスを実行する操作。</span><span class="sxs-lookup"><span data-stu-id="c3a46-310">The operation to perform maintenance on a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-311">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-311">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-312">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-312">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-313">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-313">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PowerOffWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; PowerOffWithHttpMessagesAsync (string resourceGroupName, string vmName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; PowerOffWithHttpMessagesAsync(string resourceGroupName, string vmName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.PowerOffWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PowerOffWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachinesOperations.PowerOffWithHttpMessagesAsync (resourceGroupName, vmName, customHeaders, cancellationToken)" />
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
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-314">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-314">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="c3a46-315">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-315">The name of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-316">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-316">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-317">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-317">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-318">仮想マシンの電源をオフ (停止) する操作です。</span><span class="sxs-lookup"><span data-stu-id="c3a46-318">The operation to power off (stop) a virtual machine.</span></span> <span data-ttu-id="c3a46-319">同じプロビジョニングされているリソースを持つ仮想マシンを再起動することができます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-319">The virtual machine can be restarted with the same provisioned resources.</span></span> <span data-ttu-id="c3a46-320">また、この仮想マシンの引き続き課金されます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-320">You are still charged for this virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-321">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-321">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-322">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-322">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-323">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-323">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RedeployWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; RedeployWithHttpMessagesAsync (string resourceGroupName, string vmName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; RedeployWithHttpMessagesAsync(string resourceGroupName, string vmName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.RedeployWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RedeployWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachinesOperations.RedeployWithHttpMessagesAsync (resourceGroupName, vmName, customHeaders, cancellationToken)" />
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
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-324">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-324">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="c3a46-325">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-325">The name of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-326">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-326">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-327">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-327">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-328">仮想マシンを再デプロイ操作です。</span><span class="sxs-lookup"><span data-stu-id="c3a46-328">The operation to redeploy a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-329">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-329">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-330">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-330">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-331">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-331">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RestartWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; RestartWithHttpMessagesAsync (string resourceGroupName, string vmName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; RestartWithHttpMessagesAsync(string resourceGroupName, string vmName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.RestartWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestartWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachinesOperations.RestartWithHttpMessagesAsync (resourceGroupName, vmName, customHeaders, cancellationToken)" />
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
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-332">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-332">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="c3a46-333">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-333">The name of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-334">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-334">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-335">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-335">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-336">仮想マシンを再起動する操作です。</span><span class="sxs-lookup"><span data-stu-id="c3a46-336">The operation to restart a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-337">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-337">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-338">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-338">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-339">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-339">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RunCommandWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.RunCommandResult&gt;&gt; RunCommandWithHttpMessagesAsync (string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.RunCommandInput parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.RunCommandResult&gt;&gt; RunCommandWithHttpMessagesAsync(string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.RunCommandInput parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.RunCommandWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Compute.Models.RunCommandInput,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RunCommandWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Compute.Models.RunCommandInput * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.RunCommandResult&gt;&gt;" Usage="iVirtualMachinesOperations.RunCommandWithHttpMessagesAsync (resourceGroupName, vmName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.RunCommandResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.RunCommandInput" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-340">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-340">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="c3a46-341">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-341">The name of the virtual machine.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c3a46-342">Run コマンドの操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="c3a46-342">Parameters supplied to the Run command operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-343">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-343">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-344">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-344">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-345">VM 上のコマンドを実行します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-345">Run command on the VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-346">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-346">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-347">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-347">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-348">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-348">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="StartWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; StartWithHttpMessagesAsync (string resourceGroupName, string vmName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; StartWithHttpMessagesAsync(string resourceGroupName, string vmName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachinesOperations.StartWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StartWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachinesOperations.StartWithHttpMessagesAsync (resourceGroupName, vmName, customHeaders, cancellationToken)" />
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
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="c3a46-349">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-349">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="c3a46-350">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="c3a46-350">The name of the virtual machine.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="c3a46-351">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="c3a46-351">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c3a46-352">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="c3a46-352">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c3a46-353">バーチャル マシンを起動する操作です。</span><span class="sxs-lookup"><span data-stu-id="c3a46-353">The operation to start a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="c3a46-354">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-354">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="c3a46-355">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-355">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3a46-356">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="c3a46-356">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>