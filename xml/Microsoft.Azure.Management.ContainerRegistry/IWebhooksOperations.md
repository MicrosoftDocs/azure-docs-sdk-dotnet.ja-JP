<Type Name="IWebhooksOperations" FullName="Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations">
  <TypeSignature Language="C#" Value="public interface IWebhooksOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWebhooksOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWebhooksOperations" />
  <TypeSignature Language="F#" Value="type IWebhooksOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b5c20-101">WebhooksOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="b5c20-101">WebhooksOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt; BeginCreateWithHttpMessagesAsync (string resourceGroupName, string registryName, string webhookName, Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters webhookCreateParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt; BeginCreateWithHttpMessagesAsync(string resourceGroupName, string registryName, string webhookName, class Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters webhookCreateParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations.BeginCreateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt;" Usage="iWebhooksOperations.BeginCreateWithHttpMessagesAsync (resourceGroupName, registryName, webhookName, webhookCreateParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="webhookCreateParameters" Type="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b5c20-102">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-102">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="b5c20-103">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-103">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="b5c20-104">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-104">The name of the webhook.</span></span>
            </param>
        <param name="webhookCreateParameters">
            <span data-ttu-id="b5c20-105">Webhook を作成するためのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="b5c20-105">The parameters for creating a webhook.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b5c20-106">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b5c20-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b5c20-107">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b5c20-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b5c20-108">指定したパラメーターにコンテナー レジストリの webhook を作成します。</span><span class="sxs-lookup"><span data-stu-id="b5c20-108">Creates a webhook for a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b5c20-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b5c20-110">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b5c20-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string registryName, string webhookName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string registryName, string webhookName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iWebhooksOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, registryName, webhookName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b5c20-112">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-112">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="b5c20-113">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-113">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="b5c20-114">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-114">The name of the webhook.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b5c20-115">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b5c20-115">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b5c20-116">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b5c20-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b5c20-117">コンテナー レジストリから、webhook を削除します。</span><span class="sxs-lookup"><span data-stu-id="b5c20-117">Deletes a webhook from a container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b5c20-118">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-118">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b5c20-119">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-119">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt; BeginUpdateWithHttpMessagesAsync (string resourceGroupName, string registryName, string webhookName, Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters webhookUpdateParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt; BeginUpdateWithHttpMessagesAsync(string resourceGroupName, string registryName, string webhookName, class Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters webhookUpdateParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations.BeginUpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt;" Usage="iWebhooksOperations.BeginUpdateWithHttpMessagesAsync (resourceGroupName, registryName, webhookName, webhookUpdateParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="webhookUpdateParameters" Type="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b5c20-120">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-120">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="b5c20-121">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-121">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="b5c20-122">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-122">The name of the webhook.</span></span>
            </param>
        <param name="webhookUpdateParameters">
            <span data-ttu-id="b5c20-123">Webhook を更新するためのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="b5c20-123">The parameters for updating a webhook.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b5c20-124">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b5c20-124">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b5c20-125">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b5c20-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b5c20-126">指定されたパラメーターで、webhook を更新します。</span><span class="sxs-lookup"><span data-stu-id="b5c20-126">Updates a webhook with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b5c20-127">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-127">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b5c20-128">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-128">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b5c20-129">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-129">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt; CreateWithHttpMessagesAsync (string resourceGroupName, string registryName, string webhookName, Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters webhookCreateParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt; CreateWithHttpMessagesAsync(string resourceGroupName, string registryName, string webhookName, class Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters webhookCreateParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations.CreateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt;" Usage="iWebhooksOperations.CreateWithHttpMessagesAsync (resourceGroupName, registryName, webhookName, webhookCreateParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="webhookCreateParameters" Type="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookCreateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b5c20-130">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-130">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="b5c20-131">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-131">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="b5c20-132">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-132">The name of the webhook.</span></span>
            </param>
        <param name="webhookCreateParameters">
            <span data-ttu-id="b5c20-133">Webhook を作成するためのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="b5c20-133">The parameters for creating a webhook.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b5c20-134">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b5c20-134">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b5c20-135">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b5c20-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b5c20-136">指定したパラメーターにコンテナー レジストリの webhook を作成します。</span><span class="sxs-lookup"><span data-stu-id="b5c20-136">Creates a webhook for a container registry with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b5c20-137">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-137">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b5c20-138">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-138">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b5c20-139">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-139">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string registryName, string webhookName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string registryName, string webhookName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iWebhooksOperations.DeleteWithHttpMessagesAsync (resourceGroupName, registryName, webhookName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b5c20-140">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-140">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="b5c20-141">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-141">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="b5c20-142">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-142">The name of the webhook.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b5c20-143">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b5c20-143">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b5c20-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b5c20-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b5c20-145">コンテナー レジストリから、webhook を削除します。</span><span class="sxs-lookup"><span data-stu-id="b5c20-145">Deletes a webhook from a container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b5c20-146">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-146">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b5c20-147">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-147">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetCallbackConfigWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerRegistry.Models.CallbackConfig&gt;&gt; GetCallbackConfigWithHttpMessagesAsync (string resourceGroupName, string registryName, string webhookName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.CallbackConfig&gt;&gt; GetCallbackConfigWithHttpMessagesAsync(string resourceGroupName, string registryName, string webhookName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations.GetCallbackConfigWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCallbackConfigWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerRegistry.Models.CallbackConfig&gt;&gt;" Usage="iWebhooksOperations.GetCallbackConfigWithHttpMessagesAsync (resourceGroupName, registryName, webhookName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerRegistry.Models.CallbackConfig&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b5c20-148">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-148">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="b5c20-149">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-149">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="b5c20-150">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-150">The name of the webhook.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b5c20-151">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b5c20-151">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b5c20-152">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b5c20-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b5c20-153">Webhook の URI をサービスの構成とカスタム ヘッダーを取得します。</span><span class="sxs-lookup"><span data-stu-id="b5c20-153">Gets the configuration of service URI and custom headers for the webhook.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b5c20-154">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-154">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b5c20-155">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-155">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b5c20-156">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-156">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string registryName, string webhookName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string registryName, string webhookName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt;" Usage="iWebhooksOperations.GetWithHttpMessagesAsync (resourceGroupName, registryName, webhookName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b5c20-157">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-157">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="b5c20-158">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-158">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="b5c20-159">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-159">The name of the webhook.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b5c20-160">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b5c20-160">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b5c20-161">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b5c20-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b5c20-162">指定の webhook のプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="b5c20-162">Gets the properties of the specified webhook.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b5c20-163">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-163">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b5c20-164">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-164">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b5c20-165">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-165">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListEventsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;&gt;&gt; ListEventsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;&gt;&gt; ListEventsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations.ListEventsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListEventsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;&gt;&gt;" Usage="iWebhooksOperations.ListEventsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="b5c20-166">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="b5c20-166">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b5c20-167">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b5c20-167">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b5c20-168">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b5c20-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b5c20-169">指定の webhook の最近のイベントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b5c20-169">Lists recent events for the specified webhook.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b5c20-170">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-170">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b5c20-171">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-171">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b5c20-172">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-172">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListEventsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;&gt;&gt; ListEventsWithHttpMessagesAsync (string resourceGroupName, string registryName, string webhookName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;&gt;&gt; ListEventsWithHttpMessagesAsync(string resourceGroupName, string registryName, string webhookName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations.ListEventsWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListEventsWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;&gt;&gt;" Usage="iWebhooksOperations.ListEventsWithHttpMessagesAsync (resourceGroupName, registryName, webhookName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventModel&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b5c20-173">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-173">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="b5c20-174">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-174">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="b5c20-175">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-175">The name of the webhook.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b5c20-176">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b5c20-176">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b5c20-177">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b5c20-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b5c20-178">指定の webhook の最近のイベントを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b5c20-178">Lists recent events for the specified webhook.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b5c20-179">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-179">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b5c20-180">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-180">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b5c20-181">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-181">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt;&gt;" Usage="iWebhooksOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="b5c20-182">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="b5c20-182">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b5c20-183">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b5c20-183">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b5c20-184">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b5c20-184">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b5c20-185">指定したコンテナー レジストリに対するすべての webhook を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b5c20-185">Lists all the webhooks for the specified container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b5c20-186">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-186">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b5c20-187">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-187">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b5c20-188">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-188">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt;&gt; ListWithHttpMessagesAsync (string resourceGroupName, string registryName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt;&gt; ListWithHttpMessagesAsync(string resourceGroupName, string registryName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations.ListWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt;&gt;" Usage="iWebhooksOperations.ListWithHttpMessagesAsync (resourceGroupName, registryName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b5c20-189">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-189">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="b5c20-190">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-190">The name of the container registry.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b5c20-191">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b5c20-191">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b5c20-192">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b5c20-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b5c20-193">指定したコンテナー レジストリに対するすべての webhook を一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b5c20-193">Lists all the webhooks for the specified container registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b5c20-194">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-194">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b5c20-195">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-195">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b5c20-196">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-196">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="PingWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventInfo&gt;&gt; PingWithHttpMessagesAsync (string resourceGroupName, string registryName, string webhookName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.EventInfo&gt;&gt; PingWithHttpMessagesAsync(string resourceGroupName, string registryName, string webhookName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations.PingWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PingWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventInfo&gt;&gt;" Usage="iWebhooksOperations.PingWithHttpMessagesAsync (resourceGroupName, registryName, webhookName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerRegistry.Models.EventInfo&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b5c20-197">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-197">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="b5c20-198">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-198">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="b5c20-199">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-199">The name of the webhook.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b5c20-200">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b5c20-200">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b5c20-201">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b5c20-201">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b5c20-202">Webhook に送信される ping のイベントをトリガーします。</span><span class="sxs-lookup"><span data-stu-id="b5c20-202">Triggers a ping event to be sent to the webhook.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b5c20-203">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-203">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b5c20-204">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-204">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b5c20-205">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-205">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string registryName, string webhookName, Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters webhookUpdateParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string registryName, string webhookName, class Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters webhookUpdateParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.IWebhooksOperations.UpdateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt;" Usage="iWebhooksOperations.UpdateWithHttpMessagesAsync (resourceGroupName, registryName, webhookName, webhookUpdateParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerRegistry.Models.Webhook&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="registryName" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
        <Parameter Name="webhookUpdateParameters" Type="Microsoft.Azure.Management.ContainerRegistry.Models.WebhookUpdateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b5c20-206">コンテナー レジストリが属するリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-206">The name of the resource group to which the container registry belongs.</span></span>
            </param>
        <param name="registryName">
            <span data-ttu-id="b5c20-207">コンテナー レジストリの名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-207">The name of the container registry.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="b5c20-208">Webhook の名前。</span><span class="sxs-lookup"><span data-stu-id="b5c20-208">The name of the webhook.</span></span>
            </param>
        <param name="webhookUpdateParameters">
            <span data-ttu-id="b5c20-209">Webhook を更新するためのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="b5c20-209">The parameters for updating a webhook.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b5c20-210">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b5c20-210">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b5c20-211">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b5c20-211">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b5c20-212">指定されたパラメーターで、webhook を更新します。</span><span class="sxs-lookup"><span data-stu-id="b5c20-212">Updates a webhook with the specified parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b5c20-213">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-213">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b5c20-214">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-214">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b5c20-215">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b5c20-215">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>