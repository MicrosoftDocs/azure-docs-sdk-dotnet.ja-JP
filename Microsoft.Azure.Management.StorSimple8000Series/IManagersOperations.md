<Type Name="IManagersOperations" FullName="Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations">
  <TypeSignature Language="C#" Value="public interface IManagersOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IManagersOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IManagersOperations" />
  <TypeSignature Language="F#" Value="type IManagersOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="28cc7-101">ManagersOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="28cc7-101">ManagersOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateExtendedInfoWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo&gt;&gt; CreateExtendedInfoWithHttpMessagesAsync (Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo&gt;&gt; CreateExtendedInfoWithHttpMessagesAsync(class Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations.CreateExtendedInfoWithHttpMessagesAsync(Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateExtendedInfoWithHttpMessagesAsync : Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo&gt;&gt;" Usage="iManagersOperations.CreateExtendedInfoWithHttpMessagesAsync (parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="28cc7-102">マネージャーは、情報を拡張します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-102">The manager extended information.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="28cc7-103">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="28cc7-103">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="28cc7-104">管理者名</span><span class="sxs-lookup"><span data-stu-id="28cc7-104">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="28cc7-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="28cc7-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="28cc7-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="28cc7-107">マネージャーの拡張情報を作成します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-107">Creates the extended info of the manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="28cc7-108">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-108">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="28cc7-109">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-109">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="28cc7-110">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-110">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (Microsoft.Azure.Management.StorSimple8000Series.Models.Manager parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(class Microsoft.Azure.Management.StorSimple8000Series.Models.Manager parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations.CreateOrUpdateWithHttpMessagesAsync(Microsoft.Azure.Management.StorSimple8000Series.Models.Manager,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : Microsoft.Azure.Management.StorSimple8000Series.Models.Manager * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt;" Usage="iManagersOperations.CreateOrUpdateWithHttpMessagesAsync (parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.Manager" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="28cc7-111">マネージャーです。</span><span class="sxs-lookup"><span data-stu-id="28cc7-111">The manager.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="28cc7-112">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="28cc7-112">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="28cc7-113">管理者名</span><span class="sxs-lookup"><span data-stu-id="28cc7-113">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="28cc7-114">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-114">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="28cc7-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="28cc7-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="28cc7-116">作成するか、マネージャーを更新します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-116">Creates or updates the manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="28cc7-117">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-117">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="28cc7-118">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-118">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="28cc7-119">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-119">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteExtendedInfoWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteExtendedInfoWithHttpMessagesAsync (string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteExtendedInfoWithHttpMessagesAsync(string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations.DeleteExtendedInfoWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteExtendedInfoWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iManagersOperations.DeleteExtendedInfoWithHttpMessagesAsync (resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="28cc7-120">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="28cc7-120">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="28cc7-121">管理者名</span><span class="sxs-lookup"><span data-stu-id="28cc7-121">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="28cc7-122">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-122">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="28cc7-123">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="28cc7-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="28cc7-124">マネージャーの拡張情報を削除します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-124">Deletes the extended info of the manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="28cc7-125">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-125">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="28cc7-126">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-126">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iManagersOperations.DeleteWithHttpMessagesAsync (resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="28cc7-127">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="28cc7-127">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="28cc7-128">管理者名</span><span class="sxs-lookup"><span data-stu-id="28cc7-128">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="28cc7-129">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-129">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="28cc7-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="28cc7-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="28cc7-131">管理者を削除します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-131">Deletes the manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="28cc7-132">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-132">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="28cc7-133">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-133">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetActivationKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Key&gt;&gt; GetActivationKeyWithHttpMessagesAsync (string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Key&gt;&gt; GetActivationKeyWithHttpMessagesAsync(string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations.GetActivationKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetActivationKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Key&gt;&gt;" Usage="iManagersOperations.GetActivationKeyWithHttpMessagesAsync (resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Key&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="28cc7-134">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="28cc7-134">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="28cc7-135">管理者名</span><span class="sxs-lookup"><span data-stu-id="28cc7-135">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="28cc7-136">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-136">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="28cc7-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="28cc7-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="28cc7-138">マネージャーのアクティブ化キーを返します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-138">Returns the activation key of the manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="28cc7-139">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-139">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="28cc7-140">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-140">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="28cc7-141">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-141">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDevicePublicEncryptionKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.PublicKey&gt;&gt; GetDevicePublicEncryptionKeyWithHttpMessagesAsync (string deviceName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.PublicKey&gt;&gt; GetDevicePublicEncryptionKeyWithHttpMessagesAsync(string deviceName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations.GetDevicePublicEncryptionKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDevicePublicEncryptionKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.PublicKey&gt;&gt;" Usage="iManagersOperations.GetDevicePublicEncryptionKeyWithHttpMessagesAsync (deviceName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.PublicKey&gt;&gt;</ReturnType>
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
            <span data-ttu-id="28cc7-142">デバイス名</span><span class="sxs-lookup"><span data-stu-id="28cc7-142">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="28cc7-143">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="28cc7-143">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="28cc7-144">管理者名</span><span class="sxs-lookup"><span data-stu-id="28cc7-144">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="28cc7-145">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-145">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="28cc7-146">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="28cc7-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="28cc7-147">デバイスの公開暗号化キーを返します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-147">Returns the public encryption key of the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="28cc7-148">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-148">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="28cc7-149">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-149">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="28cc7-150">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-150">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetEncryptionSettingsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings&gt;&gt; GetEncryptionSettingsWithHttpMessagesAsync (string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings&gt;&gt; GetEncryptionSettingsWithHttpMessagesAsync(string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations.GetEncryptionSettingsWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetEncryptionSettingsWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings&gt;&gt;" Usage="iManagersOperations.GetEncryptionSettingsWithHttpMessagesAsync (resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.EncryptionSettings&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="28cc7-151">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="28cc7-151">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="28cc7-152">管理者名</span><span class="sxs-lookup"><span data-stu-id="28cc7-152">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="28cc7-153">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-153">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="28cc7-154">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="28cc7-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="28cc7-155">マネージャーの暗号化の設定を返します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-155">Returns the encryption settings of the manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="28cc7-156">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-156">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="28cc7-157">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-157">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="28cc7-158">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-158">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetExtendedInfoWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo&gt;&gt; GetExtendedInfoWithHttpMessagesAsync (string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo&gt;&gt; GetExtendedInfoWithHttpMessagesAsync(string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations.GetExtendedInfoWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetExtendedInfoWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo&gt;&gt;" Usage="iManagersOperations.GetExtendedInfoWithHttpMessagesAsync (resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="28cc7-159">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="28cc7-159">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="28cc7-160">管理者名</span><span class="sxs-lookup"><span data-stu-id="28cc7-160">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="28cc7-161">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-161">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="28cc7-162">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="28cc7-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="28cc7-163">指定されたマネージャー名の拡張情報を返します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-163">Returns the extended information of the specified manager name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="28cc7-164">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-164">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="28cc7-165">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-165">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="28cc7-166">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-166">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPublicEncryptionKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret&gt;&gt; GetPublicEncryptionKeyWithHttpMessagesAsync (string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret&gt;&gt; GetPublicEncryptionKeyWithHttpMessagesAsync(string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations.GetPublicEncryptionKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPublicEncryptionKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret&gt;&gt;" Usage="iManagersOperations.GetPublicEncryptionKeyWithHttpMessagesAsync (resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.SymmetricEncryptedSecret&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="28cc7-167">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="28cc7-167">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="28cc7-168">管理者名</span><span class="sxs-lookup"><span data-stu-id="28cc7-168">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="28cc7-169">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-169">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="28cc7-170">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="28cc7-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="28cc7-171">マネージャーの対称の暗号化された公開暗号化キーを返します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-171">Returns the symmetric encrypted public encryption key of the manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="28cc7-172">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-172">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="28cc7-173">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-173">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="28cc7-174">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-174">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt;" Usage="iManagersOperations.GetWithHttpMessagesAsync (resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="28cc7-175">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="28cc7-175">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="28cc7-176">管理者名</span><span class="sxs-lookup"><span data-stu-id="28cc7-176">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="28cc7-177">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-177">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="28cc7-178">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="28cc7-178">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="28cc7-179">指定されたマネージャー名のプロパティを返します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-179">Returns the properties of the specified manager name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="28cc7-180">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-180">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="28cc7-181">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-181">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="28cc7-182">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-182">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt;&gt;" Usage="iManagersOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="28cc7-183">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="28cc7-183">The resource group name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="28cc7-184">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-184">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="28cc7-185">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="28cc7-185">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="28cc7-186">リソース グループ内のすべてのマネージャーを取得します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-186">Retrieves all the managers in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="28cc7-187">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-187">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="28cc7-188">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-188">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="28cc7-189">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-189">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListFeatureSupportStatusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Feature&gt;&gt;&gt; ListFeatureSupportStatusWithHttpMessagesAsync (string resourceGroupName, string managerName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FeatureFilter&gt; odataQuery = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Feature&gt;&gt;&gt; ListFeatureSupportStatusWithHttpMessagesAsync(string resourceGroupName, string managerName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.FeatureFilter&gt; odataQuery, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations.ListFeatureSupportStatusWithHttpMessagesAsync(System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.FeatureFilter},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListFeatureSupportStatusWithHttpMessagesAsync : string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FeatureFilter&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Feature&gt;&gt;&gt;" Usage="iManagersOperations.ListFeatureSupportStatusWithHttpMessagesAsync (resourceGroupName, managerName, odataQuery, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Feature&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.FeatureFilter&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="28cc7-190">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="28cc7-190">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="28cc7-191">管理者名</span><span class="sxs-lookup"><span data-stu-id="28cc7-191">The manager name</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="28cc7-192">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="28cc7-192">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="28cc7-193">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-193">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="28cc7-194">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="28cc7-194">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="28cc7-195">機能とサポートの状態を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-195">Lists the features and their support status</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="28cc7-196">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-196">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="28cc7-197">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-197">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="28cc7-198">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-198">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinitionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt;&gt; ListMetricDefinitionWithHttpMessagesAsync (string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt;&gt; ListMetricDefinitionWithHttpMessagesAsync(string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations.ListMetricDefinitionWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMetricDefinitionWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt;&gt;" Usage="iManagersOperations.ListMetricDefinitionWithHttpMessagesAsync (resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="28cc7-199">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="28cc7-199">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="28cc7-200">管理者名</span><span class="sxs-lookup"><span data-stu-id="28cc7-200">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="28cc7-201">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-201">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="28cc7-202">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="28cc7-202">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="28cc7-203">指定したマネージャーのメトリックの定義を取得します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-203">Gets the metric definitions for the specified manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="28cc7-204">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-204">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="28cc7-205">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-205">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="28cc7-206">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-206">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt;&gt; ListMetricsWithHttpMessagesAsync (Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt;&gt; ListMetricsWithHttpMessagesAsync(class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations.ListMetricsWithHttpMessagesAsync(Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter},System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMetricsWithHttpMessagesAsync : Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt;&gt;" Usage="iManagersOperations.ListMetricsWithHttpMessagesAsync (odataQuery, resourceGroupName, managerName, customHeaders, cancellationToken)" />
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
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="odataQuery">
            <span data-ttu-id="28cc7-207">OData の操作に適用するパラメーター。</span><span class="sxs-lookup"><span data-stu-id="28cc7-207">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="28cc7-208">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="28cc7-208">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="28cc7-209">管理者名</span><span class="sxs-lookup"><span data-stu-id="28cc7-209">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="28cc7-210">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-210">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="28cc7-211">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="28cc7-211">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="28cc7-212">指定したマネージャーのメトリックを取得します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-212">Gets the metrics for the specified manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="28cc7-213">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-213">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="28cc7-214">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-214">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="28cc7-215">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-215">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt;&gt; ListWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt;&gt; ListWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations.ListWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt;&gt;" Usage="iManagersOperations.ListWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="28cc7-216">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-216">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="28cc7-217">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="28cc7-217">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="28cc7-218">サブスクリプション内のすべてのマネージャーを取得します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-218">Retrieves all the managers in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="28cc7-219">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-219">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="28cc7-220">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-220">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="28cc7-221">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-221">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RegenerateActivationKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Key&gt;&gt; RegenerateActivationKeyWithHttpMessagesAsync (string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Key&gt;&gt; RegenerateActivationKeyWithHttpMessagesAsync(string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations.RegenerateActivationKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateActivationKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Key&gt;&gt;" Usage="iManagersOperations.RegenerateActivationKeyWithHttpMessagesAsync (resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Key&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="28cc7-222">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="28cc7-222">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="28cc7-223">管理者名</span><span class="sxs-lookup"><span data-stu-id="28cc7-223">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="28cc7-224">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-224">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="28cc7-225">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="28cc7-225">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="28cc7-226">再生成し、マネージャーのライセンス認証キーを返します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-226">Re-generates and returns the activation key of the manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="28cc7-227">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-227">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="28cc7-228">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-228">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="28cc7-229">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-229">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateExtendedInfoWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo&gt;&gt; UpdateExtendedInfoWithHttpMessagesAsync (Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo parameters, string resourceGroupName, string managerName, string ifMatch, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo&gt;&gt; UpdateExtendedInfoWithHttpMessagesAsync(class Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo parameters, string resourceGroupName, string managerName, string ifMatch, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations.UpdateExtendedInfoWithHttpMessagesAsync(Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateExtendedInfoWithHttpMessagesAsync : Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo&gt;&gt;" Usage="iManagersOperations.UpdateExtendedInfoWithHttpMessagesAsync (parameters, resourceGroupName, managerName, ifMatch, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerExtendedInfo" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="28cc7-230">マネージャーは、情報を拡張します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-230">The manager extended information.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="28cc7-231">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="28cc7-231">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="28cc7-232">管理者名</span><span class="sxs-lookup"><span data-stu-id="28cc7-232">The manager name</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="28cc7-233">GET 呼び出しから現在フェッチ ExtendedInfo の ETag を渡す</span><span class="sxs-lookup"><span data-stu-id="28cc7-233">Pass the ETag of ExtendedInfo fetched from GET call</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="28cc7-234">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-234">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="28cc7-235">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="28cc7-235">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="28cc7-236">マネージャーの拡張情報を更新します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-236">Updates the extended info of the manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="28cc7-237">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-237">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="28cc7-238">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-238">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="28cc7-239">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-239">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt; UpdateWithHttpMessagesAsync (Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerPatch parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt; UpdateWithHttpMessagesAsync(class Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerPatch parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IManagersOperations.UpdateWithHttpMessagesAsync(Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerPatch,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerPatch * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt;" Usage="iManagersOperations.UpdateWithHttpMessagesAsync (parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Manager&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ManagerPatch" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="28cc7-240">管理者は、パラメーターを更新できます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-240">The manager update parameters.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="28cc7-241">リソース グループ名</span><span class="sxs-lookup"><span data-stu-id="28cc7-241">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="28cc7-242">管理者名</span><span class="sxs-lookup"><span data-stu-id="28cc7-242">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="28cc7-243">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-243">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="28cc7-244">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="28cc7-244">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="28cc7-245">StorSimple Manager を更新します。</span><span class="sxs-lookup"><span data-stu-id="28cc7-245">Updates the StorSimple Manager.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="28cc7-246">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-246">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="28cc7-247">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-247">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="28cc7-248">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="28cc7-248">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>