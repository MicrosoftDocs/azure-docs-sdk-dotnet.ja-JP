<Type Name="IEventSubscriptionsOperations" FullName="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations">
  <TypeSignature Language="C#" Value="public interface IEventSubscriptionsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IEventSubscriptionsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IEventSubscriptionsOperations" />
  <TypeSignature Language="F#" Value="type IEventSubscriptionsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b478d-101">EventSubscriptionsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="b478d-101">EventSubscriptionsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; BeginCreateWithHttpMessagesAsync (string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; BeginCreateWithHttpMessagesAsync(string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.BeginCreateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscription,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscription * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="iEventSubscriptionsOperations.BeginCreateWithHttpMessagesAsync (scope, eventSubscriptionName, eventSubscriptionInfo, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionInfo" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscription" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            <span data-ttu-id="b478d-102">イベント サブスクリプションを作成する必要とするリソースのスコープです。</span><span class="sxs-lookup"><span data-stu-id="b478d-102">The scope of the resource to which the event subscription needs to be created.</span></span> <span data-ttu-id="b478d-103">スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。</span><span class="sxs-lookup"><span data-stu-id="b478d-103">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="b478d-104">たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。</span><span class="sxs-lookup"><span data-stu-id="b478d-104">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="b478d-105">イベント サブスクリプションを作成するの名前です。</span><span class="sxs-lookup"><span data-stu-id="b478d-105">Name of the event subscription to be created.</span></span> <span data-ttu-id="b478d-106">イベント サブスクリプション名は、3 ~ 64 文字以下でなければし、英数字文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="b478d-106">Event subscription names must be between 3 and 64 characters in length and use alphanumeric letters only.</span></span>
            </param>
        <param name="eventSubscriptionInfo">
            <span data-ttu-id="b478d-107">移行先とフィルター情報を含むイベント サブスクリプションのプロパティ</span><span class="sxs-lookup"><span data-stu-id="b478d-107">Event subscription properties containing the destination and filter information</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b478d-108">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b478d-108">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b478d-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b478d-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b478d-110">イベント サブスクリプションを作成します。</span><span class="sxs-lookup"><span data-stu-id="b478d-110">Create an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b478d-111">指定されたスコープに新しいイベント サブスクリプションを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="b478d-111">Asynchronously creates a new event subscription to the specified scope.</span></span> <span data-ttu-id="b478d-112">既存のサブスクリプションのイベントは、この API で更新することはできず、イベント サブスクリプションの更新 API を代わりに使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="b478d-112">Existing event subscriptions cannot be updated with this API and should instead use the Update event subscription API.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b478d-113">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-113">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b478d-114">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-114">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b478d-115">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-115">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string scope, string eventSubscriptionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string scope, string eventSubscriptionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iEventSubscriptionsOperations.BeginDeleteWithHttpMessagesAsync (scope, eventSubscriptionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            <span data-ttu-id="b478d-116">イベント サブスクリプションのスコープです。</span><span class="sxs-lookup"><span data-stu-id="b478d-116">The scope of the event subscription.</span></span> <span data-ttu-id="b478d-117">スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。</span><span class="sxs-lookup"><span data-stu-id="b478d-117">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span>
            <span data-ttu-id="b478d-118">たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。</span><span class="sxs-lookup"><span data-stu-id="b478d-118">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="b478d-119">イベント サブスクリプションの名前</span><span class="sxs-lookup"><span data-stu-id="b478d-119">Name of the event subscription</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b478d-120">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b478d-120">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b478d-121">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b478d-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b478d-122">イベント サブスクリプションを削除します。</span><span class="sxs-lookup"><span data-stu-id="b478d-122">Delete an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b478d-123">既存のイベント サブスクリプションを削除します。</span><span class="sxs-lookup"><span data-stu-id="b478d-123">Delete an existing event subscription</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b478d-124">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-124">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b478d-125">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-125">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; BeginUpdateWithHttpMessagesAsync (string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; BeginUpdateWithHttpMessagesAsync(string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.BeginUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="iEventSubscriptionsOperations.BeginUpdateWithHttpMessagesAsync (scope, eventSubscriptionName, eventSubscriptionUpdateParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionUpdateParameters" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            <span data-ttu-id="b478d-126">既存のイベント サブスクリプションのスコープです。</span><span class="sxs-lookup"><span data-stu-id="b478d-126">The scope of existing event subscription.</span></span> <span data-ttu-id="b478d-127">スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。</span><span class="sxs-lookup"><span data-stu-id="b478d-127">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span>
            <span data-ttu-id="b478d-128">たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。</span><span class="sxs-lookup"><span data-stu-id="b478d-128">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="b478d-129">イベント サブスクリプションを作成するの名前</span><span class="sxs-lookup"><span data-stu-id="b478d-129">Name of the event subscription to be created</span></span>
            </param>
        <param name="eventSubscriptionUpdateParameters">
            <span data-ttu-id="b478d-130">サブスクリプションの更新されたイベント情報</span><span class="sxs-lookup"><span data-stu-id="b478d-130">Updated event subscription information</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b478d-131">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b478d-131">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b478d-132">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b478d-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b478d-133">イベント サブスクリプションを更新します。</span><span class="sxs-lookup"><span data-stu-id="b478d-133">Update an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b478d-134">既存のイベント サブスクリプションを非同期に更新します。</span><span class="sxs-lookup"><span data-stu-id="b478d-134">Asynchronously updates an existing event subscription.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b478d-135">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-135">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b478d-136">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-136">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b478d-137">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-137">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; CreateWithHttpMessagesAsync (string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; CreateWithHttpMessagesAsync(string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.CreateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscription,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscription * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="iEventSubscriptionsOperations.CreateWithHttpMessagesAsync (scope, eventSubscriptionName, eventSubscriptionInfo, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionInfo" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscription" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            <span data-ttu-id="b478d-138">イベント サブスクリプションを作成する必要とするリソースのスコープです。</span><span class="sxs-lookup"><span data-stu-id="b478d-138">The scope of the resource to which the event subscription needs to be created.</span></span> <span data-ttu-id="b478d-139">スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。</span><span class="sxs-lookup"><span data-stu-id="b478d-139">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="b478d-140">たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。</span><span class="sxs-lookup"><span data-stu-id="b478d-140">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="b478d-141">イベント サブスクリプションを作成するの名前です。</span><span class="sxs-lookup"><span data-stu-id="b478d-141">Name of the event subscription to be created.</span></span> <span data-ttu-id="b478d-142">イベント サブスクリプション名は、3 ~ 64 文字以下でなければし、英数字文字のみを使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="b478d-142">Event subscription names must be between 3 and 64 characters in length and use alphanumeric letters only.</span></span>
            </param>
        <param name="eventSubscriptionInfo">
            <span data-ttu-id="b478d-143">移行先とフィルター情報を含むイベント サブスクリプションのプロパティ</span><span class="sxs-lookup"><span data-stu-id="b478d-143">Event subscription properties containing the destination and filter information</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b478d-144">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b478d-144">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b478d-145">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b478d-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b478d-146">イベント サブスクリプションを作成します。</span><span class="sxs-lookup"><span data-stu-id="b478d-146">Create an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b478d-147">指定されたスコープに新しいイベント サブスクリプションを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="b478d-147">Asynchronously creates a new event subscription to the specified scope.</span></span> <span data-ttu-id="b478d-148">既存のサブスクリプションのイベントは、この API で更新することはできず、イベント サブスクリプションの更新 API を代わりに使用する必要があります。</span><span class="sxs-lookup"><span data-stu-id="b478d-148">Existing event subscriptions cannot be updated with this API and should instead use the Update event subscription API.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b478d-149">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-149">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b478d-150">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-150">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b478d-151">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-151">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string scope, string eventSubscriptionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string scope, string eventSubscriptionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iEventSubscriptionsOperations.DeleteWithHttpMessagesAsync (scope, eventSubscriptionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            <span data-ttu-id="b478d-152">イベント サブスクリプションのスコープです。</span><span class="sxs-lookup"><span data-stu-id="b478d-152">The scope of the event subscription.</span></span> <span data-ttu-id="b478d-153">スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。</span><span class="sxs-lookup"><span data-stu-id="b478d-153">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span>
            <span data-ttu-id="b478d-154">たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。</span><span class="sxs-lookup"><span data-stu-id="b478d-154">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="b478d-155">イベント サブスクリプションの名前</span><span class="sxs-lookup"><span data-stu-id="b478d-155">Name of the event subscription</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b478d-156">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b478d-156">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b478d-157">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b478d-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b478d-158">イベント サブスクリプションを削除します。</span><span class="sxs-lookup"><span data-stu-id="b478d-158">Delete an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b478d-159">既存のイベント サブスクリプションを削除します。</span><span class="sxs-lookup"><span data-stu-id="b478d-159">Delete an existing event subscription</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b478d-160">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-160">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b478d-161">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-161">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFullUrlWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl&gt;&gt; GetFullUrlWithHttpMessagesAsync (string scope, string eventSubscriptionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl&gt;&gt; GetFullUrlWithHttpMessagesAsync(string scope, string eventSubscriptionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.GetFullUrlWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetFullUrlWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl&gt;&gt;" Usage="iEventSubscriptionsOperations.GetFullUrlWithHttpMessagesAsync (scope, eventSubscriptionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            <span data-ttu-id="b478d-162">イベント サブスクリプションのスコープです。</span><span class="sxs-lookup"><span data-stu-id="b478d-162">The scope of the event subscription.</span></span> <span data-ttu-id="b478d-163">スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。</span><span class="sxs-lookup"><span data-stu-id="b478d-163">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span>
            <span data-ttu-id="b478d-164">たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。</span><span class="sxs-lookup"><span data-stu-id="b478d-164">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="b478d-165">イベント サブスクリプションの名前</span><span class="sxs-lookup"><span data-stu-id="b478d-165">Name of the event subscription</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b478d-166">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b478d-166">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b478d-167">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b478d-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b478d-168">イベント サブスクリプションの完全な URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="b478d-168">Get full URL of an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b478d-169">イベント サブスクリプションの完全なエンドポイント URL を取得します。</span><span class="sxs-lookup"><span data-stu-id="b478d-169">Get the full endpoint URL for an event subscription</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b478d-170">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-170">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b478d-171">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-171">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b478d-172">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-172">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; GetWithHttpMessagesAsync (string scope, string eventSubscriptionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; GetWithHttpMessagesAsync(string scope, string eventSubscriptionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="iEventSubscriptionsOperations.GetWithHttpMessagesAsync (scope, eventSubscriptionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            <span data-ttu-id="b478d-173">イベント サブスクリプションのスコープです。</span><span class="sxs-lookup"><span data-stu-id="b478d-173">The scope of the event subscription.</span></span> <span data-ttu-id="b478d-174">スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。</span><span class="sxs-lookup"><span data-stu-id="b478d-174">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span>
            <span data-ttu-id="b478d-175">たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。</span><span class="sxs-lookup"><span data-stu-id="b478d-175">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="b478d-176">イベント サブスクリプションの名前</span><span class="sxs-lookup"><span data-stu-id="b478d-176">Name of the event subscription</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b478d-177">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b478d-177">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b478d-178">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b478d-178">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b478d-179">イベント サブスクリプションを取得します。</span><span class="sxs-lookup"><span data-stu-id="b478d-179">Get an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b478d-180">イベント サブスクリプションのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="b478d-180">Get properties of an event subscription</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b478d-181">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-181">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b478d-182">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-182">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b478d-183">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-183">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListByResourceWithHttpMessagesAsync (string resourceGroupName, string providerNamespace, string resourceTypeName, string resourceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListByResourceWithHttpMessagesAsync(string resourceGroupName, string providerNamespace, string resourceTypeName, string resourceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.ListByResourceWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;" Usage="iEventSubscriptionsOperations.ListByResourceWithHttpMessagesAsync (resourceGroupName, providerNamespace, resourceTypeName, resourceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="providerNamespace" Type="System.String" />
        <Parameter Name="resourceTypeName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b478d-184">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b478d-184">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="providerNamespace">
            <span data-ttu-id="b478d-185">トピックのプロバイダーの Namespace</span><span class="sxs-lookup"><span data-stu-id="b478d-185">Namespace of the provider of the topic</span></span>
            </param>
        <param name="resourceTypeName">
            <span data-ttu-id="b478d-186">リソースの種類の名前</span><span class="sxs-lookup"><span data-stu-id="b478d-186">Name of the resource type</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="b478d-187">リソースの名前</span><span class="sxs-lookup"><span data-stu-id="b478d-187">Name of the resource</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b478d-188">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b478d-188">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b478d-189">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b478d-189">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b478d-190">特定のトピックのすべてのイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b478d-190">List all event subscriptions for a specific topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b478d-191">特定のトピック用に作成されたすべてのイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b478d-191">List all event subscriptions that have been created for a specific topic</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b478d-192">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-192">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b478d-193">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-193">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b478d-194">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-194">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalByResourceGroupForTopicTypeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListGlobalByResourceGroupForTopicTypeWithHttpMessagesAsync (string resourceGroupName, string topicTypeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListGlobalByResourceGroupForTopicTypeWithHttpMessagesAsync(string resourceGroupName, string topicTypeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.ListGlobalByResourceGroupForTopicTypeWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListGlobalByResourceGroupForTopicTypeWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;" Usage="iEventSubscriptionsOperations.ListGlobalByResourceGroupForTopicTypeWithHttpMessagesAsync (resourceGroupName, topicTypeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicTypeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b478d-195">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b478d-195">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicTypeName">
            <span data-ttu-id="b478d-196">トピックの種類の名前</span><span class="sxs-lookup"><span data-stu-id="b478d-196">Name of the topic type</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b478d-197">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b478d-197">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b478d-198">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b478d-198">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b478d-199">トピックの種類のリソース グループの下のすべてのグローバル イベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b478d-199">List all global event subscriptions under a resource group for a topic type</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b478d-200">特定のトピックの種類のリソース グループの下のすべてのグローバル イベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b478d-200">List all global event subscriptions under a resource group for a specific topic type.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b478d-201">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-201">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b478d-202">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-202">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b478d-203">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-203">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListGlobalByResourceGroupWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListGlobalByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.ListGlobalByResourceGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListGlobalByResourceGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;" Usage="iEventSubscriptionsOperations.ListGlobalByResourceGroupWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b478d-204">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b478d-204">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b478d-205">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b478d-205">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b478d-206">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b478d-206">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b478d-207">Azure のサブスクリプションとリソース グループの下のすべてのグローバル イベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b478d-207">List all global event subscriptions under an Azure subscription and resource group</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b478d-208">特定の Azure サブスクリプションとリソース グループの下のすべてのグローバル イベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b478d-208">List all global event subscriptions under a specific Azure subscription and resource group</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b478d-209">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-209">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b478d-210">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-210">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b478d-211">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-211">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalBySubscriptionForTopicTypeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListGlobalBySubscriptionForTopicTypeWithHttpMessagesAsync (string topicTypeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListGlobalBySubscriptionForTopicTypeWithHttpMessagesAsync(string topicTypeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.ListGlobalBySubscriptionForTopicTypeWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListGlobalBySubscriptionForTopicTypeWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;" Usage="iEventSubscriptionsOperations.ListGlobalBySubscriptionForTopicTypeWithHttpMessagesAsync (topicTypeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicTypeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="topicTypeName">
            <span data-ttu-id="b478d-212">トピックの種類の名前</span><span class="sxs-lookup"><span data-stu-id="b478d-212">Name of the topic type</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b478d-213">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b478d-213">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b478d-214">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b478d-214">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b478d-215">トピックの種類のすべてのグローバル イベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b478d-215">List all global event subscriptions for a topic type</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b478d-216">トピックの種類の Azure サブスクリプションの下のすべてのグローバル イベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b478d-216">List all global event subscriptions under an Azure subscription for a topic type.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b478d-217">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-217">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b478d-218">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-218">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b478d-219">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-219">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalBySubscriptionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListGlobalBySubscriptionWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListGlobalBySubscriptionWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.ListGlobalBySubscriptionWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListGlobalBySubscriptionWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;" Usage="iEventSubscriptionsOperations.ListGlobalBySubscriptionWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="b478d-220">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b478d-220">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b478d-221">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b478d-221">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b478d-222">Azure サブスクリプションの下のすべてのグローバル イベント サブスクリプションの集計の一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="b478d-222">Get an aggregated list of all global event subscriptions under an Azure subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b478d-223">特定の Azure サブスクリプションの下のすべての集計のグローバル イベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b478d-223">List all aggregated global event subscriptions under a specific Azure subscription</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b478d-224">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-224">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b478d-225">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-225">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b478d-226">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-226">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalByResourceGroupForTopicTypeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListRegionalByResourceGroupForTopicTypeWithHttpMessagesAsync (string resourceGroupName, string location, string topicTypeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListRegionalByResourceGroupForTopicTypeWithHttpMessagesAsync(string resourceGroupName, string location, string topicTypeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.ListRegionalByResourceGroupForTopicTypeWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListRegionalByResourceGroupForTopicTypeWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;" Usage="iEventSubscriptionsOperations.ListRegionalByResourceGroupForTopicTypeWithHttpMessagesAsync (resourceGroupName, location, topicTypeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="topicTypeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b478d-227">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b478d-227">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="b478d-228">場所の名前</span><span class="sxs-lookup"><span data-stu-id="b478d-228">Name of the location</span></span>
            </param>
        <param name="topicTypeName">
            <span data-ttu-id="b478d-229">トピックの種類の名前</span><span class="sxs-lookup"><span data-stu-id="b478d-229">Name of the topic type</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b478d-230">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b478d-230">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b478d-231">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b478d-231">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b478d-232">トピックの種類の Azure サブスクリプションとリソース グループの下のすべての地域のイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b478d-232">List all regional event subscriptions under an Azure subscription and resource group for a topic type</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b478d-233">特定 Azure サブスクリプションとリソース グループとトピックの種類の下にある指定した場所からのすべてのイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b478d-233">List all event subscriptions from the given location under a specific Azure subscription and resource group and topic type</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b478d-234">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-234">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b478d-235">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-235">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b478d-236">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-236">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListRegionalByResourceGroupWithHttpMessagesAsync (string resourceGroupName, string location, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListRegionalByResourceGroupWithHttpMessagesAsync(string resourceGroupName, string location, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.ListRegionalByResourceGroupWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListRegionalByResourceGroupWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;" Usage="iEventSubscriptionsOperations.ListRegionalByResourceGroupWithHttpMessagesAsync (resourceGroupName, location, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b478d-237">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="b478d-237">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="b478d-238">場所の名前</span><span class="sxs-lookup"><span data-stu-id="b478d-238">Name of the location</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b478d-239">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b478d-239">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b478d-240">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b478d-240">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b478d-241">Azure のサブスクリプションとリソース グループの下のすべての地域のイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b478d-241">List all regional event subscriptions under an Azure subscription and resource group</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b478d-242">特定の Azure サブスクリプションとリソース グループの下にある指定した場所からのすべてのイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b478d-242">List all event subscriptions from the given location under a specific Azure subscription and resource group</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b478d-243">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-243">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b478d-244">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-244">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b478d-245">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-245">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalBySubscriptionForTopicTypeWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListRegionalBySubscriptionForTopicTypeWithHttpMessagesAsync (string location, string topicTypeName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListRegionalBySubscriptionForTopicTypeWithHttpMessagesAsync(string location, string topicTypeName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.ListRegionalBySubscriptionForTopicTypeWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListRegionalBySubscriptionForTopicTypeWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;" Usage="iEventSubscriptionsOperations.ListRegionalBySubscriptionForTopicTypeWithHttpMessagesAsync (location, topicTypeName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="topicTypeName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="location">
            <span data-ttu-id="b478d-246">場所の名前</span><span class="sxs-lookup"><span data-stu-id="b478d-246">Name of the location</span></span>
            </param>
        <param name="topicTypeName">
            <span data-ttu-id="b478d-247">トピックの種類の名前</span><span class="sxs-lookup"><span data-stu-id="b478d-247">Name of the topic type</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b478d-248">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b478d-248">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b478d-249">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b478d-249">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b478d-250">トピックの種類の Azure サブスクリプションの下のすべての地域のイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b478d-250">List all regional event subscriptions under an Azure subscription for a topic type</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b478d-251">特定の Azure サブスクリプションとトピック種類の指定した場所からのすべてのイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b478d-251">List all event subscriptions from the given location under a specific Azure subscription and topic type.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b478d-252">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-252">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b478d-253">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-253">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b478d-254">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-254">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalBySubscriptionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListRegionalBySubscriptionWithHttpMessagesAsync (string location, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt; ListRegionalBySubscriptionWithHttpMessagesAsync(string location, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.ListRegionalBySubscriptionWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListRegionalBySubscriptionWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;" Usage="iEventSubscriptionsOperations.ListRegionalBySubscriptionWithHttpMessagesAsync (location, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="location">
            <span data-ttu-id="b478d-255">場所の名前</span><span class="sxs-lookup"><span data-stu-id="b478d-255">Name of the location</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b478d-256">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b478d-256">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b478d-257">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b478d-257">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b478d-258">Azure サブスクリプションの下のすべての地域のイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b478d-258">List all regional event subscriptions under an Azure subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b478d-259">特定の Azure サブスクリプションの下にある指定した場所からのすべてのイベント サブスクリプションを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="b478d-259">List all event subscriptions from the given location under a specific Azure subscription</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b478d-260">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-260">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b478d-261">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-261">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b478d-262">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-262">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; UpdateWithHttpMessagesAsync (string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; UpdateWithHttpMessagesAsync(string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations.UpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="iEventSubscriptionsOperations.UpdateWithHttpMessagesAsync (scope, eventSubscriptionName, eventSubscriptionUpdateParameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionUpdateParameters" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            <span data-ttu-id="b478d-263">既存のイベント サブスクリプションのスコープです。</span><span class="sxs-lookup"><span data-stu-id="b478d-263">The scope of existing event subscription.</span></span> <span data-ttu-id="b478d-264">スコープには、サブスクリプション、またはリソース グループ、またはリソース プロバイダーの名前空間または EventGrid トピックに属している、トップ レベル リソースを指定できます。</span><span class="sxs-lookup"><span data-stu-id="b478d-264">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span>
            <span data-ttu-id="b478d-265">たとえば、使用して 'サブスクリプション/{subscriptionid}/' 'のサブスクリプション/{subscriptionid} 必要な {resourcegroupname}' リソース グループで、サブスクリプションの場合と' サブスクリプション/{subscriptionid} 必要な {resourcegroupname}/プロバイダー/{resourceProviderNamespace}/{resourcetype}/{resourcename} ' のリソースのおよび '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' EventGrid トピックです。</span><span class="sxs-lookup"><span data-stu-id="b478d-265">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="b478d-266">イベント サブスクリプションを作成するの名前</span><span class="sxs-lookup"><span data-stu-id="b478d-266">Name of the event subscription to be created</span></span>
            </param>
        <param name="eventSubscriptionUpdateParameters">
            <span data-ttu-id="b478d-267">サブスクリプションの更新されたイベント情報</span><span class="sxs-lookup"><span data-stu-id="b478d-267">Updated event subscription information</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="b478d-268">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="b478d-268">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b478d-269">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="b478d-269">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b478d-270">イベント サブスクリプションを更新します。</span><span class="sxs-lookup"><span data-stu-id="b478d-270">Update an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="b478d-271">既存のイベント サブスクリプションを非同期に更新します。</span><span class="sxs-lookup"><span data-stu-id="b478d-271">Asynchronously updates an existing event subscription.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="b478d-272">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-272">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="b478d-273">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-273">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b478d-274">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="b478d-274">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>