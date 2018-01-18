<Type Name="IVirtualMachineScaleSetExtensionsOperations" FullName="Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineScaleSetExtensionsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineScaleSetExtensionsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineScaleSetExtensionsOperations" />
  <TypeSignature Language="F#" Value="type IVirtualMachineScaleSetExtensionsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b9783-101">VirtualMachineScaleSetExtensionsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="b9783-101">VirtualMachineScaleSetExtensionsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, string vmssExtensionName, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension extensionParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, string vmssExtensionName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension extensionParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt;" Usage="iVirtualMachineScaleSetExtensionsOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, vmssExtensionName, extensionParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="vmssExtensionName" Type="System.String" />
        <Parameter Name="extensionParameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b9783-102">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b9783-102">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="b9783-103">設定の拡張機能が表示される必要のある VM スケールの名前は、作成または更新します。</span><span class="sxs-lookup"><span data-stu-id="b9783-103">The name of the VM scale set where the extension should be create or updated.</span></span>
            </param>
        <param name="vmssExtensionName">
            <span data-ttu-id="b9783-104">VM スケールの名前は、拡張機能を設定します。</span><span class="sxs-lookup"><span data-stu-id="b9783-104">The name of the VM scale set extension.</span></span>
            </param>
        <param name="extensionParameters">
            <span data-ttu-id="b9783-105">VM の作成のスケールを指定するパラメーターは、拡張機能の操作を設定します。</span><span class="sxs-lookup"><span data-stu-id="b9783-105">Parameters supplied to the Create VM scale set Extension operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b9783-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b9783-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b9783-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b9783-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b9783-108">作成または拡張機能を更新する操作です。</span><span class="sxs-lookup"><span data-stu-id="b9783-108">The operation to create or update an extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b9783-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b9783-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b9783-110">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b9783-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b9783-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b9783-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, string vmssExtensionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, string vmssExtensionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachineScaleSetExtensionsOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, vmssExtensionName, customHeaders, cancellationToken)" />
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
        <Parameter Name="vmssExtensionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b9783-112">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b9783-112">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="b9783-113">拡張機能を削除するか、VM スケール セットの名前です。</span><span class="sxs-lookup"><span data-stu-id="b9783-113">The name of the VM scale set where the extension should be deleted.</span></span>
            </param>
        <param name="vmssExtensionName">
            <span data-ttu-id="b9783-114">VM スケールの名前は、拡張機能を設定します。</span><span class="sxs-lookup"><span data-stu-id="b9783-114">The name of the VM scale set extension.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b9783-115">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b9783-115">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b9783-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b9783-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b9783-117">拡張機能を削除する操作です。</span><span class="sxs-lookup"><span data-stu-id="b9783-117">The operation to delete the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b9783-118">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b9783-118">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b9783-119">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b9783-119">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b9783-120">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b9783-120">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, string vmssExtensionName, Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension extensionParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, string vmssExtensionName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension extensionParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt;" Usage="iVirtualMachineScaleSetExtensionsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, vmssExtensionName, extensionParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="vmssExtensionName" Type="System.String" />
        <Parameter Name="extensionParameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b9783-121">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b9783-121">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="b9783-122">設定の拡張機能が表示される必要のある VM スケールの名前は、作成または更新します。</span><span class="sxs-lookup"><span data-stu-id="b9783-122">The name of the VM scale set where the extension should be create or updated.</span></span>
            </param>
        <param name="vmssExtensionName">
            <span data-ttu-id="b9783-123">VM スケールの名前は、拡張機能を設定します。</span><span class="sxs-lookup"><span data-stu-id="b9783-123">The name of the VM scale set extension.</span></span>
            </param>
        <param name="extensionParameters">
            <span data-ttu-id="b9783-124">VM の作成のスケールを指定するパラメーターは、拡張機能の操作を設定します。</span><span class="sxs-lookup"><span data-stu-id="b9783-124">Parameters supplied to the Create VM scale set Extension operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b9783-125">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b9783-125">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b9783-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b9783-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b9783-127">作成または拡張機能を更新する操作です。</span><span class="sxs-lookup"><span data-stu-id="b9783-127">The operation to create or update an extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b9783-128">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b9783-128">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b9783-129">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b9783-129">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b9783-130">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b9783-130">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, string vmssExtensionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, string vmssExtensionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;&gt;" Usage="iVirtualMachineScaleSetExtensionsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, vmssExtensionName, customHeaders, cancellationToken)" />
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
        <Parameter Name="vmssExtensionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b9783-131">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b9783-131">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="b9783-132">拡張機能を削除するか、VM スケール セットの名前です。</span><span class="sxs-lookup"><span data-stu-id="b9783-132">The name of the VM scale set where the extension should be deleted.</span></span>
            </param>
        <param name="vmssExtensionName">
            <span data-ttu-id="b9783-133">VM スケールの名前は、拡張機能を設定します。</span><span class="sxs-lookup"><span data-stu-id="b9783-133">The name of the VM scale set extension.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b9783-134">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b9783-134">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b9783-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b9783-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b9783-136">拡張機能を削除する操作です。</span><span class="sxs-lookup"><span data-stu-id="b9783-136">The operation to delete the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b9783-137">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b9783-137">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b9783-138">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b9783-138">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b9783-139">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b9783-139">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, string vmssExtensionName, string expand = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, string vmssExtensionName, string expand, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt;" Usage="iVirtualMachineScaleSetExtensionsOperations.GetWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, vmssExtensionName, expand, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="vmssExtensionName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b9783-140">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b9783-140">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="b9783-141">VM スケールの名前は、拡張を含むを設定します。</span><span class="sxs-lookup"><span data-stu-id="b9783-141">The name of the VM scale set containing the extension.</span></span>
            </param>
        <param name="vmssExtensionName">
            <span data-ttu-id="b9783-142">VM スケールの名前は、拡張機能を設定します。</span><span class="sxs-lookup"><span data-stu-id="b9783-142">The name of the VM scale set extension.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="b9783-143">操作に適用する展開式です。</span><span class="sxs-lookup"><span data-stu-id="b9783-143">The expand expression to apply on the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b9783-144">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b9783-144">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b9783-145">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b9783-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b9783-146">拡張機能を取得する操作です。</span><span class="sxs-lookup"><span data-stu-id="b9783-146">The operation to get the extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b9783-147">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b9783-147">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b9783-148">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b9783-148">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b9783-149">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b9783-149">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt;&gt;" Usage="iVirtualMachineScaleSetExtensionsOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="b9783-150">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="b9783-150">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b9783-151">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b9783-151">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b9783-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b9783-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b9783-153">VM スケール セット内のすべての拡張機能の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="b9783-153">Gets a list of all extensions in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b9783-154">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b9783-154">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b9783-155">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b9783-155">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b9783-156">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b9783-156">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt;&gt; ListWithHttpMessagesAsync (string resourceGroupName, string vmScaleSetName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt;&gt; ListWithHttpMessagesAsync(string resourceGroupName, string vmScaleSetName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.IVirtualMachineScaleSetExtensionsOperations.ListWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt;&gt;" Usage="iVirtualMachineScaleSetExtensionsOperations.ListWithHttpMessagesAsync (resourceGroupName, vmScaleSetName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineScaleSetExtension&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmScaleSetName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b9783-157">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b9783-157">The name of the resource group.</span></span>
            </param>
        <param name="vmScaleSetName">
            <span data-ttu-id="b9783-158">VM スケールの名前は、拡張を含むを設定します。</span><span class="sxs-lookup"><span data-stu-id="b9783-158">The name of the VM scale set containing the extension.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b9783-159">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b9783-159">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b9783-160">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b9783-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b9783-161">VM スケール セット内のすべての拡張機能の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="b9783-161">Gets a list of all extensions in a VM scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b9783-162">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b9783-162">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b9783-163">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b9783-163">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b9783-164">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b9783-164">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>