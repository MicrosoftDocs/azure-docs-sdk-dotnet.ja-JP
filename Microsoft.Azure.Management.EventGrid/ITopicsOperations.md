<Type Name="ITopicsOperations" FullName="Microsoft.Azure.Management.EventGrid.ITopicsOperations">
  <TypeSignature Language="C#" Value="public interface ITopicsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITopicsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventGrid.ITopicsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITopicsOperations" />
  <TypeSignature Language="F#" Value="type ITopicsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8a679-101">TopicsOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="8a679-101">TopicsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string topicName, Microsoft.Azure.Management.EventGrid.Models.Topic topicInfo, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt; BeginCreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string topicName, class Microsoft.Azure.Management.EventGrid.Models.Topic topicInfo, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.ITopicsOperations.BeginCreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.Topic,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.EventGrid.Models.Topic * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt;" Usage="iTopicsOperations.BeginCreateOrUpdateWithHttpMessagesAsync (resourceGroupName, topicName, topicInfo, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="topicInfo" Type="Microsoft.Azure.Management.EventGrid.Models.Topic" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8a679-102">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8a679-102">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="8a679-103">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="8a679-103">Name of the topic</span></span>
            </param>
        <param name="topicInfo">
            <span data-ttu-id="8a679-104">トピックの情報</span><span class="sxs-lookup"><span data-stu-id="8a679-104">Topic information</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8a679-105">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8a679-105">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a679-106">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8a679-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a679-107">トピックを作成する</span><span class="sxs-lookup"><span data-stu-id="8a679-107">Create a topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8a679-108">指定されたパラメーターを使用して、新しいトピックを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="8a679-108">Asynchronously creates a new topic with the specified parameters.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8a679-109">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8a679-110">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8a679-111">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync (string resourceGroupName, string topicName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginDeleteWithHttpMessagesAsync(string resourceGroupName, string topicName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.ITopicsOperations.BeginDeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iTopicsOperations.BeginDeleteWithHttpMessagesAsync (resourceGroupName, topicName, customHeaders, cancellationToken)" />
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
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8a679-112">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8a679-112">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="8a679-113">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="8a679-113">Name of the topic</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8a679-114">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8a679-114">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a679-115">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8a679-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a679-116">トピックを削除する</span><span class="sxs-lookup"><span data-stu-id="8a679-116">Delete a topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8a679-117">既存のトピックを削除します。</span><span class="sxs-lookup"><span data-stu-id="8a679-117">Delete existing topic</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8a679-118">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-118">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8a679-119">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-119">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt; BeginUpdateWithHttpMessagesAsync (string resourceGroupName, string topicName, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt; BeginUpdateWithHttpMessagesAsync(string resourceGroupName, string topicName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.ITopicsOperations.BeginUpdateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateWithHttpMessagesAsync : string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt;" Usage="iTopicsOperations.BeginUpdateWithHttpMessagesAsync (resourceGroupName, topicName, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8a679-120">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8a679-120">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="8a679-121">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="8a679-121">Name of the topic</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="8a679-122">リソースのタグ</span><span class="sxs-lookup"><span data-stu-id="8a679-122">Tags of the resource</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8a679-123">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8a679-123">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a679-124">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8a679-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a679-125">トピックを更新します。</span><span class="sxs-lookup"><span data-stu-id="8a679-125">Update a topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8a679-126">指定されたパラメーターでトピックを非同期に更新します。</span><span class="sxs-lookup"><span data-stu-id="8a679-126">Asynchronously updates a topic with the specified parameters.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8a679-127">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-127">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8a679-128">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-128">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8a679-129">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-129">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string topicName, Microsoft.Azure.Management.EventGrid.Models.Topic topicInfo, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string topicName, class Microsoft.Azure.Management.EventGrid.Models.Topic topicInfo, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.ITopicsOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.Topic,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.EventGrid.Models.Topic * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt;" Usage="iTopicsOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, topicName, topicInfo, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="topicInfo" Type="Microsoft.Azure.Management.EventGrid.Models.Topic" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8a679-130">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8a679-130">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="8a679-131">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="8a679-131">Name of the topic</span></span>
            </param>
        <param name="topicInfo">
            <span data-ttu-id="8a679-132">トピックの情報</span><span class="sxs-lookup"><span data-stu-id="8a679-132">Topic information</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8a679-133">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8a679-133">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a679-134">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8a679-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a679-135">トピックを作成する</span><span class="sxs-lookup"><span data-stu-id="8a679-135">Create a topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8a679-136">指定されたパラメーターを使用して、新しいトピックを非同期に作成します。</span><span class="sxs-lookup"><span data-stu-id="8a679-136">Asynchronously creates a new topic with the specified parameters.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8a679-137">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-137">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8a679-138">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-138">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8a679-139">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-139">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string topicName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string topicName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.ITopicsOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iTopicsOperations.DeleteWithHttpMessagesAsync (resourceGroupName, topicName, customHeaders, cancellationToken)" />
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
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8a679-140">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8a679-140">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="8a679-141">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="8a679-141">Name of the topic</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8a679-142">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8a679-142">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a679-143">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8a679-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a679-144">トピックを削除する</span><span class="sxs-lookup"><span data-stu-id="8a679-144">Delete a topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8a679-145">既存のトピックを削除します。</span><span class="sxs-lookup"><span data-stu-id="8a679-145">Delete existing topic</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8a679-146">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-146">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8a679-147">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-147">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string topicName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string topicName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.ITopicsOperations.GetWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt;" Usage="iTopicsOperations.GetWithHttpMessagesAsync (resourceGroupName, topicName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8a679-148">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8a679-148">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="8a679-149">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="8a679-149">Name of the topic</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8a679-150">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8a679-150">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a679-151">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8a679-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a679-152">トピックを取得します。</span><span class="sxs-lookup"><span data-stu-id="8a679-152">Get a topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8a679-153">トピックのプロパティを取得します。</span><span class="sxs-lookup"><span data-stu-id="8a679-153">Get properties of a topic</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8a679-154">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-154">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8a679-155">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-155">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8a679-156">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-156">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync (string resourceGroupName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt;&gt; ListByResourceGroupWithHttpMessagesAsync(string resourceGroupName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.ITopicsOperations.ListByResourceGroupWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByResourceGroupWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt;&gt;" Usage="iTopicsOperations.ListByResourceGroupWithHttpMessagesAsync (resourceGroupName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8a679-157">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8a679-157">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8a679-158">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8a679-158">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a679-159">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8a679-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a679-160">リソース グループ下にあるトピックをリストします。</span><span class="sxs-lookup"><span data-stu-id="8a679-160">List topics under a resource group</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8a679-161">リソース グループの下のすべてのトピックを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="8a679-161">List all the topics under a resource group</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8a679-162">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-162">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8a679-163">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-163">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8a679-164">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-164">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscriptionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt;&gt; ListBySubscriptionWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt;&gt; ListBySubscriptionWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.ITopicsOperations.ListBySubscriptionWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListBySubscriptionWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt;&gt;" Usage="iTopicsOperations.ListBySubscriptionWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="8a679-165">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8a679-165">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a679-166">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8a679-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a679-167">Azure サブスクリプションの下にあるトピックをリストします。</span><span class="sxs-lookup"><span data-stu-id="8a679-167">List topics under an Azure subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8a679-168">Azure サブスクリプションの下のすべてのトピックを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="8a679-168">List all the topics under an Azure subscription</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8a679-169">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-169">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8a679-170">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-170">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8a679-171">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-171">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListEventTypesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventType&gt;&gt;&gt; ListEventTypesWithHttpMessagesAsync (string resourceGroupName, string providerNamespace, string resourceTypeName, string resourceName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventType&gt;&gt;&gt; ListEventTypesWithHttpMessagesAsync(string resourceGroupName, string providerNamespace, string resourceTypeName, string resourceName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.ITopicsOperations.ListEventTypesWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListEventTypesWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventType&gt;&gt;&gt;" Usage="iTopicsOperations.ListEventTypesWithHttpMessagesAsync (resourceGroupName, providerNamespace, resourceTypeName, resourceName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventType&gt;&gt;&gt;</ReturnType>
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
            <span data-ttu-id="8a679-172">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8a679-172">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="providerNamespace">
            <span data-ttu-id="8a679-173">トピックのプロバイダーの Namespace</span><span class="sxs-lookup"><span data-stu-id="8a679-173">Namespace of the provider of the topic</span></span>
            </param>
        <param name="resourceTypeName">
            <span data-ttu-id="8a679-174">トピックの種類の名前</span><span class="sxs-lookup"><span data-stu-id="8a679-174">Name of the topic type</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="8a679-175">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="8a679-175">Name of the topic</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8a679-176">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8a679-176">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a679-177">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8a679-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a679-178">トピック イベントの種類の一覧</span><span class="sxs-lookup"><span data-stu-id="8a679-178">List topic event types</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8a679-179">トピックの一覧のイベントの種類</span><span class="sxs-lookup"><span data-stu-id="8a679-179">List event types for a topic</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8a679-180">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-180">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8a679-181">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-181">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8a679-182">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-182">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListSharedAccessKeysWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys&gt;&gt; ListSharedAccessKeysWithHttpMessagesAsync (string resourceGroupName, string topicName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys&gt;&gt; ListSharedAccessKeysWithHttpMessagesAsync(string resourceGroupName, string topicName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.ITopicsOperations.ListSharedAccessKeysWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSharedAccessKeysWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys&gt;&gt;" Usage="iTopicsOperations.ListSharedAccessKeysWithHttpMessagesAsync (resourceGroupName, topicName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8a679-183">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8a679-183">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="8a679-184">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="8a679-184">Name of the topic</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8a679-185">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8a679-185">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a679-186">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8a679-186">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a679-187">トピックのキーの一覧表示</span><span class="sxs-lookup"><span data-stu-id="8a679-187">List keys for a topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8a679-188">トピックへの公開に使用される 2 つのキーを一覧表示します。</span><span class="sxs-lookup"><span data-stu-id="8a679-188">List the two keys used to publish to a topic</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8a679-189">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-189">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8a679-190">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-190">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8a679-191">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-191">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys&gt;&gt; RegenerateKeyWithHttpMessagesAsync (string resourceGroupName, string topicName, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys&gt;&gt; RegenerateKeyWithHttpMessagesAsync(string resourceGroupName, string topicName, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.ITopicsOperations.RegenerateKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys&gt;&gt;" Usage="iTopicsOperations.RegenerateKeyWithHttpMessagesAsync (resourceGroupName, topicName, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.TopicSharedAccessKeys&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8a679-192">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8a679-192">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="8a679-193">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="8a679-193">Name of the topic</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="8a679-194">Key1、key2 または再生成するキーの名前</span><span class="sxs-lookup"><span data-stu-id="8a679-194">Key name to regenerate key1 or key2</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8a679-195">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8a679-195">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a679-196">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8a679-196">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a679-197">トピックのキーを再生成</span><span class="sxs-lookup"><span data-stu-id="8a679-197">Regenerate key for a topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8a679-198">トピックの共有アクセス キーを再生成します。</span><span class="sxs-lookup"><span data-stu-id="8a679-198">Regenerate a shared access key for a topic</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8a679-199">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-199">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8a679-200">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-200">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8a679-201">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-201">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt; UpdateWithHttpMessagesAsync (string resourceGroupName, string topicName, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt; UpdateWithHttpMessagesAsync(string resourceGroupName, string topicName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.ITopicsOperations.UpdateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateWithHttpMessagesAsync : string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt;" Usage="iTopicsOperations.UpdateWithHttpMessagesAsync (resourceGroupName, topicName, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.EventGrid.Models.Topic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="8a679-202">ユーザーのサブスクリプション内のリソース グループの名前。</span><span class="sxs-lookup"><span data-stu-id="8a679-202">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="8a679-203">トピックの名前</span><span class="sxs-lookup"><span data-stu-id="8a679-203">Name of the topic</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="8a679-204">リソースのタグ</span><span class="sxs-lookup"><span data-stu-id="8a679-204">Tags of the resource</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="8a679-205">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="8a679-205">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a679-206">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="8a679-206">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a679-207">トピックを更新します。</span><span class="sxs-lookup"><span data-stu-id="8a679-207">Update a topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="8a679-208">指定されたパラメーターでトピックを非同期に更新します。</span><span class="sxs-lookup"><span data-stu-id="8a679-208">Asynchronously updates a topic with the specified parameters.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="8a679-209">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-209">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="8a679-210">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-210">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="8a679-211">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="8a679-211">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>