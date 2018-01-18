<Type Name="IContainerServicesOperations" FullName="Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations">
  <TypeSignature Language="C#" Value="public interface IContainerServicesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IContainerServicesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IContainerServicesOperations" />
  <TypeSignature Language="F#" Value="type IContainerServicesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="898cc-101">ContainerServicesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="898cc-101">ContainerServicesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string containerServiceName, Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string containerServiceName, class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;" Usage="iContainerServicesOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, containerServiceName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="898cc-102">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="898cc-102">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="898cc-103">指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="898cc-103">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="898cc-104">作成または更新コンテナー サービス操作に渡されるパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="898cc-104">Parameters supplied to the Create or Update a Container Service operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="898cc-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="898cc-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="898cc-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="898cc-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="898cc-107">作成するか、コンテナー サービスを更新します。</span><span class="sxs-lookup"><span data-stu-id="898cc-107">Creates or updates a container service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="898cc-108">作成または、orchestrator、マスター、およびエージェントの指定の構成を持つコンテナー サービスを更新します。</span><span class="sxs-lookup"><span data-stu-id="898cc-108">Creates or updates a container service with the specified configuration of orchestrator, masters, and agents.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="898cc-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="898cc-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="898cc-110">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="898cc-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="898cc-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="898cc-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string containerServiceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string containerServiceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iContainerServicesOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, containerServiceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="898cc-112">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="898cc-112">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="898cc-113">指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="898cc-113">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="898cc-114">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="898cc-114">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="898cc-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="898cc-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="898cc-116">指定されたコンテナー サービスを削除します。</span><span class="sxs-lookup"><span data-stu-id="898cc-116">Deletes the specified container service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="898cc-117">指定したサブスクリプションとリソース グループ内の指定されたコンテナー サービスを削除します。</span><span class="sxs-lookup"><span data-stu-id="898cc-117">Deletes the specified container service in the specified subscription and resource group.</span></span> <span data-ttu-id="898cc-118">操作では、ストレージ アカウント、Vm を含む、コンテナー サービスの作成の一部として作成されたその他のリソースは削除されませんし、可用性セットします。</span><span class="sxs-lookup"><span data-stu-id="898cc-118">The operation does not delete other resources created as part of creating a container service, including storage accounts, VMs, and availability sets.</span></span> <span data-ttu-id="898cc-119">コンテナー サービスで作成されたその他のすべてのリソースは、同じリソース グループの一部であるし、個別に削除することができます。</span><span class="sxs-lookup"><span data-stu-id="898cc-119">All the other resources created with the container service are part of the same resource group and can be deleted individually.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="898cc-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="898cc-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="898cc-121">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="898cc-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string containerServiceName, Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string containerServiceName, class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;" Usage="iContainerServicesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, containerServiceName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="898cc-122">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="898cc-122">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="898cc-123">指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="898cc-123">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="898cc-124">作成または更新コンテナー サービス操作に渡されるパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="898cc-124">Parameters supplied to the Create or Update a Container Service operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="898cc-125">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="898cc-125">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="898cc-126">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="898cc-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="898cc-127">作成するか、コンテナー サービスを更新します。</span><span class="sxs-lookup"><span data-stu-id="898cc-127">Creates or updates a container service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="898cc-128">作成または、orchestrator、マスター、およびエージェントの指定の構成を持つコンテナー サービスを更新します。</span><span class="sxs-lookup"><span data-stu-id="898cc-128">Creates or updates a container service with the specified configuration of orchestrator, masters, and agents.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="898cc-129">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="898cc-129">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="898cc-130">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="898cc-130">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="898cc-131">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="898cc-131">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string containerServiceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string containerServiceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iContainerServicesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, containerServiceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="898cc-132">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="898cc-132">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="898cc-133">指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="898cc-133">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="898cc-134">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="898cc-134">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="898cc-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="898cc-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="898cc-136">指定されたコンテナー サービスを削除します。</span><span class="sxs-lookup"><span data-stu-id="898cc-136">Deletes the specified container service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="898cc-137">指定したサブスクリプションとリソース グループ内の指定されたコンテナー サービスを削除します。</span><span class="sxs-lookup"><span data-stu-id="898cc-137">Deletes the specified container service in the specified subscription and resource group.</span></span> <span data-ttu-id="898cc-138">操作では、ストレージ アカウント、Vm を含む、コンテナー サービスの作成の一部として作成されたその他のリソースは削除されませんし、可用性セットします。</span><span class="sxs-lookup"><span data-stu-id="898cc-138">The operation does not delete other resources created as part of creating a container service, including storage accounts, VMs, and availability sets.</span></span> <span data-ttu-id="898cc-139">コンテナー サービスで作成されたその他のすべてのリソースは、同じリソース グループの一部であるし、個別に削除することができます。</span><span class="sxs-lookup"><span data-stu-id="898cc-139">All the other resources created with the container service are part of the same resource group and can be deleted individually.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="898cc-140">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="898cc-140">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="898cc-141">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="898cc-141">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string containerServiceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string containerServiceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;" Usage="iContainerServicesOperations.GetWithHttpMessagesAsync (resourceGroupName, containerServiceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerServiceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="898cc-142">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="898cc-142">The name of the resource group.</span></span>
            </param>
        <param name="containerServiceName">
            <span data-ttu-id="898cc-143">指定したサブスクリプションとリソース グループ内のコンテナー サービスの名前。</span><span class="sxs-lookup"><span data-stu-id="898cc-143">The name of the container service in the specified subscription and resource group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="898cc-144">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="898cc-144">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="898cc-145">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="898cc-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="898cc-146">指定されたコンテナー サービスのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="898cc-146">Gets the properties of the specified container service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="898cc-147">指定したサブスクリプションとリソース グループで指定されたコンテナー サービスのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="898cc-147">Gets the properties of the specified container service in the specified subscription and resource group.</span></span> <span data-ttu-id="898cc-148">操作は、状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。</span><span class="sxs-lookup"><span data-stu-id="898cc-148">The operation returns the properties including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="898cc-149">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="898cc-149">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="898cc-150">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="898cc-150">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="898cc-151">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="898cc-151">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;&gt; ListByResourceGroupNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations.ListByResourceGroupNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;&gt;" Usage="iContainerServicesOperations.ListByResourceGroupNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="898cc-152">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="898cc-152">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="898cc-153">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="898cc-153">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="898cc-154">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="898cc-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="898cc-155">指定されたリソース グループ内のコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="898cc-155">Gets a list of container services in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="898cc-156">指定したサブスクリプションとリソース グループ内のコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="898cc-156">Gets a list of container services in the specified subscription and resource group.</span></span> <span data-ttu-id="898cc-157">操作は、各コンテナー サービスの状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。</span><span class="sxs-lookup"><span data-stu-id="898cc-157">The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="898cc-158">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="898cc-158">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="898cc-159">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="898cc-159">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="898cc-160">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="898cc-160">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;&gt;" Usage="iContainerServicesOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="898cc-161">リソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="898cc-161">The name of the resource group.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="898cc-162">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="898cc-162">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="898cc-163">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="898cc-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="898cc-164">指定されたリソース グループ内のコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="898cc-164">Gets a list of container services in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="898cc-165">指定したサブスクリプションとリソース グループ内のコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="898cc-165">Gets a list of container services in the specified subscription and resource group.</span></span> <span data-ttu-id="898cc-166">操作は、各コンテナー サービスの状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。</span><span class="sxs-lookup"><span data-stu-id="898cc-166">The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="898cc-167">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="898cc-167">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="898cc-168">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="898cc-168">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="898cc-169">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="898cc-169">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;&gt;" Usage="iContainerServicesOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="898cc-170">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="898cc-170">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="898cc-171">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="898cc-171">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="898cc-172">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="898cc-172">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="898cc-173">指定されたサブスクリプションのコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="898cc-173">Gets a list of container services in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="898cc-174">指定されたサブスクリプションのコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="898cc-174">Gets a list of container services in the specified subscription.</span></span>
            <span data-ttu-id="898cc-175">操作は、各コンテナー サービスの状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。</span><span class="sxs-lookup"><span data-stu-id="898cc-175">The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="898cc-176">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="898cc-176">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="898cc-177">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="898cc-177">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="898cc-178">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="898cc-178">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;&gt; ListWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;&gt; ListWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations.ListWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;&gt;" Usage="iContainerServicesOperations.ListWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ContainerServiceInner&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="898cc-179">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="898cc-179">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="898cc-180">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="898cc-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="898cc-181">指定されたサブスクリプションのコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="898cc-181">Gets a list of container services in the specified subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="898cc-182">指定されたサブスクリプションのコンテナー サービスの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="898cc-182">Gets a list of container services in the specified subscription.</span></span>
            <span data-ttu-id="898cc-183">操作は、各コンテナー サービスの状態、orchestrator、マスターとのエージェントの数などのプロパティを返しますおよびマスターとエージェントの Fqdn です。</span><span class="sxs-lookup"><span data-stu-id="898cc-183">The operation returns properties of each container service including state, orchestrator, number of masters and agents, and FQDNs of masters and agents.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="898cc-184">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="898cc-184">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="898cc-185">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="898cc-185">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="898cc-186">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="898cc-186">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>