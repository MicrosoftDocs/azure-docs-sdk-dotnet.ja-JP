<Type Name="IVolumesOperations" FullName="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations">
  <TypeSignature Language="C#" Value="public interface IVolumesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVolumesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVolumesOperations" />
  <TypeSignature Language="F#" Value="type IVolumesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="51e31-101">VolumesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="51e31-101">VolumesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string deviceName, string volumeContainerName, string volumeName, Microsoft.Azure.Management.StorSimple8000Series.Models.Volume parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string deviceName, string volumeContainerName, string volumeName, class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.Volume,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.Volume * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt;" Usage="iVolumesOperations.BeginCreateOrUpdateWithHttpMessagesAsync (deviceName, volumeContainerName, volumeName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="51e31-102">デバイス名</span><span class="sxs-lookup"><span data-stu-id="51e31-102">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="51e31-103">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="51e31-103">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="51e31-104">ボリュームの名前。</span><span class="sxs-lookup"><span data-stu-id="51e31-104">The volume name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="51e31-105">作成または更新するボリューム。</span><span class="sxs-lookup"><span data-stu-id="51e31-105">Volume to be created or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51e31-106">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="51e31-106">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="51e31-107">管理者名</span><span class="sxs-lookup"><span data-stu-id="51e31-107">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="51e31-108">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="51e31-108">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="51e31-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="51e31-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51e31-110">作成するか、ボリュームを更新します。</span><span class="sxs-lookup"><span data-stu-id="51e31-110">Creates or updates the volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="51e31-111">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="51e31-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="51e31-112">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="51e31-112">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="51e31-113">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="51e31-113">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iVolumesOperations.BeginDeleteWithHttpMessagesAsync (deviceName, volumeContainerName, volumeName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
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
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="51e31-114">デバイス名</span><span class="sxs-lookup"><span data-stu-id="51e31-114">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="51e31-115">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="51e31-115">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="51e31-116">ボリュームの名前。</span><span class="sxs-lookup"><span data-stu-id="51e31-116">The volume name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51e31-117">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="51e31-117">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="51e31-118">管理者名</span><span class="sxs-lookup"><span data-stu-id="51e31-118">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="51e31-119">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="51e31-119">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="51e31-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="51e31-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51e31-121">ボリュームを削除します。</span><span class="sxs-lookup"><span data-stu-id="51e31-121">Deletes the volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="51e31-122">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="51e31-122">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="51e31-123">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="51e31-123">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string deviceName, string volumeContainerName, string volumeName, Microsoft.Azure.Management.StorSimple8000Series.Models.Volume parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string deviceName, string volumeContainerName, string volumeName, class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.Volume,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.Volume * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt;" Usage="iVolumesOperations.CreateOrUpdateWithHttpMessagesAsync (deviceName, volumeContainerName, volumeName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="51e31-124">デバイス名</span><span class="sxs-lookup"><span data-stu-id="51e31-124">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="51e31-125">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="51e31-125">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="51e31-126">ボリュームの名前。</span><span class="sxs-lookup"><span data-stu-id="51e31-126">The volume name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="51e31-127">作成または更新するボリューム。</span><span class="sxs-lookup"><span data-stu-id="51e31-127">Volume to be created or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51e31-128">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="51e31-128">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="51e31-129">管理者名</span><span class="sxs-lookup"><span data-stu-id="51e31-129">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="51e31-130">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="51e31-130">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="51e31-131">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="51e31-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51e31-132">作成するか、ボリュームを更新します。</span><span class="sxs-lookup"><span data-stu-id="51e31-132">Creates or updates the volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="51e31-133">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="51e31-133">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="51e31-134">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="51e31-134">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="51e31-135">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="51e31-135">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iVolumesOperations.DeleteWithHttpMessagesAsync (deviceName, volumeContainerName, volumeName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
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
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="51e31-136">デバイス名</span><span class="sxs-lookup"><span data-stu-id="51e31-136">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="51e31-137">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="51e31-137">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="51e31-138">ボリュームの名前。</span><span class="sxs-lookup"><span data-stu-id="51e31-138">The volume name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51e31-139">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="51e31-139">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="51e31-140">管理者名</span><span class="sxs-lookup"><span data-stu-id="51e31-140">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="51e31-141">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="51e31-141">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="51e31-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="51e31-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51e31-143">ボリュームを削除します。</span><span class="sxs-lookup"><span data-stu-id="51e31-143">Deletes the volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="51e31-144">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="51e31-144">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="51e31-145">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="51e31-145">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt; GetWithHttpMessagesAsync (string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt; GetWithHttpMessagesAsync(string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt;" Usage="iVolumesOperations.GetWithHttpMessagesAsync (deviceName, volumeContainerName, volumeName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="51e31-146">デバイス名</span><span class="sxs-lookup"><span data-stu-id="51e31-146">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="51e31-147">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="51e31-147">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="51e31-148">ボリュームの名前。</span><span class="sxs-lookup"><span data-stu-id="51e31-148">The volume name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51e31-149">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="51e31-149">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="51e31-150">管理者名</span><span class="sxs-lookup"><span data-stu-id="51e31-150">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="51e31-151">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="51e31-151">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="51e31-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="51e31-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51e31-153">指定したボリューム名のプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="51e31-153">Returns the properties of the specified volume name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="51e31-154">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="51e31-154">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="51e31-155">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="51e31-155">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="51e31-156">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="51e31-156">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByDeviceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt;&gt; ListByDeviceWithHttpMessagesAsync (string deviceName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt;&gt; ListByDeviceWithHttpMessagesAsync(string deviceName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations.ListByDeviceWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByDeviceWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt;&gt;" Usage="iVolumesOperations.ListByDeviceWithHttpMessagesAsync (deviceName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt;&gt;</ReturnType>
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
            <span data-ttu-id="51e31-157">デバイス名</span><span class="sxs-lookup"><span data-stu-id="51e31-157">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51e31-158">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="51e31-158">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="51e31-159">管理者名</span><span class="sxs-lookup"><span data-stu-id="51e31-159">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="51e31-160">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="51e31-160">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="51e31-161">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="51e31-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51e31-162">デバイスのすべてのボリュームを取得します。</span><span class="sxs-lookup"><span data-stu-id="51e31-162">Retrieves all the volumes in a device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="51e31-163">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="51e31-163">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="51e31-164">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="51e31-164">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="51e31-165">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="51e31-165">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByVolumeContainerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt;&gt; ListByVolumeContainerWithHttpMessagesAsync (string deviceName, string volumeContainerName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt;&gt; ListByVolumeContainerWithHttpMessagesAsync(string deviceName, string volumeContainerName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations.ListByVolumeContainerWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByVolumeContainerWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt;&gt;" Usage="iVolumesOperations.ListByVolumeContainerWithHttpMessagesAsync (deviceName, volumeContainerName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt;&gt;</ReturnType>
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
            <span data-ttu-id="51e31-166">デバイス名</span><span class="sxs-lookup"><span data-stu-id="51e31-166">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="51e31-167">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="51e31-167">The volume container name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51e31-168">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="51e31-168">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="51e31-169">管理者名</span><span class="sxs-lookup"><span data-stu-id="51e31-169">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="51e31-170">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="51e31-170">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="51e31-171">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="51e31-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51e31-172">ボリューム コンテナー内のすべてのボリュームを取得します。</span><span class="sxs-lookup"><span data-stu-id="51e31-172">Retrieves all the volumes in a volume container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="51e31-173">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="51e31-173">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="51e31-174">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="51e31-174">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="51e31-175">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="51e31-175">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinitionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt;&gt; ListMetricDefinitionWithHttpMessagesAsync (string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt;&gt; ListMetricDefinitionWithHttpMessagesAsync(string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations.ListMetricDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMetricDefinitionWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt;&gt;" Usage="iVolumesOperations.ListMetricDefinitionWithHttpMessagesAsync (deviceName, volumeContainerName, volumeName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
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
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="51e31-176">デバイス名</span><span class="sxs-lookup"><span data-stu-id="51e31-176">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="51e31-177">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="51e31-177">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="51e31-178">ボリュームの名前。</span><span class="sxs-lookup"><span data-stu-id="51e31-178">The volume name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51e31-179">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="51e31-179">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="51e31-180">管理者名</span><span class="sxs-lookup"><span data-stu-id="51e31-180">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="51e31-181">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="51e31-181">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="51e31-182">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="51e31-182">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51e31-183">指定したボリュームのメトリックの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="51e31-183">Gets the metric definitions for the specified volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="51e31-184">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="51e31-184">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="51e31-185">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="51e31-185">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="51e31-186">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="51e31-186">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt;&gt; ListMetricsWithHttpMessagesAsync (Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt;&gt; ListMetricsWithHttpMessagesAsync(class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations.ListMetricsWithHttpMessagesAsync(Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter},System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMetricsWithHttpMessagesAsync : Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; * string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt;&gt;" Usage="iVolumesOperations.ListMetricsWithHttpMessagesAsync (odataQuery, deviceName, volumeContainerName, volumeName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
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
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="odataQuery">
            <span data-ttu-id="51e31-187">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="51e31-187">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="51e31-188">デバイス名</span><span class="sxs-lookup"><span data-stu-id="51e31-188">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="51e31-189">ボリューム コンテナーの名前。</span><span class="sxs-lookup"><span data-stu-id="51e31-189">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="51e31-190">ボリュームの名前。</span><span class="sxs-lookup"><span data-stu-id="51e31-190">The volume name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="51e31-191">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="51e31-191">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="51e31-192">管理者名</span><span class="sxs-lookup"><span data-stu-id="51e31-192">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="51e31-193">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="51e31-193">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="51e31-194">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="51e31-194">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="51e31-195">指定したボリュームのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="51e31-195">Gets the metrics for the specified volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="51e31-196">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="51e31-196">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="51e31-197">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="51e31-197">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="51e31-198">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="51e31-198">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>