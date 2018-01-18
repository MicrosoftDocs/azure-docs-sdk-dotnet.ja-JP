<Type Name="VirtualMachinesOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualMachinesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualMachinesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualMachinesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualMachinesOperationsExtensions = class" />
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
            <span data-ttu-id="64a70-101">VirtualMachinesOperations の拡張メソッド。</span><span class="sxs-lookup"><span data-stu-id="64a70-101">Extension methods for VirtualMachinesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCapture">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult BeginCapture (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult BeginCapture(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginCapture(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCapture (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String, parameters As VirtualMachineCaptureParameters) As VirtualMachineCaptureResult" />
      <MemberSignature Language="F#" Value="static member BeginCapture : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginCapture (operations, resourceGroupName, vmName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-102">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-103">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-103">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-104">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-104">The name of the virtual machine.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="64a70-105">パラメーターは、仮想マシンのキャプチャ操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="64a70-105">Parameters supplied to the Capture Virtual Machine operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-106">VM の仮想ハード_ディスクをコピーして、VM をキャプチャし、類似した Vm の作成に使用できるテンプレートを出力します。</span><span class="sxs-lookup"><span data-stu-id="64a70-106">Captures the VM by copying virtual hard disks of the VM and outputs a template that can be used to create similar VMs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCaptureAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult&gt; BeginCaptureAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult&gt; BeginCaptureAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginCaptureAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCaptureAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginCaptureAsync (operations, resourceGroupName, vmName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;BeginCaptureAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-107">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-108">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-108">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-109">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-109">The name of the virtual machine.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="64a70-110">パラメーターは、仮想マシンのキャプチャ操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="64a70-110">Parameters supplied to the Capture Virtual Machine operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-111">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-112">VM の仮想ハード_ディスクをコピーして、VM をキャプチャし、類似した Vm の作成に使用できるテンプレートを出力します。</span><span class="sxs-lookup"><span data-stu-id="64a70-112">Captures the VM by copying virtual hard disks of the VM and outputs a template that can be used to create similar VMs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginConvertToManagedDisks">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginConvertToManagedDisks (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginConvertToManagedDisks(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginConvertToManagedDisks(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginConvertToManagedDisks (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginConvertToManagedDisks : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginConvertToManagedDisks (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-113">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-114">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-114">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-115">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-115">The name of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-116">仮想マシンのディスクを blob に基づくから管理されるディスクに変換します。</span><span class="sxs-lookup"><span data-stu-id="64a70-116">Converts virtual machine disks from blob-based to managed disks.</span></span> <span data-ttu-id="64a70-117">仮想マシンがあります停止-割り当て解除されたこの操作を呼び出す前にします。</span><span class="sxs-lookup"><span data-stu-id="64a70-117">Virtual machine must be stop-deallocated before invoking this operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginConvertToManagedDisksAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginConvertToManagedDisksAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginConvertToManagedDisksAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginConvertToManagedDisksAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginConvertToManagedDisksAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginConvertToManagedDisksAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;BeginConvertToManagedDisksAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-118">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-118">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-119">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-119">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-120">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-120">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-122">仮想マシンのディスクを blob に基づくから管理されるディスクに変換します。</span><span class="sxs-lookup"><span data-stu-id="64a70-122">Converts virtual machine disks from blob-based to managed disks.</span></span> <span data-ttu-id="64a70-123">仮想マシンがあります停止-割り当て解除されたこの操作を呼び出す前にします。</span><span class="sxs-lookup"><span data-stu-id="64a70-123">Virtual machine must be stop-deallocated before invoking this operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachine BeginCreateOrUpdate (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.VirtualMachine parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachine BeginCreateOrUpdate(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.VirtualMachine parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachine)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String, parameters As VirtualMachine) As VirtualMachine" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachine -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachine" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, vmName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachine</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachine" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-124">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-125">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-125">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-126">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-126">The name of the virtual machine.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="64a70-127">パラメーターは、仮想マシンの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="64a70-127">Parameters supplied to the Create Virtual Machine operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-128">作成または仮想マシンを更新する操作です。</span><span class="sxs-lookup"><span data-stu-id="64a70-128">The operation to create or update a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.VirtualMachine parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.VirtualMachine parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachine,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachine * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, vmName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachine" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-129">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-129">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-130">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-130">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-131">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-131">The name of the virtual machine.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="64a70-132">パラメーターは、仮想マシンの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="64a70-132">Parameters supplied to the Create Virtual Machine operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-133">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-134">作成または仮想マシンを更新する操作です。</span><span class="sxs-lookup"><span data-stu-id="64a70-134">The operation to create or update a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeallocate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDeallocate (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDeallocate(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginDeallocate(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDeallocate (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginDeallocate : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginDeallocate (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-135">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-135">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-136">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-136">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-137">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-137">The name of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-138">仮想マシンをシャット ダウンし、コンピューティング リソースを解放します。</span><span class="sxs-lookup"><span data-stu-id="64a70-138">Shuts down the virtual machine and releases the compute resources.</span></span> <span data-ttu-id="64a70-139">このバーチャル マシンを使用するコンピューティング リソースには課金されません。</span><span class="sxs-lookup"><span data-stu-id="64a70-139">You are not billed for the compute resources that this virtual machine uses.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeallocateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeallocateAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeallocateAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginDeallocateAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeallocateAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginDeallocateAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;BeginDeallocateAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-140">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-140">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-141">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-141">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-142">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-142">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-143">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-144">仮想マシンをシャット ダウンし、コンピューティング リソースを解放します。</span><span class="sxs-lookup"><span data-stu-id="64a70-144">Shuts down the virtual machine and releases the compute resources.</span></span> <span data-ttu-id="64a70-145">このバーチャル マシンを使用するコンピューティング リソースには課金されません。</span><span class="sxs-lookup"><span data-stu-id="64a70-145">You are not billed for the compute resources that this virtual machine uses.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDelete (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDelete(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginDelete (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-146">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-147">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-147">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-148">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-148">The name of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-149">仮想マシンを削除する操作です。</span><span class="sxs-lookup"><span data-stu-id="64a70-149">The operation to delete a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-150">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-151">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-151">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-152">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-152">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-153">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-154">仮想マシンを削除する操作です。</span><span class="sxs-lookup"><span data-stu-id="64a70-154">The operation to delete a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPerformMaintenance">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginPerformMaintenance (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginPerformMaintenance(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginPerformMaintenance(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginPerformMaintenance (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginPerformMaintenance : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginPerformMaintenance (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-155">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-156">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-156">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-157">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-157">The name of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-158">仮想マシンでメンテナンスを実行する操作。</span><span class="sxs-lookup"><span data-stu-id="64a70-158">The operation to perform maintenance on a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPerformMaintenanceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginPerformMaintenanceAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginPerformMaintenanceAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginPerformMaintenanceAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginPerformMaintenanceAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginPerformMaintenanceAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;BeginPerformMaintenanceAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-159">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-159">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-160">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-160">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-161">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-161">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-163">仮想マシンでメンテナンスを実行する操作。</span><span class="sxs-lookup"><span data-stu-id="64a70-163">The operation to perform maintenance on a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPowerOff">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginPowerOff (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginPowerOff(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginPowerOff(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginPowerOff (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginPowerOff : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginPowerOff (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-164">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-165">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-165">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-166">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-166">The name of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-167">仮想マシンの電源をオフ (停止) する操作です。</span><span class="sxs-lookup"><span data-stu-id="64a70-167">The operation to power off (stop) a virtual machine.</span></span> <span data-ttu-id="64a70-168">同じプロビジョニングされているリソースを持つ仮想マシンを再起動することができます。</span><span class="sxs-lookup"><span data-stu-id="64a70-168">The virtual machine can be restarted with the same provisioned resources.</span></span> <span data-ttu-id="64a70-169">また、この仮想マシンの引き続き課金されます。</span><span class="sxs-lookup"><span data-stu-id="64a70-169">You are still charged for this virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPowerOffAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginPowerOffAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginPowerOffAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginPowerOffAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginPowerOffAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginPowerOffAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;BeginPowerOffAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-170">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-170">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-171">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-171">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-172">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-172">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-173">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-173">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-174">仮想マシンの電源をオフ (停止) する操作です。</span><span class="sxs-lookup"><span data-stu-id="64a70-174">The operation to power off (stop) a virtual machine.</span></span> <span data-ttu-id="64a70-175">同じプロビジョニングされているリソースを持つ仮想マシンを再起動することができます。</span><span class="sxs-lookup"><span data-stu-id="64a70-175">The virtual machine can be restarted with the same provisioned resources.</span></span> <span data-ttu-id="64a70-176">また、この仮想マシンの引き続き課金されます。</span><span class="sxs-lookup"><span data-stu-id="64a70-176">You are still charged for this virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRedeploy">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginRedeploy (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginRedeploy(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginRedeploy(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginRedeploy (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginRedeploy : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginRedeploy (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-177">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-177">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-178">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-178">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-179">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-179">The name of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-180">仮想マシンを再デプロイ操作です。</span><span class="sxs-lookup"><span data-stu-id="64a70-180">The operation to redeploy a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRedeployAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginRedeployAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginRedeployAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginRedeployAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRedeployAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginRedeployAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;BeginRedeployAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-181">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-181">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-182">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-182">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-183">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-183">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-184">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-184">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-185">仮想マシンを再デプロイ操作です。</span><span class="sxs-lookup"><span data-stu-id="64a70-185">The operation to redeploy a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRestart">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginRestart (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginRestart(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginRestart(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginRestart (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginRestart : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginRestart (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-186">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-186">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-187">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-187">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-188">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-188">The name of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-189">仮想マシンを再起動する操作です。</span><span class="sxs-lookup"><span data-stu-id="64a70-189">The operation to restart a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRestartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginRestartAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginRestartAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginRestartAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRestartAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginRestartAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;BeginRestartAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-190">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-191">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-191">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-192">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-192">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-193">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-193">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-194">仮想マシンを再起動する操作です。</span><span class="sxs-lookup"><span data-stu-id="64a70-194">The operation to restart a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRunCommand">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.RunCommandResult BeginRunCommand (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.RunCommandInput parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.RunCommandResult BeginRunCommand(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.RunCommandInput parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginRunCommand(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.RunCommandInput)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginRunCommand (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String, parameters As RunCommandInput) As RunCommandResult" />
      <MemberSignature Language="F#" Value="static member BeginRunCommand : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Models.RunCommandInput -&gt; Microsoft.Azure.Management.Compute.Models.RunCommandResult" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginRunCommand (operations, resourceGroupName, vmName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.RunCommandResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.RunCommandInput" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-195">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-195">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-196">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-196">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-197">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-197">The name of the virtual machine.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="64a70-198">Run コマンドの操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="64a70-198">Parameters supplied to the Run command operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-199">VM 上のコマンドを実行します。</span><span class="sxs-lookup"><span data-stu-id="64a70-199">Run command on the VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRunCommandAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.RunCommandResult&gt; BeginRunCommandAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.RunCommandInput parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.RunCommandResult&gt; BeginRunCommandAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.RunCommandInput parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginRunCommandAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.RunCommandInput,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRunCommandAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Models.RunCommandInput * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.RunCommandResult&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginRunCommandAsync (operations, resourceGroupName, vmName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;BeginRunCommandAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.RunCommandResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.RunCommandInput" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-200">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-200">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-201">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-201">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-202">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-202">The name of the virtual machine.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="64a70-203">Run コマンドの操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="64a70-203">Parameters supplied to the Run command operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-204">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-204">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-205">VM 上のコマンドを実行します。</span><span class="sxs-lookup"><span data-stu-id="64a70-205">Run command on the VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStart">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginStart (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginStart(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginStart(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginStart (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginStart : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginStart (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-206">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-206">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-207">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-207">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-208">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-208">The name of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-209">バーチャル マシンを起動する操作です。</span><span class="sxs-lookup"><span data-stu-id="64a70-209">The operation to start a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginStartAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginStartAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginStartAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStartAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginStartAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;BeginStartAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-210">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-210">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-211">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-211">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-212">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-212">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-213">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-213">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-214">バーチャル マシンを起動する操作です。</span><span class="sxs-lookup"><span data-stu-id="64a70-214">The operation to start a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capture">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult Capture (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult Capture(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Capture(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Capture (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String, parameters As VirtualMachineCaptureParameters) As VirtualMachineCaptureResult" />
      <MemberSignature Language="F#" Value="static member Capture : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Capture (operations, resourceGroupName, vmName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-215">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-215">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-216">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-216">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-217">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-217">The name of the virtual machine.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="64a70-218">パラメーターは、仮想マシンのキャプチャ操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="64a70-218">Parameters supplied to the Capture Virtual Machine operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-219">VM の仮想ハード_ディスクをコピーして、VM をキャプチャし、類似した Vm の作成に使用できるテンプレートを出力します。</span><span class="sxs-lookup"><span data-stu-id="64a70-219">Captures the VM by copying virtual hard disks of the VM and outputs a template that can be used to create similar VMs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CaptureAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult&gt; CaptureAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult&gt; CaptureAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.CaptureAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CaptureAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.CaptureAsync (operations, resourceGroupName, vmName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;CaptureAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-220">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-220">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-221">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-221">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-222">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-222">The name of the virtual machine.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="64a70-223">パラメーターは、仮想マシンのキャプチャ操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="64a70-223">Parameters supplied to the Capture Virtual Machine operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-224">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-224">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-225">VM の仮想ハード_ディスクをコピーして、VM をキャプチャし、類似した Vm の作成に使用できるテンプレートを出力します。</span><span class="sxs-lookup"><span data-stu-id="64a70-225">Captures the VM by copying virtual hard disks of the VM and outputs a template that can be used to create similar VMs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConvertToManagedDisks">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse ConvertToManagedDisks (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse ConvertToManagedDisks(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ConvertToManagedDisks(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ConvertToManagedDisks (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member ConvertToManagedDisks : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ConvertToManagedDisks (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-226">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-226">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-227">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-227">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-228">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-228">The name of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-229">仮想マシンのディスクを blob に基づくから管理されるディスクに変換します。</span><span class="sxs-lookup"><span data-stu-id="64a70-229">Converts virtual machine disks from blob-based to managed disks.</span></span> <span data-ttu-id="64a70-230">仮想マシンがあります停止-割り当て解除されたこの操作を呼び出す前にします。</span><span class="sxs-lookup"><span data-stu-id="64a70-230">Virtual machine must be stop-deallocated before invoking this operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConvertToManagedDisksAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; ConvertToManagedDisksAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; ConvertToManagedDisksAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ConvertToManagedDisksAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ConvertToManagedDisksAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ConvertToManagedDisksAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;ConvertToManagedDisksAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-231">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-231">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-232">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-232">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-233">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-233">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-234">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-234">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-235">仮想マシンのディスクを blob に基づくから管理されるディスクに変換します。</span><span class="sxs-lookup"><span data-stu-id="64a70-235">Converts virtual machine disks from blob-based to managed disks.</span></span> <span data-ttu-id="64a70-236">仮想マシンがあります停止-割り当て解除されたこの操作を呼び出す前にします。</span><span class="sxs-lookup"><span data-stu-id="64a70-236">Virtual machine must be stop-deallocated before invoking this operation.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachine CreateOrUpdate (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.VirtualMachine parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachine CreateOrUpdate(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.VirtualMachine parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachine)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String, parameters As VirtualMachine) As VirtualMachine" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachine -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachine" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, vmName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachine</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachine" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-237">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-237">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-238">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-238">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-239">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-239">The name of the virtual machine.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="64a70-240">パラメーターは、仮想マシンの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="64a70-240">Parameters supplied to the Create Virtual Machine operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-241">作成または仮想マシンを更新する操作です。</span><span class="sxs-lookup"><span data-stu-id="64a70-241">The operation to create or update a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.VirtualMachine parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.VirtualMachine parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachine,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachine * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, vmName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachine" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-242">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-242">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-243">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-243">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-244">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-244">The name of the virtual machine.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="64a70-245">パラメーターは、仮想マシンの作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="64a70-245">Parameters supplied to the Create Virtual Machine operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-246">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-246">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-247">作成または仮想マシンを更新する操作です。</span><span class="sxs-lookup"><span data-stu-id="64a70-247">The operation to create or update a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Deallocate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Deallocate (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Deallocate(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Deallocate(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Deallocate (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Deallocate : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Deallocate (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-248">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-248">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-249">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-249">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-250">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-250">The name of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-251">仮想マシンをシャット ダウンし、コンピューティング リソースを解放します。</span><span class="sxs-lookup"><span data-stu-id="64a70-251">Shuts down the virtual machine and releases the compute resources.</span></span> <span data-ttu-id="64a70-252">このバーチャル マシンを使用するコンピューティング リソースには課金されません。</span><span class="sxs-lookup"><span data-stu-id="64a70-252">You are not billed for the compute resources that this virtual machine uses.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeallocateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeallocateAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeallocateAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.DeallocateAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeallocateAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.DeallocateAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;DeallocateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-253">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-253">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-254">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-254">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-255">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-255">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-256">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-256">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-257">仮想マシンをシャット ダウンし、コンピューティング リソースを解放します。</span><span class="sxs-lookup"><span data-stu-id="64a70-257">Shuts down the virtual machine and releases the compute resources.</span></span> <span data-ttu-id="64a70-258">このバーチャル マシンを使用するコンピューティング リソースには課金されません。</span><span class="sxs-lookup"><span data-stu-id="64a70-258">You are not billed for the compute resources that this virtual machine uses.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Delete (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Delete(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Delete(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Delete (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-259">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-259">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-260">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-260">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-261">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-261">The name of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-262">仮想マシンを削除する操作です。</span><span class="sxs-lookup"><span data-stu-id="64a70-262">The operation to delete a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.DeleteAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-263">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-263">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-264">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-264">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-265">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-265">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-266">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-266">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-267">仮想マシンを削除する操作です。</span><span class="sxs-lookup"><span data-stu-id="64a70-267">The operation to delete a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Generalize">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Generalize (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Generalize(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Generalize(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Generalize (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Generalize : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Generalize (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-268">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-268">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-269">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-269">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-270">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-270">The name of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-271">一般化された仮想マシンの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="64a70-271">Sets the state of the virtual machine to generalized.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeneralizeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; GeneralizeAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; GeneralizeAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.GeneralizeAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GeneralizeAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.GeneralizeAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;GeneralizeAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-272">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-272">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-273">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-273">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-274">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-274">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-275">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-275">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-276">一般化された仮想マシンの状態を設定します。</span><span class="sxs-lookup"><span data-stu-id="64a70-276">Sets the state of the virtual machine to generalized.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachine Get (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Nullable&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewTypes&gt; expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachine Get(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.InstanceViewTypes&gt; expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Get(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Nullable{Microsoft.Azure.Management.Compute.Models.InstanceViewTypes})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String, Optional expand As Nullable(Of InstanceViewTypes) = null) As VirtualMachine" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Nullable&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewTypes&gt; -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachine" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Get (operations, resourceGroupName, vmName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachine</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="expand" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewTypes&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-277">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-277">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-278">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-278">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-279">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-279">The name of the virtual machine.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="64a70-280">操作に適用する展開式です。</span><span class="sxs-lookup"><span data-stu-id="64a70-280">The expand expression to apply on the operation.</span></span> <span data-ttu-id="64a70-281">使用可能な値が含まれます: 'instanceView'</span><span class="sxs-lookup"><span data-stu-id="64a70-281">Possible values include: 'instanceView'</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-282">モデル ビューまたはバーチャル マシンのインスタンス ビューに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="64a70-282">Retrieves information about the model view or the instance view of a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; GetAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Nullable&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewTypes&gt; expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; GetAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.InstanceViewTypes&gt; expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Nullable{Microsoft.Azure.Management.Compute.Models.InstanceViewTypes},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Nullable&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewTypes&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.GetAsync (operations, resourceGroupName, vmName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="expand" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewTypes&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-283">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-283">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-284">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-284">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-285">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-285">The name of the virtual machine.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="64a70-286">操作に適用する展開式です。</span><span class="sxs-lookup"><span data-stu-id="64a70-286">The expand expression to apply on the operation.</span></span> <span data-ttu-id="64a70-287">使用可能な値が含まれます: 'instanceView'</span><span class="sxs-lookup"><span data-stu-id="64a70-287">Possible values include: 'instanceView'</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-288">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-288">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-289">モデル ビューまたはバーチャル マシンのインスタンス ビューに関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="64a70-289">Retrieves information about the model view or the instance view of a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceView">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView InstanceView (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView InstanceView(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.InstanceView(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function InstanceView (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As VirtualMachineInstanceView" />
      <MemberSignature Language="F#" Value="static member InstanceView : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.InstanceView (operations, resourceGroupName, vmName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-290">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-290">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-291">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-291">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-292">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-292">The name of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-293">仮想マシンの実行時の状態に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="64a70-293">Retrieves information about the run-time state of a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceViewAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView&gt; InstanceViewAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView&gt; InstanceViewAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.InstanceViewAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member InstanceViewAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.InstanceViewAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;InstanceViewAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-294">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-294">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-295">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-295">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-296">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-296">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-297">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-297">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-298">仮想マシンの実行時の状態に関する情報を取得します。</span><span class="sxs-lookup"><span data-stu-id="64a70-298">Retrieves information about the run-time state of a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; List (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; List(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.List(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IVirtualMachinesOperations, resourceGroupName As String) As IPage(Of VirtualMachine)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-299">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-299">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-300">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-300">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-301">指定されたリソース グループの仮想マシンのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="64a70-301">Lists all of the virtual machines in the specified resource group.</span></span> <span data-ttu-id="64a70-302">応答で nextLink プロパティを使用すると、仮想マシンの次のページを取得できます。</span><span class="sxs-lookup"><span data-stu-id="64a70-302">Use the nextLink property in the response to get the next page of virtual machines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAll">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; ListAll (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; ListAll(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAll(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAll (operations As IVirtualMachinesOperations) As IPage(Of VirtualMachine)" />
      <MemberSignature Language="F#" Value="static member ListAll : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAll operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-303">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-303">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-304">すべての指定されたサブスクリプションの仮想マシンの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="64a70-304">Lists all of the virtual machines in the specified subscription.</span></span> <span data-ttu-id="64a70-305">応答で nextLink プロパティを使用すると、仮想マシンの次のページを取得できます。</span><span class="sxs-lookup"><span data-stu-id="64a70-305">Use the nextLink property in the response to get the next page of virtual machines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;ListAllAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-306">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-306">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-307">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-307">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-308">すべての指定されたサブスクリプションの仮想マシンの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="64a70-308">Lists all of the virtual machines in the specified subscription.</span></span> <span data-ttu-id="64a70-309">応答で nextLink プロパティを使用すると、仮想マシンの次のページを取得できます。</span><span class="sxs-lookup"><span data-stu-id="64a70-309">Use the nextLink property in the response to get the next page of virtual machines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; ListAllNext (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; ListAllNext(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAllNext(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAllNext (operations As IVirtualMachinesOperations, nextPageLink As String) As IPage(Of VirtualMachine)" />
      <MemberSignature Language="F#" Value="static member ListAllNext : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAllNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-310">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-310">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="64a70-311">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="64a70-311">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-312">すべての指定されたサブスクリプションの仮想マシンの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="64a70-312">Lists all of the virtual machines in the specified subscription.</span></span> <span data-ttu-id="64a70-313">応答で nextLink プロパティを使用すると、仮想マシンの次のページを取得できます。</span><span class="sxs-lookup"><span data-stu-id="64a70-313">Use the nextLink property in the response to get the next page of virtual machines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;ListAllNextAsync&gt;d__59))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-314">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-314">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="64a70-315">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="64a70-315">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-316">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-316">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-317">すべての指定されたサブスクリプションの仮想マシンの一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="64a70-317">Lists all of the virtual machines in the specified subscription.</span></span> <span data-ttu-id="64a70-318">応答で nextLink プロパティを使用すると、仮想マシンの次のページを取得できます。</span><span class="sxs-lookup"><span data-stu-id="64a70-318">Use the nextLink property in the response to get the next page of virtual machines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;ListAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-319">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-319">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-320">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-320">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-321">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-321">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-322">指定されたリソース グループの仮想マシンのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="64a70-322">Lists all of the virtual machines in the specified resource group.</span></span> <span data-ttu-id="64a70-323">応答で nextLink プロパティを使用すると、仮想マシンの次のページを取得できます。</span><span class="sxs-lookup"><span data-stu-id="64a70-323">Use the nextLink property in the response to get the next page of virtual machines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableSizes">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt; ListAvailableSizes (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt; ListAvailableSizes(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAvailableSizes(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAvailableSizes (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As IEnumerable(Of VirtualMachineSize)" />
      <MemberSignature Language="F#" Value="static member ListAvailableSizes : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAvailableSizes (operations, resourceGroupName, vmName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-324">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-324">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-325">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-325">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-326">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-326">The name of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-327">指定された仮想マシンのサイズ変更するすべての利用可能な仮想マシンのサイズを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="64a70-327">Lists all available virtual machine sizes to which the specified virtual machine can be resized.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableSizesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;&gt; ListAvailableSizesAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;&gt; ListAvailableSizesAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAvailableSizesAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAvailableSizesAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAvailableSizesAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;ListAvailableSizesAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-328">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-328">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-329">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-329">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-330">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-330">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-331">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-331">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-332">指定された仮想マシンのサイズ変更するすべての利用可能な仮想マシンのサイズを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="64a70-332">Lists all available virtual machine sizes to which the specified virtual machine can be resized.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; ListNext (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; ListNext(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListNext(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IVirtualMachinesOperations, nextPageLink As String) As IPage(Of VirtualMachine)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-333">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-333">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="64a70-334">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="64a70-334">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-335">指定されたリソース グループの仮想マシンのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="64a70-335">Lists all of the virtual machines in the specified resource group.</span></span> <span data-ttu-id="64a70-336">応答で nextLink プロパティを使用すると、仮想マシンの次のページを取得できます。</span><span class="sxs-lookup"><span data-stu-id="64a70-336">Use the nextLink property in the response to get the next page of virtual machines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;ListNextAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-337">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-337">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="64a70-338">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="64a70-338">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-339">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-339">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-340">指定されたリソース グループの仮想マシンのすべての一覧を表示します。</span><span class="sxs-lookup"><span data-stu-id="64a70-340">Lists all of the virtual machines in the specified resource group.</span></span> <span data-ttu-id="64a70-341">応答で nextLink プロパティを使用すると、仮想マシンの次のページを取得できます。</span><span class="sxs-lookup"><span data-stu-id="64a70-341">Use the nextLink property in the response to get the next page of virtual machines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PerformMaintenance">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse PerformMaintenance (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse PerformMaintenance(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.PerformMaintenance(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PerformMaintenance (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member PerformMaintenance : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.PerformMaintenance (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-342">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-342">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-343">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-343">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-344">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-344">The name of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-345">仮想マシンでメンテナンスを実行する操作。</span><span class="sxs-lookup"><span data-stu-id="64a70-345">The operation to perform maintenance on a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PerformMaintenanceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; PerformMaintenanceAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; PerformMaintenanceAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.PerformMaintenanceAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PerformMaintenanceAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.PerformMaintenanceAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;PerformMaintenanceAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-346">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-346">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-347">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-347">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-348">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-348">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-349">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-349">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-350">仮想マシンでメンテナンスを実行する操作。</span><span class="sxs-lookup"><span data-stu-id="64a70-350">The operation to perform maintenance on a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PowerOff">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse PowerOff (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse PowerOff(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.PowerOff(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PowerOff (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member PowerOff : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.PowerOff (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-351">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-351">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-352">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-352">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-353">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-353">The name of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-354">仮想マシンの電源をオフ (停止) する操作です。</span><span class="sxs-lookup"><span data-stu-id="64a70-354">The operation to power off (stop) a virtual machine.</span></span> <span data-ttu-id="64a70-355">同じプロビジョニングされているリソースを持つ仮想マシンを再起動することができます。</span><span class="sxs-lookup"><span data-stu-id="64a70-355">The virtual machine can be restarted with the same provisioned resources.</span></span> <span data-ttu-id="64a70-356">また、この仮想マシンの引き続き課金されます。</span><span class="sxs-lookup"><span data-stu-id="64a70-356">You are still charged for this virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PowerOffAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; PowerOffAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; PowerOffAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.PowerOffAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PowerOffAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.PowerOffAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;PowerOffAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-357">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-357">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-358">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-358">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-359">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-359">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-360">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-360">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-361">仮想マシンの電源をオフ (停止) する操作です。</span><span class="sxs-lookup"><span data-stu-id="64a70-361">The operation to power off (stop) a virtual machine.</span></span> <span data-ttu-id="64a70-362">同じプロビジョニングされているリソースを持つ仮想マシンを再起動することができます。</span><span class="sxs-lookup"><span data-stu-id="64a70-362">The virtual machine can be restarted with the same provisioned resources.</span></span> <span data-ttu-id="64a70-363">また、この仮想マシンの引き続き課金されます。</span><span class="sxs-lookup"><span data-stu-id="64a70-363">You are still charged for this virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Redeploy">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Redeploy (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Redeploy(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Redeploy(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Redeploy (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Redeploy : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Redeploy (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-364">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-364">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-365">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-365">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-366">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-366">The name of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-367">仮想マシンを再デプロイ操作です。</span><span class="sxs-lookup"><span data-stu-id="64a70-367">The operation to redeploy a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedeployAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; RedeployAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; RedeployAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.RedeployAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RedeployAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.RedeployAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;RedeployAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-368">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-368">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-369">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-369">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-370">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-370">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-371">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-371">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-372">仮想マシンを再デプロイ操作です。</span><span class="sxs-lookup"><span data-stu-id="64a70-372">The operation to redeploy a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Restart">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Restart (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Restart(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Restart(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Restart (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Restart : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Restart (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-373">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-373">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-374">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-374">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-375">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-375">The name of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-376">仮想マシンを再起動する操作です。</span><span class="sxs-lookup"><span data-stu-id="64a70-376">The operation to restart a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; RestartAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; RestartAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.RestartAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RestartAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.RestartAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;RestartAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-377">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-377">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-378">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-378">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-379">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-379">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-380">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-380">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-381">仮想マシンを再起動する操作です。</span><span class="sxs-lookup"><span data-stu-id="64a70-381">The operation to restart a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunCommand">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.RunCommandResult RunCommand (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.RunCommandInput parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.RunCommandResult RunCommand(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.RunCommandInput parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.RunCommand(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.RunCommandInput)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RunCommand (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String, parameters As RunCommandInput) As RunCommandResult" />
      <MemberSignature Language="F#" Value="static member RunCommand : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Models.RunCommandInput -&gt; Microsoft.Azure.Management.Compute.Models.RunCommandResult" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.RunCommand (operations, resourceGroupName, vmName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.RunCommandResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.RunCommandInput" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-382">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-382">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-383">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-383">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-384">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-384">The name of the virtual machine.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="64a70-385">Run コマンドの操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="64a70-385">Parameters supplied to the Run command operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-386">VM 上のコマンドを実行します。</span><span class="sxs-lookup"><span data-stu-id="64a70-386">Run command on the VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunCommandAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.RunCommandResult&gt; RunCommandAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.RunCommandInput parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.RunCommandResult&gt; RunCommandAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.RunCommandInput parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.RunCommandAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.RunCommandInput,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RunCommandAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Models.RunCommandInput * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.RunCommandResult&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.RunCommandAsync (operations, resourceGroupName, vmName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;RunCommandAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.RunCommandResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.RunCommandInput" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-387">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-387">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-388">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-388">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-389">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-389">The name of the virtual machine.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="64a70-390">Run コマンドの操作に渡されるパラメーター。</span><span class="sxs-lookup"><span data-stu-id="64a70-390">Parameters supplied to the Run command operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-391">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-391">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-392">VM 上のコマンドを実行します。</span><span class="sxs-lookup"><span data-stu-id="64a70-392">Run command on the VM.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Start (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Start(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Start(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Start (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Start : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Start (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-393">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-393">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-394">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-394">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-395">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-395">The name of the virtual machine.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-396">バーチャル マシンを起動する操作です。</span><span class="sxs-lookup"><span data-stu-id="64a70-396">The operation to start a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; StartAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; StartAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.StartAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StartAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.StartAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;StartAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="64a70-397">この拡張メソッドの操作のグループです。</span><span class="sxs-lookup"><span data-stu-id="64a70-397">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="64a70-398">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-398">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="64a70-399">仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="64a70-399">The name of the virtual machine.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="64a70-400">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="64a70-400">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="64a70-401">バーチャル マシンを起動する操作です。</span><span class="sxs-lookup"><span data-stu-id="64a70-401">The operation to start a virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>