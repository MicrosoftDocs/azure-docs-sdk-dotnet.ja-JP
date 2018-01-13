<Type Name="IVolumeContainersOperations" FullName="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations">
  <TypeSignature Language="C#" Value="public interface IVolumeContainersOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVolumeContainersOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVolumeContainersOperations" />
  <TypeSignature Language="F#" Value="type IVolumeContainersOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="99b91-101">VolumeContainersOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="99b91-101">VolumeContainersOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string deviceName, string volumeContainerName, Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string deviceName, string volumeContainerName, class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;&gt;" Usage="iVolumeContainersOperations.BeginCreateOrUpdateWithHttpMessagesAsync (deviceName, volumeContainerName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="99b91-102">デバイス名</span><span class="sxs-lookup"><span data-stu-id="99b91-102">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="99b91-103">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="99b91-103">The name of the volume container.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="99b91-104">ボリューム コンテナーを追加または更新をします。</span><span class="sxs-lookup"><span data-stu-id="99b91-104">The volume container to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="99b91-105">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="99b91-105">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="99b91-106">管理者名</span><span class="sxs-lookup"><span data-stu-id="99b91-106">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="99b91-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="99b91-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="99b91-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="99b91-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="99b91-109">作成するか、ボリューム コンテナーを更新します。</span><span class="sxs-lookup"><span data-stu-id="99b91-109">Creates or updates the volume container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="99b91-110">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99b91-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="99b91-111">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99b91-111">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="99b91-112">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99b91-112">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string deviceName, string volumeContainerName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string deviceName, string volumeContainerName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iVolumeContainersOperations.BeginDeleteWithHttpMessagesAsync (deviceName, volumeContainerName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="99b91-113">デバイス名</span><span class="sxs-lookup"><span data-stu-id="99b91-113">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="99b91-114">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="99b91-114">The name of the volume container.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="99b91-115">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="99b91-115">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="99b91-116">管理者名</span><span class="sxs-lookup"><span data-stu-id="99b91-116">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="99b91-117">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="99b91-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="99b91-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="99b91-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="99b91-119">ボリューム コンテナーを削除します。</span><span class="sxs-lookup"><span data-stu-id="99b91-119">Deletes the volume container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="99b91-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99b91-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="99b91-121">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99b91-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string deviceName, string volumeContainerName, Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string deviceName, string volumeContainerName, class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;&gt;" Usage="iVolumeContainersOperations.CreateOrUpdateWithHttpMessagesAsync (deviceName, volumeContainerName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="99b91-122">デバイス名</span><span class="sxs-lookup"><span data-stu-id="99b91-122">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="99b91-123">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="99b91-123">The name of the volume container.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="99b91-124">ボリューム コンテナーを追加または更新をします。</span><span class="sxs-lookup"><span data-stu-id="99b91-124">The volume container to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="99b91-125">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="99b91-125">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="99b91-126">管理者名</span><span class="sxs-lookup"><span data-stu-id="99b91-126">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="99b91-127">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="99b91-127">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="99b91-128">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="99b91-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="99b91-129">作成するか、ボリューム コンテナーを更新します。</span><span class="sxs-lookup"><span data-stu-id="99b91-129">Creates or updates the volume container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="99b91-130">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99b91-130">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="99b91-131">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99b91-131">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="99b91-132">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99b91-132">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string deviceName, string volumeContainerName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string deviceName, string volumeContainerName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iVolumeContainersOperations.DeleteWithHttpMessagesAsync (deviceName, volumeContainerName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="99b91-133">デバイス名</span><span class="sxs-lookup"><span data-stu-id="99b91-133">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="99b91-134">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="99b91-134">The name of the volume container.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="99b91-135">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="99b91-135">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="99b91-136">管理者名</span><span class="sxs-lookup"><span data-stu-id="99b91-136">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="99b91-137">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="99b91-137">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="99b91-138">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="99b91-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="99b91-139">ボリューム コンテナーを削除します。</span><span class="sxs-lookup"><span data-stu-id="99b91-139">Deletes the volume container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="99b91-140">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99b91-140">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="99b91-141">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99b91-141">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;&gt; GetWithHttpMessagesAsync (string deviceName, string volumeContainerName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;&gt; GetWithHttpMessagesAsync(string deviceName, string volumeContainerName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;&gt;" Usage="iVolumeContainersOperations.GetWithHttpMessagesAsync (deviceName, volumeContainerName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="99b91-142">デバイス名</span><span class="sxs-lookup"><span data-stu-id="99b91-142">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="99b91-143">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="99b91-143">The name of the volume container.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="99b91-144">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="99b91-144">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="99b91-145">管理者名</span><span class="sxs-lookup"><span data-stu-id="99b91-145">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="99b91-146">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="99b91-146">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="99b91-147">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="99b91-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="99b91-148">指定したボリューム コンテナー名のプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="99b91-148">Gets the properties of the specified volume container name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="99b91-149">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99b91-149">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="99b91-150">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99b91-150">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="99b91-151">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99b91-151">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByDeviceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;&gt;&gt; ListByDeviceWithHttpMessagesAsync (string deviceName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;&gt;&gt; ListByDeviceWithHttpMessagesAsync(string deviceName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations.ListByDeviceWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByDeviceWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;&gt;&gt;" Usage="iVolumeContainersOperations.ListByDeviceWithHttpMessagesAsync (deviceName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="99b91-152">デバイス名</span><span class="sxs-lookup"><span data-stu-id="99b91-152">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="99b91-153">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="99b91-153">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="99b91-154">管理者名</span><span class="sxs-lookup"><span data-stu-id="99b91-154">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="99b91-155">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="99b91-155">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="99b91-156">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="99b91-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="99b91-157">デバイスのすべてのボリューム コンテナーを取得します。</span><span class="sxs-lookup"><span data-stu-id="99b91-157">Gets all the volume containers in a device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="99b91-158">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99b91-158">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="99b91-159">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99b91-159">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="99b91-160">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99b91-160">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinitionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt;&gt; ListMetricDefinitionWithHttpMessagesAsync (string deviceName, string volumeContainerName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt;&gt; ListMetricDefinitionWithHttpMessagesAsync(string deviceName, string volumeContainerName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations.ListMetricDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMetricDefinitionWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt;&gt;" Usage="iVolumeContainersOperations.ListMetricDefinitionWithHttpMessagesAsync (deviceName, volumeContainerName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="99b91-161">デバイス名</span><span class="sxs-lookup"><span data-stu-id="99b91-161">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="99b91-162">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="99b91-162">The volume container name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="99b91-163">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="99b91-163">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="99b91-164">管理者名</span><span class="sxs-lookup"><span data-stu-id="99b91-164">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="99b91-165">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="99b91-165">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="99b91-166">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="99b91-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="99b91-167">指定したボリューム コンテナーのメトリックの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="99b91-167">Gets the metric definitions for the specified volume container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="99b91-168">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99b91-168">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="99b91-169">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99b91-169">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="99b91-170">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99b91-170">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt;&gt; ListMetricsWithHttpMessagesAsync (Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string volumeContainerName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt;&gt; ListMetricsWithHttpMessagesAsync(class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string volumeContainerName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations.ListMetricsWithHttpMessagesAsync(Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter},System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMetricsWithHttpMessagesAsync : Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt;&gt;" Usage="iVolumeContainersOperations.ListMetricsWithHttpMessagesAsync (odataQuery, deviceName, volumeContainerName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt;" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="odataQuery">
            <span data-ttu-id="99b91-171">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="99b91-171">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="99b91-172">デバイス名</span><span class="sxs-lookup"><span data-stu-id="99b91-172">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="99b91-173">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="99b91-173">The volume container name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="99b91-174">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="99b91-174">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="99b91-175">管理者名</span><span class="sxs-lookup"><span data-stu-id="99b91-175">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="99b91-176">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="99b91-176">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="99b91-177">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="99b91-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="99b91-178">指定したボリューム コンテナーのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="99b91-178">Gets the metrics for the specified volume container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="99b91-179">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99b91-179">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="99b91-180">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99b91-180">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="99b91-181">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="99b91-181">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>