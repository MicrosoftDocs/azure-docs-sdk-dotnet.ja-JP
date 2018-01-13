<Type Name="IProfilesOperations" FullName="Microsoft.Azure.Management.TrafficManager.IProfilesOperations">
  <TypeSignature Language="C#" Value="public interface IProfilesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IProfilesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.IProfilesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IProfilesOperations" />
  <TypeSignature Language="F#" Value="type IProfilesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e56db-101">ProfilesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="e56db-101">ProfilesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckTrafficManagerRelativeDnsNameAvailabilityWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability&gt;&gt; CheckTrafficManagerRelativeDnsNameAvailabilityWithHttpMessagesAsync (Microsoft.Azure.Management.TrafficManager.Models.CheckTrafficManagerRelativeDnsNameAvailabilityParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability&gt;&gt; CheckTrafficManagerRelativeDnsNameAvailabilityWithHttpMessagesAsync(class Microsoft.Azure.Management.TrafficManager.Models.CheckTrafficManagerRelativeDnsNameAvailabilityParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.IProfilesOperations.CheckTrafficManagerRelativeDnsNameAvailabilityWithHttpMessagesAsync(Microsoft.Azure.Management.TrafficManager.Models.CheckTrafficManagerRelativeDnsNameAvailabilityParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckTrafficManagerRelativeDnsNameAvailabilityWithHttpMessagesAsync : Microsoft.Azure.Management.TrafficManager.Models.CheckTrafficManagerRelativeDnsNameAvailabilityParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability&gt;&gt;" Usage="iProfilesOperations.CheckTrafficManagerRelativeDnsNameAvailabilityWithHttpMessagesAsync (parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerNameAvailability&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Models.CheckTrafficManagerRelativeDnsNameAvailabilityParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="e56db-102">CheckTrafficManagerNameAvailability 操作に指定された Traffic Manager 名パラメーター。</span><span class="sxs-lookup"><span data-stu-id="e56db-102">The Traffic Manager name parameters supplied to the CheckTrafficManagerNameAvailability operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e56db-103">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e56db-103">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e56db-104">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e56db-104">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e56db-105">Traffic Manager の相対 DNS 名を使用できるかどうかを確認します。</span><span class="sxs-lookup"><span data-stu-id="e56db-105">Checks the availability of a Traffic Manager Relative DNS name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e56db-106">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e56db-106">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e56db-107">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e56db-107">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e56db-108">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e56db-108">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string profileName, Microsoft.Azure.Management.TrafficManager.Models.Profile parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string profileName, class Microsoft.Azure.Management.TrafficManager.Models.Profile parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.IProfilesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.TrafficManager.Models.Profile,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.TrafficManager.Models.Profile * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt;" Usage="iProfilesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, profileName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Models.Profile" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e56db-109">Traffic Manager プロファイルを含む、リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e56db-109">The name of the resource group containing the Traffic Manager profile.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="e56db-110">Traffic Manager プロファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="e56db-110">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e56db-111">CreateOrUpdate 操作に指定された Traffic Manager プロファイルのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="e56db-111">The Traffic Manager profile parameters supplied to the CreateOrUpdate operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e56db-112">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e56db-112">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e56db-113">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e56db-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e56db-114">作成または Traffic Manager プロファイルを更新します。</span><span class="sxs-lookup"><span data-stu-id="e56db-114">Create or update a Traffic Manager profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e56db-115">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e56db-115">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e56db-116">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e56db-116">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e56db-117">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e56db-117">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult&gt;&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string profileName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult&gt;&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string profileName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.IProfilesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult&gt;&gt;" Usage="iProfilesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, profileName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.DeleteOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e56db-118">削除する Traffic Manager プロファイルを含む、リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e56db-118">The name of the resource group containing the Traffic Manager profile to be deleted.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="e56db-119">削除する Traffic Manager プロファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="e56db-119">The name of the Traffic Manager profile to be deleted.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e56db-120">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e56db-120">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e56db-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e56db-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e56db-122">Traffic Manager プロファイルを削除します。</span><span class="sxs-lookup"><span data-stu-id="e56db-122">Deletes a Traffic Manager profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e56db-123">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e56db-123">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e56db-124">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e56db-124">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e56db-125">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e56db-125">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string profileName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string profileName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.IProfilesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt;" Usage="iProfilesOperations.GetWithHttpMessagesAsync (resourceGroupName, profileName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e56db-126">Traffic Manager プロファイルを含む、リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e56db-126">The name of the resource group containing the Traffic Manager profile.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="e56db-127">Traffic Manager プロファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="e56db-127">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e56db-128">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e56db-128">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e56db-129">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e56db-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e56db-130">Traffic Manager プロファイルを取得します。</span><span class="sxs-lookup"><span data-stu-id="e56db-130">Gets a Traffic Manager profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e56db-131">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e56db-131">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e56db-132">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e56db-132">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e56db-133">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e56db-133">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAllInResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt;&gt; ListAllInResourceGroupWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt;&gt; ListAllInResourceGroupWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.IProfilesOperations.ListAllInResourceGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAllInResourceGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt;&gt;" Usage="iProfilesOperations.ListAllInResourceGroupWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e56db-134">一覧表示する Traffic Manager プロファイルを含むリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e56db-134">The name of the resource group containing the Traffic Manager profiles to be listed.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e56db-135">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e56db-135">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e56db-136">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e56db-136">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e56db-137">リソース グループ内のすべてのトラフィック マネージャー プロファイルを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="e56db-137">Lists all Traffic Manager profiles within a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e56db-138">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e56db-138">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e56db-139">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e56db-139">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e56db-140">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e56db-140">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListAllWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt;&gt; ListAllWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt;&gt; ListAllWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.IProfilesOperations.ListAllWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAllWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt;&gt;" Usage="iProfilesOperations.ListAllWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="e56db-141">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e56db-141">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e56db-142">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e56db-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e56db-143">サブスクリプション内のすべてのトラフィック マネージャー プロファイルを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="e56db-143">Lists all Traffic Manager profiles within a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e56db-144">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e56db-144">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e56db-145">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e56db-145">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e56db-146">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e56db-146">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string profileName, Microsoft.Azure.Management.TrafficManager.Models.Profile parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string profileName, class Microsoft.Azure.Management.TrafficManager.Models.Profile parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.IProfilesOperations.UpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.TrafficManager.Models.Profile,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.TrafficManager.Models.Profile * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt;" Usage="iProfilesOperations.UpdateWithHttpMessagesAsync (resourceGroupName, profileName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.TrafficManager.Models.Profile&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Models.Profile" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="e56db-147">Traffic Manager プロファイルを含む、リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="e56db-147">The name of the resource group containing the Traffic Manager profile.</span></span>
            </param>
        <param name="profileName">
            <span data-ttu-id="e56db-148">Traffic Manager プロファイルの名前。</span><span class="sxs-lookup"><span data-stu-id="e56db-148">The name of the Traffic Manager profile.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e56db-149">更新操作に指定された Traffic Manager プロファイルのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="e56db-149">The Traffic Manager profile parameters supplied to the Update operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="e56db-150">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="e56db-150">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e56db-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="e56db-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e56db-152">Traffic Manager プロファイルを更新します。</span><span class="sxs-lookup"><span data-stu-id="e56db-152">Update a Traffic Manager profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="e56db-153">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e56db-153">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="e56db-154">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e56db-154">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e56db-155">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e56db-155">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>