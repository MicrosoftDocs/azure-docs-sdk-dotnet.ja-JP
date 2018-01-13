<Type Name="IVirtualMachineExtensionsOperations" FullName="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineExtensionsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineExtensionsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineExtensionsOperations" />
  <TypeSignature Language="F#" Value="type IVirtualMachineExtensionsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cf7dd-101">VirtualMachineExtensionsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-101">VirtualMachineExtensionsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string vmName, string vmExtensionName, Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension extensionParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string vmName, string vmExtensionName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension extensionParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;&gt;" Usage="iVirtualMachineExtensionsOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, vmName, vmExtensionName, extensionParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
        <Parameter Name="extensionParameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="cf7dd-102">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-102">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="cf7dd-103">拡張機能が表示される必要のある仮想マシンの名前は、作成または更新します。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-103">The name of the virtual machine where the extension should be create or updated.</span></span>
            </param>
        <param name="vmExtensionName">
            <span data-ttu-id="cf7dd-104">仮想マシンの拡張機能の名前。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-104">The name of the virtual machine extension.</span></span>
            </param>
        <param name="extensionParameters">
            <span data-ttu-id="cf7dd-105">パラメーターは、仮想マシン拡張機能の作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-105">Parameters supplied to the Create Virtual Machine Extension operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cf7dd-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cf7dd-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf7dd-108">作成または拡張機能を更新する操作です。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-108">The operation to create or update the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cf7dd-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="cf7dd-110">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cf7dd-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string vmName, string vmExtensionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string vmName, string vmExtensionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachineExtensionsOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, vmName, vmExtensionName, customHeaders, cancellationToken)" />
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
        <Parameter Name="vmExtensionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="cf7dd-112">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-112">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="cf7dd-113">拡張機能を削除するか、バーチャル マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-113">The name of the virtual machine where the extension should be deleted.</span></span>
            </param>
        <param name="vmExtensionName">
            <span data-ttu-id="cf7dd-114">仮想マシンの拡張機能の名前。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-114">The name of the virtual machine extension.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cf7dd-115">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-115">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cf7dd-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf7dd-117">拡張機能を削除する操作です。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-117">The operation to delete the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cf7dd-118">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-118">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="cf7dd-119">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-119">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cf7dd-120">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-120">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string vmName, string vmExtensionName, Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension extensionParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string vmName, string vmExtensionName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension extensionParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;&gt;" Usage="iVirtualMachineExtensionsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, vmName, vmExtensionName, extensionParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
        <Parameter Name="extensionParameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="cf7dd-121">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-121">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="cf7dd-122">拡張機能が表示される必要のある仮想マシンの名前は、作成または更新します。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-122">The name of the virtual machine where the extension should be create or updated.</span></span>
            </param>
        <param name="vmExtensionName">
            <span data-ttu-id="cf7dd-123">仮想マシンの拡張機能の名前。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-123">The name of the virtual machine extension.</span></span>
            </param>
        <param name="extensionParameters">
            <span data-ttu-id="cf7dd-124">パラメーターは、仮想マシン拡張機能の作成操作に指定します。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-124">Parameters supplied to the Create Virtual Machine Extension operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cf7dd-125">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-125">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cf7dd-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf7dd-127">作成または拡張機能を更新する操作です。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-127">The operation to create or update the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cf7dd-128">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-128">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="cf7dd-129">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-129">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cf7dd-130">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-130">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string vmName, string vmExtensionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string vmName, string vmExtensionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachineExtensionsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, vmName, vmExtensionName, customHeaders, cancellationToken)" />
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
        <Parameter Name="vmExtensionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="cf7dd-131">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-131">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="cf7dd-132">拡張機能を削除するか、バーチャル マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-132">The name of the virtual machine where the extension should be deleted.</span></span>
            </param>
        <param name="vmExtensionName">
            <span data-ttu-id="cf7dd-133">仮想マシンの拡張機能の名前。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-133">The name of the virtual machine extension.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cf7dd-134">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-134">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cf7dd-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf7dd-136">拡張機能を削除する操作です。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-136">The operation to delete the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cf7dd-137">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-137">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="cf7dd-138">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-138">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cf7dd-139">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-139">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string vmName, string vmExtensionName, string expand = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string vmName, string vmExtensionName, string expand, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;&gt;" Usage="iVirtualMachineExtensionsOperations.GetWithHttpMessagesAsync (resourceGroupName, vmName, vmExtensionName, expand, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="cf7dd-140">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-140">The name of the resource group.</span></span>
            </param>
        <param name="vmName">
            <span data-ttu-id="cf7dd-141">拡張子を含む仮想マシンの名前。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-141">The name of the virtual machine containing the extension.</span></span>
            </param>
        <param name="vmExtensionName">
            <span data-ttu-id="cf7dd-142">仮想マシンの拡張機能の名前。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-142">The name of the virtual machine extension.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="cf7dd-143">操作に適用する展開式です。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-143">The expand expression to apply on the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="cf7dd-144">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-144">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cf7dd-145">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf7dd-146">拡張機能を取得する操作です。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-146">The operation to get the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="cf7dd-147">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-147">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="cf7dd-148">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-148">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cf7dd-149">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="cf7dd-149">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>