<Type Name="IRulesOperations" FullName="Microsoft.Azure.Management.ServiceBus.IRulesOperations">
  <TypeSignature Language="C#" Value="public interface IRulesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRulesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.IRulesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRulesOperations" />
  <TypeSignature Language="F#" Value="type IRulesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="232a1-101">RulesOperations 操作です。</span><span class="sxs-lookup"><span data-stu-id="232a1-101">RulesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;&gt; CreateOrUpdateWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string topicName, string subscriptionName, string ruleName, Microsoft.Azure.Management.ServiceBus.Models.Rule parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;&gt; CreateOrUpdateWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string topicName, string subscriptionName, string ruleName, class Microsoft.Azure.Management.ServiceBus.Models.Rule parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.IRulesOperations.CreateOrUpdateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.Rule,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithHttpMessagesAsync : string * string * string * string * string * Microsoft.Azure.Management.ServiceBus.Models.Rule * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;&gt;" Usage="iRulesOperations.CreateOrUpdateWithHttpMessagesAsync (resourceGroupName, namespaceName, topicName, subscriptionName, ruleName, parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Models.Rule" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="232a1-102">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="232a1-102">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="232a1-103">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="232a1-103">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="232a1-104">トピック名。</span><span class="sxs-lookup"><span data-stu-id="232a1-104">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="232a1-105">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="232a1-105">The subscription name.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="232a1-106">規則の名前。</span><span class="sxs-lookup"><span data-stu-id="232a1-106">The rule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="232a1-107">ルールを作成する指定されたパラメーター。</span><span class="sxs-lookup"><span data-stu-id="232a1-107">Parameters supplied to create a rule.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="232a1-108">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="232a1-108">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="232a1-109">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="232a1-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="232a1-110">新しいルールを作成し、既存のルールを更新</span><span class="sxs-lookup"><span data-stu-id="232a1-110">Creates a new rule and updates an existing rule</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ServiceBus.Models.ErrorResponseException">
            <span data-ttu-id="232a1-111">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="232a1-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="232a1-112">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="232a1-112">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="232a1-113">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="232a1-113">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string topicName, string subscriptionName, string ruleName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; DeleteWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string topicName, string subscriptionName, string ruleName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.IRulesOperations.DeleteWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iRulesOperations.DeleteWithHttpMessagesAsync (resourceGroupName, namespaceName, topicName, subscriptionName, ruleName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="232a1-114">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="232a1-114">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="232a1-115">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="232a1-115">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="232a1-116">トピック名。</span><span class="sxs-lookup"><span data-stu-id="232a1-116">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="232a1-117">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="232a1-117">The subscription name.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="232a1-118">規則の名前。</span><span class="sxs-lookup"><span data-stu-id="232a1-118">The rule name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="232a1-119">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="232a1-119">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="232a1-120">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="232a1-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="232a1-121">既存のルールを削除します。</span><span class="sxs-lookup"><span data-stu-id="232a1-121">Deletes an existing rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ServiceBus.Models.ErrorResponseException">
            <span data-ttu-id="232a1-122">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="232a1-122">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="232a1-123">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="232a1-123">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;&gt; GetWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string topicName, string subscriptionName, string ruleName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;&gt; GetWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string topicName, string subscriptionName, string ruleName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.IRulesOperations.GetWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;&gt;" Usage="iRulesOperations.GetWithHttpMessagesAsync (resourceGroupName, namespaceName, topicName, subscriptionName, ruleName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="232a1-124">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="232a1-124">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="232a1-125">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="232a1-125">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="232a1-126">トピック名。</span><span class="sxs-lookup"><span data-stu-id="232a1-126">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="232a1-127">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="232a1-127">The subscription name.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="232a1-128">規則の名前。</span><span class="sxs-lookup"><span data-stu-id="232a1-128">The rule name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="232a1-129">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="232a1-129">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="232a1-130">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="232a1-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="232a1-131">指定された規則の説明を取得します。</span><span class="sxs-lookup"><span data-stu-id="232a1-131">Retrieves the description for the specified rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ServiceBus.Models.ErrorResponseException">
            <span data-ttu-id="232a1-132">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="232a1-132">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="232a1-133">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="232a1-133">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="232a1-134">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="232a1-134">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscriptionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;&gt;&gt; ListBySubscriptionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;&gt;&gt; ListBySubscriptionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.IRulesOperations.ListBySubscriptionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListBySubscriptionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;&gt;&gt;" Usage="iRulesOperations.ListBySubscriptionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="232a1-135">一覧表示操作に成功した呼び出しからの NextLink です。</span><span class="sxs-lookup"><span data-stu-id="232a1-135">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="232a1-136">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="232a1-136">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="232a1-137">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="232a1-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="232a1-138">一覧内のすべてのルール トピック サブスクリプションを指定</span><span class="sxs-lookup"><span data-stu-id="232a1-138">List all the rules within given topic-subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ServiceBus.Models.ErrorResponseException">
            <span data-ttu-id="232a1-139">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="232a1-139">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="232a1-140">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="232a1-140">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="232a1-141">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="232a1-141">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscriptionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;&gt;&gt; ListBySubscriptionsWithHttpMessagesAsync (string resourceGroupName, string namespaceName, string topicName, string subscriptionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;&gt;&gt; ListBySubscriptionsWithHttpMessagesAsync(string resourceGroupName, string namespaceName, string topicName, string subscriptionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.IRulesOperations.ListBySubscriptionsWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListBySubscriptionsWithHttpMessagesAsync : string * string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;&gt;&gt;" Usage="iRulesOperations.ListBySubscriptionsWithHttpMessagesAsync (resourceGroupName, namespaceName, topicName, subscriptionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="232a1-142">Azure サブスクリプション内のリソース グループの名前です。</span><span class="sxs-lookup"><span data-stu-id="232a1-142">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="232a1-143">名前空間の名前</span><span class="sxs-lookup"><span data-stu-id="232a1-143">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="232a1-144">トピック名。</span><span class="sxs-lookup"><span data-stu-id="232a1-144">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="232a1-145">サブスクリプションの名前。</span><span class="sxs-lookup"><span data-stu-id="232a1-145">The subscription name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="232a1-146">追加されるヘッダーを要求します。</span><span class="sxs-lookup"><span data-stu-id="232a1-146">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="232a1-147">キャンセル トークン。</span><span class="sxs-lookup"><span data-stu-id="232a1-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="232a1-148">一覧内のすべてのルール トピック サブスクリプションを指定</span><span class="sxs-lookup"><span data-stu-id="232a1-148">List all the rules within given topic-subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.Management.ServiceBus.Models.ErrorResponseException">
            <span data-ttu-id="232a1-149">操作には、無効な状態コードが返された場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="232a1-149">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="232a1-150">応答をシリアル化を解除できない場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="232a1-150">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="232a1-151">必須のパラメーターが null の場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="232a1-151">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>