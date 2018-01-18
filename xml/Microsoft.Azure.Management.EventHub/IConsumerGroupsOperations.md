<Type Name="IConsumerGroupsOperations" FullName="Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations">
  <TypeSignature Language="C#" Value="public interface IConsumerGroupsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IConsumerGroupsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IConsumerGroupsOperations" />
  <TypeSignature Language="F#" Value="type IConsumerGroupsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d3246-101">ConsumerGroupsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="d3246-101">ConsumerGroupsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string eventHubName, string consumerGroupName, Microsoft.Azure.Management.EventHub.Models.ConsumerGroup parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string eventHubName, string consumerGroupName, class Microsoft.Azure.Management.EventHub.Models.ConsumerGroup parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.Management.EventHub.Models.ConsumerGroup,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.Management.EventHub.Models.ConsumerGroup * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;&gt;" Usage="iConsumerGroupsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, namespaceName, eventHubName, consumerGroupName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.EventHub.Models.ConsumerGroup" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d3246-102">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="d3246-102">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="d3246-103">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="d3246-103">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="d3246-104">イベント ハブの名前</span><span class="sxs-lookup"><span data-stu-id="d3246-104">The Event Hub name</span></span>
            </param>
        <param name="consumerGroupName">
            <span data-ttu-id="d3246-105">コンシューマー グループ名</span><span class="sxs-lookup"><span data-stu-id="d3246-105">The consumer group name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d3246-106">作成またはコンシューマー グループ リソースの更新に渡されるパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="d3246-106">Parameters supplied to create or update a consumer group resource.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d3246-107">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d3246-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d3246-108">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d3246-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d3246-109">作成するか、Namespace 内で入れ子になったリソースとして、イベント ハブ コンシューマー グループを更新します。</span><span class="sxs-lookup"><span data-stu-id="d3246-109">Creates or updates an Event Hubs consumer group as a nested resource within a Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.EventHub.Models.ErrorResponseException">
            <span data-ttu-id="d3246-110">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d3246-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d3246-111">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d3246-111">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d3246-112">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d3246-112">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string eventHubName, string consumerGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string eventHubName, string consumerGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iConsumerGroupsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, namespaceName, eventHubName, consumerGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d3246-113">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="d3246-113">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="d3246-114">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="d3246-114">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="d3246-115">イベント ハブの名前</span><span class="sxs-lookup"><span data-stu-id="d3246-115">The Event Hub name</span></span>
            </param>
        <param name="consumerGroupName">
            <span data-ttu-id="d3246-116">コンシューマー グループ名</span><span class="sxs-lookup"><span data-stu-id="d3246-116">The consumer group name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d3246-117">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d3246-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d3246-118">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d3246-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d3246-119">指定されたイベント ハブとリソース グループからのコンシューマー グループを削除します。</span><span class="sxs-lookup"><span data-stu-id="d3246-119">Deletes a consumer group from the specified Event Hub and resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.EventHub.Models.ErrorResponseException">
            <span data-ttu-id="d3246-120">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d3246-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d3246-121">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d3246-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string eventHubName, string consumerGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string eventHubName, string consumerGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;&gt;" Usage="iConsumerGroupsOperations.GetWithHttpMessagesAsync (resourceGroupName, namespaceName, eventHubName, consumerGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d3246-122">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="d3246-122">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="d3246-123">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="d3246-123">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="d3246-124">イベント ハブの名前</span><span class="sxs-lookup"><span data-stu-id="d3246-124">The Event Hub name</span></span>
            </param>
        <param name="consumerGroupName">
            <span data-ttu-id="d3246-125">コンシューマー グループ名</span><span class="sxs-lookup"><span data-stu-id="d3246-125">The consumer group name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d3246-126">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d3246-126">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d3246-127">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d3246-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d3246-128">指定されたコンシューマー グループの説明を取得します。</span><span class="sxs-lookup"><span data-stu-id="d3246-128">Gets a description for the specified consumer group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.EventHub.Models.ErrorResponseException">
            <span data-ttu-id="d3246-129">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d3246-129">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d3246-130">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d3246-130">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d3246-131">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d3246-131">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByEventHubNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;&gt;&gt; ListByEventHubNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;&gt;&gt; ListByEventHubNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations.ListByEventHubNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByEventHubNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;&gt;&gt;" Usage="iConsumerGroupsOperations.ListByEventHubNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="d3246-132">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="d3246-132">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d3246-133">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d3246-133">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d3246-134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d3246-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d3246-135">Namespace 内のすべてのコンシューマー グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="d3246-135">Gets all the consumer groups in a Namespace.</span></span> <span data-ttu-id="d3246-136">Namespace にコンシューマー グループが存在しない場合は、空のフィードが返されます。</span><span class="sxs-lookup"><span data-stu-id="d3246-136">An empty feed is returned if no consumer group exists in the Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.EventHub.Models.ErrorResponseException">
            <span data-ttu-id="d3246-137">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d3246-137">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d3246-138">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d3246-138">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d3246-139">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d3246-139">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByEventHubWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;&gt;&gt; ListByEventHubWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string eventHubName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;&gt;&gt; ListByEventHubWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string eventHubName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.IConsumerGroupsOperations.ListByEventHubWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByEventHubWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;&gt;&gt;" Usage="iConsumerGroupsOperations.ListByEventHubWithHttpMessagesAsync (resourceGroupName, namespaceName, eventHubName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.EventHub.Models.ConsumerGroup&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d3246-140">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="d3246-140">Name of the resource group within the azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="d3246-141">Namespace 名</span><span class="sxs-lookup"><span data-stu-id="d3246-141">The Namespace name</span></span>
            </param>
        <param name="eventHubName">
            <span data-ttu-id="d3246-142">イベント ハブの名前</span><span class="sxs-lookup"><span data-stu-id="d3246-142">The Event Hub name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="d3246-143">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="d3246-143">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d3246-144">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="d3246-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d3246-145">Namespace 内のすべてのコンシューマー グループを取得します。</span><span class="sxs-lookup"><span data-stu-id="d3246-145">Gets all the consumer groups in a Namespace.</span></span> <span data-ttu-id="d3246-146">Namespace にコンシューマー グループが存在しない場合は、空のフィードが返されます。</span><span class="sxs-lookup"><span data-stu-id="d3246-146">An empty feed is returned if no consumer group exists in the Namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.EventHub.Models.ErrorResponseException">
            <span data-ttu-id="d3246-147">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d3246-147">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="d3246-148">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d3246-148">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="d3246-149">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="d3246-149">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>